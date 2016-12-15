# chef-provisioning-vra CHANGELOG

## v1.0.0 (2016-12-15)

* Updated to the new `vmware-vra` gem. Now supports 7.0+ vRA.

## v0.3.0 (2016-01-06)

* [pr#7](https://github.com/chef-partners/chef-provisioning-vra/pull/7) Storing the vRA resource (host) name in the Chef node object so it can be displayed/queried in cases where the machine resource name does not match the vRA-generated hostname

## v0.2.1 (2015-12-17)
* [pr#6](https://github.com/chef-partners/chef-provisioning-vra/pull/6) Fixing bug that would cause machines to not properly converge when used with machine_batch

## v0.2.0 (2015-12-15)
* [pr#5](https://github.com/chef-partners/chef-provisioning-vra/pull/5) Adding retry logic in wait_for method if an exception is encountered

## v0.1.1 (2015-11-18)
* [pr#3](https://github.com/chef-partners/chef-provisioning-vra/pull/3) Loosen version constraing on vmware-vra-gem

## v0.1.0
* Initial release
