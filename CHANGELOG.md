### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

#### [v1.10.2](https://github.com/leolabs/ableton.js/compare/v1.10.1...v1.10.2)

> 2 June 2020

- :sparkles: Implement the ability to get the current time in smpte format [`e23c9cc`](https://github.com/leolabs/ableton.js/commit/e23c9cc63cd12c0bf6e8f4e4192abbbb18084717)
- :pencil2: Add AbleSet link to the readme [`95dc859`](https://github.com/leolabs/ableton.js/commit/95dc8599ac9d33ccfc2bdc95ffabe3b44300b07e)
- :pencil2: Add AbleSet section to readme [`5d40bf2`](https://github.com/leolabs/ableton.js/commit/5d40bf2ece2afc732b59e6b33ed457b282cf0e41)

#### [v1.10.1](https://github.com/leolabs/ableton.js/compare/v1.10.0...v1.10.1)

> 29 May 2020

- :wrench: Update ports again because NTKDaemon uses them [`e581ada`](https://github.com/leolabs/ableton.js/commit/e581ada288058cb60006476c1ab5bd8faa34fd9a)

#### [v1.10.0](https://github.com/leolabs/ableton.js/compare/v1.9.2...v1.10.0)

> 19 April 2020

- :wrench: Update ports because they're clashing with NI's NTKDaemon again [`5e69043`](https://github.com/leolabs/ableton.js/commit/5e6904306973227e26347a7e636212a0c66371e4)

#### [v1.9.2](https://github.com/leolabs/ableton.js/compare/v1.9.1...v1.9.2)

> 12 March 2020

- :zap: Don't stringify set data [`ddc1596`](https://github.com/leolabs/ableton.js/commit/ddc1596c8a38e44483bca88b1b4d1153a3f035e8)
- :wrench: Increase max UDP packet size to 60500 bytes [`6233dd9`](https://github.com/leolabs/ableton.js/commit/6233dd9b1b239f8dbe233e71de055f9f0c637233)

#### [v1.9.1](https://github.com/leolabs/ableton.js/compare/v1.9.0...v1.9.1)

> 10 March 2020

- :construction: Add jsdoc to generate docs during build [`bdb5ad4`](https://github.com/leolabs/ableton.js/commit/bdb5ad40f05eedd6c37463adcf18822ac51f5b6c)
- :pencil: Automatically generate a changelog on publish [`141354a`](https://github.com/leolabs/ableton.js/commit/141354a019d3c2eb67bfa9ab2e52ef24a46628f9)
- :bug: time and name properties of cues are read-only, remove them from settableProperties [`87493de`](https://github.com/leolabs/ableton.js/commit/87493de49ab890d55f27351aadd5237f6d2fa433)

#### [v1.9.0](https://github.com/leolabs/ableton.js/compare/v1.8.5...v1.9.0)

> 10 March 2020

- :sparkles: Add support for set-/getData and begin-/endUndoStep [`6471946`](https://github.com/leolabs/ableton.js/commit/64719465750cbeffcb86433105cce945bfdf7153)
- :wrench: Change the default ports (again 😅) because Max for Live was using port 9005 already [`bb6c9f3`](https://github.com/leolabs/ableton.js/commit/bb6c9f3fe2deb66026c7528297716774094f37f5)
- :sparkles: Add "message" event that lets users listen to decoded incoming messages [`5475ec4`](https://github.com/leolabs/ableton.js/commit/5475ec49ee90d9839af62b46bf551c4f5a231d55)

#### [v1.8.5](https://github.com/leolabs/ableton.js/compare/v1.8.4...v1.8.5)

> 9 March 2020

- :bug: Don't throw an error when the version check fails [`6f9b726`](https://github.com/leolabs/ableton.js/commit/6f9b726317ad27759506360f18b9a75667de1449)
- :sparkles: Add rough latency measurement functionality [`814cb05`](https://github.com/leolabs/ableton.js/commit/814cb0555e344e845b5413f1d1aff88e1e5df22f)
- :pencil: Add docs to the new getPing method [`7a70f63`](https://github.com/leolabs/ableton.js/commit/7a70f63bf7fcb4062282ff061f01b2d7de36eff7)

#### [v1.8.4](https://github.com/leolabs/ableton.js/compare/v1.8.3...v1.8.4)

> 5 March 2020

- :wrench: Improve the list of included files for NPM [`fa20b1b`](https://github.com/leolabs/ableton.js/commit/fa20b1b938132b62bc4fc11a7fa78479f4927dd2)

#### [v1.8.3](https://github.com/leolabs/ableton.js/compare/v1.8.2...v1.8.3)

> 5 March 2020

- :wrench: Improve selection of files included in the NPM package [`b237e3e`](https://github.com/leolabs/ableton.js/commit/b237e3e93ae004d33be80c3401a3a1c933204ab3)

#### [v1.8.2](https://github.com/leolabs/ableton.js/compare/v1.8.1...v1.8.2)

> 5 March 2020

- :truck: Extract packageVersion script into separate file [`0861560`](https://github.com/leolabs/ableton.js/commit/0861560e851140890a27a6be8fb60b7270345220)
- :pencil: Document gzip and chunking for responses [`227e193`](https://github.com/leolabs/ableton.js/commit/227e1934063161b8209c960b5f779916e331e304)
- :wrench: Include midi script in the NPM package for easier installation [`ae18a67`](https://github.com/leolabs/ableton.js/commit/ae18a6728782cee5fdc6e042a47c0b2b78d57a88)

#### [v1.8.1](https://github.com/leolabs/ableton.js/compare/v1.8.0...v1.8.1)

> 5 March 2020

- :speech_balloon: Add better explanations to TimeoutErrors [`f5690f3`](https://github.com/leolabs/ableton.js/commit/f5690f312d85a21e2bf0d000de2656862b5c5aa2)

#### [v1.8.0](https://github.com/leolabs/ableton.js/compare/v1.7.2...v1.8.0)

> 5 March 2020

- :sparkles: Add scenes, clip slots [`#7`](https://github.com/leolabs/ableton.js/pull/7)
- :zap: Use gzip and chunking to allow a much higher message length [`#8`](https://github.com/leolabs/ableton.js/issues/8)
- :bug: Fix missing ClipSlot conversion in Song.View [`308ab48`](https://github.com/leolabs/ableton.js/commit/308ab48bc781720e40bf7b5e4c05080533ac6d44)
- :sparkles: Make view available only as a fixed property of song [`af51c31`](https://github.com/leolabs/ableton.js/commit/af51c314947d35d82ff8a34cb70a9e3e8543e825)
- :lipstick: Make post-install warning message yellow [`f7e6403`](https://github.com/leolabs/ableton.js/commit/f7e6403fcb3d4488a511d9925eb916b166195485)

#### [v1.7.2](https://github.com/leolabs/ableton.js/compare/v1.7.1...v1.7.2)

> 4 March 2020

- :sparkles: Improve timeout errors by including which command actually timed out [`011473d`](https://github.com/leolabs/ableton.js/commit/011473df0a424d5f277f9e85a9b114c8b7aa230d)

#### [v1.7.1](https://github.com/leolabs/ableton.js/compare/v1.7.0...v1.7.1)

> 4 March 2020

- :wrench: Auto-commit change to Internal.py on version bump [`590c1a3`](https://github.com/leolabs/ableton.js/commit/590c1a3ec02043589416909bd5e7b9e82d5fcf29)

#### [v1.7.0](https://github.com/leolabs/ableton.js/compare/v1.6.0...v1.7.0)

> 4 March 2020

- :bug: Fix wrong build output structure cause by importing a file outside of the src directory [`540f328`](https://github.com/leolabs/ableton.js/commit/540f3281c2bb3d4397dec997f1528d46e845a9c8)
- :sparkles: Automatically sync the Python script version with the Package version [`1254f03`](https://github.com/leolabs/ableton.js/commit/1254f03d6e90ec5c1a6520c55c654728d33c6e51)
- :wrench: Change the default ports to avoid clashes with Native Instruments software [`77ae3ec`](https://github.com/leolabs/ableton.js/commit/77ae3ecc07832c395ed38717af26efcddd00dc5a)

#### [v1.6.0](https://github.com/leolabs/ableton.js/compare/v1.5.0...v1.6.0)

> 3 March 2020

- :sparkles: Allow JS to check whether the Python plugin is up to date [`dddb9fe`](https://github.com/leolabs/ableton.js/commit/dddb9fe94366a78e2b3b6284e4b3d0048e6af62c)
- :zap: De-duplicate multiple event listeners on the same prop [`3763c94`](https://github.com/leolabs/ableton.js/commit/3763c94ae8775fbbe2b82b42bd2b0af64c1e6141)
- :pencil: Add findings section to the README file [`9b8cde6`](https://github.com/leolabs/ableton.js/commit/9b8cde6238f7a181cb8cc4fa78e40f7eb8425182)

#### [v1.5.0](https://github.com/leolabs/ableton.js/compare/v1.4.4...v1.5.0)

> 2 March 2020

- :white_check_mark: Improve tests [`e8bbd1b`](https://github.com/leolabs/ableton.js/commit/e8bbd1b61e4f99e948c4015768e7de73c46a0bfd)
- :wrench: Run Jest tests sequentially [`74c09eb`](https://github.com/leolabs/ableton.js/commit/74c09ebb5844ecc18295582e4a05a892fc544b8a)
- :sparkles: Allow multiple processes to communicate with the Python script at the same time [`75ce56e`](https://github.com/leolabs/ableton.js/commit/75ce56e155f0732c1bbd64ceb23a459280a66071)

#### [v1.4.4](https://github.com/leolabs/ableton.js/compare/v1.4.3...v1.4.4)

> 8 December 2019

- :lock: Switch to uuid v4 [`dca7886`](https://github.com/leolabs/ableton.js/commit/dca78863729da20f0627c781006f04983fdb260a)

#### [v1.4.3](https://github.com/leolabs/ableton.js/compare/v1.4.2...v1.4.3)

> 27 November 2019

- :label: Fix types for removeListener function [`4d0d1a8`](https://github.com/leolabs/ableton.js/commit/4d0d1a8a16c2d50cf1dae2e0258f075eb2268aa5)

#### [v1.4.2](https://github.com/leolabs/ableton.js/compare/v1.4.1...v1.4.2)

> 27 November 2019

- :lock: Use uuid instead of node-uuid [`ebf02c8`](https://github.com/leolabs/ableton.js/commit/ebf02c800a597847995b5806347ee23546c123c0)
- :sparkles: Clear heartbeatInterval on close [`2844b75`](https://github.com/leolabs/ableton.js/commit/2844b7530fd14901472b1e8c595f84d4c2444bf1)

#### [v1.4.1](https://github.com/leolabs/ableton.js/compare/v1.4.0...v1.4.1)

> 27 November 2019

- :sparkles: Add a method to check the current connection state [`b3950dd`](https://github.com/leolabs/ableton.js/commit/b3950ddb97d8c5a58f6d3b2255c437f353cdd2ac)

#### [v1.4.0](https://github.com/leolabs/ableton.js/compare/v1.3.3...v1.4.0)

> 27 November 2019

- :sparkles: Send regular heartbeats to check if Ableton is still connected [`34fff71`](https://github.com/leolabs/ableton.js/commit/34fff71c9f1669a2aecb6d9bd3bd4070fbb56b91)
- :bug: Handle serialized objects potentially being None [`c92ed1d`](https://github.com/leolabs/ableton.js/commit/c92ed1d54ef26abbbbce2c2d51bdc45fe2bce01a)
- :pencil: Change syntax highlighting mode to JS to avoid weird styling [`391b6f1`](https://github.com/leolabs/ableton.js/commit/391b6f1a28cd2010dbc5e3f9c10e9045c32783e0)

#### [v1.3.3](https://github.com/leolabs/ableton.js/compare/v1.3.2...v1.3.3)

> 31 May 2019

- :pencil: Improve docs [`9d6e303`](https://github.com/leolabs/ableton.js/commit/9d6e3032bd08d6e8c5ea22b877cffd622eb62511)
- :art: Require message handler to be set [`49956da`](https://github.com/leolabs/ableton.js/commit/49956da103e1f0acd0fd65b19d88506bbadcbaa5)
- :pencil: Add information about available yarn scripts [`b0f5943`](https://github.com/leolabs/ableton.js/commit/b0f5943352944cc78c5d5a12747b58e4370b5297)

#### [v1.3.2](https://github.com/leolabs/ableton.js/compare/v1.3.1...v1.3.2)

> 30 May 2019

#### [v1.3.1](https://github.com/leolabs/ableton.js/compare/v1.3.0...v1.3.1)

> 30 May 2019

- :sparkles: Implement Song methods in JS [`da661ad`](https://github.com/leolabs/ableton.js/commit/da661ad2902178af242268feea10811c1b89541d)
- :label: Change nsid type from string to number [`7fa34f2`](https://github.com/leolabs/ableton.js/commit/7fa34f2c48c19ee09204f6472ed4b99182796e00)
- :label: Fix typing of is_counting_in and is_playing [`333a1d6`](https://github.com/leolabs/ableton.js/commit/333a1d63fac0d806f4a1504534a783f169e6d824)

#### [v1.3.0](https://github.com/leolabs/ableton.js/compare/v1.2.5...v1.3.0)

> 30 May 2019

- :fire: Remove unnecessary jumpToCue method [`6ceef9c`](https://github.com/leolabs/ableton.js/commit/6ceef9c0fc3480fb1ba2114df2f5936eae8080ff)

#### [v1.2.5](https://github.com/leolabs/ableton.js/compare/v1.2.4...v1.2.5)

> 29 May 2019

#### [v1.2.4](https://github.com/leolabs/ableton.js/compare/v1.2.3...v1.2.4)

> 29 May 2019

#### [v1.2.3](https://github.com/leolabs/ableton.js/compare/v1.2.2...v1.2.3)

> 29 May 2019

#### [v1.2.2](https://github.com/leolabs/ableton.js/compare/v1.2.1...v1.2.2)

> 29 May 2019

#### [v1.2.1](https://github.com/leolabs/ableton.js/compare/v1.2.0...v1.2.1)

> 29 May 2019

#### [v1.2.0](https://github.com/leolabs/ableton.js/compare/v1.1.0...v1.2.0)

> 29 May 2019

- :sparkles: Add listeners for connect and disconnect [`00f42f6`](https://github.com/leolabs/ableton.js/commit/00f42f69d508b6cd671d7ca4f3fcf4b1fc26e75e)
- :sparkles: Add connect and disconnect messages [`a27c632`](https://github.com/leolabs/ableton.js/commit/a27c632a9ae660125a1f1edb7c1dac94ad7e85c7)

#### v1.1.0

> 29 May 2019

- :sparkles: Add Jest for testing [`8bc8dbf`](https://github.com/leolabs/ableton.js/commit/8bc8dbfcb5415605ba7b0769be1754c1fb65fa6b)
- :sparkles: Implement transformers structure [`00a6a6f`](https://github.com/leolabs/ableton.js/commit/00a6a6f1925c422d8f6df82b21fb0e3bc93a6f45)
- :tada: Implement basic song control and UDP protocol [`a760214`](https://github.com/leolabs/ableton.js/commit/a7602145138fefe47e40a70c0afde5a6da631d7a)
