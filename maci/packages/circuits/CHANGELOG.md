# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.3.0](https://github.com/privacy-scaling-explorations/maci/compare/v2.2.1...v2.3.0) (2024-09-05)


### Bug Fixes

* do not cleanup thread all the time while doing parallel proof gen ([#1808](https://github.com/privacy-scaling-explorations/maci/issues/1808)) ([d683cb3](https://github.com/privacy-scaling-explorations/maci/commit/d683cb35e3b1fb54df05e200be85386fb7328de5))


### Miscellaneous

* **ceremony:** update ceremony tests to work with v2 params and keys ([#1807](https://github.com/privacy-scaling-explorations/maci/issues/1807)) ([6bf1ffb](https://github.com/privacy-scaling-explorations/maci/commit/6bf1ffb42e4537dba52fb25b1fc7e370e9a39d76))



## [2.2.0](https://github.com/privacy-scaling-explorations/maci/compare/v2.1.0...v2.2.0) (2024-08-19)


### Miscellaneous

* **deps-dev:** bump @types/node from 22.1.0 to 22.2.0 ([ac18985](https://github.com/privacy-scaling-explorations/maci/commit/ac189852bf6abb787736c474ad87927afaa5163c))
* **deps-dev:** bump @types/node from 22.2.0 to 22.4.1 ([#1779](https://github.com/privacy-scaling-explorations/maci/issues/1779)) ([4a929e0](https://github.com/privacy-scaling-explorations/maci/commit/4a929e0b9a5c4de5ac0345e742668a3400798867))
* **deps-dev:** bump fast-check from 3.20.0 to 3.21.0 ([63baf2c](https://github.com/privacy-scaling-explorations/maci/commit/63baf2cd3e000f36fd426f4cf65c2f01d6858642))
* **deps-dev:** bump mocha from 10.7.0 to 10.7.3 ([6ba908f](https://github.com/privacy-scaling-explorations/maci/commit/6ba908f5f78628aa6afe973b3d71ae54ff08c735))



## [2.1.0](https://github.com/privacy-scaling-explorations/maci/compare/v2.0.0...v2.1.0) (2024-08-07)


### Bug Fixes

* **circuits:** use dynamic imports for promisify ([d5c2d11](https://github.com/privacy-scaling-explorations/maci/commit/d5c2d1127bb26f2abb5079dc4afe62f2d491f21c))


### Miscellaneous

* **circuits:** add constraint info print script ([a9cc93e](https://github.com/privacy-scaling-explorations/maci/commit/a9cc93e975b845419a366a07573c27aabdc1bf35))



## [2.0.0](https://github.com/privacy-scaling-explorations/maci/compare/v1.2.0...v2.0.0) (2024-08-06)


### ⚠ BREAKING CHANGES

* **topup:** No more topups

### Features

* **coordinator:** deploy subgraph from coordinator service ([d04d82c](https://github.com/privacy-scaling-explorations/maci/commit/d04d82cb4a3e022471726f87b24b2ee14b8ae0a2))
* **coordinator:** update authorization ([47ef8ab](https://github.com/privacy-scaling-explorations/maci/commit/47ef8abf3c433f3992feddcced3a9ac5e1cb2cc4))
* export merge function and modify package version ([#1584](https://github.com/privacy-scaling-explorations/maci/issues/1584)) ([f6ae34a](https://github.com/privacy-scaling-explorations/maci/commit/f6ae34a3f9ea375cd5dac8f0ce8618e33509f8ad))
* **multiple-polls:** allow concurrent polls ([14e89ba](https://github.com/privacy-scaling-explorations/maci/commit/14e89baea1ede9bc9bad79fafb5c362d6a6a81e9))


### Bug Fixes

* add coordinator public key hash public input ([9766bbf](https://github.com/privacy-scaling-explorations/maci/commit/9766bbfcecd41bd0f39c1422978d959705b1b500))
* **circuits:** ensure we check index < numSignups ([adeb6b8](https://github.com/privacy-scaling-explorations/maci/commit/adeb6b8fbcca01fdc73168cd73b66301f5268eaf))
* **circuits:** remove only for circuits tests ([6b6e82b](https://github.com/privacy-scaling-explorations/maci/commit/6b6e82bb026947cf099e70a01f3e6f0fb823222d))
* typos workflow ([b36898c](https://github.com/privacy-scaling-explorations/maci/commit/b36898c1e5aad05ff77fdf91f0660055ff428fa9))


### Code Refactoring

* **circuits:** remove duplicate constraints ([#1644](https://github.com/privacy-scaling-explorations/maci/issues/1644)) ([cd7ea49](https://github.com/privacy-scaling-explorations/maci/commit/cd7ea492aaace4c0aaa0c50ce0449a35eb8013d1))
* **circuits:** simplify generatePathIndices templates ([2ee32f4](https://github.com/privacy-scaling-explorations/maci/commit/2ee32f470fb8d2dbb02bdea2769166754c480706))
* enhance MACI circuits readability  ([#1337](https://github.com/privacy-scaling-explorations/maci/issues/1337)) ([3770a2a](https://github.com/privacy-scaling-explorations/maci/commit/3770a2ab6626c4beffb71e7b2d9dce595e5e9f53))
* **maci:** remove subsidy feature to simplify further protocol improvements ([52fc7c5](https://github.com/privacy-scaling-explorations/maci/commit/52fc7c5b8f2d389868bca6171ffd15a94b1d1659))
* **topup:** remove the topup feature ([67711d4](https://github.com/privacy-scaling-explorations/maci/commit/67711d44058831302d4556f12d1972ffacede653))


### Miscellaneous

* add @types/snarkjs package ([57bf0ed](https://github.com/privacy-scaling-explorations/maci/commit/57bf0edf4453d18c7c154ae928c30899b6996ebd))
* add doc entries for new maci version (currently being developed) ([c72a130](https://github.com/privacy-scaling-explorations/maci/commit/c72a130cf6dcd4e8e5e59b374d8a63c1cfaae8cd))
* bump to 1.2.2 ([e63278f](https://github.com/privacy-scaling-explorations/maci/commit/e63278f71937a1fa908ec8f4be2d43114701c134))
* **ceremony:** update ceremony params tests ([b78830d](https://github.com/privacy-scaling-explorations/maci/commit/b78830d921d39952fbbca0fe7529340ee47ca59f))
* **circuits:** add fuzz tests for incremental quinary tree ([#1520](https://github.com/privacy-scaling-explorations/maci/issues/1520)) ([7a812ef](https://github.com/privacy-scaling-explorations/maci/commit/7a812efc13250cf98754341f772f87ed00da3d09))
* **circuits:** optimize converting message to command ([#1681](https://github.com/privacy-scaling-explorations/maci/issues/1681)) ([be7a659](https://github.com/privacy-scaling-explorations/maci/commit/be7a6598b7aeab2e11717bea509c697d61b556db))
* **circuits:** optimize message to command ([#1682](https://github.com/privacy-scaling-explorations/maci/issues/1682)) ([ad04340](https://github.com/privacy-scaling-explorations/maci/commit/ad04340972f3d35a8d4915227d15c5502af7fe63))
* cleanup circuits folder and update docs ([122c1f7](https://github.com/privacy-scaling-explorations/maci/commit/122c1f72fb3ce309a51479669e8d819a463cb956))
* **cleanup:** remove references to topup ([1cda690](https://github.com/privacy-scaling-explorations/maci/commit/1cda690ceaaac49525e02fffcbaa11bad77541e8))
* **deps-dev:** bump @types/mocha from 10.0.6 to 10.0.7 ([07c3480](https://github.com/privacy-scaling-explorations/maci/commit/07c3480efc40ad1d3f651b78cd7c3aaeee8d7f8a))
* **deps-dev:** bump @types/node from 20.11.20 to 20.11.24 ([c575eca](https://github.com/privacy-scaling-explorations/maci/commit/c575eca7c54c262764ce794a919f3b1d58d7d8e7))
* **deps-dev:** bump @types/node from 20.11.24 to 20.11.25 ([5eb49f9](https://github.com/privacy-scaling-explorations/maci/commit/5eb49f9090fc6db3a80ad2d63548d93430ff7645))
* **deps-dev:** bump @types/node from 20.11.25 to 20.11.28 ([81bebaa](https://github.com/privacy-scaling-explorations/maci/commit/81bebaa880cbc15b8c8445d412b9fc9d89580e67))
* **deps-dev:** bump @types/node from 20.11.28 to 20.11.30 ([5ef4420](https://github.com/privacy-scaling-explorations/maci/commit/5ef44209d16cd441067fb67201daa61cf968382d))
* **deps-dev:** bump @types/node from 20.11.30 to 20.12.2 ([e7c32d0](https://github.com/privacy-scaling-explorations/maci/commit/e7c32d0ddd506727f229d950239a116961bbe1a0))
* **deps-dev:** bump @types/node from 20.12.10 to 20.12.11 ([3019c66](https://github.com/privacy-scaling-explorations/maci/commit/3019c66eb70e54b376e9464417e073bd98d96b6a))
* **deps-dev:** bump @types/node from 20.12.11 to 20.12.12 ([bd0a0a5](https://github.com/privacy-scaling-explorations/maci/commit/bd0a0a5a1ec685542c2af4f6962186176d5453ba))
* **deps-dev:** bump @types/node from 20.12.2 to 20.12.5 ([588392f](https://github.com/privacy-scaling-explorations/maci/commit/588392f2f773addce0204f236fc26981ead1f7bb))
* **deps-dev:** bump @types/node from 20.12.5 to 20.12.7 ([f1b00de](https://github.com/privacy-scaling-explorations/maci/commit/f1b00deb29788e390dcecd5b1741339f96f06f73))
* **deps-dev:** bump @types/node from 20.12.7 to 20.12.10 ([cf5026a](https://github.com/privacy-scaling-explorations/maci/commit/cf5026a42a41c0078467fb477fdd51a2afb31e1f))
* **deps-dev:** bump @types/node from 20.14.10 to 20.14.11 ([01564c0](https://github.com/privacy-scaling-explorations/maci/commit/01564c0503379ca65ce90ea77fdc5ebcd9ae81c5))
* **deps-dev:** bump @types/node from 20.14.11 to 22.1.0 ([#1732](https://github.com/privacy-scaling-explorations/maci/issues/1732)) ([3c4b9d9](https://github.com/privacy-scaling-explorations/maci/commit/3c4b9d9c9eb7439c4ea9791e4388ff586530be50))
* **deps-dev:** bump @types/node from 20.14.2 to 20.14.8 ([636ac22](https://github.com/privacy-scaling-explorations/maci/commit/636ac22bd29d12e5af7f69c7dd639d0223595992))
* **deps-dev:** bump @types/node from 20.14.8 to 20.14.10 ([add0ce4](https://github.com/privacy-scaling-explorations/maci/commit/add0ce4e406fea4bfe2b839facc6a0a33b3fe3bf))
* **deps-dev:** bump chai-as-promised from 7.1.1 to 7.1.2 ([6930a1c](https://github.com/privacy-scaling-explorations/maci/commit/6930a1c6590f0b8d9971ac38bf06d44f90b88760))
* **deps-dev:** bump fast-check from 3.19.0 to 3.20.0 ([5e0796b](https://github.com/privacy-scaling-explorations/maci/commit/5e0796bac212e78a4ebc01b4a78cc4cf66309d8e))
* **deps-dev:** bump mocha from 10.3.0 to 10.4.0 ([7bf5afe](https://github.com/privacy-scaling-explorations/maci/commit/7bf5afe954bcb6b34dbe7f109c9c7e8d5396f1b2))
* **deps-dev:** bump mocha from 10.4.0 to 10.5.0 ([e5c14cf](https://github.com/privacy-scaling-explorations/maci/commit/e5c14cf01e9b5beb6232e80345121dbb47190fd0))
* **deps-dev:** bump mocha from 10.5.0 to 10.6.0 ([6847bb3](https://github.com/privacy-scaling-explorations/maci/commit/6847bb374893672bf7e809fc80d124e2d874b784))
* **deps-dev:** bump mocha from 10.6.0 to 10.7.0 ([#1687](https://github.com/privacy-scaling-explorations/maci/issues/1687)) ([2cad35b](https://github.com/privacy-scaling-explorations/maci/commit/2cad35bab133af79f77ea9c19098d3561ba06f69))
* **deps-dev:** bump typescript from 5.3.3 to 5.4.2 ([591c767](https://github.com/privacy-scaling-explorations/maci/commit/591c767308f746fbfc32a9f184192912895f080c))
* **deps-dev:** bump typescript from 5.4.2 to 5.4.3 ([a2f5c8a](https://github.com/privacy-scaling-explorations/maci/commit/a2f5c8ac32394fc7672051d5342baf7e6f9567ce))
* **deps-dev:** bump typescript from 5.4.3 to 5.4.4 ([5e047ea](https://github.com/privacy-scaling-explorations/maci/commit/5e047eaa96d508addf34e35764ddaf4deb221593))
* **deps-dev:** bump typescript from 5.4.4 to 5.4.5 ([ea6339d](https://github.com/privacy-scaling-explorations/maci/commit/ea6339da96dda38a931cb6d39615c9267ca45b81))
* **deps-dev:** bump typescript from 5.4.5 to 5.5.2 ([e2b4d45](https://github.com/privacy-scaling-explorations/maci/commit/e2b4d45235c82bba349d959a164442cae90ad97f))
* **deps-dev:** bump typescript from 5.5.2 to 5.5.3 ([c979188](https://github.com/privacy-scaling-explorations/maci/commit/c979188358becfc4b434a2f73331e640ce595846))
* **deps-dev:** bump typescript from 5.5.3 to 5.5.4 ([8ed2e2b](https://github.com/privacy-scaling-explorations/maci/commit/8ed2e2b109a950137dd289aa7d3eca4268079272))
* **deps:** bump @zk-kit/circuits from 0.3.0 to 0.4.0 ([49f098f](https://github.com/privacy-scaling-explorations/maci/commit/49f098fcce122589bc9a07cbfd1863878939df2a))
* **deps:** bump circomkit from 0.0.24 to 0.0.25 ([b3eccf8](https://github.com/privacy-scaling-explorations/maci/commit/b3eccf86587edd9b2f4193894c0608f1a2aec677))
* **deps:** bump circomkit from 0.0.25 to 0.1.0 ([09a1ccf](https://github.com/privacy-scaling-explorations/maci/commit/09a1ccf3b33b3377d4abc38cb345d2927ff9fc79))
* **deps:** bump circomkit from 0.1.0 to 0.2.1 ([#1480](https://github.com/privacy-scaling-explorations/maci/issues/1480)) ([9cb775f](https://github.com/privacy-scaling-explorations/maci/commit/9cb775fab5ee8a04e17bcbef533a1ab8d2414446))
* **deps:** bump snarkjs from 0.7.3 to 0.7.4 ([50642af](https://github.com/privacy-scaling-explorations/maci/commit/50642afa368a91c47ebe32089f4bdb4a159ac1cd))
* **docs:** fixed broken links ([#1585](https://github.com/privacy-scaling-explorations/maci/issues/1585)) ([4b2012e](https://github.com/privacy-scaling-explorations/maci/commit/4b2012eb3827611e8a7fb0d441e6fd1da8df478e))
* fuzz testing for circuits ([429bd12](https://github.com/privacy-scaling-explorations/maci/commit/429bd126a73094a6e54f78a3c3817b3fab704be3))
* optimize message processor and tally ([d75b244](https://github.com/privacy-scaling-explorations/maci/commit/d75b2446c2ee012d146afe8d7bc423f5b94e4579))
* **release:** publish 1.2.1 ([93564f8](https://github.com/privacy-scaling-explorations/maci/commit/93564f8a98baa0fee65db16e2e40209d9ac1b3ae))
* **release:** publish 2.0.0 ([04e647d](https://github.com/privacy-scaling-explorations/maci/commit/04e647d231df34952569ad6ff802e0b2333eb658))
* remove max values ([8f951b0](https://github.com/privacy-scaling-explorations/maci/commit/8f951b0fcc73212d99d3ddc962fbaa9788471fb6))
* use async fs instead of sync version ([fb8317e](https://github.com/privacy-scaling-explorations/maci/commit/fb8317ef3943a8434083de6e1b0f9469f15dd113))



## [1.2.0](https://github.com/privacy-scaling-explorations/maci/compare/v1.1.1...v1.2.0) (2024-02-23)


### Features

* **circuits:** remove circomlib fork in favour of latest and zk-kit ([bf11b40](https://github.com/privacy-scaling-explorations/maci/commit/bf11b4092cd531cf0993534061cf7c24e8de44e2)), closes [#772](https://github.com/privacy-scaling-explorations/maci/issues/772)
* **circuits:** remove zkey-manager in favour of circomkit ([d79e9c0](https://github.com/privacy-scaling-explorations/maci/commit/d79e9c0ee18df27c3bd3e5e49924db21303d1c45))
* **contracts:** return contract addresses when deploying the poll contract ([e94998c](https://github.com/privacy-scaling-explorations/maci/commit/e94998c12d8a5f2bde2fb54b4af384d42e35d646))
* **proofs:** make preferred witness type in circuit's genProof function ([2b95044](https://github.com/privacy-scaling-explorations/maci/commit/2b95044921cd0bed72694d069e2f9ed8fa44e72e))
* **qv:** add optional flag to use quadratic voting or not in MACI ([86ba854](https://github.com/privacy-scaling-explorations/maci/commit/86ba8548780049245482e5277cc47f4a8776e9e6))


### Bug Fixes

* **add safelessthan:** add SafeLessThan in utility.circom and use it in incrementalQuinnTree.circom ([60727d4](https://github.com/privacy-scaling-explorations/maci/commit/60727d4d10406edda32ad28e53d399d41d45ed88))
* **build:** fix bug that prevented c witness from being compiled ([d22caad](https://github.com/privacy-scaling-explorations/maci/commit/d22caadca15dc6de639720faf1d9a53259714ce8))
* **circuits:** enforce use of stateIndex from message ([510e6ee](https://github.com/privacy-scaling-explorations/maci/commit/510e6ee365958e8c7f72cfca6cea75d15a89d28b))
* **circuits:** ensure we account for correct num signups in messageValidator ([04c847c](https://github.com/privacy-scaling-explorations/maci/commit/04c847cbc3f34979f292ec7561109f14e274efaf))
* **circuits:** fix coordinator censoring by passing currentVoteWeight = 0 ([22e091d](https://github.com/privacy-scaling-explorations/maci/commit/22e091d2941b5e86ecd7df2f228bd0e10b6c4c47))
* **circuits:** replace execSync with execFileSync ([4c121ca](https://github.com/privacy-scaling-explorations/maci/commit/4c121ca0413495979be7af87da5474a9f0b093bf))
* **contracts:** save numSignups after merging maciStateAq inside the Poll contract ([4985b2d](https://github.com/privacy-scaling-explorations/maci/commit/4985b2d61655f3b802186fc03c2d85a658c0f0da)), closes [#1091](https://github.com/privacy-scaling-explorations/maci/issues/1091)
* **crypto:** get rid of potential prototype polution ([9b8a97c](https://github.com/privacy-scaling-explorations/maci/commit/9b8a97cc9661e0ee6f535cdcab19b4aa0fa98136))
* fixed the maci-circuit package to allow building on circom >2.0.7 ([e954f78](https://github.com/privacy-scaling-explorations/maci/commit/e954f78224d53342826bfe73b082b673e0f147c8))
* **incrementalquintree:** remove unnecessary condition check in incrementalQuinnTree.circom ([87b3397](https://github.com/privacy-scaling-explorations/maci/commit/87b339790a5d44adb8c5bf447346e16933c48d5c))
* **publish:** ensure we publish the correct files ([bc42724](https://github.com/privacy-scaling-explorations/maci/commit/bc42724b34cf0c047c5692fbf477ed013a102aee))
* remove trailing chars ([3101a60](https://github.com/privacy-scaling-explorations/maci/commit/3101a6016ebda3385273b47b2de33f5fd9c1221f))
* **safelessthan:** replaced several LessThan with SafeLessThan; fixed check on enoughVoiceCredit ([2d7a3a0](https://github.com/privacy-scaling-explorations/maci/commit/2d7a3a0efd33dfc3a5f4d3f95bec3adda7abb963))
* **topup:** check valid new state leaf balance ([ec12d2b](https://github.com/privacy-scaling-explorations/maci/commit/ec12d2b1ec31b0607f65be49a5679fcae5e3939d))


### Code Refactoring

* **circuits:** fix ts types, improve docs ([a849486](https://github.com/privacy-scaling-explorations/maci/commit/a84948685d2e4be426cef50c5c608c107b5142b1))
* **core:** refactor the core package subsidy and tally functions ([0af7dd2](https://github.com/privacy-scaling-explorations/maci/commit/0af7dd2d448c4796c3872665d43654343f9fc3e3))
* **core:** refactor the process message functions and general cleanup ([823cacd](https://github.com/privacy-scaling-explorations/maci/commit/823cacd8659281b8390b74c8d765b23ee7a83a80))
* **core:** remove unnecessary messageAq from Poll ([d3930f7](https://github.com/privacy-scaling-explorations/maci/commit/d3930f706963747903305cce1ee5a716ea28c31d))
* **core:** remove unnecessary stateAq from MaciState ([22a4f28](https://github.com/privacy-scaling-explorations/maci/commit/22a4f286010ff5add413eee88d933c0e74898346))
* **crypto:** remove ffjavascript and implement utils functions locally ([0b2986f](https://github.com/privacy-scaling-explorations/maci/commit/0b2986fcaadbfce37ff9fc0007ddeae97573924e)), closes [#458](https://github.com/privacy-scaling-explorations/maci/issues/458)
* fix ESLint issues ([6c0ed97](https://github.com/privacy-scaling-explorations/maci/commit/6c0ed97c0976a81b5e5506699d550ec93a553cb8))
* **maci-core:** refactor directory structure for quick core component access ([3aeba77](https://github.com/privacy-scaling-explorations/maci/commit/3aeba77435fbd783e5cecf88a1f2c0d4c58c8022))
* **nonqv:** optimize tally votes non qv circuit and contracts ([ea632a9](https://github.com/privacy-scaling-explorations/maci/commit/ea632a97862c4304c764f511ab480b3664224b5f))
* **optimisedmt:** remove dependency and implement locally ([c7d81e2](https://github.com/privacy-scaling-explorations/maci/commit/c7d81e20aaf6308c7d4e1efc09c497729f6a8f10))
* **remove messageaqfactory:** remove messageAqFactory; remove redundant pollFactory dependency ([dcd1c67](https://github.com/privacy-scaling-explorations/maci/commit/dcd1c67f14f0cb92979d13e7887373ff6e354a6f))
* **repo:** remove redundant code from certain packages ([d55497a](https://github.com/privacy-scaling-explorations/maci/commit/d55497a9805812b2d2472386caecf75995d6efcf))


### Miscellaneous

* add a badges to README.md ([888524b](https://github.com/privacy-scaling-explorations/maci/commit/888524baae82d56edbf0c794e587de174906c34c))
* add test file routes to circuit test commands ([6f0228f](https://github.com/privacy-scaling-explorations/maci/commit/6f0228f115211f8cf6581d7e80438791f98f6de0))
* add types check ([69f038f](https://github.com/privacy-scaling-explorations/maci/commit/69f038f55e6c740d43b8b5376db999bcf92de845))
* apply prettier ([8b905c0](https://github.com/privacy-scaling-explorations/maci/commit/8b905c0948d4a1f950653c6812067ec98ebfcbc8))
* bundle size optimizations ([18da49c](https://github.com/privacy-scaling-explorations/maci/commit/18da49c791e53350158659df8248d48af8e80f6d))
* **ceremony:** add circuit tests with ceremony params ([58611db](https://github.com/privacy-scaling-explorations/maci/commit/58611dbf62f2dc01cf978d6bf01cf15bdef77356))
* **changelog:** add CHANGELOG of v1.1.1 ([f0c315a](https://github.com/privacy-scaling-explorations/maci/commit/f0c315a4c1b86f88839f2dbe4c4b9f59193f7be4))
* **circuits:** integrate linter ([93e8a65](https://github.com/privacy-scaling-explorations/maci/commit/93e8a657fccb3232b18bf191984c6bea5ccabf85))
* **circuits:** refactor and add tests for the circom circuits ([4d6419b](https://github.com/privacy-scaling-explorations/maci/commit/4d6419b4962af6e94929721a3008406b6bc29c1e))
* **circuits:** remove todo messages ([071acc4](https://github.com/privacy-scaling-explorations/maci/commit/071acc42322be736932ef05d6e02356da4808bda))
* **cli:** optimize bundle size ([39268b2](https://github.com/privacy-scaling-explorations/maci/commit/39268b2ff8e0d27d062c6d3bc52a63ce8038ec5e))
* **contract:** apply linter for deploy scripts and contracts ([9af9c04](https://github.com/privacy-scaling-explorations/maci/commit/9af9c0497a2491eaf89fbff475cf0f60bc04f59c))
* **contracts:** add proof generation for task coordinator ([c145883](https://github.com/privacy-scaling-explorations/maci/commit/c145883ecc42b87170a401894b68cd2287d15832))
* **core:** add `CircuitInputs` type ([c4b72b0](https://github.com/privacy-scaling-explorations/maci/commit/c4b72b0f0b25a1bb147348a728a9550c8b6460a1))
* **core:** add Typedoc comments ([a8521ee](https://github.com/privacy-scaling-explorations/maci/commit/a8521eea97bca47298bc2c59ae1c31df9533258b))
* **core:** integrate linter ([614e76b](https://github.com/privacy-scaling-explorations/maci/commit/614e76b1b1de5d2c9876b11f15439e92b86db8f6))
* **dependencies:** update project dependencies and remove redundant ones ([4c5ac27](https://github.com/privacy-scaling-explorations/maci/commit/4c5ac27767492c9867a6e2ab2acd6b10fe132847))
* **deps-dev:** bump @types/node from 18.19.6 to 20.10.8 ([6645120](https://github.com/privacy-scaling-explorations/maci/commit/664512038212d36d40799e8c4787847735bd7d82))
* **deps-dev:** bump @types/node from 20.10.8 to 20.11.0 ([805d253](https://github.com/privacy-scaling-explorations/maci/commit/805d2536a54478c51403362419ecad0b6ab736a7))
* **deps-dev:** bump @types/node from 20.11.0 to 20.11.2 ([45839e8](https://github.com/privacy-scaling-explorations/maci/commit/45839e8c2668ec56ea06221758605f88029ea8a1))
* **deps-dev:** bump @types/node from 20.11.10 to 20.11.16 ([8144919](https://github.com/privacy-scaling-explorations/maci/commit/8144919939f7d9a841eb6fce7182628cedbf8746))
* **deps-dev:** bump @types/node from 20.11.16 to 20.11.17 ([44de5db](https://github.com/privacy-scaling-explorations/maci/commit/44de5db0c25a5fdfd5c13c397f49edb7185bf1f5))
* **deps-dev:** bump @types/node from 20.11.17 to 20.11.19 ([8d86b32](https://github.com/privacy-scaling-explorations/maci/commit/8d86b32ef70b89f4239aad3903fd36937cf6a90f))
* **deps-dev:** bump @types/node from 20.11.2 to 20.11.5 ([7698ede](https://github.com/privacy-scaling-explorations/maci/commit/7698edef2b95bc017e54c1fc0d796ccc9da3de85))
* **deps-dev:** bump @types/node from 20.11.5 to 20.11.10 ([a2c445a](https://github.com/privacy-scaling-explorations/maci/commit/a2c445a295e792e421f6c1537b2b21f8a7648683))
* **deps-dev:** bump lerna from 6.6.2 to 8.0.2 ([4b150ad](https://github.com/privacy-scaling-explorations/maci/commit/4b150ade7c4fbaf88eb0e1f629cec6749377706d))
* **deps-dev:** bump mocha from 10.2.0 to 10.3.0 ([2b76e04](https://github.com/privacy-scaling-explorations/maci/commit/2b76e0445f5da5864a335352f66eac33c070ab29))
* **deps-dev:** bump typescript from 5.2.2 to 5.3.3 ([4ec399d](https://github.com/privacy-scaling-explorations/maci/commit/4ec399dd6e984c12ebd24d0b20c14c1104872500))
* **deps:** bump circomkit from 0.0.21 to 0.0.22 ([1c4e405](https://github.com/privacy-scaling-explorations/maci/commit/1c4e4051920e84df88a28b1ed908ee8e6d3266b8))
* **deps:** bump circomkit from 0.0.22 to 0.0.24 ([2ff4d38](https://github.com/privacy-scaling-explorations/maci/commit/2ff4d380d6601e363abd2435d59ac150ca2c190f))
* **deps:** bump snarkjs from 0.7.2 to 0.7.3 ([cf95b6f](https://github.com/privacy-scaling-explorations/maci/commit/cf95b6ff6f66342e3b75dedd5c70d62f8f0816b1))
* **deps:** update circomkit to latest version and add console logs ([9f7ec50](https://github.com/privacy-scaling-explorations/maci/commit/9f7ec50dadcfb1a27bccb845f1552a2af2b8b1f2))
* linter ([42ea4f0](https://github.com/privacy-scaling-explorations/maci/commit/42ea4f0ae8b342f6bd5ca5ac86f1bdd143978324))
* linter unification ([61a8bcd](https://github.com/privacy-scaling-explorations/maci/commit/61a8bcd915fd3e4b4da3c00d40704d892c02f51b))
* **maci:** added README for the circuit package and fixed typo in contract's README ([4d0f74b](https://github.com/privacy-scaling-explorations/maci/commit/4d0f74b8480cd2d20e835d43b33c2aab6578d194))
* **maci:** updated docs after review ([fd0da34](https://github.com/privacy-scaling-explorations/maci/commit/fd0da346406a5c2c6648bbff1b081863039bcf2b)), closes [#531](https://github.com/privacy-scaling-explorations/maci/issues/531) [#556](https://github.com/privacy-scaling-explorations/maci/issues/556)
* **poll:** unify pollId type ([21d01ef](https://github.com/privacy-scaling-explorations/maci/commit/21d01efc565df74ea8b71dfeeead60be5a07db56))
* **publishing:** remove bash script for empty ballot roots contract ([025287c](https://github.com/privacy-scaling-explorations/maci/commit/025287c778547e0acb1582532f3412e022cca6fa))
* **release:** publish 1.1.2 ([10b3a85](https://github.com/privacy-scaling-explorations/maci/commit/10b3a85cc9b53c0fc1ccdf54221a48ec8d6efe0d))
* remove `gitHead` field from package.json ([d38ba71](https://github.com/privacy-scaling-explorations/maci/commit/d38ba71301469f350b3d80eab5bf94e779dda9cc))
* run prettier ([d09cd0e](https://github.com/privacy-scaling-explorations/maci/commit/d09cd0e01ac747245307ceec5343d9ed30d7a6f0))
* run prettier fix after bumping version ([e1f85a5](https://github.com/privacy-scaling-explorations/maci/commit/e1f85a53bbb72696b6998af5406748fd18df4701))
* **topup:** implement test cases for the topup feature ([7775a8b](https://github.com/privacy-scaling-explorations/maci/commit/7775a8b3295f29b098446d3e78a4200c03c847dd))
* update circomlib dependency format in package.json ([f0e8d19](https://github.com/privacy-scaling-explorations/maci/commit/f0e8d1978db6a0771d876b828843bc763e397220))
* update README with build guide for MACI circuits ([77fdb63](https://github.com/privacy-scaling-explorations/maci/commit/77fdb63c9993612117505bc8319555321bf8b9d0))



## [1.1.2](https://github.com/gurrpi/maci/compare/v1.1.1...v1.1.2) (2023-01-19)

### Code Refactoring

- **remove messageaqfactory:** remove messageAqFactory; remove redundant pollFactory dependency ([dcd1c67](https://github.com/gurrpi/maci/commit/dcd1c67f14f0cb92979d13e7887373ff6e354a6f))

### Miscellaneous

- add a badges to README.md ([888524b](https://github.com/gurrpi/maci/commit/888524baae82d56edbf0c794e587de174906c34c))
- **changelog:** add CHANGELOG of v1.1.1 ([ea1f0ca](https://github.com/gurrpi/maci/commit/ea1f0ca93f1618df0ba046f1f01b2abad57e0ee1))
- **maci:** added README for the circuit package and fixed typo in contract's README ([4d0f74b](https://github.com/gurrpi/maci/commit/4d0f74b8480cd2d20e835d43b33c2aab6578d194))
- **maci:** updated docs after review ([fd0da34](https://github.com/gurrpi/maci/commit/fd0da346406a5c2c6648bbff1b081863039bcf2b)), closes [#531](https://github.com/gurrpi/maci/issues/531) [#556](https://github.com/gurrpi/maci/issues/556)

## [1.1.1](https://github.com/gurrpi/maci/compare/v1.1.0...v1.1.1) (2022-12-03)

### Bug Fixes

- **core/ts/macistate.ts:** fix nothing_up_to_my_sleeve bug in MaciState.ts as well as unit tests ([3d2b21f](https://github.com/gurrpi/maci/commit/3d2b21f185c285542b92512a871b0886a3fedc83))
- **float.circom:** add a\*b overflow check ([c9a24ba](https://github.com/gurrpi/maci/commit/c9a24bac757568d1d46ec0d876d67bdc82f770ba))
- **float.circom:** rewrite float.circom ([efd4617](https://github.com/gurrpi/maci/commit/efd4617724e956d2566062c6fe882e1d45cba7c4))
- **maci:** reverted a fix and fixed test suits ([8300cc5](https://github.com/gurrpi/maci/commit/8300cc548e954a80ab6fb39ab9d559c999e07c10))
- **maci:** upgraded minor version and fixed bug in testnet deployment ([5ef5ed8](https://github.com/gurrpi/maci/commit/5ef5ed842360277ac823c6919e171d0c51ff5702)), closes [#551](https://github.com/gurrpi/maci/issues/551) [#552](https://github.com/gurrpi/maci/issues/552)
- **maci:** upgraded snarkjs and other dependencies ([0ce643a](https://github.com/gurrpi/maci/commit/0ce643a18704c1a2d9245e8e85032874a11f004e))
- **processmessages.circom:** data are not fully verified during state update ([6df6a40](https://github.com/gurrpi/maci/commit/6df6a4054da926b07f35c5befab4f1f8af33dcc6))
- **topupcredit.sol, subsidy.circom:** add comments for upper bound of constants ([c8eb37a](https://github.com/gurrpi/maci/commit/c8eb37ad593ee671652f11458909df2a95db3581))

### Reverts

- **circuits:** revert snarkjs upgrade ([b045893](https://github.com/gurrpi/maci/commit/b045893e18f105ce2019ab9d010aa57ef896adc8))
