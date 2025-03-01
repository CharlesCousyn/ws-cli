# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.2.0](https://github.com/FlorentinTh/ws-cli/compare/v1.1.4...v1.2.0) (2021-06-16)


### Features

* **labelizer:** complete labelizer ([58893e3](https://github.com/FlorentinTh/ws-cli/commit/58893e302940e73efecb41adcb8c7eb67df80559))
* **websocketserver:** complete websocketserver code to suit recording in the lab ([0576c2a](https://github.com/FlorentinTh/ws-cli/commit/0576c2adf6b5644509a43a1f48a9dab113c4a7e7))


### Bug Fixes

* **consolehelper:** fix wrong function call: replace old printError by new printMessage ([9db9b90](https://github.com/FlorentinTh/ws-cli/commit/9db9b90ab4decb42eb10439d7626da121d860bc6))
* **postprocessing:** remove no longer required postProcessing class ([ceac72a](https://github.com/FlorentinTh/ws-cli/commit/ceac72a53d22da85dfb098b33fd1eaf6631dc471))
* **sanitizer&labelizer:** change liara specific checks for sanitization and labelization ([343cb2b](https://github.com/FlorentinTh/ws-cli/commit/343cb2bde5cf8d79ed523d22417aad3e07a766e8))


### Reverts

* **cli:** remove no longer required sanitize option ([6d551c6](https://github.com/FlorentinTh/ws-cli/commit/6d551c6f059f79f364132a62c6c9f5296382424c))
* **commandhelper:** remove no longer required no-sanitize flag command ([ab4956b](https://github.com/FlorentinTh/ws-cli/commit/ab4956b5568507ee4a1c5c644730f29c6d8167e3))


### Refactors

* **websocketserver:** optimize and refactor webSocketServer according to previous changes ([e788966](https://github.com/FlorentinTh/ws-cli/commit/e7889667aa3c36fc025e066880a99f658c404efb))


### Build System

* **npm:** change build command in npm scripts ([00b8117](https://github.com/FlorentinTh/ws-cli/commit/00b8117ad9ab0d77f0aa5b60cafa2bd9f2c617ac))


### Documentation

* **readme:** add badges to README ([beeef7e](https://github.com/FlorentinTh/ws-cli/commit/beeef7e3ea09c91712f3eba8084a696754cf4f77))


### Chore

* **deps:** update dependencies ([5ffb9a9](https://github.com/FlorentinTh/ws-cli/commit/5ffb9a90935142e10d843c62344eb9ec9672ad3a))
* **deps:** update dependencies ([fc40de1](https://github.com/FlorentinTh/ws-cli/commit/fc40de19161a56d2c74ca73f434ddedd47974ea1))
* **gitignore:** add file to gitignore ([7625c97](https://github.com/FlorentinTh/ws-cli/commit/7625c97715a41e39d9872a3e3a95cc7f3957b0cf))


### CI

* **dependabot:** only check for production dependencies updates ([8734eac](https://github.com/FlorentinTh/ws-cli/commit/8734eac6b6fcdbac1dfdff069727bcf1b76905cc))
* **workflows:** add github action workflow file to check dependencies vulnerabilities with Snyk ([2c42f0f](https://github.com/FlorentinTh/ws-cli/commit/2c42f0f27a3269a9ac9e7736b5466ddabda2f4da))
* **workflows:** change name of the upload-assets workflow ([4d96c24](https://github.com/FlorentinTh/ws-cli/commit/4d96c24eafe3c1aa00bfefca542440c6c4b0e9a9))
* **workflows:** disable trigger of workflows for dependabot alerts ([1ba350f](https://github.com/FlorentinTh/ws-cli/commit/1ba350f0efc99173f950a2a09617cf372a4faa52))

### [1.1.4](https://github.com/FlorentinTh/ws-cli/compare/v1.1.3...v1.1.4) (2021-06-03)


### Refactors

* **commandhelper:** fix text formatting of the output of the help option ([91685aa](https://github.com/FlorentinTh/ws-cli/commit/91685aa2dc1dc68240544c1ee17d960a0b9258aa))
* **consolehelper:** replace printError function by more generic printMessage with several tags ([27766db](https://github.com/FlorentinTh/ws-cli/commit/27766db38cf2429ea10b183de3c1270fad45a20d))


### Performance

* **platform-folders:** remove use of platform-folders external dependency in favor of native code ([5e31544](https://github.com/FlorentinTh/ws-cli/commit/5e3154424cb2ff79a890a28010e1e6a2b1264a5d))


### CI

* **workflows:** add new upload-assets workflow file that fixes all previous issues ([de25b49](https://github.com/FlorentinTh/ws-cli/commit/de25b496b241b70330f69764a3d64aacc692d7f3))


### Build System

* **npm:** update, remove deps and fix script to suit upload-assets workflow ([e652355](https://github.com/FlorentinTh/ws-cli/commit/e6523550f1a817dca7c119a72a4a605f50c9cd75))


### Chore

* **deps:** update dependencies ([b81dde4](https://github.com/FlorentinTh/ws-cli/commit/b81dde4c5e778afb9c57ec7a2477f353b9f1cf36))


### Documentation

* **readme:** update readme ([827379e](https://github.com/FlorentinTh/ws-cli/commit/827379eb0b47a104c69387f1a9edae998978d6ba))

### [1.1.3](https://github.com/FlorentinTh/ws-cli/compare/v1.1.2...v1.1.3) (2021-06-03)


### CI

* **upload-assets:** remove upload-assets github actions workflow file for now ([a23d1cc](https://github.com/FlorentinTh/ws-cli/commit/a23d1cce8d239eb59a7b102b5dd023c89bb5c8a9))

### [1.1.2](https://github.com/FlorentinTh/ws-cli/compare/v1.1.1...v1.1.2) (2021-06-03)


### CI

* **upload-assets:** update command in upload-assets workflow file ([7a6ae26](https://github.com/FlorentinTh/ws-cli/commit/7a6ae269829fbf5406dec583051972aad531f415))

### [1.1.1](https://github.com/FlorentinTh/ws-cli/compare/v1.1.0...v1.1.1) (2021-06-03)


### CI

* **upload-assets:** fix an issue with upload-assets.yml file content ([c8c5f6b](https://github.com/FlorentinTh/ws-cli/commit/c8c5f6b2094ba7bbdc59866335afafc02d856aea))

## 1.1.0 (2021-06-03)


### Features

* **cli:** add cli options to use external YAML configuration file for WebSocket servers ([d643556](https://github.com/FlorentinTh/ws-cli/commit/d64355667950543e2cc261797c6efd28395fa47a))
* **cli:** add compilation scripts to produce executable files for the 3 main targets ([224f09d](https://github.com/FlorentinTh/ws-cli/commit/224f09dabf93f931144feca3c91b9ad4a799b020))
* **cli:** start working on cli ([7ffc784](https://github.com/FlorentinTh/ws-cli/commit/7ffc784d6cf237d03f31083b5d5bdea9090aebbb))
* **consolehelper:** add CLI description ([a4a6785](https://github.com/FlorentinTh/ws-cli/commit/a4a6785fca69546fbe0ed1cc703253899e0e4f5d))
* **postprocessing:** start working on PostProcessing features ([85965aa](https://github.com/FlorentinTh/ws-cli/commit/85965aaed0f93d8835b3b6d2f5099c56bc43d8cc))


### Bug Fixes

* **cli:** add missing exit codes ([efbf991](https://github.com/FlorentinTh/ws-cli/commit/efbf9914f5211ff0e6ec60e0cb3c11b0f97d5b84))
* **cli:** fix weird issue replacing original name of isOptionSet function ([f4839a6](https://github.com/FlorentinTh/ws-cli/commit/f4839a6edf481e7341f7d53edd58a13a245734b8))
* **cli-label-opt:** add override or rename capability if same folder for label already exists ([0e181e2](https://github.com/FlorentinTh/ws-cli/commit/0e181e2e7b240667ca6cc3bcd29079d83b1c9818))
* **consolehelper:** add missing default null value for error object parameter in printError function ([c7db2ae](https://github.com/FlorentinTh/ws-cli/commit/c7db2aeecbd66bcdaa7855cb24359eddeecaaf48))
* **filehelper:** add missing function required to check if conf file exists for default value ([8d71269](https://github.com/FlorentinTh/ws-cli/commit/8d71269bbe17f986244a0d28aa00acb103c1a2b0))
* **main:** use dynamic app name instead of a hardcoded value ([f0b8d68](https://github.com/FlorentinTh/ws-cli/commit/f0b8d68bcaba570412a6f3bd90ffcce5b612944a))
* **mock:** remove now unused mock function for WebSocket connection ([05458a9](https://github.com/FlorentinTh/ws-cli/commit/05458a9f5a6f50abba5484ff5924c032d0853832))
* **project:** fix intial project configuration according to the needs ([abdb4a1](https://github.com/FlorentinTh/ws-cli/commit/abdb4a1735d173ff0eb51ba42c4086f7cdaf64dc))
* **websocketserver:** fix issues with all servers ([bdc491d](https://github.com/FlorentinTh/ws-cli/commit/bdc491df2137058f46ff31555a7e08d09b021326))


### Chore

* **deps:** update dependencies ([c762e4c](https://github.com/FlorentinTh/ws-cli/commit/c762e4c9e2f89a04aa74219dc8b6d84f2facb4c1))
* **deps:** update dependencies ([022ea3b](https://github.com/FlorentinTh/ws-cli/commit/022ea3b77f0e5e133f931879bb803d466fe1a13d))
* **deps:** update dependencies ([db9791b](https://github.com/FlorentinTh/ws-cli/commit/db9791b78abe12ca76174e91c0138d391741075a))
* **deps:** update dependencies ([0750f05](https://github.com/FlorentinTh/ws-cli/commit/0750f05e45aff19841e6d04b24199f4673bd32f6))
* **deps:** update dependencies ([bd6c293](https://github.com/FlorentinTh/ws-cli/commit/bd6c293393ae29a3537ecc6bcf122e49acc8616d))
* **deps:** update dependencies and update npm to v7.x ([96411b7](https://github.com/FlorentinTh/ws-cli/commit/96411b7e852dea446ac9d32d49851ae43a1edbd9))


### Documentation

* **readme:** update readme ([bbf4d79](https://github.com/FlorentinTh/ws-cli/commit/bbf4d7975b2251d6a8ef721f015fa51cf525f71b))


### Styling

* **.vscode:** remove useless space in vscode settings file ([7b31624](https://github.com/FlorentinTh/ws-cli/commit/7b31624df39572c4da18145526bbafcbfb22f8f5))


### Refactors

* **cli:** change the way bin file call the main app source file ([c556cc1](https://github.com/FlorentinTh/ws-cli/commit/c556cc1dcf1918bb13fd89e0f7290bc94f6d52c1))
* **cli-default:** replace yes option name by default option name ([13f6e80](https://github.com/FlorentinTh/ws-cli/commit/13f6e802f280fd70d82be6f56428801f916f0962))
* **commandhelper:** move optionsHelper to commandHelper and add few aliases ([e3fc610](https://github.com/FlorentinTh/ws-cli/commit/e3fc61089f9f8937409d97811579699aec1b810a))
* **project:** add better error handling and better class member visibility ([8478554](https://github.com/FlorentinTh/ws-cli/commit/8478554e1aa4824c8c3129223db0530a57d7056b))
* **project:** init project ([a1cd811](https://github.com/FlorentinTh/ws-cli/commit/a1cd811939cb657b8786d4cae4cdf007fea84e8a))
* **recording:** add new required dependencies ([7a78966](https://github.com/FlorentinTh/ws-cli/commit/7a7896670a1e0c1350530ae27dc2fce2607f2145))
* **recording:** remove recording and refactor websocketServer accordingly ([d5ee6f3](https://github.com/FlorentinTh/ws-cli/commit/d5ee6f3e4676cef308be3908c3aa6c123937669b))
* **websocketserver:** refactor unused code ([8ee4b74](https://github.com/FlorentinTh/ws-cli/commit/8ee4b74ef1f72e671accc37df95022fb1f2868e6))


### Build System

* **npm:** add pkg-ver to version executables created by vercel/pkg at the end of the build ([bfd83b1](https://github.com/FlorentinTh/ws-cli/commit/bfd83b1b68b9d634559ec0d73c9980f959dae798))
* **npm:** add some scripts in package.json ([afd1744](https://github.com/FlorentinTh/ws-cli/commit/afd1744ec7b2a22677b43994bc8268cf9a4c9682))
* **npm script:** remove dist folder before a new build ([205f56b](https://github.com/FlorentinTh/ws-cli/commit/205f56b41944cdd36ccfe5430583741da3b425b1))


### CI

* **gh actions:** add first version of github actions workflow to upload executables in release assets ([dc1d8b1](https://github.com/FlorentinTh/ws-cli/commit/dc1d8b1dfbc44a98537d6fcbd7cb1a79f752e518))
