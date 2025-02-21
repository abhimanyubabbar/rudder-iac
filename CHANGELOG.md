# Changelog

## 1.0.0 (2025-02-21)


### Features

* add base catalog support ([#3](https://github.com/abhimanyubabbar/rudder-iac/issues/3)) ([0de722a](https://github.com/abhimanyubabbar/rudder-iac/commit/0de722a520e52e1d6377d92020e708d57d18227c))
* add base tracking plan devex support ([#5](https://github.com/abhimanyubabbar/rudder-iac/issues/5)) ([0c04e10](https://github.com/abhimanyubabbar/rudder-iac/commit/0c04e10e7f3df1d25ca6c8929e5d1c96f298c648))
* add CLI application with basic configuration handling, and access token authentication ([#1](https://github.com/abhimanyubabbar/rudder-iac/issues/1)) ([2af47a4](https://github.com/abhimanyubabbar/rudder-iac/commit/2af47a45996780474f875b828039c47ca0c1301e))
* add support for configuring rudderstack api url ([#8](https://github.com/abhimanyubabbar/rudder-iac/issues/8)) ([9d87b52](https://github.com/abhimanyubabbar/rudder-iac/commit/9d87b52be2e8caa1c7f0a8cde9c12a11db7ff1ff))
* added base support for syncing properties using new sync framework ([#6](https://github.com/abhimanyubabbar/rudder-iac/issues/6)) ([f3790d0](https://github.com/abhimanyubabbar/rudder-iac/commit/f3790d066ac4bb022c2d73298642e2d954268e10))
* added proper support to handle identify page screen group ([#26](https://github.com/abhimanyubabbar/rudder-iac/issues/26)) ([d452eaa](https://github.com/abhimanyubabbar/rudder-iac/commit/d452eaa0faf4537ae4f68f14affef753e8d588eb))
* added support for registering resources to the new state machine ([#18](https://github.com/abhimanyubabbar/rudder-iac/issues/18)) ([c524ce5](https://github.com/abhimanyubabbar/rudder-iac/commit/c524ce5b71b959e7c54ee8a3f9ef4e728e7ff110))
* added support to check if error is not found and allow the operation to succeed if that's the case ([#25](https://github.com/abhimanyubabbar/rudder-iac/issues/25)) ([e297380](https://github.com/abhimanyubabbar/rudder-iac/commit/e297380a6321c8b3d6c4c18006bb5e0e11670d5f))
* added workflow to test and generate coverage report for codecov ([#32](https://github.com/abhimanyubabbar/rudder-iac/issues/32)) ([2a1a636](https://github.com/abhimanyubabbar/rudder-iac/commit/2a1a6364aa21cdd1718578adb253806b7e26bfc0))
* capture panics and perform recovery with logging the stack into the logfile ([#22](https://github.com/abhimanyubabbar/rudder-iac/issues/22)) ([5517329](https://github.com/abhimanyubabbar/rudder-iac/commit/5517329c0307acdf6cfabcc9b26d845c57df9e75))
* delete operation should remove resources from state ([#10](https://github.com/abhimanyubabbar/rudder-iac/issues/10)) ([e196bd6](https://github.com/abhimanyubabbar/rudder-iac/commit/e196bd601050b21c674e3214eca6006a10c4c8cc))
* implement dry run support in syncer ([#16](https://github.com/abhimanyubabbar/rudder-iac/issues/16)) ([3b8a999](https://github.com/abhimanyubabbar/rudder-iac/commit/3b8a99918943463a652d10f66c2b60efa2eeee69))
* implement state persistence using local filesystem ([#11](https://github.com/abhimanyubabbar/rudder-iac/issues/11)) ([ee55162](https://github.com/abhimanyubabbar/rudder-iac/commit/ee5516203a3d783986323f2734af95db4859dfc9))
* Implemented basic framework for syncing resources ([#4](https://github.com/abhimanyubabbar/rudder-iac/issues/4)) ([aecf3e5](https://github.com/abhimanyubabbar/rudder-iac/commit/aecf3e5db810b26c2784c3404ebcccbde022b1e1))
* isNil check on the values during diff to allow for mismatch caused by nil pointer ([#17](https://github.com/abhimanyubabbar/rudder-iac/issues/17)) ([d8f235e](https://github.com/abhimanyubabbar/rudder-iac/commit/d8f235e4ed7f2d586e44e18b08fb0fc2c5950969))
* logger package now writes logs to file ([#13](https://github.com/abhimanyubabbar/rudder-iac/issues/13)) ([23e80b3](https://github.com/abhimanyubabbar/rudder-iac/commit/23e80b33193349e9effad88fe66909c08e95d808))
* port API library from github.com/rudderlabs/rudder-api-go ([#2](https://github.com/abhimanyubabbar/rudder-iac/issues/2)) ([87fbe02](https://github.com/abhimanyubabbar/rudder-iac/commit/87fbe026031b0fe23341c7e7247f02144a7e128e))
* provider functions can return errors ([#7](https://github.com/abhimanyubabbar/rudder-iac/issues/7)) ([8a100b9](https://github.com/abhimanyubabbar/rudder-iac/commit/8a100b91980ae2ed97315987559e1c003422b338))
* syncer updats state after every operation, instead of at the end ([#15](https://github.com/abhimanyubabbar/rudder-iac/issues/15)) ([4722bb8](https://github.com/abhimanyubabbar/rudder-iac/commit/4722bb8d54f3b98fefb87324ea061c89093bf1fd))
* tp destroy command to remove all resources ([#19](https://github.com/abhimanyubabbar/rudder-iac/issues/19)) ([7fcc404](https://github.com/abhimanyubabbar/rudder-iac/commit/7fcc4049e9a4a2f661fd9957d23acc6e0daf00ce))
* ui improvements for asking the access token and reporting errors. ([#14](https://github.com/abhimanyubabbar/rudder-iac/issues/14)) ([e8e5651](https://github.com/abhimanyubabbar/rudder-iac/commit/e8e56511fc43ff2e2bc517ed30aadb2a0c8b64e9))


### Bug Fixes

* auth logic does not expect an access token to already exist in config ([#35](https://github.com/abhimanyubabbar/rudder-iac/issues/35)) ([f6fc990](https://github.com/abhimanyubabbar/rudder-iac/commit/f6fc990cc054b52afb25434ff9f5cd3ee5dffa5a))
* destroy command to carry forward the last good state in case the operation fails ([#23](https://github.com/abhimanyubabbar/rudder-iac/issues/23)) ([537fce1](https://github.com/abhimanyubabbar/rudder-iac/commit/537fce15f7815b3fd17229828f163d3afc61454a))
* error when trying to attach a property of multi-type to trackingplan ([#21](https://github.com/abhimanyubabbar/rudder-iac/issues/21)) ([cc302c1](https://github.com/abhimanyubabbar/rudder-iac/commit/cc302c1b2886311a86abc5b3743b6f51fed9acfa))
* fixed the issue of not detecting event changes in trackingplan ([#20](https://github.com/abhimanyubabbar/rudder-iac/issues/20)) ([7c532a7](https://github.com/abhimanyubabbar/rudder-iac/commit/7c532a7da210fa2a0b817fd465060824f3ec5308))
* handle the itemTypes on the property config properly ([#24](https://github.com/abhimanyubabbar/rudder-iac/issues/24)) ([84745da](https://github.com/abhimanyubabbar/rudder-iac/commit/84745dae3b71e292dbcc1043bf30edde49492c14))
* log the error in panic raised in addition to the stack trace ([#34](https://github.com/abhimanyubabbar/rudder-iac/issues/34)) ([2e86043](https://github.com/abhimanyubabbar/rudder-iac/commit/2e860430be5b54b047ca4fa7a3002260247a298b))
* update and delete provider functions also receive previous state as inputs ([#12](https://github.com/abhimanyubabbar/rudder-iac/issues/12)) ([679686c](https://github.com/abhimanyubabbar/rudder-iac/commit/679686c061428ee7064f5c0f29736231c43030b1))


### Miscellaneous

* add goreleaser workflow ([#28](https://github.com/abhimanyubabbar/rudder-iac/issues/28)) ([f0c7256](https://github.com/abhimanyubabbar/rudder-iac/commit/f0c72567066b14e6d70370ab413b74d3d57ba933))
* add goreleaser workflow ([#28](https://github.com/abhimanyubabbar/rudder-iac/issues/28)) ([#29](https://github.com/abhimanyubabbar/rudder-iac/issues/29)) ([1ef7bd2](https://github.com/abhimanyubabbar/rudder-iac/commit/1ef7bd28dcf6617d478a97c242aba08699cc153c))
* add release please support ([f1f7eed](https://github.com/abhimanyubabbar/rudder-iac/commit/f1f7eedbb140efb68f8e1ebe9eadccb7c1023b10))
* cleanup pulumi references ([#9](https://github.com/abhimanyubabbar/rudder-iac/issues/9)) ([827d999](https://github.com/abhimanyubabbar/rudder-iac/commit/827d999015b1ebc3244245ca246b4de2de123215))
* update goreleaser yaml format options ([#36](https://github.com/abhimanyubabbar/rudder-iac/issues/36)) ([2a760d0](https://github.com/abhimanyubabbar/rudder-iac/commit/2a760d0dbd38d42890dde0ceebcc4bd45727f32c))
* updated go to 1.22.10 ([#31](https://github.com/abhimanyubabbar/rudder-iac/issues/31)) ([2a17239](https://github.com/abhimanyubabbar/rudder-iac/commit/2a17239f9f9d81a51d675a80c73a0fcd95c0c105))
