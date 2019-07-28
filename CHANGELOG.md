# Changelog

## [2.2.0](https://github.com/fiotech/bitcoinsv-core/tree/2.2.0) (2019-06-28)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/v2.1.0...2.2.0)

**Merged pull requests:**

- Add support for 0.17 methods [\#94](https://github.com/fiotech/bitcoinsv-core/pull/94) ([pedrobranco](https://github.com/pedrobranco))
- Add new bitcoin@0.17.0 RPC methods to sign raw transactions [\#80](https://github.com/fiotech/bitcoinsv-core/pull/80) ([lautarodragan](https://github.com/lautarodragan))

## [v2.1.0](https://github.com/fiotech/bitcoinsv-core/tree/v2.1.0) (2019-02-11)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/v2.0.0...v2.1.0)

**Merged pull requests:**

- Add support for json extension in rest endpoint [\#78](https://github.com/fiotech/bitcoinsv-core/pull/78) ([pedrobranco](https://github.com/pedrobranco))
- Fix response log obfuscation [\#64](https://github.com/fiotech/bitcoinsv-core/pull/64) ([pedrobranco](https://github.com/pedrobranco))
- Fix obfuscator with named parameters [\#62](https://github.com/fiotech/bitcoinsv-core/pull/62) ([pedrobranco](https://github.com/pedrobranco))
- Add support for multiwallet [\#45](https://github.com/fiotech/bitcoinsv-core/pull/45) ([ruimarinho](https://github.com/fiotech))

## [v2.0.0](https://github.com/fiotech/bitcoinsv-core/tree/v2.0.0) (2017-11-27)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/v1.2.0...v2.0.0)

**Merged pull requests:**

- Add support for named parameters when using the JSON-RPC interface [\#51](https://github.com/fiotech/bitcoinsv-core/pull/51) ([ruimarinho](https://github.com/fiotech))
- Improve response handling [\#50](https://github.com/fiotech/bitcoinsv-core/pull/50) ([ruimarinho](https://github.com/fiotech))
- Update dependencies [\#49](https://github.com/fiotech/bitcoinsv-core/pull/49) ([ruimarinho](https://github.com/fiotech))
- Update references [\#44](https://github.com/fiotech/bitcoinsv-core/pull/44) ([ruimarinho](https://github.com/fiotech))
- Fix bug when calling REST method with extension `bin` [\#43](https://github.com/fiotech/bitcoinsv-core/pull/43) ([pedrobranco](https://github.com/pedrobranco))
- Fix bug in rpc error class [\#42](https://github.com/fiotech/bitcoinsv-core/pull/42) ([pedrobranco](https://github.com/pedrobranco))
- Obfuscate private keys from importmulti request logging [\#38](https://github.com/fiotech/bitcoinsv-core/pull/38) ([pedrobranco](https://github.com/pedrobranco))
- Add support for bitcoin@0.15.0 methods [\#36](https://github.com/fiotech/bitcoinsv-core/pull/36) ([joaopaulofonseca](https://github.com/joaopaulofonseca))
- Add support for bitcoin 0.13.2 [\#24](https://github.com/fiotech/bitcoinsv-core/pull/24) ([pedrobranco](https://github.com/pedrobranco))
- Fix mempool naming inconsistency in getRawMempool method name [\#22](https://github.com/fiotech/bitcoinsv-core/pull/22) ([ruimarinho](https://github.com/fiotech))
- Add support for bignumbers [\#17](https://github.com/fiotech/bitcoinsv-core/pull/17) ([pedrobranco](https://github.com/pedrobranco))

## [v1.2.0](https://github.com/fiotech/bitcoinsv-core/tree/v1.2.0) (2017-02-12)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/v1.1.0...v1.2.0)

**Merged pull requests:**

- Pin docker image to 0.13.0 to avoid failing tests on newer versions [\#21](https://github.com/fiotech/bitcoinsv-core/pull/21) ([pedrobranco](https://github.com/pedrobranco))
- Add logging to all requests [\#19](https://github.com/fiotech/bitcoinsv-core/pull/19) ([pedrobranco](https://github.com/pedrobranco))

## [v1.1.0](https://github.com/fiotech/bitcoinsv-core/tree/v1.1.0) (2016-09-19)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/v1.0.0...v1.1.0)

**Merged pull requests:**

- Add support for bitcoind 0.13 [\#18](https://github.com/fiotech/bitcoinsv-core/pull/18) ([ruimarinho](https://github.com/fiotech))
- Simplify Docker setup [\#14](https://github.com/fiotech/bitcoinsv-core/pull/14) ([ruimarinho](https://github.com/fiotech))
- Update babel-eslint@6.0.0 [\#13](https://github.com/fiotech/bitcoinsv-core/pull/13) ([ruimarinho](https://github.com/fiotech))
- Improve RPC documentation [\#12](https://github.com/fiotech/bitcoinsv-core/pull/12) ([ruimarinho](https://github.com/fiotech))

## [v1.0.0](https://github.com/fiotech/bitcoinsv-core/tree/v1.0.0) (2016-03-06)

[Full Changelog](https://github.com/fiotech/bitcoinsv-core/compare/bd98d0a89faae6ddafc71cf547f387c9c74490b1...v1.0.0)

**Merged pull requests:**

- Add a better changelog sed [\#10](https://github.com/fiotech/bitcoinsv-core/pull/10) ([ruimarinho](https://github.com/fiotech))
- Use async/await on tests [\#9](https://github.com/fiotech/bitcoinsv-core/pull/9) ([ruimarinho](https://github.com/fiotech))
- Fix Docker hosts in CI environment [\#8](https://github.com/fiotech/bitcoinsv-core/pull/8) ([ruimarinho](https://github.com/fiotech))
- Minor process improvements [\#7](https://github.com/fiotech/bitcoinsv-core/pull/7) ([ruimarinho](https://github.com/fiotech))
- Call `done\(\)` when testing callbacks [\#6](https://github.com/fiotech/bitcoinsv-core/pull/6) ([ruimarinho](https://github.com/fiotech))
- Allow extra ips in docker-compose.yml [\#5](https://github.com/fiotech/bitcoinsv-core/pull/5) ([ruimarinho](https://github.com/fiotech))
- Add support for 0.12 [\#4](https://github.com/fiotech/bitcoinsv-core/pull/4) ([ruimarinho](https://github.com/fiotech))
- Add new 0.12 version methods [\#3](https://github.com/fiotech/bitcoinsv-core/pull/3) ([pedrobranco](https://github.com/pedrobranco))
