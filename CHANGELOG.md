# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.36.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.3...0.36.4) (2022-10-05)

### [0.36.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.2...0.36.3) (2022-10-05)

### [0.36.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.1...0.36.2) (2022-10-05)


### Features

* shcedule use range and frequency ([bb1cb0e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bb1cb0eb9c3e907b0b240deefc9f167afa86fea9))

### [0.36.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.0...0.36.1) (2022-10-05)


### Bug Fixes

* **proto:** reverse `source_id` and `target_id` ([271ba4d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/271ba4d5cc209790dc2a086cec5675eace752ba4))

## [0.36.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.35.2...0.36.0) (2022-10-05)


### ⚠ BREAKING CHANGES

* **proto:** add services for `Read` and `List`
* **proto:** create request uses new `Job`

### Features

* **proto:** add message for `AccountInfo` ([f58303b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f58303b5d1c2a23dae1d87845971a1b6987fa09c))
* **proto:** add message for `BitsightCompanyInfo` ([828c978](https://github.com/WhitehawkCEC/whitehawk-proto/commit/828c978ab501704b89ec18c1b52c9dfd663cfd85))
* **proto:** add message for `CyberOneAsset` ([9e9b69d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9e9b69d5e39e3e8b9dbbc170a73d315a2641b2b6))
* **proto:** add message for `SupplyWisdomAsset` ([719451b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/719451b1de8163a85fb6353c0824b7b5bd78be9b))
* **proto:** add message for `SupplyWisdomTarget` ([44e35f5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/44e35f57470ff37dc1462fdd18869d544d5c865c))
* **proto:** add messages for `Job` ([e1edecf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e1edecf82427bd924008422015833b218b9b839c))
* **proto:** add services for `Read` and `List` ([8a0bee2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8a0bee28aa1d1f9d017e29e3785618746be503dc))
* **proto:** create request uses new `Job` ([4dc790e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4dc790ec89a2e1e7306fd17a896e55bfcdff9fc4))

### [0.35.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.35.1...0.35.2) (2022-10-04)

### Bug Fixes

- def error ([033f6cc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/033f6cc4b5440255b339908fa496aa5332e6eaf0))

### [0.35.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.35.0...0.35.1) (2022-10-04)

### Features

- use slug instead of ulid for read ([4b9969b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4b9969b5d9d845cd26f648b2e79c37e1ffe11d1d))

## [0.35.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.34.2...0.35.0) (2022-10-04)

### ⚠ BREAKING CHANGES

- target id as slug

### Features

- target id as slug ([6612c76](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6612c765868003f16816344376f19d7fe04822e5))

### [0.34.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.34.1...0.34.2) (2022-10-04)

### [0.34.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.34.0...0.34.1) (2022-10-04)

### Bug Fixes

- **proto:** build errors ([d0486fd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d0486fd39e9f1a3b0882f6be099fd00c1ac36a18))

## [0.34.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.33.3...0.34.0) (2022-10-04)

### ⚠ BREAKING CHANGES

- **proto:** move service to return list of products for manufacturer

### Features

- **proto:** add service to return count of products ([95ea5cd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/95ea5cd8d84143f4402fd7119ac3f69297b20e2a))

- **proto:** move service to return list of products for manufacturer ([5877779](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5877779f8243cad01cfac1339aa3586311c30c5d))

### [0.33.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.33.2...0.33.3) (2022-10-03)

### Features

- **proto:** add service to list all products for manufacturers ([7ab4dfe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7ab4dfecb7938d49619595fdf409f69fca5917c0))
- **proto:** service to return manufacturer if it has only one product ([f777494](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f777494c9cb0d0f32b18845ae974c2a00420caaa))

### [0.33.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.33.1...0.33.2) (2022-09-30)

### Features

- **proto:** create, update, delete services for industries ([86c6b1e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/86c6b1e20680152227f892aea5bb9a07a0a6c6b7))

### Bug Fixes

- **proto:** actually include `product_id` ([70c0aff](https://github.com/WhitehawkCEC/whitehawk-proto/commit/70c0affeab0b7819192a3cbc30c03e5999ba65f8))

### [0.33.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.33.0...0.33.1) (2022-09-30)

### Bug Fixes

- **proto:** remove unused import ([21e233d](https://github.com/whitehawkcec/whitehawk-proto/commit/21e233d18799086790d5aa7e56ac47fa231ba88c))

## [0.33.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.32.1...0.33.0) (2022-09-30)

### ⚠ BREAKING CHANGES

- **proto:** use snake case

### Features

- **proto:** use snake case ([a226c5e](https://github.com/whitehawkcec/whitehawk-proto/commit/a226c5eb9f5aafea975d52cf92c2c8a83bc4fed8))

### [0.32.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.32.0...0.32.1) (2022-09-30)

### Features

- **proto:** add BK v2 config messages ([298a528](https://github.com/whitehawkcec/whitehawk-proto/commit/298a5288a2114e655c54ec73b7767cc4d6db469a))
- **proto:** add resource messages ([daa9624](https://github.com/whitehawkcec/whitehawk-proto/commit/daa96246d9b130778a18e17d8a78eef9e2a22657))
- **proto:** add service for account subscription BK config ([e550809](https://github.com/whitehawkcec/whitehawk-proto/commit/e55080997819e83216fdee96d053b0346a329612))

## [0.32.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.31.0...0.32.0) (2022-09-29)

### ⚠ BREAKING CHANGES

- **proto:** nest under `subscriptions`

### Features

- **proto:** nest under `subscriptions` ([49f70d4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/49f70d46963d6584debf2e1f4bcc0be625d63c78))

## [0.31.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.12...0.31.0) (2022-09-29)

### ⚠ BREAKING CHANGES

- **proto:** remove bk entity service
- **proto:** remove bk entity message

### Features

- **proto:** add black kite entity to domain message ([f441ac2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f441ac2a6dce7fb4ee8cc09bb99d099d4f46fc56))
- **proto:** add service to get black kite entities ([19500ea](https://github.com/WhitehawkCEC/whitehawk-proto/commit/19500ea8b38e501f8ba48f04a481a4197e8a738e))
- **proto:** remove bk entity message ([a84ad49](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a84ad4958634e610e9b0e31ebb0f83617a6870e6))
- **proto:** remove bk entity service ([613cf68](https://github.com/WhitehawkCEC/whitehawk-proto/commit/613cf68539d49daf3ee9b46f26eca6ea3ec639f6))

### [0.30.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.11...0.30.12) (2022-09-29)

### Features

- add message for black kite entity ([5aa2041](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5aa2041e0edb10cbe1720676f891b8e72a5c9378))
- add service to get black kite entities ([b4c26c7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b4c26c75d00c620592ee39763ba26f612093f6fb))

### [0.30.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.10...0.30.11) (2022-09-29)

### Features

- **proto:** correctly add service to read company ([34227da](https://github.com/WhitehawkCEC/whitehawk-proto/commit/34227dae1c743ef5a01fbf14aee6223638e3d1d0))

### [0.30.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.9...0.30.10) (2022-09-29)

### Features

- **proto:** add service to read company ([4e32049](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4e320495593a11b35f679714209ae73e046de305))

### [0.30.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.8...0.30.9) (2022-09-28)

### Features

- list isoloted products by feature ([b5a2b09](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b5a2b0979c97c91877504a22d6eaae78cd5f6be8))

### [0.30.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.7...0.30.8) (2022-09-28)

## [0.25.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.24.0...0.25.0) (2022-09-28)

### ⚠ BREAKING CHANGES

- sync request now contains source and destionations ids
- matched request carry source and destination ids
- missing import
- **proto:** use correct field name/type
- **proto:** make field `oneof`
- **proto:** account for signify breaking changes

### Features

- add `Job` messages ([c511509](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c5115090e2636e66b87ebc25cc3cf3f4c47c29c8))
- add read request ([cc2f4d0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cc2f4d08b75eedf46ec751b2dbbbf7b461215865))
- create result return result instead of job ([4aca5eb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4aca5eb7f1d85c63fafc60eedad5078244836c60))
- **proto:** account for signify breaking changes ([aabe804](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aabe8048aad0645b4a8df4f9f606482e7751701f))
- **proto:** add cyber one domain message ([be9a194](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be9a1941346369096405460d48af65c2c59c5c2f))
- **proto:** add example for `JobDetails` ([7ba00b2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7ba00b2a99c0bdd5f3abcaa2c19f0585e895f44d))
- **proto:** add scorecard licensing messages ([bc0b65b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bc0b65b6e973716b2d9530581a5c2b8ff2c338d8))
- **proto:** add service to manage subscription group license batch quantities ([a5f2fe8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a5f2fe8bf056749369ba9d26f15a9344c4edf5b3))
- **proto:** add service to manage subscription group license batches ([7e3339c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7e3339c8c5bd9947a024cce49f1a6bd2eb9ab263))
- **proto:** add service to manage subscription license batch quantities ([4eee581](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4eee581f4f0f90397736ab0c6914d3f6fb153baa))
- **proto:** add service to manage subscription license batches ([2f668e5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2f668e5ea97b08c547dc6320877e64fef00449a8))
- **proto:** add service to manage subscription product group license batch quantities ([70a2a30](https://github.com/WhitehawkCEC/whitehawk-proto/commit/70a2a30072ff8c20ebf41e9c803ca856b28adaf6))
- **proto:** add service to manage subscription product group license batches ([34879ea](https://github.com/WhitehawkCEC/whitehawk-proto/commit/34879eac709d5b80571516e9ab823ce3d9a0105e))
- **proto:** add service to manage subscription product license batch quantities ([c9dd733](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c9dd733053481ad5a09c8056729f1709ff03e62b))
- **proto:** add service to manage subscription product license batches ([361e1d0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/361e1d052e14cce5a31f83a3c01265e4d81659d8))
- **proto:** add supply wisdom domain message ([c615ab7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c615ab7f01c410f3fd8a1049063c8d2a13aa95bd))
- **proto:** add v1 service for creating job ([b882f6f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b882f6f36a174c53a63551f822a4dbe746b579c1))
- **proto:** make field `oneof` ([353e93c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/353e93cedb5eb0682e8c87f9713fb100d0f033f3))
- **proto:** prefer message in `whitehawk.proto` ([6fd6121](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6fd61218028404a671c09359de6b8c606ce9fbcc))
- **proto:** remove v1 of account group state service ([e875b6b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e875b6b1affe39a4babedf00ca9b7276bece9a39))
- **proto:** remove v1 of account group summary service ([7f9cb4d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7f9cb4d2cf56129f14bc138a77da2534d5f007e1))
- **proto:** remove v1 of account summary service ([5fbf550](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5fbf5509a6416b940e087078c98f2e876ddf257a))
- **proto:** remove v1 of subscription product config service ([058a39a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/058a39a12244d7267f31da10b2df497e922f4258))
- **proto:** remove v1 of subscription product service ([8a5c101](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8a5c101aa430b801043db87bca2e90d8f434be7b))
- **proto:** remove v2 of subscription product config service ([eb21918](https://github.com/WhitehawkCEC/whitehawk-proto/commit/eb21918669abf2d4271e5e558b873d48cae3fecb))
- schedule jobs ([424ccbc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/424ccbc2e005ca860cf459ff452a251556015517))
- sync request now contains source and destionations ids ([0bd7689](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0bd76891d6bddd5007afa76db8275f63453f7204))
- sync request send rating type as well ([6e6f752](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6e6f75277099e990112d35f46e45f73b9dcb05b0))

### Bug Fixes

- all lower snake case ([22d4d94](https://github.com/WhitehawkCEC/whitehawk-proto/commit/22d4d94e82e8ee8b6f8d56fa0d6355c09e1ac34c))
- buf lint ([7c88f7d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7c88f7dcd2276a49022906933278c8451110b5b6))
- matched request carry source and destination ids ([fff6b59](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fff6b59b06bd6fb476caf313053628c50997c359))
- missing import ([63ad39e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/63ad39e7b6f2e38d072b7e8694394a2d99598243))
- **proto:** use correct field name/type ([9efd655](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9efd65593053a7e28d4ef13f9f788d143d457cd9))

### [0.30.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.6...0.30.7) (2022-09-22)

### Features

- create result return result instead of job ([4aca5eb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4aca5eb7f1d85c63fafc60eedad5078244836c60))

### [0.30.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.5...0.30.6) (2022-09-22)

### Features

- add read request ([cc2f4d0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cc2f4d08b75eedf46ec751b2dbbbf7b461215865))

### [0.30.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.4...0.30.5) (2022-09-22)

### [0.30.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.3...0.30.4) (2022-09-22)

### Bug Fixes

- buf lint ([7c88f7d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7c88f7dcd2276a49022906933278c8451110b5b6))

### [0.30.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.2...0.30.3) (2022-09-22)

### Features

- schedule jobs ([424ccbc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/424ccbc2e005ca860cf459ff452a251556015517))

### [0.30.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.1...0.30.2) (2022-09-22)

### [0.30.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.30.0...0.30.1) (2022-09-22)

### Features

- sync request send rating type as well ([6e6f752](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6e6f75277099e990112d35f46e45f73b9dcb05b0))

## [0.30.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.29.1...0.30.0) (2022-09-22)

### ⚠ BREAKING CHANGES

- sync request now contains source and destionations ids

### Features

- sync request now contains source and destionations ids ([0bd7689](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0bd76891d6bddd5007afa76db8275f63453f7204))

### [0.29.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.29.0...0.29.1) (2022-09-22)

### Bug Fixes

- all lower snake case ([22d4d94](https://github.com/WhitehawkCEC/whitehawk-proto/commit/22d4d94e82e8ee8b6f8d56fa0d6355c09e1ac34c))

## [0.29.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.28.0...0.29.0) (2022-09-22)

### ⚠ BREAKING CHANGES

- matched request carry source and destination ids

### Bug Fixes

- matched request carry source and destination ids ([fff6b59](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fff6b59b06bd6fb476caf313053628c50997c359))

## [0.28.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.27.3...0.28.0) (2022-09-21)

### ⚠ BREAKING CHANGES

- missing import

### Bug Fixes

- missing import ([63ad39e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/63ad39e7b6f2e38d072b7e8694394a2d99598243))

### [0.27.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.27.2...0.27.3) (2022-09-21)

### [0.27.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.27.1...0.27.2) (2022-09-20)

### Features

- **proto:** add service to manage subscription product group license batch quantities ([70a2a30](https://github.com/whitehawkcec/whitehawk-proto/commit/70a2a30072ff8c20ebf41e9c803ca856b28adaf6))
- **proto:** add service to manage subscription product group license batches ([34879ea](https://github.com/whitehawkcec/whitehawk-proto/commit/34879eac709d5b80571516e9ab823ce3d9a0105e))

### [0.27.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.27.0...0.27.1) (2022-09-16)

### Features

- **proto:** add service to manage subscription product license batch quantities ([c9dd733](https://github.com/whitehawkcec/whitehawk-proto/commit/c9dd733053481ad5a09c8056729f1709ff03e62b))
- **proto:** add service to manage subscription product license batches ([361e1d0](https://github.com/whitehawkcec/whitehawk-proto/commit/361e1d052e14cce5a31f83a3c01265e4d81659d8))

## [0.27.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.26.0...0.27.0) (2022-09-16)

### ⚠ BREAKING CHANGES

- **proto:** use correct field name/type

### Bug Fixes

- **proto:** use correct field name/type ([9efd655](https://github.com/whitehawkcec/whitehawk-proto/commit/9efd65593053a7e28d4ef13f9f788d143d457cd9))

## [0.26.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.25.0...0.26.0) (2022-09-16)

### ⚠ BREAKING CHANGES

- **proto:** make field `oneof`

### Features

- **proto:** make field `oneof` ([353e93c](https://github.com/whitehawkcec/whitehawk-proto/commit/353e93cedb5eb0682e8c87f9713fb100d0f033f3))

## [0.25.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.24.0...0.25.0) (2022-09-16)

### ⚠ BREAKING CHANGES

- **proto:** account for signify breaking changes

### Features

- add `Job` messages ([c511509](https://github.com/whitehawkcec/whitehawk-proto/commit/c5115090e2636e66b87ebc25cc3cf3f4c47c29c8))
- **proto:** account for signify breaking changes ([aabe804](https://github.com/whitehawkcec/whitehawk-proto/commit/aabe8048aad0645b4a8df4f9f606482e7751701f))
- **proto:** add cyber one domain message ([be9a194](https://github.com/whitehawkcec/whitehawk-proto/commit/be9a1941346369096405460d48af65c2c59c5c2f))
- **proto:** add example for `JobDetails` ([7ba00b2](https://github.com/whitehawkcec/whitehawk-proto/commit/7ba00b2a99c0bdd5f3abcaa2c19f0585e895f44d))
- **proto:** add scorecard licensing messages ([bc0b65b](https://github.com/whitehawkcec/whitehawk-proto/commit/bc0b65b6e973716b2d9530581a5c2b8ff2c338d8))
- **proto:** add service to manage subscription group license batch quantities ([a5f2fe8](https://github.com/whitehawkcec/whitehawk-proto/commit/a5f2fe8bf056749369ba9d26f15a9344c4edf5b3))
- **proto:** add service to manage subscription group license batches ([7e3339c](https://github.com/whitehawkcec/whitehawk-proto/commit/7e3339c8c5bd9947a024cce49f1a6bd2eb9ab263))
- **proto:** add service to manage subscription license batch quantities ([4eee581](https://github.com/whitehawkcec/whitehawk-proto/commit/4eee581f4f0f90397736ab0c6914d3f6fb153baa))
- **proto:** add service to manage subscription license batches ([2f668e5](https://github.com/whitehawkcec/whitehawk-proto/commit/2f668e5ea97b08c547dc6320877e64fef00449a8))
- **proto:** add supply wisdom domain message ([c615ab7](https://github.com/whitehawkcec/whitehawk-proto/commit/c615ab7f01c410f3fd8a1049063c8d2a13aa95bd))
- **proto:** add v1 service for creating job ([b882f6f](https://github.com/whitehawkcec/whitehawk-proto/commit/b882f6f36a174c53a63551f822a4dbe746b579c1))
- **proto:** prefer message in `whitehawk.proto` ([6fd6121](https://github.com/whitehawkcec/whitehawk-proto/commit/6fd61218028404a671c09359de6b8c606ce9fbcc))
- **proto:** remove v1 of account group state service ([e875b6b](https://github.com/whitehawkcec/whitehawk-proto/commit/e875b6b1affe39a4babedf00ca9b7276bece9a39))
- **proto:** remove v1 of account group summary service ([7f9cb4d](https://github.com/whitehawkcec/whitehawk-proto/commit/7f9cb4d2cf56129f14bc138a77da2534d5f007e1))
- **proto:** remove v1 of account summary service ([5fbf550](https://github.com/whitehawkcec/whitehawk-proto/commit/5fbf5509a6416b940e087078c98f2e876ddf257a))
- **proto:** remove v1 of subscription product config service ([058a39a](https://github.com/whitehawkcec/whitehawk-proto/commit/058a39a12244d7267f31da10b2df497e922f4258))
- **proto:** remove v1 of subscription product service ([8a5c101](https://github.com/whitehawkcec/whitehawk-proto/commit/8a5c101aa430b801043db87bca2e90d8f434be7b))
- **proto:** remove v2 of subscription product config service ([eb21918](https://github.com/whitehawkcec/whitehawk-proto/commit/eb21918669abf2d4271e5e558b873d48cae3fecb))

## [0.24.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.23.13...0.24.0) (2022-09-12)

### ⚠ BREAKING CHANGES

- **proto:** change input param to slug

### Bug Fixes

- **proto:** change input param to slug ([94b672e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/94b672e4d04daa43e7d4465be025b53dd51728b5))

### [0.23.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.23.12...0.23.13) (2022-09-09)

### Features

- add listisolatedBundlesAndProducts ([58f6010](https://github.com/WhitehawkCEC/whitehawk-proto/commit/58f6010ad30ed71bc8caee6d2fcba4b5119a3ca6))

### [0.23.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.23.11...0.23.12) (2022-09-09)

## [0.23.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.22.0...0.23.0) (2022-09-09)

### ⚠ BREAKING CHANGES

- **proto:** remove accidentally commited account groups service

### Features

- add optional `domain` fields for subscription product config ([643aff0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/643aff0cf6439a0ec1c1a2d486764c72600a5d22))
- **proto:** add `Subscription` `features` field ([6c8da99](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6c8da9982a820a880430a91a69a0193542071eeb))
- **proto:** add `SubscriptionGroup` ([a92fdf1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a92fdf150988ba8e5116c70c0ae92d36987dcdfa))
- **proto:** add messages for subscription supplier ([0952ef0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0952ef099b277c67b3b2e8184883300f6a48b58c))
- **proto:** add new package for subscription product messages ([4980ccd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4980ccd0cf3822cb97cad7a48119981d7d2f0c1a))
- **proto:** add rpc to get subscription product config ([3bb906e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3bb906edf6ca9737837fafd5cb134919912eed94))
- **proto:** add rpc to update subscription product info ([1f7ec9b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1f7ec9b6d427e513b401ffee0429a5ee78cb245c))
- **proto:** add service to get BK performance report ([629e86e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/629e86e7bd332d8b7960f37134ea544facf37af4))
- **proto:** add service to get BS performance evaluation ([adafa6a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/adafa6a2aa377248771322b8c6f0c83148287102))
- **proto:** add service to manage subscription groups ([b50f3b7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b50f3b798695a640bf12c66040f9dee69537f07c))
- **proto:** add service to manage subscription groups (really) ([59c0359](https://github.com/WhitehawkCEC/whitehawk-proto/commit/59c0359d984cb3d4a308aeac08d8c82c67356e3b))
- **proto:** add service to manage subscription product config ([45d4600](https://github.com/WhitehawkCEC/whitehawk-proto/commit/45d4600a6250fb9ff9bb942418c392b2873199a3))
- **proto:** add service to manage subscription suppliers ([b2181a9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b2181a9cba1efae811a01c4dd91d860ceffe4c19))
- **proto:** add service to manage subscription validity ([3c10511](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3c10511d64a51c37992f7d201b9f3cd496405b95))
- **proto:** add v2 service for account summary ([5c5d1d1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5c5d1d1ffaa226a837b55214f6daea904faa7b13))
- **proto:** add v2 service for group state ([3e0bf10](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3e0bf10becaf9bbd3a8f4f45e3b9e010bc8d1aea))
- **proto:** add v2 service for group summary ([7b04c33](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7b04c33ffdf7ead0875cdf3a57a13f1c2ad9d51c))
- **proto:** add v2 service for subscriptions product config ([2c51598](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2c51598370a3a3c5263fe8c006144ad54b57834e))
- **proto:** add v2 service for subscriptions products ([588454c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/588454cf3a4b1958eca50a06dec7324cfeee38ca))
- **proto:** add v3 service for subscriptions product config ([4d77c53](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4d77c531d119d00e5667ef2862858ede7f710ee2))
- **proto:** remove accidentally commited account groups service ([50507f0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/50507f0f3e33ad0cfa0409a9ae6300811960a42b))

### [0.23.11](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.10...0.23.11) (2022-09-01)

### Features

- **proto:** add `Subscription` `features` field ([6c8da99](https://github.com/whitehawkcec/whitehawk-proto/commit/6c8da9982a820a880430a91a69a0193542071eeb))

### [0.23.10](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.9...0.23.10) (2022-08-31)

### Features

- add optional `domain` fields for subscription product config ([643aff0](https://github.com/whitehawkcec/whitehawk-proto/commit/643aff0cf6439a0ec1c1a2d486764c72600a5d22))

### [0.23.9](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.8...0.23.9) (2022-08-30)

### Features

- **proto:** add service to get BS performance evaluation ([adafa6a](https://github.com/whitehawkcec/whitehawk-proto/commit/adafa6a2aa377248771322b8c6f0c83148287102))

### [0.23.8](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.7...0.23.8) (2022-08-30)

### Features

- **proto:** add v3 service for subscriptions product config ([4d77c53](https://github.com/whitehawkcec/whitehawk-proto/commit/4d77c531d119d00e5667ef2862858ede7f710ee2))

### [0.23.7](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.6...0.23.7) (2022-08-30)

### Features

- **proto:** add v2 service for subscriptions product config ([2c51598](https://github.com/whitehawkcec/whitehawk-proto/commit/2c51598370a3a3c5263fe8c006144ad54b57834e))

### [0.23.6](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.5...0.23.6) (2022-08-30)

### Features

- **proto:** add new package for subscription product messages ([4980ccd](https://github.com/whitehawkcec/whitehawk-proto/commit/4980ccd0cf3822cb97cad7a48119981d7d2f0c1a))
- **proto:** add v2 service for subscriptions products ([588454c](https://github.com/whitehawkcec/whitehawk-proto/commit/588454cf3a4b1958eca50a06dec7324cfeee38ca))

### [0.23.5](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.4...0.23.5) (2022-08-26)

### Features

- **proto:** add service to get BK performance report ([629e86e](https://github.com/whitehawkcec/whitehawk-proto/commit/629e86e7bd332d8b7960f37134ea544facf37af4))

### [0.23.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.3...0.23.4) (2022-08-25)

### Features

- **proto:** add rpc to get subscription product config ([3bb906e](https://github.com/whitehawkcec/whitehawk-proto/commit/3bb906edf6ca9737837fafd5cb134919912eed94))

### [0.23.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.1...0.23.2) (2022-08-19)

### [0.23.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.23.1...0.23.2) (2022-08-19)

### [0.21.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.21.3...0.21.4) (2022-08-12)

### [0.23.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.2...0.23.3) (2022-08-25)

### [0.23.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.1...0.23.2) (2022-08-25)

### Features

- **proto:** add service to manage subscription product config ([45d4600](https://github.com/whitehawkcec/whitehawk-proto/commit/45d4600a6250fb9ff9bb942418c392b2873199a3))

### [0.21.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.21.3...0.21.4) (2022-08-12)

### [0.23.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.23.0...0.23.1) (2022-08-19)

### Features

- **proto:** add messages for subscription supplier ([0952ef0](https://github.com/whitehawkcec/whitehawk-proto/commit/0952ef099b277c67b3b2e8184883300f6a48b58c))
- **proto:** add service to manage subscription suppliers ([b2181a9](https://github.com/whitehawkcec/whitehawk-proto/commit/b2181a9cba1efae811a01c4dd91d860ceffe4c19))

## [0.23.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.22.4...0.23.0) (2022-08-18)

### ⚠ BREAKING CHANGES

- **proto:** remove accidentally commited account groups service

### Features

- **proto:** add service to manage subscription groups (really) ([59c0359](https://github.com/whitehawkcec/whitehawk-proto/commit/59c0359d984cb3d4a308aeac08d8c82c67356e3b))
- **proto:** remove accidentally commited account groups service ([50507f0](https://github.com/whitehawkcec/whitehawk-proto/commit/50507f0f3e33ad0cfa0409a9ae6300811960a42b))

### [0.22.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.22.3...0.22.4) (2022-08-18)

### Features

- **proto:** add `SubscriptionGroup` ([a92fdf1](https://github.com/whitehawkcec/whitehawk-proto/commit/a92fdf150988ba8e5116c70c0ae92d36987dcdfa))
- **proto:** add service to manage subscription groups ([b50f3b7](https://github.com/whitehawkcec/whitehawk-proto/commit/b50f3b798695a640bf12c66040f9dee69537f07c))

### [0.22.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.22.2...0.22.3) (2022-08-17)

### Features

- **proto:** add rpc to update subscription product info ([1f7ec9b](https://github.com/whitehawkcec/whitehawk-proto/commit/1f7ec9b6d427e513b401ffee0429a5ee78cb245c))

### [0.22.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.22.1...0.22.2) (2022-08-17)

### Features

- **proto:** add v2 service for account summary ([5c5d1d1](https://github.com/whitehawkcec/whitehawk-proto/commit/5c5d1d1ffaa226a837b55214f6daea904faa7b13))
- **proto:** add v2 service for group state ([3e0bf10](https://github.com/whitehawkcec/whitehawk-proto/commit/3e0bf10becaf9bbd3a8f4f45e3b9e010bc8d1aea))
- **proto:** add v2 service for group summary ([7b04c33](https://github.com/whitehawkcec/whitehawk-proto/commit/7b04c33ffdf7ead0875cdf3a57a13f1c2ad9d51c))

### [0.22.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.22.0...0.22.1) (2022-08-17)

### Features

- **proto:** add service to manage subscription validity ([3c10511](https://github.com/whitehawkcec/whitehawk-proto/commit/3c10511d64a51c37992f7d201b9f3cd496405b95))

## [0.22.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.21.3...0.22.0) (2022-08-16)

### ⚠ BREAKING CHANGES

- **proto:** return param should be singular

### Features

- **proto:** return param should be singular ([1a135fd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1a135fdfe35c3942ff5c3527472212b1d7b570c1))

### [0.21.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.21.2...0.21.3) (2022-08-12)

### [0.21.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.21.1...0.21.2) (2022-08-12)

### [0.21.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.21.0...0.21.1) (2022-08-12)

## [0.21.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.20.4...0.21.0) (2022-08-12)

### ⚠ BREAKING CHANGES

- **proto:** disallow updates to subscription type/validity

### Features

- **proto:** disallow updates to subscription type/validity ([4672cc0](https://github.com/whitehawkcec/whitehawk-proto/commit/4672cc0e3cc687532c233dfad367df3efffa0a40))

### Bug Fixes

- cut and paste error ([fd6b372](https://github.com/whitehawkcec/whitehawk-proto/commit/fd6b37270981e13116ed985d784218bd07610c48))

### [0.20.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.20.3...0.20.4) (2022-08-11)

### Features

- add description field ([6127841](https://github.com/WhitehawkCEC/whitehawk-proto/commit/612784103b05c5cd9c661aa1aea2cdb0b202e4e9))
- add meta field ([0a7d74d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0a7d74d5f526f69257698dd13483f47631e48772))
- add meta field ([6ba1b89](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6ba1b8988a66af1b8966e27ca35c8358ff42be45))
- add read service ([e6ec10b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e6ec10b2c11f4adfd0615ed6542217f9d6b6d4b5))
- add read service ([6072dd4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6072dd44108416aedfa9f78ec7042c6881dd7fe2))

### [0.20.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.20.2...0.20.3) (2022-08-11)

### [0.20.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.20.1...0.20.2) (2022-08-08)

### [0.20.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.20.0...0.20.1) (2022-08-08)

### [0.19.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.19.1...0.19.2) (2022-08-05)

## [0.20.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.19.3...0.20.0) (2022-08-08)

### ⚠ BREAKING CHANGES

- use correct type

### Bug Fixes

- use correct type ([b48d466](https://github.com/whitehawkcec/whitehawk-proto/commit/b48d466d5770b756706a4629c636c04945e1973a))

### [0.19.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.19.2...0.19.3) (2022-08-08)

### Features

- add BS as subscription product option ([f851f08](https://github.com/whitehawkcec/whitehawk-proto/commit/f851f087245daeee5b88ad684856165b76e67273))
- add BS config message ([ae17e75](https://github.com/whitehawkcec/whitehawk-proto/commit/ae17e75518dc62763e730f618bea10ac2a5ab204))
- add BS domain message ([8b7c577](https://github.com/whitehawkcec/whitehawk-proto/commit/8b7c5777058becb43a5ef82ca514a3adafee0f95))

### [0.19.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.19.1...0.19.2) (2022-08-05)

### Bug Fixes

- **proto:** properly implement `read` for subscription products ([d39bb47](https://github.com/whitehawkcec/whitehawk-proto/commit/d39bb47f79db032bda628f9049e90931cb531e80))

### [0.19.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.19.0...0.19.1) (2022-08-05)

### [0.15.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.22...0.15.23) (2022-08-04)

## [0.19.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.18.0...0.19.0) (2022-08-05)

### ⚠ BREAKING CHANGES

- **proto:** use correct type
- **proto:** use correct type

### Features

- **proto:** use correct type ([2fe5f00](https://github.com/whitehawkcec/whitehawk-proto/commit/2fe5f00cf1b6fd0e73ee0ee10c3fe8208264089f))
- **proto:** use correct type ([dd82a22](https://github.com/whitehawkcec/whitehawk-proto/commit/dd82a224a8105c42c42ff92a20773b62ab11726f))

## [0.18.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.17.2...0.18.0) (2022-08-05)

### ⚠ BREAKING CHANGES

- **proto:** remove `SubscriptionProduct` `config` field

### Features

- **proto:** remove `SubscriptionProduct` `config` field ([680d6f0](https://github.com/whitehawkcec/whitehawk-proto/commit/680d6f071787c6558fbc59ad67d5c609ea819e33))

### [0.17.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.17.1...0.17.2) (2022-08-05)

### Features

- **proto:** return `product_id` in response ([e901599](https://github.com/whitehawkcec/whitehawk-proto/commit/e901599e4e2370fa3048ec5ebba9a46997113c49))

### [0.17.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.17.0...0.17.1) (2022-08-05)

### Features

- **proto:** add BK `license_type` ([c8fa0f8](https://github.com/whitehawkcec/whitehawk-proto/commit/c8fa0f89bcb682a661612923904d4dfccd2589f6))

## [0.17.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.16.0...0.17.0) (2022-08-05)

### ⚠ BREAKING CHANGES

- **proto:** change create request for subscription product

### Features

- **proto:** change create request for subscription product ([a285da3](https://github.com/whitehawkcec/whitehawk-proto/commit/a285da39497436f4105f00f1240f75a7c8c11ea2))

## [0.16.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.15.22...0.16.0) (2022-08-05)

### ⚠ BREAKING CHANGES

- **proto:** remove unnecessary messages for subscriptions
- **proto:** change shape of `SubscriptionProduct`
- **proto:** remove `Subscription` `products` field

### Features

- **proto:** add BK config message ([5b529e8](https://github.com/whitehawkcec/whitehawk-proto/commit/5b529e860faf290f786aa53ace0c0d99d24e2ebc))
- **proto:** add BK domain messages ([4ea5213](https://github.com/whitehawkcec/whitehawk-proto/commit/4ea521396a157c0d7fdbb3578fb745fd13492255))
- **proto:** add service for subscription products ([e8e1d53](https://github.com/whitehawkcec/whitehawk-proto/commit/e8e1d5360f9e67f4b1225bcee688c8586e6ba5f5))
- **proto:** add subscription product for BK ([3a71ea0](https://github.com/whitehawkcec/whitehawk-proto/commit/3a71ea0f9817cfc34be2ac2a45add99321f8d7a1))
- **proto:** change shape of `SubscriptionProduct` ([6d3cbe4](https://github.com/whitehawkcec/whitehawk-proto/commit/6d3cbe43d8b428e4a7e6ea714c84c85e1035a8b5))
- **proto:** remove `Subscription` `products` field ([16e3707](https://github.com/whitehawkcec/whitehawk-proto/commit/16e37072cd281f86832d88cf15f10f457dd88847))
- **proto:** remove unnecessary messages for subscriptions ([73d1114](https://github.com/whitehawkcec/whitehawk-proto/commit/73d11147f25de0f58fb96bf62d41dab13850c0e8))

### [0.15.22](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.21...0.15.22) (2022-08-04)

### [0.15.21](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.20...0.15.21) (2022-08-04)

### [0.15.20](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.19...0.15.20) (2022-08-04)

### [0.15.19](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.18...0.15.19) (2022-08-03)

### [0.15.18](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.17...0.15.18) (2022-08-03)

### [0.15.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.16...0.15.17) (2022-08-03)

### [0.15.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.15...0.15.16) (2022-08-03)

### [0.15.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.14...0.15.15) (2022-08-03)

### [0.15.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.13...0.15.14) (2022-08-03)

### [0.15.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.12...0.15.13) (2022-08-03)

### [0.15.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.11...0.15.12) (2022-08-02)

### [0.15.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.10...0.15.11) (2022-08-02)

### [0.15.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.9...0.15.10) (2022-08-02)

### [0.15.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.8...0.15.9) (2022-08-02)

### [0.15.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.7...0.15.8) (2022-08-01)

### [0.15.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.6...0.15.7) (2022-08-01)

### [0.15.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.5...0.15.6) (2022-08-01)

### [0.15.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.4...0.15.5) (2022-08-01)

### [0.15.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.3...0.15.4) (2022-08-01)

### [0.15.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.2...0.15.3) (2022-07-28)

### [0.15.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.1...0.15.2) (2022-07-28)

### [0.15.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.15.0...0.15.1) (2022-07-28)

## [0.15.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.27...0.15.0) (2022-07-28)

### Bug Fixes

- refactor ulid to slug for cyberone ([42d5448](https://github.com/WhitehawkCEC/whitehawk-proto/commit/42d5448991e42dde2adbfaa4c6d1ebf00ff1a061))

### [0.14.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.14.0...0.14.1) (2022-07-27)

### Features

- proto def for cyberone and supplywisdom ([359dafa](https://github.com/WhitehawkCEC/whitehawk-proto/commit/359dafa46e1be2eed48da75368fac1b8d6956801))

## [0.14.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.13.0...0.14.0) (2022-07-26)

### ⚠ BREAKING CHANGES

- change delete parameter for bundle template and set

### Features

- change delete parameter for bundle template and set ([7582ee5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7582ee5d836f53059451e6d93f58f58a34ca2ab9))

## [0.13.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.28...0.13.0) (2022-07-25)

### ⚠ BREAKING CHANGES

- return bundle set summary for list function
- return bundle set summary for list function

### Features

- return bundle set summary for list function ([b21ba88](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b21ba885223d2608ac61c58f3fbb35be3b48ee62))
- return bundle set summary for list function ([333697c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/333697cee2be7f472ba4b4f700bdb3dc2f1c981c))

### [0.12.28](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.26...0.12.28) (2022-07-23)

### Features

- add `Company` service ([5b74a92](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5b74a927779b4a64b38f50407ea712710d37fcdf))
- add `Industry` service ([c084782](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c084782574a37e06b7a57b83cf356bcc0e196d00))

### [0.14.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.14.0...0.14.1) (2022-07-27)

### Features

- proto def for cyberone and supplywisdom ([359dafa](https://github.com/WhitehawkCEC/whitehawk-proto/commit/359dafa46e1be2eed48da75368fac1b8d6956801))

## [0.14.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.13.0...0.14.0) (2022-07-26)

### ⚠ BREAKING CHANGES

- change delete parameter for bundle template and set

### Features

- change delete parameter for bundle template and set ([7582ee5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7582ee5d836f53059451e6d93f58f58a34ca2ab9))

## [0.13.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.18...0.13.0) (2022-07-25)

### ⚠ BREAKING CHANGES

- return bundle set summary for list function
- return bundle set summary for list function

### Features

- add `Company` service ([5b74a92](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5b74a927779b4a64b38f50407ea712710d37fcdf))
- add `Industry` service ([c084782](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c084782574a37e06b7a57b83cf356bcc0e196d00))
- return bundle set summary for list function ([b21ba88](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b21ba885223d2608ac61c58f3fbb35be3b48ee62))
- return bundle set summary for list function ([333697c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/333697cee2be7f472ba4b4f700bdb3dc2f1c981c))

### [0.12.28](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.27...0.12.28) (2022-07-23)

### Features

- add `Industry` service ([c084782](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c084782574a37e06b7a57b83cf356bcc0e196d00))

### [0.12.27](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.26...0.12.27) (2022-07-22)

### Features

- add `Company` service ([5b74a92](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5b74a927779b4a64b38f50407ea712710d37fcdf))

### [0.12.26](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.25...0.12.26) (2022-07-21)

### [0.12.25](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.24...0.12.25) (2022-07-21)

### [0.12.24](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.23...0.12.24) (2022-07-21)

### [0.12.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.22...0.12.23) (2022-07-21)

### [0.12.22](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.21...0.12.22) (2022-07-21)

### [0.12.21](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.20...0.12.21) (2022-07-21)

### [0.12.20](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.19...0.12.20) (2022-07-20)

### [0.12.19](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.18...0.12.19) (2022-07-19)

### [0.12.18](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.17...0.12.18) (2022-07-19)

### [0.12.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.16...0.12.17) (2022-07-19)

### [0.12.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.14...0.12.15) (2022-07-18)

### [0.12.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.13...0.12.14) (2022-07-18)

### [0.12.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.15...0.12.16) (2022-07-19)

### [0.12.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.14...0.12.15) (2022-07-19)

### [0.12.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.13...0.12.14) (2022-07-19)

### [0.12.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.12...0.12.13) (2022-07-19)

### [0.12.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.11...0.12.12) (2022-07-19)

### [0.12.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.10...0.12.11) (2022-07-19)

### Bug Fixes

- remove unused service ([c1d443a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c1d443af0079c63138a43b20f335f54e086f3674))

### [0.12.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.9...0.12.10) (2022-07-19)

### Features

- add product services ([30f25fa](https://github.com/WhitehawkCEC/whitehawk-proto/commit/30f25fa9d08ef6409389bc7914d43b80253effb8))

### [0.12.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.12...0.12.13) (2022-07-18)

### [0.12.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.11...0.12.12) (2022-07-18)

### [0.12.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.10...0.12.11) (2022-07-15)

### [0.12.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.9...0.12.10) (2022-07-15)

### [0.12.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.8...0.12.9) (2022-07-14)

### [0.12.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.7...0.12.8) (2022-07-14)

### [0.12.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.6...0.12.7) (2022-07-14)

### [0.12.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.6...0.12.7) (2022-07-14)

### [0.12.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.5...0.12.6) (2022-07-14)

### [0.12.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.4...0.12.5) (2022-07-14)

### [0.12.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.3...0.12.4) (2022-07-14)

### [0.12.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.3...0.12.4) (2022-07-14)

### [0.12.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.3...0.12.4) (2022-07-14)

### [0.12.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.3...0.12.4) (2022-07-14)

### [0.12.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.4...0.12.5) (2022-07-14)

### [0.12.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.3...0.12.4) (2022-07-14)

### [0.12.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.2...0.12.3) (2022-07-08)

### Features

- product feature service ([c2c1c74](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c2c1c74b4d603b588d92670d6cacba8522d7edd5))

### [0.12.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.1...0.12.2) (2022-07-05)

### Features

- read service for bundle templates and sets ([8f38ba8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8f38ba869fbf8bae2222ff36571c14dcebadaa9a))

### [0.12.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.12.0...0.12.1) (2022-06-22)

## [0.12.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.11.0...0.12.0) (2022-06-22)

### ⚠ BREAKING CHANGES

- add generated Ulid for bundle set and template, make industries repeated and move from template to set, remove assigned_to_companies from template
- **proto:** prefer `SubscriptionType` enum

### Features

- **proto:** add `SubscriptionType` ([a41ca75](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a41ca75e9b16650e804fd12811d0788ae7dbabe5))
- **proto:** add `validity` when creating/updating subscriptions ([8481401](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8481401e1d5f822aec5d42e5b18569d86325dd02))
- **proto:** prefer `SubscriptionType` enum ([0768047](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0768047c5e2450428ab369d13d5f1af49136b552))
- return created bundle set ([23ae890](https://github.com/WhitehawkCEC/whitehawk-proto/commit/23ae8900b1917be8d9e5ebc3e067e9f6f78b785e))
- return created bundle template ([fc14857](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fc1485706559b27dfd01a0396ca1ab6dca5a8892))

- add generated Ulid for bundle set and template, make industries repeated and move from template to set, remove assigned_to_companies from template ([69f0041](https://github.com/WhitehawkCEC/whitehawk-proto/commit/69f0041a392ebf1f2ea6d2dc191eb33759f3aae0))

## [0.12.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.11.0...0.12.0) (2022-06-07)

### ⚠ BREAKING CHANGES

- **proto:** prefer `SubscriptionType` enum

### Features

- **proto:** add `SubscriptionType` ([a41ca75](https://github.com/whitehawkcec/whitehawk-proto/commit/a41ca75e9b16650e804fd12811d0788ae7dbabe5))
- **proto:** add `validity` when creating/updating subscriptions ([8481401](https://github.com/whitehawkcec/whitehawk-proto/commit/8481401e1d5f822aec5d42e5b18569d86325dd02))
- **proto:** prefer `SubscriptionType` enum ([0768047](https://github.com/whitehawkcec/whitehawk-proto/commit/0768047c5e2450428ab369d13d5f1af49136b552))

## [0.11.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.10.0...0.11.0) (2022-06-02)

### ⚠ BREAKING CHANGES

- change package name

### Features

- add bundle set ([267d1bc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/267d1bce787a4a909c91aab2d0a453cac0fdc313))
- add bundle set service ([b543367](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b543367e4a0a922392c4bcb496436e847e98384d))
- change package name ([9efbdc7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9efbdc79bb5adeb8e6b3e1667fb1547ea2fbf282))

### [0.10.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.10.1...0.10.2) (2022-05-12)

### [0.10.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.10.0...0.10.1) (2022-05-12)

## [0.10.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.9.0...0.10.0) (2022-05-12)

### ⚠ BREAKING CHANGES

- prefer more explicit names
- remove unnecessary `displayName` field
- add `product_validity`
- describe `Subscription`

### Features

- add `product_validity` ([f6e4263](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f6e42632b6f0e9c72fee6b50d5870d4826ab8aa1))
- add `Subscription` ([53a1e78](https://github.com/WhitehawkCEC/whitehawk-proto/commit/53a1e7815f2b91e339e0600a6b299115d4be2072))
- add bundle template ([391c138](https://github.com/WhitehawkCEC/whitehawk-proto/commit/391c1389fa94c99cf7eafbf378afeb13b44297df))
- add bundle template services ([2f260ce](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2f260ce8a8be39b33dbdacda78a6929cb30ab0f2))
- add CRUD for `Subscription` ([9ff0353](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9ff03536666b20571427c02b014c2c7cc9fca213))
- add product and product category ([96e0a8e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/96e0a8ef991ac704a5741b02c25fe09c8147d15e))
- add product category services ([1e58b13](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1e58b130e43b203cfd447f5e150b2cf716577bbd))
- describe `Subscription` ([1140203](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1140203ba75ae7cfb970fdb0c5c3d529ad01ad36))
- prefer more explicit names ([e1e8e03](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e1e8e0328b0152580f74f9113968dfb3849a2289))
- **proto:** add `Industry` ([bb87e40](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bb87e406da7d281d88baeca438ad78e63b835994))
- remove unnecessary `displayName` field ([9856fa2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9856fa27bbf54e0b871da032b925e11fe2e4b82c))

## [0.10.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.9.0...0.10.0) (2022-05-12)

### ⚠ BREAKING CHANGES

- prefer more explicit names
- remove unnecessary `displayName` field
- add `product_validity`
- describe `Subscription`

### Features

- add `product_validity` ([f6e4263](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f6e42632b6f0e9c72fee6b50d5870d4826ab8aa1))
- add `Subscription` ([53a1e78](https://github.com/WhitehawkCEC/whitehawk-proto/commit/53a1e7815f2b91e339e0600a6b299115d4be2072))
- add bundle template ([391c138](https://github.com/WhitehawkCEC/whitehawk-proto/commit/391c1389fa94c99cf7eafbf378afeb13b44297df))
- add bundle template services ([2f260ce](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2f260ce8a8be39b33dbdacda78a6929cb30ab0f2))
- add CRUD for `Subscription` ([9ff0353](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9ff03536666b20571427c02b014c2c7cc9fca213))
- add product and product category ([96e0a8e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/96e0a8ef991ac704a5741b02c25fe09c8147d15e))
- add product category services ([1e58b13](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1e58b130e43b203cfd447f5e150b2cf716577bbd))
- describe `Subscription` ([1140203](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1140203ba75ae7cfb970fdb0c5c3d529ad01ad36))
- prefer more explicit names ([e1e8e03](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e1e8e0328b0152580f74f9113968dfb3849a2289))
- **proto:** add `Industry` ([bb87e40](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bb87e406da7d281d88baeca438ad78e63b835994))
- remove unnecessary `displayName` field ([9856fa2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9856fa27bbf54e0b871da032b925e11fe2e4b82c))

### [0.9.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.9.1...0.9.2) (2022-04-05)

### [0.9.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.9.0...0.9.1) (2022-04-05)

### Features

- add `Subscription` ([53a1e78](https://github.com/whitehawkcec/whitehawk-proto/commit/53a1e7815f2b91e339e0600a6b299115d4be2072))
- add CRUD for `Subscription` ([9ff0353](https://github.com/whitehawkcec/whitehawk-proto/commit/9ff03536666b20571427c02b014c2c7cc9fca213))
- **proto:** add `Industry` ([bb87e40](https://github.com/whitehawkcec/whitehawk-proto/commit/bb87e406da7d281d88baeca438ad78e63b835994))
