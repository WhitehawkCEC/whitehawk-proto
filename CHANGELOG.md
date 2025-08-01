# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.91.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.90.2...0.91.0) (2025-07-18)


### ⚠ BREAKING CHANGES

* **proto:** remove service `client_portal.manufacturers__0__resource_upload_info.v1`
* **proto:** remove service `client_portal.manufacturers__0__resource_download_info.v1`
* **proto:** remove service `client_portal.manufacturers.products.v1`
* **proto:** change `client_portal.manufacturers.v1` `CreateResponse`

### Features

* **proto:** add message `ManufacturerId` ([d071350](https://github.com/whitehawkcec/whitehawk-proto/commit/d07135002fb7a5042fc65e36692c2844f8597b6d))
* **proto:** add message `Resource*` ([42dc16e](https://github.com/whitehawkcec/whitehawk-proto/commit/42dc16e8e359e5a09094b3dd1324f15bdb43f9db))
* **proto:** add service `client_portal.manufacturers__0__resources__0__data.v1` ([b2b4cd4](https://github.com/whitehawkcec/whitehawk-proto/commit/b2b4cd4c989e17184ced457246ce0000639347ae))
* **proto:** add service `client_portal.manufacturers__0__resources.v1` ([ca7c7ff](https://github.com/whitehawkcec/whitehawk-proto/commit/ca7c7ffedbc5ebf83932355d2461d9bbeb6fcdf7))
* **proto:** change `client_portal.manufacturers.v1` `CreateResponse` ([e762c37](https://github.com/whitehawkcec/whitehawk-proto/commit/e762c3782a7a9fd7cd88ab388bc788663dc5e42d))
* **proto:** remove service `client_portal.manufacturers__0__resource_download_info.v1` ([9a2a6fa](https://github.com/whitehawkcec/whitehawk-proto/commit/9a2a6fab21f6b47d9c92b3eeab995fa1b91c0f5e))
* **proto:** remove service `client_portal.manufacturers__0__resource_upload_info.v1` ([27d5bea](https://github.com/whitehawkcec/whitehawk-proto/commit/27d5bea72fd9f66479f5447e949ae8d6de07fdfd))
* **proto:** remove service `client_portal.manufacturers.products.v1` ([6e5653d](https://github.com/whitehawkcec/whitehawk-proto/commit/6e5653d804e431b7630be8624ed33447b6704e64))

### [0.90.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.90.1...0.90.2) (2025-06-10)


### Features

* **proto:** add service `client_portal.product_types.v1` ([c794e72](https://github.com/whitehawkcec/whitehawk-proto/commit/c794e72f15f12ba8fad6bf1817726472618317b3))

### [0.90.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.90.0...0.90.1) (2025-06-03)


### Bug Fixes

* **proto:** properly mark reserved fields ([26586a1](https://github.com/whitehawkcec/whitehawk-proto/commit/26586a1c8ff381dc5a0674194fdf4189f777d75b))
* **proto:** properly mark reserved fields ([f52f948](https://github.com/whitehawkcec/whitehawk-proto/commit/f52f948999eaeb2eab3868ecee4cecbbd3ee4c41))
* **proto:** properly mark reserved fields ([1f7f9a1](https://github.com/whitehawkcec/whitehawk-proto/commit/1f7f9a14eca11c1749f8948d77c98e930f036f36))

## [0.90.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.89.0...0.90.0) (2025-06-03)


### ⚠ BREAKING CHANGES

* **proto:** change messages for `client_portal.manufacturers__0__products.v1`
* **proto:** remove rpc `Update` from `client_portal.products.v3`
* **proto:** change messages for `client_portal.manufacturers__0__products.v1`
* **proto:** introduce `*Ref` messages types for product.v2
* **proto:** remove messages `proto.report.bundle.v1`
* **proto:** remove messages `proto.custom_questionnaire.v1`
* **proto:** remove messages `proto.jobs.v1`
* **proto:** partially remove messages from `proto.scorecard_v3.indepthblackkitecmmcv2.v2`
* **proto:** remove message `proto.framework.v4`
* **proto:** remove message `proto.todo.v2`
* **proto:** remove message `proto.framework.v3`
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.cyber_risk_rating.black_kite.performance.v1`
* **proto:** remove service `client_portal.reports.bundle.set.v1`
* **proto:** remove service `client_portal.reports.account.v1`
* **proto:** remove service `client_portal.reports.account.subscription.v1`
* **proto:** remove service `client_portal.reports.account.subscription.product.v1`
* **proto:** remove service `client_portal.products.v1`
* **proto:** remove service `client_portal.products.features.v1`
* **proto:** remove service `client_portal.products.categories.v1`
* **proto:** remove service `client_portal.manufacturers.products.count.v1`
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__portfolio_reports.v2`
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__portfolio_reports.v1`
* **proto:** remove service `client_portal.accounts__0__portfolio_report_template.v1`
* **proto:** remove service `client_portal.accounts__0__frameworks__0__findings__0__result_override.v2`
* **proto:** remove service `client_portal.accounts__0__frameworks__0__findings__0__result_override.v1`
* **proto:** remove service `client_portal.accounts__0__frameworks.v2`
* **proto:** remove service `client_portal.accounts.id.integrations.bitsight.companies.company_id.cyber_risk.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.syncs.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.ecosystems.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.cyber_one.sync.v1`
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__cyber_one__sync.v1`
* **proto:** remove message `proto.todo.v1`
* **proto:** remove message `proto.status.v1`
* **proto:** remove message `proto.supply_wisdom.utils.v1`
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.targets.v1`
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.assets.v1`
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.key.v1`
* **proto:** remove service `proto.supply_wisdom.admin.v1`
* **proto:** remove message `proto.scorecard_licensing.v1`
* **proto:** remove message `proto.scorecard_v3.indepthblackkitewithframeworks.v1`
* **proto:** remove fields from service `client_portal.scorecards_v3.v1`
* **proto:** remove fields from service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v3`
* **proto:** remove fields from service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v2`
* **proto:** remove method from service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v2`
* **proto:** remove service `client_portal.accounts__0__frameworks.v1`
* **proto:** remove message `proto.framework.v2`
* **proto:** remove message `proto.framework.v1`
* **proto:** remove message `proto.files.v1`
* **proto:** remove message `proto.files.scorecard_templates.v1`
* **proto:** remove message `proto.cyberone.v1`
* **proto:** remove service `client_portal.cyberone.id.matched_pairs.supply_wisdom.v1`
* **proto:** remove service `client_portal.cyberone.id.matched_pairs.white_hawk.v1`
* **proto:** remove service `client_portal.cyberone.id.cyberone.key.v1`
* **proto:** remove service `client_portal.cyberone.id.cyberone.assets.v1`
* **proto:** remove message `proto.custom_questionnaire_taken.v1`
* **proto:** remove message `proto.custom_questionnaire_answered.v1`
* **proto:** remove message `proto.batch.zip.v3`

### Features

* **proto:** change messages for `client_portal.manufacturers__0__products.v1` ([6e3dcc3](https://github.com/whitehawkcec/whitehawk-proto/commit/6e3dcc358efdd03d83ea50014810067f9a2ca282))
* **proto:** change messages for `client_portal.manufacturers__0__products.v1` ([69dfcd0](https://github.com/whitehawkcec/whitehawk-proto/commit/69dfcd003c73a52cdfd23445ace52b33adcbdc11))
* **proto:** introduce `*Ref` messages types for product.v2 ([ca2fc2a](https://github.com/whitehawkcec/whitehawk-proto/commit/ca2fc2a1653cd077f7a8fa40bb099a073ecdf33a))
* **proto:** partially remove messages from `proto.scorecard_v3.indepthblackkitecmmcv2.v2` ([95a6aff](https://github.com/whitehawkcec/whitehawk-proto/commit/95a6aff44e4715402e64ca60041abc81a100f457))
* **proto:** remove fields from service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v3` ([47cad28](https://github.com/whitehawkcec/whitehawk-proto/commit/47cad287c482589a55956397b27727936c3e9652))
* **proto:** remove fields from service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v2` ([87f32c9](https://github.com/whitehawkcec/whitehawk-proto/commit/87f32c9d25219a0a3d7181fbc2d5f752dd27e668))
* **proto:** remove fields from service `client_portal.scorecards_v3.v1` ([7c78704](https://github.com/whitehawkcec/whitehawk-proto/commit/7c787045801e88dec341dee5f4c79ef29da96413))
* **proto:** remove message `proto.batch.zip.v3` ([a3c617b](https://github.com/whitehawkcec/whitehawk-proto/commit/a3c617b1d4838489e99ab8bc630c2839bcd40d0c))
* **proto:** remove message `proto.custom_questionnaire_answered.v1` ([f993b86](https://github.com/whitehawkcec/whitehawk-proto/commit/f993b862ec42ef382ce08b79bd7fdf0caacb0674))
* **proto:** remove message `proto.custom_questionnaire_taken.v1` ([6e9836c](https://github.com/whitehawkcec/whitehawk-proto/commit/6e9836c608972ba8d6253cb57c0cac17231f641d))
* **proto:** remove message `proto.cyberone.v1` ([5c0b720](https://github.com/whitehawkcec/whitehawk-proto/commit/5c0b720d4300f6a900450dfa39bac461662e9892))
* **proto:** remove message `proto.files.scorecard_templates.v1` ([8fef34e](https://github.com/whitehawkcec/whitehawk-proto/commit/8fef34e3a616a9af4abc4489a1812fe0ec52cafd))
* **proto:** remove message `proto.files.v1` ([560840e](https://github.com/whitehawkcec/whitehawk-proto/commit/560840eda57446766e8ffc9069498450a980e6d5))
* **proto:** remove message `proto.framework.v1` ([900d2b0](https://github.com/whitehawkcec/whitehawk-proto/commit/900d2b0c56ec6f498439606b5ac30ebb8e76a66e))
* **proto:** remove message `proto.framework.v2` ([d22e12b](https://github.com/whitehawkcec/whitehawk-proto/commit/d22e12bff5086cb0d7c609d56b15b03700dd64bb))
* **proto:** remove message `proto.framework.v3` ([7b4481c](https://github.com/whitehawkcec/whitehawk-proto/commit/7b4481c2b826129e980759a26cd7cdcaeec97d50))
* **proto:** remove message `proto.framework.v4` ([6bc5643](https://github.com/whitehawkcec/whitehawk-proto/commit/6bc56438984f7ecc18ed23cfb2a5bc433bd5a24f))
* **proto:** remove message `proto.scorecard_licensing.v1` ([c6ddad6](https://github.com/whitehawkcec/whitehawk-proto/commit/c6ddad6ef7373dd2745a49b522d5f85ddc90f79a))
* **proto:** remove message `proto.scorecard_v3.indepthblackkitewithframeworks.v1` ([655418b](https://github.com/whitehawkcec/whitehawk-proto/commit/655418b26e64ee2ea441f76cd01804cd59722543))
* **proto:** remove message `proto.status.v1` ([3684e26](https://github.com/whitehawkcec/whitehawk-proto/commit/3684e26b713dace3c7a37416889200c0b68d0913))
* **proto:** remove message `proto.supply_wisdom.utils.v1` ([ede395d](https://github.com/whitehawkcec/whitehawk-proto/commit/ede395d20414e03a9ec7de7640aa9df0c46e2540))
* **proto:** remove message `proto.todo.v1` ([a35c9c4](https://github.com/whitehawkcec/whitehawk-proto/commit/a35c9c43e9d4b209afa50533a75f21950d44be83))
* **proto:** remove message `proto.todo.v2` ([4850467](https://github.com/whitehawkcec/whitehawk-proto/commit/48504678a91c5c1a148222b4216c6addcceaa44b))
* **proto:** remove messages `proto.custom_questionnaire.v1` ([bc896ee](https://github.com/whitehawkcec/whitehawk-proto/commit/bc896eea9f62ed750a5ae293dc665f0fba0e4e48))
* **proto:** remove messages `proto.jobs.v1` ([9deeda9](https://github.com/whitehawkcec/whitehawk-proto/commit/9deeda9787f2881bb5830cf330947db2b20e1aff))
* **proto:** remove messages `proto.report.bundle.v1` ([c55f214](https://github.com/whitehawkcec/whitehawk-proto/commit/c55f214bec19c9df1ff08de3e8498694543cf5f8))
* **proto:** remove method from service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v2` ([823f36a](https://github.com/whitehawkcec/whitehawk-proto/commit/823f36abeccda711d3979fe8204040c7472b08ad))
* **proto:** remove rpc `Update` from `client_portal.products.v3` ([2e41c4d](https://github.com/whitehawkcec/whitehawk-proto/commit/2e41c4dd284a61070792e02d3f5048f1c15be3b1))
* **proto:** remove service `client_portal.accounts__0__frameworks__0__findings__0__result_override.v1` ([7043de5](https://github.com/whitehawkcec/whitehawk-proto/commit/7043de518ee3aaf8586aee6b87e94f2eb137baac))
* **proto:** remove service `client_portal.accounts__0__frameworks__0__findings__0__result_override.v2` ([2a0e8fb](https://github.com/whitehawkcec/whitehawk-proto/commit/2a0e8fb3c8b0646565a2f6a72859b60e76bcf3f9))
* **proto:** remove service `client_portal.accounts__0__frameworks.v1` ([2fbcc69](https://github.com/whitehawkcec/whitehawk-proto/commit/2fbcc69a51fa97df89ef54d866ff9678ba516e6b))
* **proto:** remove service `client_portal.accounts__0__frameworks.v2` ([0d43a9d](https://github.com/whitehawkcec/whitehawk-proto/commit/0d43a9d204d953be72f362ea2e0525682c127170))
* **proto:** remove service `client_portal.accounts__0__portfolio_report_template.v1` ([ebf089a](https://github.com/whitehawkcec/whitehawk-proto/commit/ebf089a73f88c54ce098627e155df27ce0ccd2ee))
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__cyber_one__sync.v1` ([28b123e](https://github.com/whitehawkcec/whitehawk-proto/commit/28b123ee53241baa3ff6c28d6dcb5c8582ccaaea))
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__portfolio_reports.v1` ([4bae4c7](https://github.com/whitehawkcec/whitehawk-proto/commit/4bae4c7ab129fa5fb40775f29fb7bb23596e0038))
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__portfolio_reports.v2` ([e8870ea](https://github.com/whitehawkcec/whitehawk-proto/commit/e8870ea6a159927b359ee0fb40437f000bb53f48))
* **proto:** remove service `client_portal.accounts.id.integrations.bitsight.companies.company_id.cyber_risk.v1` ([1407a11](https://github.com/whitehawkcec/whitehawk-proto/commit/1407a11c6f5c622db0eea50197bf418f96ce0d5e))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.ecosystems.v1` ([fa891a1](https://github.com/whitehawkcec/whitehawk-proto/commit/fa891a162f32146ec56845bdd86c735b12057440))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.syncs.v1` ([48b5c65](https://github.com/whitehawkcec/whitehawk-proto/commit/48b5c659d55ae7d7d0a1023c88e0ba373ba4409e))
* **proto:** remove service `client_portal.accounts.id.integrations.cyber_one.sync.v1` ([cb0d0c0](https://github.com/whitehawkcec/whitehawk-proto/commit/cb0d0c0d4528e1a40259c2e132c4548f2bdd37cd))
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.cyber_risk_rating.black_kite.performance.v1` ([cba722f](https://github.com/whitehawkcec/whitehawk-proto/commit/cba722fa74a5f9f52cc1e7d85b72c4638421b3b4))
* **proto:** remove service `client_portal.cyberone.id.cyberone.assets.v1` ([f2ac482](https://github.com/whitehawkcec/whitehawk-proto/commit/f2ac482100e48607fca537ee716e373577c88571))
* **proto:** remove service `client_portal.cyberone.id.cyberone.key.v1` ([803104b](https://github.com/whitehawkcec/whitehawk-proto/commit/803104be615f2de449cfe23555757dd0fbf9a9ab))
* **proto:** remove service `client_portal.cyberone.id.matched_pairs.supply_wisdom.v1` ([17c4184](https://github.com/whitehawkcec/whitehawk-proto/commit/17c418409e622575686dad0c3efbe9b377a50ca7))
* **proto:** remove service `client_portal.cyberone.id.matched_pairs.white_hawk.v1` ([2548282](https://github.com/whitehawkcec/whitehawk-proto/commit/25482823d9201114efe676bc3f961e5d2887b372))
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.assets.v1` ([02260c4](https://github.com/whitehawkcec/whitehawk-proto/commit/02260c48f7ddb07207ed081d7ee10df6b2ddcae3))
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.key.v1` ([ab62e8b](https://github.com/whitehawkcec/whitehawk-proto/commit/ab62e8bc2400d1078b930583d191b70d33228cad))
* **proto:** remove service `client_portal.cyberone.id.supply_wisdom.targets.v1` ([c25e532](https://github.com/whitehawkcec/whitehawk-proto/commit/c25e5329dd092efce267e7bc74f0f5088b5d2f0c))
* **proto:** remove service `client_portal.manufacturers.products.count.v1` ([ad413db](https://github.com/whitehawkcec/whitehawk-proto/commit/ad413db81c482af1ff0155278d65a8b1464f8a38))
* **proto:** remove service `client_portal.products.categories.v1` ([cdaa3bd](https://github.com/whitehawkcec/whitehawk-proto/commit/cdaa3bd3aca739efd5b54ccb8ac17f2924558eb7))
* **proto:** remove service `client_portal.products.features.v1` ([e654691](https://github.com/whitehawkcec/whitehawk-proto/commit/e654691abe9dafcf64b4854d2704dce23c21ae2c))
* **proto:** remove service `client_portal.products.v1` ([c6a81af](https://github.com/whitehawkcec/whitehawk-proto/commit/c6a81af5f181468a8125271372a812f4dc35cc82))
* **proto:** remove service `client_portal.reports.account.subscription.product.v1` ([5e1f0fa](https://github.com/whitehawkcec/whitehawk-proto/commit/5e1f0fa8db382353e83f0384391a929ad5aaa808))
* **proto:** remove service `client_portal.reports.account.subscription.v1` ([d94a1d5](https://github.com/whitehawkcec/whitehawk-proto/commit/d94a1d5511c97ee21bc9bf4c0530736c93ef5364))
* **proto:** remove service `client_portal.reports.account.v1` ([f16d6d4](https://github.com/whitehawkcec/whitehawk-proto/commit/f16d6d49a9a0def3f4668792684f2d170daa17ec))
* **proto:** remove service `client_portal.reports.bundle.set.v1` ([6d64dfb](https://github.com/whitehawkcec/whitehawk-proto/commit/6d64dfbcda4c73d179b762d6e7346f31c6e00620))
* **proto:** remove service `proto.supply_wisdom.admin.v1` ([3a7b2ad](https://github.com/whitehawkcec/whitehawk-proto/commit/3a7b2adc6fa2de6392046772515f1b39b7e3f793))

## [0.89.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.88.0...0.89.0) (2025-05-20)


### ⚠ BREAKING CHANGES

* **proto:** mark required
* **proto:** mark required
* **proto:** mark required
* **proto:** mark required
* **proto:** mark required
* **proto:** take in necessary arguments
* **proto:** take in necessary arguments
* **proto:** mark required
* **proto:** take in necessary arguments
* **proto:** mark required
* **proto:** take in necessary arguments
* **proto:** take in necessary arguments

### Features

* **proto:** mark required ([6a45a9a](https://github.com/whitehawkcec/whitehawk-proto/commit/6a45a9a42c9aaa1edebc2ce94072a36b620db1e2))
* **proto:** mark required ([2089f75](https://github.com/whitehawkcec/whitehawk-proto/commit/2089f75e1863bf1dac764b30a951c889f5a1de57))
* **proto:** mark required ([c6577ce](https://github.com/whitehawkcec/whitehawk-proto/commit/c6577ce25dafd3db9ea4bacf8d2499dbc781d002))
* **proto:** mark required ([05d49ad](https://github.com/whitehawkcec/whitehawk-proto/commit/05d49ad9b9b463afcd2d652279c738d8623ee72c))
* **proto:** mark required ([a7b655a](https://github.com/whitehawkcec/whitehawk-proto/commit/a7b655acb105a0e71e484f438bdb8e4cf1262811))
* **proto:** mark required ([4843dd4](https://github.com/whitehawkcec/whitehawk-proto/commit/4843dd41ae79e732b2ffb484b24a3e13c55072da))
* **proto:** mark required ([867b8af](https://github.com/whitehawkcec/whitehawk-proto/commit/867b8af7088a70a7946555bb1dee1720711de859))
* **proto:** reorder messages ([76f3c9d](https://github.com/whitehawkcec/whitehawk-proto/commit/76f3c9ddba3d89d01ad477375018ee8d6dbd6648))
* **proto:** reorder rpc methods ([58f8807](https://github.com/whitehawkcec/whitehawk-proto/commit/58f8807e5a37637002885bcb86baeecf8c749853))
* **proto:** reorder rpc methods ([dcd9a29](https://github.com/whitehawkcec/whitehawk-proto/commit/dcd9a29e82a04a12132bec0e46bc5b9e1deb451a))


### Bug Fixes

* **proto:** take in necessary arguments ([73c558a](https://github.com/whitehawkcec/whitehawk-proto/commit/73c558ae5d2602635f7c5ff9147414abca79f032))
* **proto:** take in necessary arguments ([6d59c6f](https://github.com/whitehawkcec/whitehawk-proto/commit/6d59c6f872ec1ba55353bce98f0398bce9f475d6))
* **proto:** take in necessary arguments ([7452234](https://github.com/whitehawkcec/whitehawk-proto/commit/7452234db32f1966b4a18f76bad003cb9a12cfc9))
* **proto:** take in necessary arguments ([0370d74](https://github.com/whitehawkcec/whitehawk-proto/commit/0370d74e086ac7fb19ae70881ddb254f50ec4cf4))
* **proto:** take in necessary arguments ([e0f1bf7](https://github.com/whitehawkcec/whitehawk-proto/commit/e0f1bf7658e9cda18504e47b8d69313c37aee2ac))

## [0.88.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.87.0...0.88.0) (2025-05-09)


### ⚠ BREAKING CHANGES

* **proto:** use correct type for manufacturer ID
* **proto:** use correct type for manufacturer ID
* **proto:** use correct type for manufacturer ID
* **proto:** use correct type for manufacturer ID
* **proto:** don't return anything in `DeleteResponse`
* **proto:** use correct type for manufacturer ID
* **proto:** make `ListResponse` streaming
* **proto:** make `ListResponse` streaming
* **proto:** make `ListResponse` streaming

### Features

* **proto:** don't return anything in `DeleteResponse` ([f54b8de](https://github.com/whitehawkcec/whitehawk-proto/commit/f54b8de5319d5c132e28d68e95936e059ce2138b))
* **proto:** make `ListResponse` streaming ([c4dd4a9](https://github.com/whitehawkcec/whitehawk-proto/commit/c4dd4a932efe68332d07d97e2bbe484ee2c3a5ab))
* **proto:** make `ListResponse` streaming ([80677e4](https://github.com/whitehawkcec/whitehawk-proto/commit/80677e4615ce4d5233f27e26fa9c74069e79c6eb))
* **proto:** make `ListResponse` streaming ([9f651db](https://github.com/whitehawkcec/whitehawk-proto/commit/9f651dbeca3048bd274398e8a943a1ff5ad2cf43))


### Bug Fixes

* **proto:** use correct type for manufacturer ID ([78f0e2a](https://github.com/whitehawkcec/whitehawk-proto/commit/78f0e2a4a8c0c7ed5f52ef24a727765b38c3ab53))
* **proto:** use correct type for manufacturer ID ([52ae4bd](https://github.com/whitehawkcec/whitehawk-proto/commit/52ae4bde428a2e8ee633f94b489c2446e414aba1))
* **proto:** use correct type for manufacturer ID ([e603d67](https://github.com/whitehawkcec/whitehawk-proto/commit/e603d67bbe3d0d42966e45e4437cd689a8a337db))
* **proto:** use correct type for manufacturer ID ([8fdccbc](https://github.com/whitehawkcec/whitehawk-proto/commit/8fdccbcfa68ba713786ce2b9a7523d97155174d1))
* **proto:** use correct type for manufacturer ID ([b76c60b](https://github.com/whitehawkcec/whitehawk-proto/commit/b76c60b88a9f2d3ca1fc02161fc3edcf3765fab0))

## [0.87.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.86.0...0.87.0) (2025-05-08)


### ⚠ BREAKING CHANGES

* **proto:** make field REQUIRED
* **proto:** remove `meta` field from `product.v2`

### Features

* **proto:** make field REQUIRED ([4a2c0ba](https://github.com/whitehawkcec/whitehawk-proto/commit/4a2c0bafc52323760418f567a202bfab9a3a9b78))
* **proto:** remove `meta` field from `product.v2` ([6f8142b](https://github.com/whitehawkcec/whitehawk-proto/commit/6f8142b2828822b885202a057ce19f5615e4170a))

## [0.86.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.85.0...0.86.0) (2025-05-07)


### ⚠ BREAKING CHANGES

* **proto:** use correct type for manufacturer ID

### Bug Fixes

* **proto:** use correct type for manufacturer ID ([63d4384](https://github.com/whitehawkcec/whitehawk-proto/commit/63d4384db56beef6e974e185b6ee08eceb4deb0d))

## [0.85.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.47...0.85.0) (2025-05-06)


### ⚠ BREAKING CHANGES

* avoid duplication
* avoid duplication, add `id` to list/read
* avoid duplication
* avoid duplication, remove `Reseller`

### Features

* avoid duplication ([e2ca5ad](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e2ca5ad4731b0b0fe22a23b4924e14060885e6cf))
* avoid duplication ([cb3c0e2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cb3c0e26f97ada85ad6c73996ff903d9dcc0869e))
* avoid duplication, add `id` to list/read ([c3f6688](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c3f668815c0466eac245c5eed7e686dbab9ee2ac))
* avoid duplication, remove `Reseller` ([9ed3a6f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9ed3a6f29f1bc241a8674d5ec33f4c7d2dd1df49))

### [0.84.47](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.46...0.84.47) (2025-05-05)


### Features

* add `Collection` v1 message ([889d616](https://github.com/WhitehawkCEC/whitehawk-proto/commit/889d61619aa6aa8db69752a589112754e8fcd2d6))
* add `collections` v1 service ([f18eeff](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f18eeff83038265d5e7a9d15b3b948e3193c73c3))
* add `IndirectFile` v1 message ([880ae9b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/880ae9b9b02d77ea263b2bfa08f572f560261004))
* add `manufacturers__0__logo_download_info` v1 service ([0a70b7d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0a70b7defe27a8bc0614f77f63f3378665933d3d))
* add `manufacturers__0__logo_upload_info` v1 service ([cc4c7ef](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cc4c7ef4ef1a3ba7f99d1ac5fe618d0d81e02f75))
* add `manufacturers__0__products` v1 service ([7ddc299](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7ddc29979c5e233628c5a031e79af551a38b0d0f))
* add `manufacturers__0__resource_download_info` v1 service ([0342ece](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0342ecefa3a49eab683cc9cd260819f859eea162))
* add `manufacturers__0__resource_upload_info` v1 service ([eee69c4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/eee69c4b25380d030d099e85e9ef61e1b7737638))
* add `manufacturers` v1 service ([27bc097](https://github.com/WhitehawkCEC/whitehawk-proto/commit/27bc09712e072e1a5c55b66529c2a25eb36f49d2))
* add `Product` v2 message ([51b26a7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/51b26a7aa976295545b572fbd6ea52d5d821be6c))
* add `products` v3 service ([7070404](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7070404888864d0fbaa77f61c58cc2fcfab392c8))

### [0.84.46](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.45...0.84.46) (2025-05-01)

### [0.84.45](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.44...0.84.45) (2025-05-01)

### [0.84.44](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.43...0.84.44) (2025-05-01)

### [0.84.43](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.42...0.84.43) (2025-04-23)


### Features

* **jproto:** add Australia Essential 8 framework ([7e0d936](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7e0d936722b23bd173d1fbb4d66a6c39766cb84f))


### Bug Fixes

* **proto:** remove  Australia Essential 8 framework from v4 ([7078a88](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7078a88968dbdff15d34f9a9deb4800fa760945e))

### [0.84.42](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.41...0.84.42) (2025-04-23)


### Features

* **jproto:** add Australia Essential 8 framework ([aa700c7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aa700c741ba4ca197dadd53dc3d360f884e609e8))

### [0.84.41](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.40...0.84.41) (2025-04-01)

### [0.84.40](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.39...0.84.40) (2025-03-26)


### Features

* service def for partner shceduler logs ([0e1d0ae](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0e1d0ae11ef510a72124f3e9ee4c80b51d719226))

### [0.84.39](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.38...0.84.39) (2025-03-26)

### [0.84.38](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.37...0.84.38) (2024-08-15)


### Features

* added bitsight pending scorecards support ([402e2a2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/402e2a237fb9b20dc8f937953b55fe7e72cf57ab))

### [0.84.37](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.36...0.84.37) (2024-08-15)

### [0.84.36](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.35...0.84.36) (2024-08-14)


### Bug Fixes

* **proto:** wrong param was changd to slug ([06cdb0f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/06cdb0f607ad08fd5db19d23b97ded4fcc311ac3))

### [0.84.35](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.34...0.84.35) (2024-08-14)


### Bug Fixes

* **proto:** buyer is account id ([b1f7f92](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b1f7f92a1160ae011ad847d5ab19771625d8447d))

### [0.84.34](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.33...0.84.34) (2024-08-14)


### Bug Fixes

* **proto:** buyer info should be uuid ([54022f3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/54022f3f984f3cfab4d85b405f1b72a8b7f11190))

### [0.84.33](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.32...0.84.33) (2024-08-13)


### Bug Fixes

* **proto:** remove debug code ([f949145](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f9491456b7f1aa7afbc8bfe85598b87fb354bd73))

### [0.84.32](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.31...0.84.32) (2024-08-13)


### Bug Fixes

* **proto:** debug code ([44df8eb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/44df8eb4b5be1e6faa9327f4b9eb2333b80cb341))

### [0.84.31](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.30...0.84.31) (2024-08-12)


### Bug Fixes

* **proto:** response need to be a stream ([51b5fa3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/51b5fa375d77ee95cd353578b8cdf196bfee2867))

### [0.84.30](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.29...0.84.30) (2024-08-12)

### [0.84.29](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.28...0.84.29) (2024-08-12)


### Bug Fixes

* **proto:** batch scorecard id is ulid ([f7b08f2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f7b08f26073897afe049c166b4b33931431b3947))

### [0.84.28](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.27...0.84.28) (2024-08-12)


### Bug Fixes

* **proto:** remove create response ([306b693](https://github.com/WhitehawkCEC/whitehawk-proto/commit/306b693eef94bac17a850e450800ebb53c622ced))

### [0.84.27](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.26...0.84.27) (2024-08-12)


### Bug Fixes

* **proto:** param name ([be2cfde](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be2cfde2a0eb6c01a809bb107b189b18c16ff4fd))

### [0.84.26](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.25...0.84.26) (2024-08-12)


### Bug Fixes

* **proto:** make parameter name consistent with other service ([7bf0680](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7bf0680b1c60ae12bb34afa7f9b26d3c6532e538))

### [0.84.25](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.24...0.84.25) (2024-08-09)


### Bug Fixes

* **proto:** put batch id back into request ([c573fe1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c573fe14a2bb431fdc5c593f93d8f555c0b51cf0))

### [0.84.24](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.23...0.84.24) (2024-08-09)


### Bug Fixes

* **proto:** change file_id to batch_id ([9c3e1b9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c3e1b93292a6a3ce48b8509e7f10827a28d249d))
* **proto:** change id to batch_id ([7e22749](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7e227496cae9fd2f4032672700dfbf0590ca8ecf))
* **proto:** rearrange params ([51066a6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/51066a6510d763e81feb9fcf6581d950ac8b7bfe))
* **proto:** remove meta from request ([ef6b351](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ef6b351a2b20b103002ce472c39cbf99a44df6a6))

### [0.84.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.22...0.84.23) (2024-08-09)


### Bug Fixes

* **proto:** separate messages for request and result ([b027e4d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b027e4d7d23a87aef227e57e5208350d45ad188a))

### [0.84.22](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.21...0.84.22) (2024-08-06)


### Bug Fixes

* **proto:** field is an id ([3fae0a3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3fae0a35e174480327c030591260f765113b6c14))

### [0.84.21](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.20...0.84.21) (2024-08-06)

### [0.84.20](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.19...0.84.20) (2024-08-06)


### Bug Fixes

* **proto:** result is not repeated ([96e14ba](https://github.com/WhitehawkCEC/whitehawk-proto/commit/96e14ba0673079d3aba55d79db49c883b055abc2))

### [0.84.19](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.18...0.84.19) (2024-08-06)


### Bug Fixes

* **proto:** change name to ScorecardInfo ([2391781](https://github.com/WhitehawkCEC/whitehawk-proto/commit/239178125c49b47d5e2f4741adfcfc65de37f89f))

### [0.84.18](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.17...0.84.18) (2024-08-06)


### Bug Fixes

* **proto:** buyer is account/subscription ([bd717a7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bd717a73ab78113e5b029558ef23175ce3b5ca25))

### [0.84.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.16...0.84.17) (2024-08-06)


### Bug Fixes

* **proto:** remove batch id from response ([ac30aec](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ac30aecdd358bbd635bfb9959050c152916ed458))

### [0.84.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.15...0.84.16) (2024-08-06)


### Bug Fixes

* **proto:** remove include_cmmc, add batch id ([9f8cb1e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9f8cb1ef964460b0330dfefefdf370bbe5fc1477))

### [0.84.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.14...0.84.15) (2024-08-06)


### Bug Fixes

* **proto:** remove unused import ([8917050](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8917050629676655514e2a2c8586acb939f5325c))

### [0.84.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.13...0.84.14) (2024-08-06)

### [0.84.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.12...0.84.13) (2024-08-05)


### Bug Fixes

* **proto:** add read and delete methods, fix subscription id ([cf42df1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cf42df110f38e6a6d3002f150f927bda661a049d))

### [0.84.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.11...0.84.12) (2024-08-05)


### Bug Fixes

* **proto:** company id should be uuid ([547a0db](https://github.com/WhitehawkCEC/whitehawk-proto/commit/547a0dbbb35c4a387cfa73c69c95ba0aea1e1218))

### [0.84.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.10...0.84.11) (2024-08-01)


### Bug Fixes

* **proto:** snake case ([aa3fc2b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aa3fc2b4c5fea881b13b40971453d72473bd5ab6))

### [0.84.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.9...0.84.10) (2024-08-01)


### Bug Fixes

* **proto:** missing field name ([a954253](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a9542535fef24d8a6e81035ea9f84754fddb4dac))

### [0.84.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.8...0.84.9) (2024-08-01)


### Bug Fixes

* **proto:** use AccountSubscriptionId ([f5f9bdf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f5f9bdf0c169a0fea04614fa8e72257066c42a9b))

### [0.84.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.7...0.84.8) (2024-08-01)

### [0.84.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.6...0.84.7) (2024-08-01)


### Features

* added missing c1 chnages ([00d91de](https://github.com/WhitehawkCEC/whitehawk-proto/commit/00d91de1f9dc1371a07b378e794789b1a9109344))

### [0.84.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.5...0.84.6) (2024-08-01)

### [0.84.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.4...0.84.5) (2024-08-01)


### Features

* add accountsubscription support endpoint for c1 and sw ([4a90394](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4a90394a2d50e85866e81fb62046f9ded45015c2))

### [0.84.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.3...0.84.4) (2024-07-31)


### Bug Fixes

* **proto:** use account status ([cc2a29f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cc2a29fe3d4bcd66a76b78900bd5ac6afb6e20da))

### [0.84.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.2...0.84.3) (2024-07-30)

### [0.84.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.1...0.84.2) (2024-07-30)


### Bug Fixes

* **proto:** remove unused import ([2949dd2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2949dd2f8a95a7784308fbe5c1f351f30585b5aa))

### [0.84.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.84.0...0.84.1) (2024-07-30)


### Features

* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__bitsight__batch_scorecards_zip.v1` ([602d701](https://github.com/WhitehawkCEC/whitehawk-proto/commit/602d7018e455fbcd0440a77a016ed1fdf3b4bac4))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__bitsight__batch_scorecards.v1` ([5f6bf4f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5f6bf4f0d81a73f6b2c41cfeae70b79b0ef19acb))

## [0.84.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.10...0.84.0) (2024-07-30)


### ⚠ BREAKING CHANGES

* **proto:** remove service `client_portal.heatmap.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.mapped_ecosystem.companies.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.latest_sync.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.entity_id.cyber_risk.v2`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.entity_id.cyber_risk.v1`
* **proto:** remove service `client_portal.integrations__black_kite__entities.v2`
* **proto:** remove service `client_portal.integrations__black_kite__entities__archive.v2`

### Features

* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.entity_id.cyber_risk.v1` ([12ee00d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/12ee00d7c85b25b1cc4855c5471b330207ea007f))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.entity_id.cyber_risk.v2` ([793622c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/793622ca3516c5d6bc0e482195328599c3df5594))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.latest_sync.v1` ([903f7fb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/903f7fb9dca3186f53e4b975d178be672d0b2124))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.mapped_ecosystem.companies.v1` ([d0eebda](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d0eebda25bc08c1048f4bc796fbc84339b5b9451))
* **proto:** remove service `client_portal.heatmap.v1` ([780ef55](https://github.com/WhitehawkCEC/whitehawk-proto/commit/780ef55bee23fc788eefba49570953c476df42ff))
* **proto:** remove service `client_portal.integrations__black_kite__entities__archive.v2` ([747ef42](https://github.com/WhitehawkCEC/whitehawk-proto/commit/747ef42376d24cf21e9889a058addfe470dcca36))
* **proto:** remove service `client_portal.integrations__black_kite__entities.v2` ([d67d843](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d67d84373dfa4f8174bda9e6e16fbe8af64812ab))

### [0.83.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.9...0.83.10) (2024-07-26)


### Bug Fixes

* **proto:** lint ignore ([d74aa96](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d74aa96844b2a5ed2eea48c4b414462018d3120c))

### [0.83.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.8...0.83.9) (2024-07-26)


### Features

* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__bitsight__companies__0__cyber_risk.v1` ([3b16171](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3b16171ed4b7a47da7ff7ee45aa6e0fd9aba9f94))

### [0.83.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.7...0.83.8) (2024-07-25)

### [0.83.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.6...0.83.7) (2024-07-25)


### Features

* **proto:** definitions for cis to cmmc mapping ([4a98143](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4a981432088536f5ce031f37e033a46cd82fd695))

### [0.83.6](https://github.com/whitehawkcec/whitehawk-proto/compare/0.83.5...0.83.6) (2024-07-25)


### Features

* **proto:** add `frameworks` field to `accounts__0__subscriptions__0__integrations__black_kite__entities__0__compliance_xlsx.v1` ([9cfa116](https://github.com/whitehawkcec/whitehawk-proto/commit/9cfa116ec059e74e4304231446b53610af07bf7d))

### [0.83.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.4...0.83.5) (2024-07-24)


### Features

* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__bitsight__sync.v1` ([ab608d8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ab608d8eedc56fc941208c7a189ddabdf979b136))

### [0.83.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.3...0.83.4) (2024-07-24)


### Bug Fixes

* **proto:** remove stream ([e9ba87a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e9ba87abc9195ef1d0d3692ae426563a8e0359b1))

### [0.83.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.3...0.83.4) (2024-07-24)


### Bug Fixes

* **proto:** remove stream ([e9ba87a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e9ba87abc9195ef1d0d3692ae426563a8e0359b1))

### [0.83.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.2...0.83.3) (2024-07-24)


### Features

* **proto:** additional fields for bitsight company ([4d50f99](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4d50f99c3e7800f681c51ccccf0c9a8fc362b3c6))

### [0.83.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.83.1...0.83.2) (2024-07-23)


### Bug Fixes

* **proto:** company id should be uuid ([5cc289c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5cc289cf51bf802d1e5469a81635f9ae4141c23b))

### [0.83.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.83.0...0.83.1) (2024-07-23)


### Bug Fixes

* **proto:** use snake case ([9c97d34](https://github.com/whitehawkcec/whitehawk-proto/commit/9c97d34e16f23a3d402c9fffabd2e17df639271e))

## [0.83.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.82.3...0.83.0) (2024-07-23)


### ⚠ BREAKING CHANGES

* **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__findings.v1`

### Features

* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__compliance_xlsx.v1` ([6253c28](https://github.com/whitehawkcec/whitehawk-proto/commit/6253c281855a1d14e156e917c87ebf6149026905))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__cyber_risk.v1` ([c071a64](https://github.com/whitehawkcec/whitehawk-proto/commit/c071a6443d428e34846750eb021efeb1a7b832e0))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__findings_xlsx.v1` ([0fb6957](https://github.com/whitehawkcec/whitehawk-proto/commit/0fb69579df4e5b8455fb5d0d9e18d3dad23d1d4b))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__heat_map.v1` ([f3578af](https://github.com/whitehawkcec/whitehawk-proto/commit/f3578afa3e8c75e8e789d02ea79ae44db75c76de))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__latest_sync.v1` ([f5558e7](https://github.com/whitehawkcec/whitehawk-proto/commit/f5558e7b8002a64e466b1b3b948b3ad9fbaa0df0))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__mapped_ecosystem__entities.v1` ([73401f3](https://github.com/whitehawkcec/whitehawk-proto/commit/73401f3c4077dd365243f8ce418e1233729fb2b1))
* **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__sync.v1` ([b91e316](https://github.com/whitehawkcec/whitehawk-proto/commit/b91e316226961d55c04f7649b3a0bf5e2833106f))
* **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__findings.v1` ([7d1686c](https://github.com/whitehawkcec/whitehawk-proto/commit/7d1686c53b800f4251985faa58c40578009a28aa))


### Bug Fixes

* **proto:** add missing parameter ([99e7ac9](https://github.com/whitehawkcec/whitehawk-proto/commit/99e7ac9a88e15c955c79d5bb54953cdb278944c1))
* **proto:** correct type for read response ([5d4d80e](https://github.com/whitehawkcec/whitehawk-proto/commit/5d4d80eca2cd6c5a3604c96aa4c06f852e17f929))
* **proto:** rename response ([424b421](https://github.com/whitehawkcec/whitehawk-proto/commit/424b421363f77cd2a60c157bde416c254a828f78))

### [0.82.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.82.2...0.82.3) (2024-07-22)


### Bug Fixes

* **proto:** copy/paste error ([944beb0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/944beb0f4faf2355e3437a2f99f1d1e91794fa79))

### [0.82.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.82.1...0.82.2) (2024-07-22)


### Features

* **proto:** add fields for bitsight company ([4983274](https://github.com/WhitehawkCEC/whitehawk-proto/commit/49832746c39b1a6578e200e70e6a0ff625d6f1ec))
* **proto:** service to retrieve bitsight companies associated with an account and subscription ([d4717e1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d4717e10589890aeb81b2e5dcf26689150a13eee))

### [0.82.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.82.0...0.82.1) (2024-07-17)

## [0.82.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.81.2...0.82.0) (2024-07-16)


### ⚠ BREAKING CHANGES

* **proto:** remove message `proto.batch.scorecards.v3`
* **proto:** remove service `accounts__0__scorecard_templates.v1`
* **proto:** remove service `client_portal.bundle.template.v1`
* **proto:** remove service `client_portal.accounts__0__todos.v2`
* **proto:** remove service `client_portal.accounts__0__todos.v1`
* **proto:** remove service `client_portal.accounts__0__scorecard_frameworks.v2`
* **proto:** remove service `client_portal.accounts__0__scorecard_frameworks.v1`
* **proto:** remove service `client_portal.custom_questionnaire_answered.v1`
* **proto:** remove service `client_portal.custom_questionnaires.v1`
* **proto:** remove service `client_portal.custom_questionnaires.taken.v1`
* **proto:** remove service `client_portal.custom_questionnaire_taken.v1`
* **proto:** remove service `client_portal.files.v2`
* **proto:** remove service `client_portal.files.scorecard_templates.v1`
* **proto:** remove service `client_portal.frameworks_lookup.v1`
* **proto:** remove service `client_portal.frameworks.v1`
* **proto:** remove service `client_portal.frameworks.lookup.v1`
* **proto:** remove service `client_portal.custom_questionnaires.answered.v1`
* **proto:** remove service `client_portal.frameworks.v3`
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.zip.v3`
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.scorecards_v3.v2`
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.batch_id.pdf_status.v2`
* **proto:** remove service `client_portal.accounts.id.jobs.job_id.v1`
* **proto:** remove service `client_portal.accounts.id.jobs.v1`
* **proto:** remove service `client_portal.accounts.id.heatmap.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.config.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.cyber_one.config.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.config.v1`
* **proto:** remove service `client_portal.accounts.id.integrations.bitsight.config.v1`

### Features

* **proto:** remove message `proto.batch.scorecards.v3` ([3305b8d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3305b8dd6c18c7a1b23fa4cdb39ac2e31ed122e3))
* **proto:** remove service `accounts__0__scorecard_templates.v1` ([cc6a4ba](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cc6a4ba5f45527473b8e5dc5cea2e7c079c37bf6))
* **proto:** remove service `client_portal.accounts__0__scorecard_frameworks.v1` ([e4ac71d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e4ac71d35734e51e32f49f9a18acd88e7938899f))
* **proto:** remove service `client_portal.accounts__0__scorecard_frameworks.v2` ([0adb7d5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0adb7d578313e19e9e2dcc88649d4d7500871918))
* **proto:** remove service `client_portal.accounts__0__todos.v1` ([c13abd7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c13abd7c990dcdc931d61930dbbf2183a150ec8b))
* **proto:** remove service `client_portal.accounts__0__todos.v2` ([a2354c0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a2354c0e1d42e96789cda6f2eb00040114caec31))
* **proto:** remove service `client_portal.accounts.id.heatmap.v1` ([0a5d7d6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0a5d7d6567629157386d2f92004b78c2e12f6794))
* **proto:** remove service `client_portal.accounts.id.integrations.bitsight.config.v1` ([d1a16df](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d1a16dfdeb8e7e597c8babf23c613f779f77e248))
* **proto:** remove service `client_portal.accounts.id.integrations.black_kite.config.v1` ([127e4e3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/127e4e3ca4679d93bea9875a5a1667ed449d839f))
* **proto:** remove service `client_portal.accounts.id.integrations.cyber_one.config.v1` ([0472963](https://github.com/WhitehawkCEC/whitehawk-proto/commit/04729634bad1647f1ce21b9e98c0ae7af0266de4))
* **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.config.v1` ([5b19209](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5b192092ffd87a33e94c2cb4f2ba4b7d101095d2))
* **proto:** remove service `client_portal.accounts.id.jobs.job_id.v1` ([43cb3c7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/43cb3c7902a42a27fc4f4c5981b680d18f3c32b6))
* **proto:** remove service `client_portal.accounts.id.jobs.v1` ([2a4c323](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2a4c32366068d46306e2927c13c25cb3f2489d47))
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.batch_id.pdf_status.v2` ([3049262](https://github.com/WhitehawkCEC/whitehawk-proto/commit/304926201dc50d77d9e7566a501be1669d15ac56))
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.scorecards_v3.v2` ([005537b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/005537bcb76decb272cb6877ef4976527fdb606d))
* **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.batch.zip.v3` ([3c02709](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3c027099061f4568f701b7bb89f88a93c4510c03))
* **proto:** remove service `client_portal.bundle.template.v1` ([a09ddce](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a09ddce85ddafa555bf2884f15777ecf6f514aa5))
* **proto:** remove service `client_portal.custom_questionnaire_answered.v1` ([9df35f4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9df35f4095360bcc59fc6cd4f13c5b8984d40fd6))
* **proto:** remove service `client_portal.custom_questionnaire_taken.v1` ([fc3ec88](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fc3ec8842515b1da235288a601d00ad33a34dd42))
* **proto:** remove service `client_portal.custom_questionnaires.answered.v1` ([cb4fac5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cb4fac5ca74d9c2ceb0408013c29c97560d12b00))
* **proto:** remove service `client_portal.custom_questionnaires.taken.v1` ([e9cb637](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e9cb63779b1c379ad60be9a7cd35e37e8c4b9e3f))
* **proto:** remove service `client_portal.custom_questionnaires.v1` ([830f83a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/830f83abbaec92798ab39ff66b898a626cf8cdb2))
* **proto:** remove service `client_portal.files.scorecard_templates.v1` ([295699b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/295699b81d496b2714558df4900854c0fa535ed8))
* **proto:** remove service `client_portal.files.v2` ([458c9c6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/458c9c65908175dc4c945a7628419b7a075717e5))
* **proto:** remove service `client_portal.frameworks_lookup.v1` ([e1684d0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e1684d04061da3879a9997ef592480294c3c77be))
* **proto:** remove service `client_portal.frameworks.lookup.v1` ([9b2e2d3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9b2e2d3ead06778ae285d721c873f2b0389b5b85))
* **proto:** remove service `client_portal.frameworks.v1` ([e8541ea](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e8541ea7fa8e764af62160bd93be644c08494476))
* **proto:** remove service `client_portal.frameworks.v3` ([e13f67d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e13f67d8a4b454a3dec5d54ad8e6d7e8acfbb4b0))
* service for archived entities associated with an account and subscription ([f8a1941](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f8a194171bfaf993725b2ca873a6af7f15b95f9b))
* service for entities associated with an account and subscription ([20cae2d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/20cae2d7993c089057260f5d1e7dbb0d6aadf192))

### [0.81.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.81.1...0.81.2) (2024-02-14)

### Bug Fixes

- remove unused imports ([ac273a6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ac273a63e0d5749ed2f4cb6eee1fd184e79ece84))

### [0.81.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.81.0...0.81.1) (2024-02-14)

### Features

- remove deprecated method ([95dd533](https://github.com/WhitehawkCEC/whitehawk-proto/commit/95dd533369d57c484ca0453d24fae35b130d6197))
- remove deprecated method, change delete request ([a0a7f2e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a0a7f2e35924bc71a12464484c1fdafd6ec6dd4b))
- remove deprecated method, change delete request ([97f71d2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/97f71d219135e005d1e5fd71a955c57389e6e475))

### Bug Fixes

- change delete request ([fe51886](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fe5188680f2d50140d7dd77c6fa537910433aa61))

## [0.81.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.80.3...0.81.0) (2024-02-13)

### ⚠ BREAKING CHANGES

- move to different package

### Bug Fixes

- move to different package ([88694bc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/88694bc16520523d4dc9744eb324056c912675a0))

### [0.80.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.80.2...0.80.3) (2024-02-12)

### Bug Fixes

- remove unused import ([a754685](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a754685c77da5a19fa1c6d5fb53f78e08881eb9c))

### [0.80.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.80.1...0.80.2) (2024-02-12)

### Bug Fixes

- buf:lint:ignore PACKAGE_LOWER_SNAKE_CASE ([3add929](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3add929c29964d2e89396b158756fdb5b005bce2))

### [0.80.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.80.0...0.80.1) (2024-02-12)

### Features

- service to get bundle sets associated with a category ([1da2db7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1da2db707a6cf8fcb9a078abf8b2468f82b909d4))
- service to get bundle sets that are allocated to a questionnaire preference ([9c0fb3f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c0fb3f344fd979cf4739c5e1ce3b9ceb416e085))
- service to get products associated with a category ([b3045a7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b3045a797381a616963e19f146281c4b4e3cebd8))
- service to get products associated with a feature ([de31b91](https://github.com/WhitehawkCEC/whitehawk-proto/commit/de31b91f8a557ee121d8f4f5c4441fee271c5354))

## [0.80.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.79.0...0.80.0) (2024-01-30)

### ⚠ BREAKING CHANGES

- remove unused return values

### eat

- remove unused return values ([9f4a4a7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9f4a4a7202f36c293eee3aa4f673a24ce0cbd666))

## [0.79.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.78.1...0.79.0) (2024-01-23)

### ⚠ BREAKING CHANGES

- remove unnecessary/unused service
- remove unnecessary/unused service

### Features

- remove unnecessary/unused service ([5116fd6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5116fd6e969f5926450acdd486a4dce8cd970f64))
- remove unnecessary/unused service ([1b63d89](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1b63d89d3f46ce48803af224d920f82f49f17bdd))

### [0.78.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.78.0...0.78.1) (2024-01-22)

### Features

- add `data_features/v1` resource ([f582cbf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f582cbfe16a6ec58b4bc8271bfc5599f7e23bb91))
- add `sync_features/v1` resource ([585fdf1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/585fdf13ebbddc0ef719f2b8fa06b3cb5ba29c02))

## [0.78.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.77.0...0.78.0) (2024-01-22)

### ⚠ BREAKING CHANGES

- prefer to pass `FrameworkId` only

### Features

- prefer to pass `FrameworkId` only ([01e7b4f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/01e7b4f5a7e917424c0eee8eb09ab11d5bc14f96))

## [0.77.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.76.0...0.77.0) (2024-01-19)

### ⚠ BREAKING CHANGES

- prefer to use `TemplateId`

### Features

- add `mapped_entity_id` to `BlackKiteConfig` message ([d9e00bf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d9e00bfea63e217a75785407ef7146f950e76c4f))
- prefer to use `TemplateId` ([2b36d22](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2b36d22d770016b060ad4e1d9e7ce21da9d44661))

## [0.76.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.75.0...0.76.0) (2024-01-12)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal.accounts.id.frameworks.v2`
- **proto:** remove service `client_portal.accounts.id.frameworks.v1`
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v2`
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v1`

### Features

- add `accounts__0__subscriptions__0__data_feature_config.v1` service ([ecdd418](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ecdd418ff776089ad2fcc9b44e7cb73184010cda))
- add `accounts__0__subscriptions__0__integrations__bitsight__config.v1` service ([afacfa9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/afacfa98879d84eb9dd63aaf40503a4a4567281f))
- add `accounts__0__subscriptions__0__integrations__black_kite__config.v1` service ([2855be8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2855be8ec96f4ac75d86e7295a17a9ff23c843a7))
- add `accounts__0__subscriptions__0__integrations__cyber_one__config.v1` service ([1ada4da](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1ada4dad2e5b7c96c8dd366796074f1b1f6dae13))
- add `accounts__0__subscriptions__0__integrations__supply_wisdom__config.v1` service ([3b1c34b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3b1c34b3cbe448e2e3a9067a3d1375672e7b291e))
- add `accounts__0__subscriptions__0__report_config.v1` service ([34289e7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/34289e7ab7c9aee228c4d6f2b7a476dfc984bb99))
- add `accounts__0__subscriptions__0__sync_config.v1` service ([a850b7f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a850b7f6f1dd8ebc34f54c490966d768cf2b04e2))
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v1` ([5e60315](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5e603156c10b0d355bc31f957c9293ecde233e22))
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v2` ([1426d02](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1426d0212c1048583f3cdda1bf3ccc9ca2fa2325))
- **proto:** remove service `client_portal.accounts.id.frameworks.v1` ([8e95bc4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8e95bc42a911309456ddb1c5be3c23b355b74c72))
- **proto:** remove service `client_portal.accounts.id.frameworks.v2` ([9ea452f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9ea452f26536d38529689ce5bba00bd9fe2bc1e9))

## [0.75.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.74.0...0.75.0) (2024-01-10)

### ⚠ BREAKING CHANGES

- deprecate unused fields
- deprecate unused fields
- deprecate unused fields
- **proto:** remove messages `whitehawk.proto.snapshot_scorecard.v1`
- **proto:** remove unused messages from `whitehawk.proto.scorecard_v3.snapshot.v1`
- **proto:** remove service `client_portal.accounts__0__snapshot_scorecards.v1`
- **proto:** remove service `client_portal.accounts.id.snapshot_scorecards.v1`

### Features

- deprecate unused fields ([fa99737](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fa9973735feef534d053c6ffa95b502e4b956eee))
- deprecate unused fields ([5626838](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5626838bff0892bb130e2b72a6adb9775cb8831e))
- deprecate unused fields ([6249bb3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6249bb32dec2a9b11d85fc94421cf8312e2f7f2d))
- **proto:** remove messages `whitehawk.proto.snapshot_scorecard.v1` ([cb9e052](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cb9e05287079a9901f57514d87c72f41956a0a2d))
- **proto:** remove service `client_portal.accounts__0__snapshot_scorecards.v1` ([49f0454](https://github.com/WhitehawkCEC/whitehawk-proto/commit/49f0454aa40961686d0e5b2e92c26a000d378bb1))
- **proto:** remove service `client_portal.accounts.id.snapshot_scorecards.v1` ([221b46e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/221b46e7ce19fd53dce745f4d50934f9433476a1))
- **proto:** remove unused messages from `whitehawk.proto.scorecard_v3.snapshot.v1` ([b66b201](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b66b2014599302b228dd363414f1b65ad8ad4eb7))

## [0.74.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.11...0.74.0) (2024-01-09)

### ⚠ BREAKING CHANGES

- add new fields, deprecate unused
- **proto:** remove service `client_portal.integrations__black_kite__entities.v1`
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities.v1`
- **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.v1`
- **proto:** remove message(s) for `custom_questionnaire.display_schema.v1`
- **proto:** remove message(s) for `custom_questionnaire.display_uischema.v1
- **proto:** remove service `client_portal.custom_questionnaire.v1`
- **proto:** remove service `client_portal.custom_questionnaires.display_ui_schemas.v1`
- **proto:** remove service `client_portal.custom_questionnaires.display_schemas.v1`
- **proto:** remove `client_portal.custom_questionnaire.display_schema.v2` service
- **proto:** remove `client_portal.custom_questionnaire.display_uischema.v2` service

### Features

- add new fields, deprecate unused ([42f6c53](https://github.com/WhitehawkCEC/whitehawk-proto/commit/42f6c538dd1834925874953262acb616cff6721b))
- **proto:** remove `client_portal.custom_questionnaire.display_schema.v2` service ([a8fd676](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a8fd67601b9746e2637c96505613f969f72ca4dd))
- **proto:** remove `client_portal.custom_questionnaire.display_uischema.v2` service ([81e7d9e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/81e7d9e81aca25cca02263da9b98119925db0121))
- **proto:** remove message(s) for `custom_questionnaire.display_schema.v1` ([75539da](https://github.com/WhitehawkCEC/whitehawk-proto/commit/75539da1dd8863a4ed7c1cebed77cc953a440c51))
- **proto:** remove message(s) for `custom_questionnaire.display_uischema.v1 ([570895e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/570895e958a22f5b06d284c12e143358105dce42))
- **proto:** remove service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities.v1` ([8f257fe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8f257fe46f62a7e75493db3497878200cf1d1fb4))
- **proto:** remove service `client_portal.accounts.id.integrations.black_kite.entities.v1` ([2bd1348](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2bd134850e2c1cbb5da3dba52f410476e5d07d99))
- **proto:** remove service `client_portal.custom_questionnaire.v1` ([7429249](https://github.com/WhitehawkCEC/whitehawk-proto/commit/74292493c2e7a20359e4482bafbd35fbfb4e8af3))
- **proto:** remove service `client_portal.custom_questionnaires.display_schemas.v1` ([22a3ab8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/22a3ab89ce50656f5b6dd3afd1b0204f0f1e9e41))
- **proto:** remove service `client_portal.custom_questionnaires.display_ui_schemas.v1` ([cb2ef48](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cb2ef48a018a537cd21f133d316db80fe22ee857))
- **proto:** remove service `client_portal.integrations__black_kite__entities.v1` ([16eeb84](https://github.com/WhitehawkCEC/whitehawk-proto/commit/16eeb8430d520fd4b55d01a554eb245cb8b6b1e4))

### [0.73.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.10...0.73.11) (2023-12-14)

### [0.73.10](https://github.com/whitehawkcec/whitehawk-proto/compare/0.73.9...0.73.10) (2023-12-07)

### Features

- **proto:** add `client_portal.portfolio_reports__0__pdf.v1` ([9c7a45c](https://github.com/whitehawkcec/whitehawk-proto/commit/9c7a45c2499caf054bcfd029d6a0ac611c392542))

### [0.73.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.8...0.73.9) (2023-12-07)

### [0.73.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.7...0.73.8) (2023-12-07)

### Features

- prefer as `repeated` values ([017db0e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/017db0e7fc6f9cd0042360ec1d85410f87bca017))

### [0.73.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.6...0.73.7) (2023-12-06)

### Features

- update `PerformanceAnalysis` message ([81effd7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/81effd7d291dfa9f40e7831adc5086a134ddb3b8))

### [0.73.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.5...0.73.6) (2023-12-06)

### [0.73.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.4...0.73.5) (2023-12-05)

### [0.73.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.3...0.73.4) (2023-12-05)

### [0.73.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.2...0.73.3) (2023-12-05)

### [0.73.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.1...0.73.2) (2023-12-05)

### [0.73.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.73.0...0.73.1) (2023-12-05)

## [0.73.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.98...0.73.0) (2023-11-30)

### ⚠ BREAKING CHANGES

- remove `FileType` from `ReadRequest` & `DeleteRequest`

### Features

- remove `FileType` from `ReadRequest` & `DeleteRequest` ([f061e5c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f061e5ceaaf2e7d7a8055cc33236e5506c7b53fc))

### [0.72.98](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.97...0.72.98) (2023-11-30)

### [0.72.97](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.96...0.72.97) (2023-11-30)

### Bug Fixes

- frameworkIdv4 replace cobit5 to 19 ([2484834](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2484834fab8b215658275a0f8ef3e896dee3a2f4))

### [0.72.96](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.95...0.72.96) (2023-11-22)

### [0.72.95](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.94...0.72.95) (2023-11-22)

### [0.72.94](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.93...0.72.94) (2023-11-20)

### Features

- add `accounts__0__portfolio_report_template` service ([18f4a91](https://github.com/WhitehawkCEC/whitehawk-proto/commit/18f4a91f9a9f9d41d083488be253c28cf34220a1))
- add `WHK_PORTFOLIO_REPORT` as `FileType` ([aee4907](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aee490703f50e41696f92c0085c1212e1d07e9e0))

### [0.72.93](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.92...0.72.93) (2023-11-20)

### [0.72.92](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.91...0.72.92) (2023-11-20)

### [0.72.91](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.90...0.72.91) (2023-11-20)

### [0.72.90](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.89...0.72.90) (2023-11-16)

### [0.72.89](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.88...0.72.89) (2023-11-15)

### [0.72.88](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.87...0.72.88) (2023-11-14)

### [0.72.87](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.86...0.72.87) (2023-11-14)

### [0.72.86](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.85...0.72.86) (2023-11-14)

### [0.72.85](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.84...0.72.85) (2023-11-14)

### [0.72.84](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.83...0.72.84) (2023-11-14)

### [0.72.83](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.82...0.72.83) (2023-11-07)

### [0.72.82](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.81...0.72.82) (2023-11-07)

### [0.72.81](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.80...0.72.81) (2023-11-07)

### [0.72.80](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.79...0.72.80) (2023-11-07)

### [0.72.79](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.78...0.72.79) (2023-10-30)

### [0.72.78](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.77...0.72.78) (2023-10-30)

### [0.72.77](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.76...0.72.77) (2023-10-30)

### [0.72.76](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.75...0.72.76) (2023-10-25)

### Bug Fixes

- **proto:** package version ([be662f8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be662f87e290169a80a230eb3bf003a5ea135031))

### [0.72.75](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.74...0.72.75) (2023-10-25)

### Bug Fixes

- **proto:** add client id to black kite entity ([39049d5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/39049d5ea6d0297cadf06439b352bc22f27de750))

### [0.72.74](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.73...0.72.74) (2023-10-25)

### Bug Fixes

- **proto:** add account id to request params ([372268e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/372268ee13d7a4a92c3b6193a95836903ed89942))

### [0.72.73](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.72...0.72.73) (2023-10-25)

### Bug Fixes

- **proto:** move package ([746912c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/746912c34ff4387cce9f861df4ec71162bae903b))

### [0.72.72](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.71...0.72.72) (2023-10-25)

### Bug Fixes

- **proto:** package name ([151c9f5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/151c9f5d7ebfb3f4619003bf60cc10bd9f393959))

### [0.72.71](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.70...0.72.71) (2023-10-25)

### [0.72.70](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.69...0.72.70) (2023-10-25)

### Features

- **proto:** add CyberRating go BlackKite entity ([5b77cbb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5b77cbbc11143662ce2addbc9093009825748690))
- **proto:** black kite entity v2 service ([040866f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/040866f1c30d70af50c30dbf663b24e7bb95cccd))
- **proto:** entity archive service ([de015be](https://github.com/WhitehawkCEC/whitehawk-proto/commit/de015bee513143b51284884cdc04b142c8ab7cdf))

### [0.72.69](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.68...0.72.69) (2023-10-04)

### Bug Fixes

- **proto:** remove unused service ([1c340ca](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1c340ca9c571698875725313391da16c9eff8faa))

### [0.72.68](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.67...0.72.68) (2023-10-04)

### Bug Fixes

- **proto:** replace entity status with archive time ([92ea3f7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/92ea3f79b88e74283bc2e3d6ecc7d69e59d0cd8a))

### [0.72.67](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.66...0.72.67) (2023-10-04)

### Features

- **proto:** add update service ([766e9ef](https://github.com/WhitehawkCEC/whitehawk-proto/commit/766e9efc14b106272a36578b93d1e2f933dc235d))

### [0.72.66](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.65...0.72.66) (2023-10-03)

### Features

- add `portfolio_report_summaries/v1` `LIST` service ([bedaf13](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bedaf13e11eb50a5d8f5f6480ffd9780347c87d3))
- add `portfolio_reports/v1` `CREATE` service ([aea9648](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aea9648adae8f6c4e0956aa42da4fc13ecbfbd76))
- add `portfolio_reports/v1` `READ`/`UPDATE` services ([e44afef](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e44afef8dba706557c2f8cb0734d23c5a10cd2f1))

### [0.72.65](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.64...0.72.65) (2023-10-03)

### Features

- add `portfolio_report/performance_analysis/v1` message ([72516b0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/72516b0bb0b54f1f7c3bca6492d9a0d24545f1cb))
- add `portfolio_report/v1` message ([906ec24](https://github.com/WhitehawkCEC/whitehawk-proto/commit/906ec24f34c8fb4d0369d72cae82b4035b44fec9))

### [0.72.64](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.63...0.72.64) (2023-09-28)

### Bug Fixes

- **proto:** move services to v2 ([7601e76](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7601e76e85e1ac7b11051e81a11d759b8774428e))

### [0.72.63](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.62...0.72.63) (2023-09-28)

### Features

- **proto:** service to retrieve entities filtered by status ([f2bc6f1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f2bc6f1f226b8c4d60a7e99e2fef3a1d8c1d923b))

### [0.72.62](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.61...0.72.62) (2023-09-27)

### Bug Fixes

- **proto:** missed the service declaration ([05dd2a3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/05dd2a31da7560594d03bc39f5407a985b1ee861))

### [0.72.61](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.60...0.72.61) (2023-09-27)

### Bug Fixes

- **proto:** no respose type from update service ([5102773](https://github.com/WhitehawkCEC/whitehawk-proto/commit/510277342b677ec7225bfd5883f3822b855f75f1))

### [0.72.60](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.59...0.72.60) (2023-09-27)

### Features

- **proto:** add status to entities ([168bef0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/168bef01c99e2c6da96e93ce50061753861ea171))

### [0.72.59](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.58...0.72.59) (2023-09-27)

### Bug Fixes

- remove unused service ([f29c84f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f29c84f4588fe929d0163630ed82d1499a162a31))

### [0.72.58](https://github.com/whitehawkcec/whitehawk-proto/compare/0.72.57...0.72.58) (2023-09-16)

### [0.72.57](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.56...0.72.57) (2023-09-12)

### Bug Fixes

- package name ([420d413](https://github.com/WhitehawkCEC/whitehawk-proto/commit/420d413d194cfe350a9af78f032843f489000a50))

### [0.72.56](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.55...0.72.56) (2023-09-12)

### Features

- use latest version of frameworks for snapshots ([d1962a5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d1962a5ab369f8839ce59146a5208d50b32b6a5b))

### [0.72.55](https://github.com/whitehawkcec/whitehawk-proto/compare/0.72.54...0.72.55) (2023-09-07)

### Features

- **proto:** add `BlackKiteConfig.web_app_credentials` ([d06628b](https://github.com/whitehawkcec/whitehawk-proto/commit/d06628beb48e48b4654c8baf01cc7be038c5d50a))

### [0.72.54](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.53...0.72.54) (2023-08-22)

### Features

- ls ([0d140fe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0d140fed5d11c472352a97fe888dca08c89845bb))

### [0.72.53](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.52...0.72.53) (2023-08-04)

### Features

- add `frameworks_lookup/v1` ([2bc83f6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2bc83f694ae26923eb53808bdb61f74ed118bae3))

### [0.72.52](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.51...0.72.52) (2023-08-04)

### Features

- fw lookup ([03b1b8c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/03b1b8c111fb3fc8e050e7244972e44e5f8dc55c))

### [0.72.51](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.50...0.72.51) (2023-08-03)

### Features

- cyber risk v2 ([d4129c1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d4129c1d06951f757c9a64d5732c30b06701d8e2))

### [0.72.50](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.49...0.72.50) (2023-08-02)

### [0.72.49](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.48...0.72.49) (2023-07-31)

### Bug Fixes

- return array of values ([bbb85f4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bbb85f49923705f5806f2698425f47905b044458))

### [0.72.48](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.47...0.72.48) (2023-07-31)

### Features

- add `accounts__0__snapshot_scorecards/v1` resource ([2fda9a6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2fda9a6f2b0935a88ed39e67587123e8725a742c))
- add `snapshot_scorecard/v1` ([b1ddd0c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b1ddd0ce831cf6e813defaae046a5a3741bf33c1))

### [0.72.47](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.46...0.72.47) (2023-07-31)

### [0.72.46](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.45...0.72.46) (2023-07-31)

### Bug Fixes

- use v5 framework info ([778741b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/778741bc627b56146d1a47b99949c52c594911b5))

### [0.72.45](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.44...0.72.45) (2023-07-31)

### Bug Fixes

- set use framework info to not drop the name and description ([130e1ed](https://github.com/WhitehawkCEC/whitehawk-proto/commit/130e1ed558ec908b7d9f46388d0ece620a500c0f))

### [0.72.44](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.43...0.72.44) (2023-07-31)

### Bug Fixes

- prefer frameworkinfo ([81f64c2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/81f64c2511cd311ff69d9147878edb5c80f4a815))

### [0.72.43](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.42...0.72.43) (2023-07-28)

### Features

- add `accounts__0__subscriptions__0__batch_scorecards_v3__zip.v1` ([83669e8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/83669e893c7c0f03d8c4ad28ed3cebc02355d386))
- add `accounts__0__subscriptions__0__batch_scorecards_v3.v1` ([be45586](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be45586f97aeaebe25794e8da1f8a1a95e84fd7a))
- add `accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard/v3` service ([58910e1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/58910e1cbdf66db89669f88dacd7e11b3a11211a))

### Bug Fixes

- prefer chronological numbering ([21a00d9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/21a00d9dd865ce2e5d0976501a38152a9a96f175))

### [0.72.42](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.41...0.72.42) (2023-07-27)

### Bug Fixes

- prefer `FrameworkInfo` ([c571d9c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c571d9ccf4d3d56470ec4667a408d659c2c97dc6))

### [0.72.41](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.40...0.72.41) (2023-07-27)

### Features

- add `accounts__0__frameworks__0__findings__0__result_override.v3` ([f93e135](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f93e135fe1c99f2d33555512a6d5b18c5dc916f7))
- add `accounts__0__todos.v3` ([9aba25e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9aba25ed59d3fba5fefcc9106c1b09e390520bf6))
- add `CreateInputInDepthBlackKiteWithFrameworksV2` type ([222ca1b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/222ca1b16e7d1138f3a2a18b1a2d2508aa9982d2))
- add `CreateInputInDepthBlackKiteWithFrameworksV2` type ([a6cbfd1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a6cbfd10685dce9f516caa13294a523a04d59c20))
- add `indepthblackkitewithframeworks.v2` message ([6a64caf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6a64caf7991570adbc51b54ed7ce6e77d766b7f0))
- add `todo` v3 ([e8ea5e8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e8ea5e827c59efcc5ae8e3d8fcef65394a51dcd6))
- prefer set request as `FrameworkId` ([0269c1d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0269c1d0bc1aaf3d66c46e73cd58105a4362341d))

### [0.72.40](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.39...0.72.40) (2023-07-27)

### [0.72.39](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.38...0.72.39) (2023-07-27)

### Bug Fixes

- accounts_0_scorecard_frameworks_v2 use framework obj instead of frameworkinfo ([566cfca](https://github.com/WhitehawkCEC/whitehawk-proto/commit/566cfcadba45c36fe27df2789b59979c83c009f7))

### [0.72.38](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.37...0.72.38) (2023-07-27)

### [0.72.37](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.36...0.72.37) (2023-07-27)

### Features

- add frameowrk obj in v5 ([ba44de7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ba44de7fb15b43565d47ed8d57a26666ba30b82d))

### [0.72.36](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.35...0.72.36) (2023-07-26)

### Bug Fixes

- frameworks v5 with refactored enum set ([004194b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/004194b5298adb188f69ad68047277826a571a1c))

### [0.72.35](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.34...0.72.35) (2023-07-25)

### Features

- add `accounts__0__frameworks_config.v1` resource ([3279a47](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3279a4760c50b8013ed21486c247adcc0f21314b))

### [0.72.34](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.33...0.72.34) (2023-07-25)

### Features

- accounts frameworks use v5 ([fb4aedf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fb4aedf94b9e1296eb90682b31d5df44d999074b))

### [0.72.33](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.32...0.72.33) (2023-07-25)

### Features

- accounts frameworks v2 ([0f245de](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0f245de4c69f9fc367dbee51c7c1b27482b9184c))

### [0.72.32](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.31...0.72.32) (2023-07-25)

### Features

- add `ISO27002` ([234611a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/234611a54dbf4c57c374643753e154f4611eeaac))

### [0.72.31](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.30...0.72.31) (2023-07-25)

### Features

- add `PCI_DSS_V4` ([a1b4ab2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a1b4ab2621bdf83ed4e9bd856acade31293e63f0))

### [0.72.30](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.29...0.72.30) (2023-07-25)

### Features

- add `CIS_V8` ([8b80e81](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8b80e814efa09ad8a4b020bb44bf622f1b0f1262))

### [0.72.29](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.28...0.72.29) (2023-07-24)

### [0.72.28](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.27...0.72.28) (2023-07-24)

### Features

- frameworks v2 use v5 version using framework id instead of ulid ([c92bba2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c92bba2420ce5d64a1744459ca772b1b87a688af))

### [0.72.27](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.26...0.72.27) (2023-07-21)

### [0.72.26](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.25...0.72.26) (2023-07-20)

### Features

- add `integrations__black_kite__entities` resource ([399d62a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/399d62ac99f514a7e915bb4ba23b271be6ae1b1d))

### [0.72.25](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.24...0.72.25) (2023-07-20)

### [0.72.24](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.23...0.72.24) (2023-07-19)

### Bug Fixes

- sync returns number of new suppliers synced ([91d75e2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/91d75e246a8e759a63d0449f19cd2ecb35015390))

### [0.72.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.22...0.72.23) (2023-07-19)

### Features

- entities portfolio sync ([fca06cd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fca06cd7c420a8e31b06abac759c2f92237fe71e))

### [0.72.22](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.21...0.72.22) (2023-07-14)

### Bug Fixes

- prefer return a `stream` ([7f26114](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7f26114088daa6b3c1568351fbdaa68a0fb065e6))

### [0.72.21](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.20...0.72.21) (2023-07-13)

### Features

- individual entity sync include domain as well ([fb92a73](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fb92a7393e6cb65953b9595595a9f82517a8b1b3))

### [0.72.20](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.19...0.72.20) (2023-07-13)

### Features

- proto def for individual sync ([b2f2bbe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b2f2bbef62e245663587ad8a01fd1c5e4504efcb))

### [0.72.19](https://github.com/whitehawkcec/whitehawk-proto/compare/0.72.18...0.72.19) (2023-07-11)

### [0.72.18](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.17...0.72.18) (2023-07-11)

### [0.72.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.16...0.72.17) (2023-06-28)

### [0.72.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.15...0.72.16) (2023-06-27)

### [0.72.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.14...0.72.15) (2023-06-22)

### Features

- add `license_type` to `LicenseStatus` ([6087389](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6087389bbfd5e1988a8efb6bd70875728f3c3fbf))

### [0.72.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.13...0.72.14) (2023-06-22)

### Features

- add `accounts__0__subscriptions__0__integrations__black_kite__entities/v1` service ([27048b7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/27048b79ffcd935dc2a5b549a50b57a214442645))
- add `accounts__0__subscriptions__0__pending_scorecards` service ([e8f0282](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e8f028247ce494e56509781c72668af02c1c68b1))
- add `LicenseStatus` to `BlackKiteEntity` message ([425ba21](https://github.com/WhitehawkCEC/whitehawk-proto/commit/425ba215e0a5222231316fb70e7bdfbcd68bf350))

### [0.72.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.12...0.72.13) (2023-06-15)

### Bug Fixes

- prefer singular tense ([98079fe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/98079fe64c43c994700d643b6d04ed4fead3a18d))

### [0.72.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.11...0.72.12) (2023-06-15)

### Bug Fixes

- remove `repeated` ([1f13af5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1f13af54d0ee77ab63f99bbd5f04ba29bc43f92e))

### [0.72.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.10...0.72.11) (2023-06-15)

### Bug Fixes

- remove repeated for template set ([70e8c5f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/70e8c5f4512a5f4bd7671c8fe63ea9976b41894a))

### [0.72.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.9...0.72.10) (2023-06-15)

### Bug Fixes

- set template send account id as well ([a7d80e5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a7d80e5940b729c023f8ad57dd8b934c4b1f009b))

### [0.72.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.8...0.72.9) (2023-06-15)

### Bug Fixes

- prefer `CRUDL` order ([e6b0622](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e6b06225cdb1825ab8caf7f2ef1bc412d8f0d43c))

### [0.72.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.7...0.72.8) (2023-06-15)

### Bug Fixes

- prefer `CRUDL` order ([4a97595](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4a97595684580671223eaeac059a18b5fb03cbdc))

### [0.72.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.6...0.72.7) (2023-06-15)

### Features

- add service for `accounts__0__scorecard_templates` ([0c62bc0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0c62bc08e9262749dd24103b21113bbb63197383))

### [0.72.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.5...0.72.6) (2023-06-05)

### Bug Fixes

- move int to double for peraton scores ([51c9413](https://github.com/WhitehawkCEC/whitehawk-proto/commit/51c9413717b0f3c56cfc3f938ce55f6ea6078e2f))

### [0.72.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.4...0.72.5) (2023-05-24)

### Features

- reports v2 add readrequest ([e449fc8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e449fc85f2fdb34a5440daaa9b8482863fc84943))

### [0.72.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.3...0.72.4) (2023-05-24)

### Features

- report subscription use v2 subscription ([2a92e1a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2a92e1ac8092411d54e5679404486423c8434706))

### [0.72.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.2...0.72.3) (2023-05-24)

### Features

- description on createrequest v2 ([1b5dccc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1b5dccc24d0270b6cc86e6e64273a0a8d15803e3))

### [0.72.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.1...0.72.2) (2023-05-24)

### Features

- subscription v2 service ([15e128f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/15e128f72e83f8203e2c17458ab735e95dbae6c7))

### [0.72.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.72.0...0.72.1) (2023-05-24)

### Features

- subscription with description v2 ([fd9297a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fd9297a96e79f186329db0372cf5795fcfc14bb5))

## [0.72.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.8...0.72.0) (2023-05-23)

### ⚠ BREAKING CHANGES

- prefer to use summary for list response
- **proto:** remove `licensing.id.packs.pack_id.quantity_changes.v1`
- **proto:** remove `licensing.id.packs.v1`
- **proto:** remove `accounts__0__subscriptions__0__groups__0__licensing_id.v1`
- **proto:** remove `accounts__0__subscriptions__0__licensing_id.v1`

### Features

- prefer to use summary for list response ([edc1ed6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/edc1ed645ab01107c20ef813970480dcab82feea))
- **proto:** remove `accounts__0__subscriptions__0__groups__0__licensing_id.v1` ([62c9a80](https://github.com/WhitehawkCEC/whitehawk-proto/commit/62c9a80c27c5b7ba82f00501adb1b86e597d78f0))
- **proto:** remove `accounts__0__subscriptions__0__licensing_id.v1` ([f1298d1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f1298d16903a7c73dbab1c226b6518e63c777882))
- **proto:** remove `licensing.id.packs.pack_id.quantity_changes.v1` ([de77c97](https://github.com/WhitehawkCEC/whitehawk-proto/commit/de77c972c6235f3e227fda4ddc27461eecb4b8f9))
- **proto:** remove `licensing.id.packs.v1` ([7541468](https://github.com/WhitehawkCEC/whitehawk-proto/commit/754146867830cc3724bd67b0b78a75645cdaa7cf))

### [0.71.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.7...0.71.8) (2023-05-23)

### Features

- add `PeratonCompany` message ([2cf6d36](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2cf6d362a617ce60fdc5d26d78bcd6dec7915fa8))
- add `RiskAnalyticsPeratonConfig` as subscription product type ([0552aa2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0552aa2a30eee9322272b4d53b08f89955338f73))
- add service for peraton risk analytics ([7ebd028](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7ebd028e74ef2cf6f981a8b2c5df07aa43f156e2))
- add service to list subscription products mapped to subscription types ([21368bf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/21368bf3f4f59f9be396ad9c122df7baaf0921ef))

### [0.71.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.6...0.71.7) (2023-05-23)

### [0.71.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.5...0.71.6) (2023-05-23)

### [0.71.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.4...0.71.5) (2023-05-18)

### Features

- **proto:** service to retrieve findings for spreadsheet ([f035203](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f035203af4b72e7e9fc513aa8ddd421bc9140218))

### Bug Fixes

- **proto:** removed unused (never used) ([d57ad1f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d57ad1f41ac7b0f175095d7f886847db538ea24c))
- **proto:** return File instead of bytes ([137204f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/137204f2c187528f1a35c3142dd884ade8f3d6ba))

### [0.71.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.71.3...0.71.4) (2023-05-17)

### Features

- **proto:** add `AccountSubscriptionGroupId` ([d132c2e](https://github.com/whitehawkcec/whitehawk-proto/commit/d132c2e3692b9295739ea0df2a45cd13613f21d6))
- **proto:** add `client_portal.accounts__0__subscriptions__0__groups__0__license_packs.v1` ([5fcfe0f](https://github.com/whitehawkcec/whitehawk-proto/commit/5fcfe0f2db426717175de48157e7af7fd647980c))
- **proto:** add `client_portal.accounts__0__subscriptions__0__license_packs.v1` ([ab35d0d](https://github.com/whitehawkcec/whitehawk-proto/commit/ab35d0d5dde9ad2668228426a4be37b723ffda1d))
- **proto:** add `LicensePackOrder` ([63db645](https://github.com/whitehawkcec/whitehawk-proto/commit/63db645cb9c26ab8769f990201481d434f2cf21f))

### [0.71.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.2...0.71.3) (2023-05-17)

### Features

- use subscription status instead of account status ([9f2b1c5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9f2b1c5743282acd87513d4d01dbf16a50ab6b44))

### [0.71.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.1...0.71.2) (2023-05-12)

### Features

- grpc subscription report v2 ([a54245e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a54245e8252eff8399384a85f890fd627f4a974c))

### [0.71.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.71.0...0.71.1) (2023-05-11)

### Features

- add list call to service ([a1ba311](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a1ba311be8c5ee8d6fe287b59a60406dc64337f8))

## [0.71.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.52...0.71.0) (2023-05-11)

### ⚠ BREAKING CHANGES

- **proto:** remove `scorecard_portfolio.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.groups.group_id.license_batches.batch_id.quantity_changes.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.license_batches.batch_id.quantity_changes.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.groups.group_id.license_batches.batch_id.quantity_changes.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.groups.group_id.license_batches.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.license_batches.v1`
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.groups.group_id.license_batches.v1`
- **proto:** remove `client_portal.accounts.id.groups.group_id.summary.v2`
- **proto:** remove `client_portal.accounts.id.groups.group_id.state.v2`
- **proto:** remove `client_portal.accounts.id.groups.group_id.license_batches.batch_id.quantity_changes.v1`
- **proto:** remove `client_portal.accounts.id.summary.v2`
- **proto:** remove `client_portal.accounts.id.license_batches.v1`
- **proto:** remove `client_portal.accounts.id.license_batches.batch_id.quantity_changes.v1`

### Features

- **proto:** remove `client_portal.accounts.id.groups.group_id.license_batches.batch_id.quantity_changes.v1` ([976817c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/976817c89164cabdb13547581f25d67e58c76dd3))
- **proto:** remove `client_portal.accounts.id.groups.group_id.state.v2` ([a0767b4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a0767b450ab8da4dba67b16fc92cb2d7f6e38f40))
- **proto:** remove `client_portal.accounts.id.groups.group_id.summary.v2` ([6eec302](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6eec3024f8b865e12de9928c7e64b9899315e738))
- **proto:** remove `client_portal.accounts.id.license_batches.batch_id.quantity_changes.v1` ([69320f7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/69320f7e67ebad5c84cc2c15f1d0b835657a6d58))
- **proto:** remove `client_portal.accounts.id.license_batches.v1` ([afa926f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/afa926fb89001e7bfd9eb416d171feaeca12c286))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.groups.group_id.license_batches.batch_id.quantity_changes.v1` ([72ef11a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/72ef11a0c88510e7f7a913189f5be55fe320bcc3))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.groups.group_id.license_batches.v1` ([9c9b1b0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c9b1b0d28a8d431de05f7c75e48404d222a8e2b))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.groups.group_id.license_batches.batch_id.quantity_changes.v1` ([d7c3564](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d7c3564b4c066b97d0c3fbe35d244983e324cce5))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.groups.group_id.license_batches.v1` ([aa93070](https://github.com/WhitehawkCEC/whitehawk-proto/commit/aa93070aa14786092f2d7f4d0e280b4e64bc1dfc))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.license_batches.batch_id.quantity_changes.v1` ([6c14e72](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6c14e724379a8b775effb6ae50120e8f34401353))
- **proto:** remove `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.license_batches.v1` ([405825e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/405825e536385f773db93ecf5a52098a6372f123))
- **proto:** remove `client_portal.accounts.id.summary.v2` ([5e13148](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5e1314851514b5a4c75ddf87917d63d2d6498804))
- **proto:** remove `scorecard_portfolio.v1` ([1de9bef](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1de9befb28828e83276e3d0c642da84715f5f1fb))

### [0.70.52](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.51...0.70.52) (2023-05-08)

### Features

- add `CreateInputInDepthBlackKiteWithFrameworks` ([0746544](https://github.com/WhitehawkCEC/whitehawk-proto/commit/074654461802c5decf1db8a28ba28ee2348d74be))

### [0.70.51](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.50...0.70.51) (2023-05-04)

### [0.70.50](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.49...0.70.50) (2023-05-04)

### [0.70.49](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.48...0.70.49) (2023-05-04)

### [0.70.48](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.47...0.70.48) (2023-05-04)

### [0.70.47](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.46...0.70.47) (2023-05-04)

### [0.70.46](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.45...0.70.46) (2023-05-04)

### [0.70.45](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.44...0.70.45) (2023-05-04)

### [0.70.44](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.43...0.70.44) (2023-05-04)

### [0.70.43](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.42...0.70.43) (2023-05-04)

### [0.70.42](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.41...0.70.42) (2023-05-04)

### Features

- sc template read rpc ([3ad35c1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3ad35c1fe0294bd41c98be00505eedc06a0367f9))

### [0.70.41](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.40...0.70.41) (2023-05-02)

### [0.70.40](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.39...0.70.40) (2023-05-02)

### Features

- **proto:** add service `client_portal.accounts__0__subscriptions__0__groups__0__licensing_id.v1` ([31652b9](https://github.com/whitehawkcec/whitehawk-proto/commit/31652b9731ce824fdf5b09ffbb8f259e0255d0ed))

### [0.70.39](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.38...0.70.39) (2023-04-27)

### [0.70.38](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.37...0.70.38) (2023-04-27)

### [0.70.37](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.36...0.70.37) (2023-04-27)

### [0.70.36](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.35...0.70.36) (2023-04-26)

### [0.70.35](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.34...0.70.35) (2023-04-26)

### Features

- template v2 ([829f880](https://github.com/WhitehawkCEC/whitehawk-proto/commit/829f880a48d80eb832bff3dd814f29f1f8af8228))

### [0.70.34](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.33...0.70.34) (2023-04-25)

### Features

- files v1 own message ([5adf4a9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5adf4a9dbc5d24e7b98cb75f23fe71cbfb0b3f27))

### [0.70.33](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.32...0.70.33) (2023-04-25)

### Features

- upload request v2 ([4cc6009](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4cc6009a7fad2fc387417acb49500bf4e4af76bc))

### [0.70.32](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.31...0.70.32) (2023-04-20)

### Features

- refactor create request to not have ids and other fields ([358a179](https://github.com/WhitehawkCEC/whitehawk-proto/commit/358a179da620395c47b59f7cbcc43b3e06ebbbb1))

### [0.70.31](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.30...0.70.31) (2023-04-20)

### [0.70.30](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.29...0.70.30) (2023-04-20)

### [0.70.29](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.28...0.70.29) (2023-04-19)

### [0.70.28](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.27...0.70.28) (2023-04-18)

### [0.70.27](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.26...0.70.27) (2023-04-18)

### Bug Fixes

- **proto:** remove unused field Meta, use scorecard V3 Status ([7f587ae](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7f587ae86a8f75d2ac202835c1aca31192b24a72))

### [0.70.26](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.25...0.70.26) (2023-04-17)

### [0.70.25](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.24...0.70.25) (2023-04-17)

### Bug Fixes

- **proto:** version number ([a5d7515](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a5d75154d1a9bbb4e931e9843319afa18617a794))
- **proto:** version number ([3723191](https://github.com/WhitehawkCEC/whitehawk-proto/commit/37231913820d87ad7ce196d1b23d75c01bbb694d))

### [0.70.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.22...0.70.23) (2023-04-17)

### Features

- delete request include type as well ([ae775f8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ae775f88fac08d931c6a25306268ef9e0a971f65))
- file meta create request include filename as well ([58b033a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/58b033a6b5f16c6d7010228f0b94cf594d1939b7))

### Bug Fixes

- **proto:** version number ([a5d7515](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a5d75154d1a9bbb4e931e9843319afa18617a794))
- **proto:** version number ([3723191](https://github.com/WhitehawkCEC/whitehawk-proto/commit/37231913820d87ad7ce196d1b23d75c01bbb694d))

### [0.70.24](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.23...0.70.24) (2023-04-14)

### Features

- file meta create request include filename as well ([58b033a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/58b033a6b5f16c6d7010228f0b94cf594d1939b7))

### [0.70.23](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.22...0.70.23) (2023-04-14)

### Features

- delete request include type as well ([ae775f8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ae775f88fac08d931c6a25306268ef9e0a971f65))

### [0.70.22](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.21...0.70.22) (2023-04-13)

### [0.70.21](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.20...0.70.21) (2023-04-13)

### [0.70.20](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.19...0.70.20) (2023-04-13)

### [0.70.19](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.18...0.70.19) (2023-04-13)

### Features

- create response return created object ([7ac3d4d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7ac3d4d6ee5b6f68085841b377630a458ef0ea66))

### [0.70.18](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.17...0.70.18) (2023-04-12)

### Features

- **proto:** service for questionnaire response ([8c319fc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8c319fc2246015e875e98cd3ddf0e969fbd1ec53))

### [0.70.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.16...0.70.17) (2023-04-12)

### Features

- **proto:** service for questionnaire response ([8c319fc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8c319fc2246015e875e98cd3ddf0e969fbd1ec53))

- template use meta ([cbb1e66](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cbb1e66d838c6ec9fe90ece13ea9f96225d301ac))

### [0.70.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.15...0.70.16) (2023-04-12)

### Features

- **proto:** service for standard questionnaire response ([307b21d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/307b21d3f553e0f5c81fd5e16e1f885ce35f1a79))

### [0.70.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.14...0.70.15) (2023-04-12)

### [0.70.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.13...0.70.14) (2023-04-12)

### Bug Fixes

- **proto:** package name ([44ae5fd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/44ae5fd56da70ef06d5180cd4c9005580ae83ebd))

### [0.70.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.12...0.70.13) (2023-04-12)

### Features

- **proto:** add bundle solution ([c3cd5f8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c3cd5f802ccda2538624c3f8f79e5938e07f96c4))
- **proto:** service to retrieve bundle solution ([058dd6b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/058dd6b7257a2c73f548c113115bdb1c4744386a))

### [0.70.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.11...0.70.12) (2023-04-12)

### Features

- templates as grpc ([1382452](https://github.com/WhitehawkCEC/whitehawk-proto/commit/138245299cd3ff30d99eb8db90ef50e40b9745e0))

### [0.70.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.10...0.70.11) (2023-04-12)

### Features

- **proto:** add archived data to meta ([55362a9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/55362a97b8f260061cc3dbd9d45d8b328a6d87f8))
- **proto:** add service for company overview ([e74484c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e74484cc0b49e7d7de3fe70df2c14a3cf3065dff))
- **proto:** add snapshot scorecard ([f05d931](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f05d9312ecacfb84ecdf5faf6893f9386dc51c7b))
- **proto:** add user with additional fields ([77896bd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/77896bdff1539f083166ba587aff0cf8d64f3b6e))

### [0.70.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.9...0.70.10) (2023-04-10)

### [0.70.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.8...0.70.9) (2023-04-05)

### [0.70.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.7...0.70.8) (2023-04-05)

### [0.70.7](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.6...0.70.7) (2023-04-04)

### Features

- **proto:** add service `client_portal.accounts__0__subscriptions__0__licensing_id.v1` ([1174d80](https://github.com/whitehawkcec/whitehawk-proto/commit/1174d80cf06cb92c98632524455d5bf83ba52743))

### [0.70.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.5...0.70.6) (2023-04-03)

### [0.70.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.4...0.70.5) (2023-04-03)

### [0.70.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.70.3...0.70.4) (2023-03-27)

### Features

- **proto:** add service `accounts__0__subscriptions__0__scorecard_summaries_v3.v1` ([7ba785b](https://github.com/whitehawkcec/whitehawk-proto/commit/7ba785b3027e505f462cd4e4535ffabf11e36b77))

### [0.70.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.2...0.70.3) (2023-03-24)

### Features

- **proto:** add service for account scorecard frameworks ([0d79189](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0d79189081c7a2fc4d0556ad92e1e4891341e197))

### [0.70.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.1...0.70.2) (2023-03-10)

### [0.70.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.70.0...0.70.1) (2023-03-10)

## [0.70.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.69.5...0.70.0) (2023-03-10)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.sync.v1`
- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.syncs.v1`
- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.report.v1`
- **web:** stop generating extra `dist/esm/`
- **web:** switch type to `module`

### Features

- add `Read` resource to todos ([c724624](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c7246240bc51505adf67a466f0b119ce84908575))
- have `DeleteResponse` return `todo_id` for ui invalidation ([c975131](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c975131072dbbbad6b0147bbb30b51498ab31e7e))
- have `UpdateResponse` return `todo_id` for ui invalidation ([d94c9a5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d94c9a5cefc42bc3a621a7b97741c3b8557fe55b))
- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.report.v1` ([b177f6a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b177f6a2ccc4e07d1244cd56e3640ad7c2dbf0d1))
- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.sync.v1` ([af80dd2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/af80dd25fa7cc4cefbc2e069d5713d30fd2711ff))
- **proto:** remove service `client_portal.accounts.id.integrations.supply_wisdom.syncs.v1` ([ffa2db9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ffa2db9f7ac3d1506a4ac6e071e05d89044ede4d))
- **web:** stop generating extra `dist/esm/` ([9058aba](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9058aba8d5416e98df635cc0a3dd4e80e605abe4))
- **web:** switch type to `module` ([2467b90](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2467b907f1ab597123e687006d98fae3dae4ad9c))

### [0.69.5](https://github.com/whitehawkcec/whitehawk-proto/compare/0.69.4...0.69.5) (2023-03-08)

### [0.69.4](https://github.com/whitehawkcec/whitehawk-proto/compare/0.69.3...0.69.4) (2023-03-08)

### Features

- **web:** use `tsup` to build ([d57f1c3](https://github.com/whitehawkcec/whitehawk-proto/commit/d57f1c3cd8ff34ee4f0a037a8f795c6ff4b58dad))

### [0.69.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.69.2...0.69.3) (2023-03-08)

### Features

- **web:** generate ESM files as well ([1aa588e](https://github.com/whitehawkcec/whitehawk-proto/commit/1aa588e5268c8b1b48c42a87488825002bcfa416))

### [0.69.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.69.1...0.69.2) (2023-03-07)

### Features

- **proto:** add supply wisdom as subscription product ([397999e](https://github.com/whitehawkcec/whitehawk-proto/commit/397999ea3db539ace605f9f116321e21ee965003))

### [0.69.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.69.0...0.69.1) (2023-03-06)

### Features

- add v2 service for `accounts__0__frameworks__0__findings__0__result_override` ([84a30a8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/84a30a8c37ed785925ea0602f36bae84834b9e70))

## [0.69.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.8...0.69.0) (2023-03-06)

### ⚠ BREAKING CHANGES

- remove `accounts__0__frameworks__0__findings__0__priority` v1 service

### Features

- remove `accounts__0__frameworks__0__findings__0__priority` v1 service ([a4fa3ff](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a4fa3ff2d967e568feef76c04a68dcf861a02db5))

### [0.68.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.7...0.68.8) (2023-03-06)

### Features

- add `Framework` message v4 ([b1ba79d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b1ba79d79a1c99cb578d9143704de83b1406a86f))
- add `Todo` message v2 ([ba0aaf2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ba0aaf257dc340b4ada58cc3154a398043214d04))
- add v2 service for `accounts__0__frameworks` ([fa190b6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fa190b619cafac2c3e9f50f1b5ffe84c753ef656))
- add v2 service for `accounts__0__todos` ([9874052](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9874052fb91be64874f108f14b19ad1cd8abc7c4))

### Bug Fixes

- use `framework/v4` ([b1df160](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b1df1608b643c0cc6b813b080b64df492d177d08))

### [0.68.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.6...0.68.7) (2023-03-02)

### [0.68.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.5...0.68.6) (2023-03-02)

### Features

- add `accounts__0__frameworks__0__findings__0__priority.v1` service ([f5eaab2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f5eaab28b4a05d936f681d33626ef8b4fe2ac11a))
- add `Priority` as global message ([a565dfd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a565dfdbcb26dbfe24040c44ce513c79196eb246))
- prefer to use `v3` message ([9d793d3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9d793d363516745720bd5de05dc7e6a62243a759))
- prefer to use global `Priority` message ([4766dfb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4766dfbe6de798e8e93bb2fa9ced1da9bf1433a4))

### [0.68.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.4...0.68.5) (2023-03-02)

### [0.68.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.3...0.68.4) (2023-02-28)

### [0.68.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.2...0.68.3) (2023-02-28)

### [0.68.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.68.1...0.68.2) (2023-02-28)

### [0.68.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.68.0...0.68.1) (2023-02-16)

### Features

- **proto:** add service `client_portal.accounts__0__subscriptions__0__feature_status.v1` ([0ce5123](https://github.com/whitehawkcec/whitehawk-proto/commit/0ce51238913eb00cab5824a233142ed346524154))

## [0.68.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.67.0...0.68.0) (2023-02-16)

### ⚠ BREAKING CHANGES

- update `client_portal.frameworks.v2` service
- remove `client_portal.accounts__0__framework_preferences.v1` service

### Features

- add `client_portal.accounts.id.frameworks.v2` service ([46f548e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/46f548ec9baa4855cf4610db5b610df56dfeec22))
- prefer consistent message to `v1` ([ad18be9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ad18be942aecde8574074b93a7c626a028ae558a))
- remove `client_portal.accounts__0__framework_preferences.v1` service ([3760141](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3760141cb3bae5bf9add282b1dc8b8ed21dbada2))
- update `client_portal.frameworks.v2` service ([dea1c74](https://github.com/WhitehawkCEC/whitehawk-proto/commit/dea1c74631ddc10fdd62ed38a0957f264d69456c))

## [0.67.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.66.0...0.67.0) (2023-02-15)

### ⚠ BREAKING CHANGES

- fix spelling

### Features

- fix spelling ([a6d08b4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a6d08b465c58435371d656bf4d9774b7bd82f5ea))

## [0.66.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.65.0...0.66.0) (2023-02-15)

### ⚠ BREAKING CHANGES

- remove `client_portal.accounts.id.framework_details.v1` service
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.result_override.v2` service
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.result_override.v1` service
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.priority.v1` service

### Features

- add `client_portal.accounts__0__framework_preferences.v1` service ([3bf7110](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3bf7110cac452bf5c6e0855ae94c798820d5f80e))
- add `client_portal.accounts__0__frameworks__0__findings__0__result_override.v1` service ([42f635f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/42f635ff385b2649e690419fb9d4b57b8e48dd8a))
- add `client_portal.accounts__0__frameworks.v1` service ([efc09e5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/efc09e5c26c651436f8be3e26a749617e6b4636e))
- add `whitehawk.proto.internal.client_portal.frameworks.v2` service ([534fe8a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/534fe8ad6e1ab6fb9ed1fd427920bf5e45af89e4))
- add framework v3 message ([940bf41](https://github.com/WhitehawkCEC/whitehawk-proto/commit/940bf41d33fe1904207519b02cf19d02a9db3e6c))
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.priority.v1` service ([f9813f7](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f9813f72a34d9c2a0a88bc36d963c56d59ed2318))
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.result_override.v1` service ([e036e33](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e036e332343a538ec85f3178b3fd09ac9f18aaf1))
- remove `client_portal.accounts.id.framework_details.framework_id.findings.finding_id.result_override.v2` service ([728b0ad](https://github.com/WhitehawkCEC/whitehawk-proto/commit/728b0ad512616ad918df2f72925fd90c87394b88))
- remove `client_portal.accounts.id.framework_details.v1` service ([4c7cdba](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4c7cdba45aaa3dce8a1b72ff87540c445383cbb0))

## [0.65.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.64.0...0.65.0) (2023-02-15)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v1`

### Features

- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v1` ([250ea1e](https://github.com/whitehawkcec/whitehawk-proto/commit/250ea1ed367a7cf49e2f1130a6ecbd24d78e085a))

## [0.64.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.63.17...0.64.0) (2023-02-15)

### ⚠ BREAKING CHANGES

- remove messages for `scorecard_v3.indepthblackkitecmmcv2.v1`

### Features

- **proto:** add `enable_scorecard_download` flag ([b310485](https://github.com/whitehawkcec/whitehawk-proto/commit/b310485804e38a6b85af7c1fbdfa518a5d81b69c))
- remove messages for `scorecard_v3.indepthblackkitecmmcv2.v1` ([109cc4e](https://github.com/whitehawkcec/whitehawk-proto/commit/109cc4e08649d858d1e7911adb1435e15dab5944))

### [0.63.17](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.16...0.63.17) (2023-01-30)

### [0.63.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.15...0.63.16) (2023-01-30)

### [0.63.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.14...0.63.15) (2023-01-30)

### [0.63.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.13...0.63.14) (2023-01-30)

### [0.63.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.12...0.63.13) (2023-01-27)

### Features

- bundle report ([1275ce0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1275ce00c828c57d0f3f22f0a9f81c8d88987ea5))

### [0.63.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.11...0.63.12) (2023-01-27)

### Features

- add `Todo` message ([670f50b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/670f50b7b3441335ad576649a84a2a689f9da8a1))
- add todo `CRUDL` services ([5ecaf96](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5ecaf9604f486ebe4337bb1fe214d7464ef100fb))

### [0.63.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.10...0.63.11) (2023-01-19)

### Features

- grpc delete service for scheduled ([548d21f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/548d21fbbd94a47faab01c6a1abbc03733142b99))

### [0.63.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.9...0.63.10) (2023-01-19)

### Features

- scheduled update grpc ([31db480](https://github.com/WhitehawkCEC/whitehawk-proto/commit/31db4801c139c365c11b1c7d105f8e25b2dbec2a))

### [0.63.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.8...0.63.9) (2023-01-18)

### Bug Fixes

- merge conflicts ([5f4b843](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5f4b84335e9fa507807cec96eea47820d1df4c39))

### [0.63.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.7...0.63.8) (2023-01-18)

### Features

- report for product categories ([88a3167](https://github.com/WhitehawkCEC/whitehawk-proto/commit/88a316775c86e245163f7bd76a4ebfe9a0220aed))
- service for product category report ([33504f3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/33504f347b2ff354c0264e08fe80042ad7656ded))

### [0.63.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.6...0.63.7) (2023-01-17)

### Features

- batch scheduled proto def ([c3087a2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c3087a221478061190723adc211aff5b06719688))

### [0.63.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.5...0.63.6) (2023-01-17)

### Features

- report for subscription products ([7a3faa6](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7a3faa690dab9873cfd4b0a1b2a590a76dbfccb1))
- service for subscription product report ([120d9e9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/120d9e959216d59aeac3c8284c6ac58252862533))

### [0.63.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.4...0.63.5) (2023-01-12)

### Bug Fixes

- remove unused import ([19c1b5e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/19c1b5ee98e1007674fdaf3c06a1db95fa6a6c0d))

### [0.63.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.3...0.63.4) (2023-01-12)

### Features

- account reports ([cddc8b9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cddc8b977cc88d8c2c052e222214d876be1f1109))
- report service to retrieve all accounts ([7257b33](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7257b333b6d7956520bf2521e7f7cc8bdab52de3))
- report service to retrieve all subscriptions for an account ([8f0db74](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8f0db7469329965451c04dbf9b0b5e6d3579f3d0))

### [0.63.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.2...0.63.3) (2023-01-09)

### Bug Fixes

- docx scorecard use pending object ([b59128e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b59128e2ee6293b13377ad82ac2640b5470072e3))

### [0.63.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.1...0.63.2) (2023-01-09)

### Features

- use framework v2 message ([31f7e49](https://github.com/WhitehawkCEC/whitehawk-proto/commit/31f7e49aa535ba97fc7f432e7f00020bdca78e9a))

### [0.63.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.63.0...0.63.1) (2023-01-09)

### Features

- use framework v2 message ([a23baa0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a23baa0aa611500302fe51812f3060e75bdaa252))

## [0.63.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.62.3...0.63.0) (2023-01-09)

### ⚠ BREAKING CHANGES

- add v2 message for framework

### Features

- add v2 message for framework ([f4b2523](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f4b252384451093d77a08ed679f86c80709cdedc))
- add v2 service for `result_override` ([eb89ef0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/eb89ef0c596e8ffbca497a514791cd1654f469e9))

### [0.62.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.62.2...0.62.3) (2023-01-09)

### [0.62.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.62.1...0.62.2) (2023-01-09)

### Features

- add `priority` field ([7e0f7fe](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7e0f7fe045668b9cc902a129a8ae37e27b4814ec))
- add `set` service for priority ([ae303b9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ae303b936807d361fe65801cadad71ae2ab1f0ae))

### [0.62.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.62.0...0.62.1) (2023-01-09)

### Features

- **proto:** add service `client_portal.accounts__0__subscriptions__0__integrations__black_kite__entities__0__latest_scorecard.v1` ([97106b2](https://github.com/whitehawkcec/whitehawk-proto/commit/97106b21bd7d16d7b5761ac55763b991b30cc761))

## [0.62.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.9...0.62.0) (2023-01-09)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.integrations.black_kite.entities.v1

### Features

- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.integrations.black_kite.entities.v1 ([9c3899c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c3899c728d95cdf3d47a26f4fd4aee12df23dc4))
- zip create response include id ([0148cd3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0148cd3f15fc7856772b41d579646b7db8518333))

### [0.61.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.8...0.61.9) (2023-01-06)

### Features

- add `confidence` field ([e796501](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e796501785bbcd06be921afa4baea66f747e7885))

### [0.61.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.7...0.61.8) (2023-01-06)

### Features

- response with meta ([de3c4ca](https://github.com/WhitehawkCEC/whitehawk-proto/commit/de3c4ca9e50859ffc925db1a9bdeee9eb318f0ee))

### [0.61.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.6...0.61.7) (2023-01-06)

### [0.61.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.5...0.61.6) (2023-01-06)

### Features

- add `completeness` + `compliance` fields ([fbe03be](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fbe03be2fb797ccccab963be392e3a8c72eb5024))

### [0.61.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.4...0.61.5) (2023-01-06)

### Bug Fixes

- refactor convert zip to include supplie name as well ([e8a8f85](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e8a8f85086f159e9af1ab919eea6ae16ed018abd))

### [0.61.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.3...0.61.4) (2023-01-06)

### Bug Fixes

- undo unwanted move ([022a65c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/022a65c7fb082da54f773980f3dbfa8cc016b401))

### [0.61.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.2...0.61.3) (2023-01-06)

### Features

- added zip grpc ([847038a](https://github.com/WhitehawkCEC/whitehawk-proto/commit/847038ad57f133aeb7d692eb362176595d6c042a))

### [0.61.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.1...0.61.2) (2023-01-06)

### [0.61.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.61.0...0.61.1) (2023-01-06)

### Features

- batch grpc read function ([b1c7a24](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b1c7a24e9d5a2f2aaf35e4517e96676f941373b7))

## [0.61.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.6...0.61.0) (2023-01-05)

### ⚠ BREAKING CHANGES

- move unused `framework_details/v1` service
- move unused `framework_details/v1` service

### Features

- move unused `framework_details/v1` service ([b3b90e0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b3b90e09b593f3ae6f06669de731923bbc0a3a45))
- move unused `framework_details/v1` service ([a562e72](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a562e724f916e472295bfb42b7c9fe04465bc565))

### [0.60.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.5...0.60.6) (2023-01-05)

### [0.60.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.4...0.60.5) (2023-01-05)

### [0.60.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.3...0.60.4) (2023-01-05)

### Bug Fixes

- missing repeated for list ([ec08e41](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ec08e41d79ba5a521462d2c1100b0f4847b49bce))

### [0.60.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.2...0.60.3) (2023-01-05)

### Features

- add rpc list for batch v3 ([219a595](https://github.com/WhitehawkCEC/whitehawk-proto/commit/219a595aac416633d86bbc95efb4f128e044361d))

### [0.60.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.1...0.60.2) (2023-01-05)

### [0.60.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.60.0...0.60.1) (2023-01-05)

### Features

- add grpc list request for batch v3 as well ([6fe55c8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6fe55c8a283e8408108d6e5d93da353b2897d4b4))

## [0.60.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.9...0.60.0) (2023-01-05)

### ⚠ BREAKING CHANGES

- rename for consistency

### Features

- add `ComplianceFramework` message ([4ade4d4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4ade4d40edcaea747def4015c8d1fc54d0f1d425))
- add `FrameworkMoreInfo` + friends message ([b84ad33](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b84ad3392559fdd53a8c441009a032d0dad1d799))
- add field for average star level ([f82e109](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f82e109bff3c0e22ce14fe08f358d18742884adf))
- add service to read `FrameworkMoreInfo` ([720e7f8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/720e7f8ffa64533bbd95df10fac0d37e720cbdc1))
- add service to set `result_override` field ([17a3af2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/17a3af28be8f4638040209287daa50c7f8167d3f))
- rename for consistency ([b158604](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b15860466abc7eb06762fa4af3cbfefbe0bba5c5))

### [0.59.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.8...0.59.9) (2023-01-05)

### [0.59.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.7...0.59.8) (2023-01-04)

### Features

- subscription on request itself ([4383c7d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4383c7d1c0b4eed922e1b4fdd93e67c3f04a0bf2))

### [0.59.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.6...0.59.7) (2022-12-29)

### Bug Fixes

- remove year and quarter as status already has it ([3439eac](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3439eac27d52e7f473e1449e6641df598a6cbf5c))

### [0.59.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.5...0.59.6) (2022-12-29)

### Bug Fixes

- add companyinfo on batch request ([1973844](https://github.com/WhitehawkCEC/whitehawk-proto/commit/19738443299fe422e243192e718ac17aa85cfaa7))

### [0.59.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.4...0.59.5) (2022-12-29)

### Features

- use account id in request object itself ([9225e18](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9225e18a7059f5ab6bcdbd29471eb5ed6f49c1c0))

### [0.59.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.59.3...0.59.4) (2022-12-29)

### Features

- batch bk v3 proto def ([0460fce](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0460fcef99826be99dd4a63f3483a1a9cb8a366a))

### [0.59.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.59.2...0.59.3) (2022-12-28)

### Features

- **proto:** add service `client_portal.scorecards_v3.v1` ([f42d63c](https://github.com/whitehawkcec/whitehawk-proto/commit/f42d63cb080eedc7768eea800fa9470513fb9b50))

### [0.59.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.59.1...0.59.2) (2022-12-23)

### Features

- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v2` ([f4e5e48](https://github.com/whitehawkcec/whitehawk-proto/commit/f4e5e4873e47c32934038cb05dc7fe9ece296f20))

### [0.59.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.59.0...0.59.1) (2022-12-23)

### Features

- **proto:** add v2 messages for BK domain ([288a39a](https://github.com/whitehawkcec/whitehawk-proto/commit/288a39a4b235260f1d551231a5644a8886b0b051))
- **proto:** add v2 messages for scorecard BK CMMC v2 ([8fc62e7](https://github.com/whitehawkcec/whitehawk-proto/commit/8fc62e7f5a7b321cef2065d28a8f398675401d9b))

## [0.59.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.58.0...0.59.0) (2022-12-23)

### ⚠ BREAKING CHANGES

- **proto:** use correct message type

### Bug Fixes

- **proto:** use correct message type ([d4d2395](https://github.com/whitehawkcec/whitehawk-proto/commit/d4d2395bc7d7f6fb77011bdf31e9676dfe037e10))

## [0.58.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.57.0...0.58.0) (2022-12-23)

### ⚠ BREAKING CHANGES

- **proto:** use correct message type

### Bug Fixes

- **proto:** use correct message type ([24b720a](https://github.com/whitehawkcec/whitehawk-proto/commit/24b720affc0ea118370695fb0e061dbd1a37155e))

## [0.57.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.56.0...0.57.0) (2022-12-20)

### ⚠ BREAKING CHANGES

- **proto:** use correct field type

### Bug Fixes

- **proto:** use correct field type ([29865c1](https://github.com/whitehawkcec/whitehawk-proto/commit/29865c139c96d2e22a03b134a4fb440e931549fb))

## [0.56.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.55.0...0.56.0) (2022-12-19)

### ⚠ BREAKING CHANGES

- **proto:** restructure scorecard v3 BK to use scorecard v3 messages
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.cyber_risk_rating.black_kite.performance.v2`

### Features

- **proto:** add messages for base scorecard v3 ([d747965](https://github.com/whitehawkcec/whitehawk-proto/commit/d7479653a71c075ec64e42e97d01b6fc4e0b2ee7))
- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.scorecard_summaries_v3.v1` ([e3033f1](https://github.com/whitehawkcec/whitehawk-proto/commit/e3033f13ec1e87a4f3dbf512dace356608edc5d4))
- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.scorecards_v3.v1` ([ba48d72](https://github.com/whitehawkcec/whitehawk-proto/commit/ba48d72d86d815279b1c553dd9c488b536c8dc18))
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.cyber_risk_rating.black_kite.performance.v2` ([7da2c49](https://github.com/whitehawkcec/whitehawk-proto/commit/7da2c495f61a1e2135673d9284fd02255fc21ddb))
- **proto:** restructure scorecard v3 BK to use scorecard v3 messages ([1ff5f4b](https://github.com/whitehawkcec/whitehawk-proto/commit/1ff5f4bbe9e53ca7096adbe57df98afa66b2ffdb))

## [0.55.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.54.1...0.55.0) (2022-12-19)

### ⚠ BREAKING CHANGES

- rename scorecard v3 package

### Features

- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.products.product_id.cyber_risk_rating.black_kite.performance.v2` ([afc0ea1](https://github.com/whitehawkcec/whitehawk-proto/commit/afc0ea1186c539d69f9a864805328c6b2b4f96cc))
- rename scorecard v3 package ([7b86d92](https://github.com/whitehawkcec/whitehawk-proto/commit/7b86d9299b6feeabf1ef2861f072529d9d241dd3))

### [0.54.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.54.0...0.54.1) (2022-12-16)

### Features

- add integration/product types ([a3a302d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a3a302dd944f87878e71fc8cf5b6337ab00c9787))

## [0.54.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.53.0...0.54.0) (2022-12-13)

### ⚠ BREAKING CHANGES

- **proto:** restructure scorecard v3 to use analysis v1
- **proto:** restructure scorecard v3 to use cmmc v2
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v2`
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v1`

### Features

- **proto:** add messages for analysis v1 ([237a4e9](https://github.com/whitehawkcec/whitehawk-proto/commit/237a4e91653758d25eca84389d8adcbfe4aeec9a))
- **proto:** add messages for BK reports ([fedf0f9](https://github.com/whitehawkcec/whitehawk-proto/commit/fedf0f96a766939afa956baedf0b0308b3a1c974))
- **proto:** add messages for cmmc v2 ([3443569](https://github.com/whitehawkcec/whitehawk-proto/commit/34435693c7399bace89530e9e8cdc86cb2903721))
- **proto:** add messages for scorecard v3 ([7a64df9](https://github.com/whitehawkcec/whitehawk-proto/commit/7a64df9ee0a44c8679bcf1041de0ade91197f917))
- **proto:** fill in bundles for scorecard v3 ([69b842d](https://github.com/whitehawkcec/whitehawk-proto/commit/69b842d7162e79a6ab6715961e1b6b0dfc68cb97))
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v1` ([9c8d66c](https://github.com/whitehawkcec/whitehawk-proto/commit/9c8d66c29994249f06c0fd25898f1ab4929dde97))
- **proto:** remove service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v2` ([0e81149](https://github.com/whitehawkcec/whitehawk-proto/commit/0e81149147dc80beb03168cddb21213f3b5ac629))
- **proto:** restructure scorecard v3 to use analysis v1 ([2824724](https://github.com/whitehawkcec/whitehawk-proto/commit/282472405547084d866cfa0e067a5c456d65dc9b))
- **proto:** restructure scorecard v3 to use cmmc v2 ([41ef6b2](https://github.com/whitehawkcec/whitehawk-proto/commit/41ef6b2ca79f48d8ec3a5c04bf02794221846b26))

## [0.53.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.16...0.53.0) (2022-12-06)

### ⚠ BREAKING CHANGES

- **proto:** Added oneof for answerId and answerText

### Features

- **proto:** Added oneof for answerId and answerText ([6a93f7d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6a93f7db70dbff015e42ae0db40ee10378f0a946))

### [0.52.16](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.15...0.52.16) (2022-12-06)

### [0.52.15](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.14...0.52.15) (2022-12-06)

### [0.52.14](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.13...0.52.14) (2022-12-06)

### [0.52.13](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.12...0.52.13) (2022-12-01)

### [0.52.12](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.11...0.52.12) (2022-11-30)

### [0.52.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.10...0.52.11) (2022-11-30)

### [0.52.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.9...0.52.10) (2022-11-30)

### [0.52.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.8...0.52.9) (2022-11-30)

### [0.52.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.7...0.52.8) (2022-11-30)

### [0.52.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.6...0.52.7) (2022-11-30)

### [0.52.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.5...0.52.6) (2022-11-23)

### Features

- add CRUDL services for accounts ([166b132](https://github.com/WhitehawkCEC/whitehawk-proto/commit/166b132d080edf775a1aaa4b675172c28164b0ee))

### [0.52.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.4...0.52.5) (2022-11-21)

### [0.52.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.3...0.52.4) (2022-11-21)

### [0.52.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.2...0.52.3) (2022-11-21)

### Features

- add `answered` service custom questionnaires ([3d979ee](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3d979ee06bbe26e7224e0e4a0d74a1cd92009204))
- add `CRUDL` custom questionnaires service ([8f5921d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8f5921dde451263e2fe1eba5ad401f81042ec892))
- add `display_schemas` as singleton resource ([6e47518](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6e47518eddbc887e728e4480a76d0c995df2e732))
- add `display_ui_schemas` as singleton resource ([a6264a0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a6264a07efad5f3dd7f401067749ee6967235f7d))
- add `taken` service custom questionnaires ([156f9b3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/156f9b30d53906933a2a423a0d6bd565c3a3889a))

### [0.52.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.52.1...0.52.2) (2022-11-18)

### Features

- add singleton resource for `/integrations/bitsight/companies/_/cyber_risk/v1` ([6e6447f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6e6447fc2890ff983bed694efe9e94d3e1d5658f))

### [0.52.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.52.0...0.52.1) (2022-11-17)

### Features

- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v3` ([c1d20ee](https://github.com/whitehawkcec/whitehawk-proto/commit/c1d20eec8635a2ce1ee157e6cb104c3178cd9fb0))

## [0.52.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.51.4...0.52.0) (2022-11-17)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal.accounts.id.integrations.black_kite.cyber_risk.v1`

### Features

- **proto:** add service `client_portal.accounts.id.integrations.black_kite.entities.entity_id.cyber_risk.v1` ([3dac721](https://github.com/whitehawkcec/whitehawk-proto/commit/3dac721ae9c04e61562846d7a108883262d8d90e))
- **proto:** remove service `client_portal.accounts.id.integrations.black_kite.cyber_risk.v1` ([6e0fc2c](https://github.com/whitehawkcec/whitehawk-proto/commit/6e0fc2c958014231cbce60902b0755c24e297375))

### [0.51.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.51.3...0.51.4) (2022-11-16)

### Features

- add `CustomQuestionnaire` v2 message ([5ea34bb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5ea34bb39b8e2a30a67afc06d2615aeafb0658c7))
- add `CustomQuestionnaireTaken` message ([0b27159](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0b271597fd7cd0e750a8a61d7db282d7a67ee78b))
- add `QuestionAnswer` message ([14cbb82](https://github.com/WhitehawkCEC/whitehawk-proto/commit/14cbb82006d1d166692b999e33eacc572029e3a4))

### [0.51.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.51.2...0.51.3) (2022-11-15)

### Features

- **proto:** add frameworks ([06fd026](https://github.com/WhitehawkCEC/whitehawk-proto/commit/06fd0267ca805f7c5968b876dd828ac5420705c8))

### [0.51.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.51.1...0.51.2) (2022-11-14)

### [0.51.1](https://github.com/whitehawkcec/whitehawk-proto/compare/0.51.0...0.51.1) (2022-11-14)

### Features

- **proto:** add service `client_portal.accounts.id.integrations.black_kite.cyber_risk.v1` ([7ef7416](https://github.com/whitehawkcec/whitehawk-proto/commit/7ef74164ccf705e0d696afe551da90672368d2fc))

## [0.51.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.50.2...0.51.0) (2022-11-14)

### ⚠ BREAKING CHANGES

- **proto:** change response for `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v2`

### Features

- **proto:** change response for `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v2` ([7317b94](https://github.com/whitehawkcec/whitehawk-proto/commit/7317b94d69a8fd161182942ab6b5ecca22bca929))

### [0.50.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.50.1...0.50.2) (2022-11-14)

### Features

- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v2` ([533b9bc](https://github.com/whitehawkcec/whitehawk-proto/commit/533b9bc1f4f8329a74dfc9c4d3f7e4255d0a1db9))

### [0.50.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.50.0...0.50.1) (2022-11-10)

### Features

- **proto:** service to determine if a bundle set is in use by a preference ([54fc27f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/54fc27f5ea80a7316412f9e1be21bbb2605a42e7))
- **proto:** service to determine if a questinonaire is in use by a preference ([3bb14e1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3bb14e1f5299799b83ad58a462f9eda396218777))

## [0.50.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.49.4...0.50.0) (2022-11-08)

### ⚠ BREAKING CHANGES

- **proto:** move to accounts

### Bug Fixes

- **proto:** move to accounts ([33f181d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/33f181d5c8cff93468cc7c9cfc0c4f7111c6ee62))

### [0.49.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.49.3...0.49.4) (2022-11-08)

### Features

- questionnaire preference ([2c01bc0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2c01bc0d8af9d7631a0094a1d047e82876157111))

### [0.49.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.49.2...0.49.3) (2022-11-07)

### [0.49.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.49.1...0.49.2) (2022-11-07)

### [0.49.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.49.0...0.49.1) (2022-11-07)

## [0.49.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.48.4...0.49.0) (2022-11-03)

### ⚠ BREAKING CHANGES

- **proto:** remove assigned_to_companies
- **proto:** return bundle sets instead of bundle templates

### Features

- **proto:** remove assigned_to_companies ([16ced8f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/16ced8f49f75c71b242338544cb584c02c35abef))
- **proto:** return bundle sets instead of bundle templates ([5066cd8](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5066cd871c80b18bb227e7253debe05c92dfb995))

### [0.48.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.48.3...0.48.4) (2022-11-01)

### [0.48.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.48.2...0.48.3) (2022-11-01)

### [0.48.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.48.1...0.48.2) (2022-11-01)

### [0.48.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.48.0...0.48.1) (2022-11-01)

## [0.48.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.47.0...0.48.0) (2022-11-01)

### ⚠ BREAKING CHANGES

- **proto:** properly define `SupplierBasicInfo`

### Features

- **proto:** properly define `SupplierBasicInfo` ([1f86aee](https://github.com/whitehawkcec/whitehawk-proto/commit/1f86aee9482422d6ec9329aaa331f4b9232b478d))

## [0.47.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.46.0...0.47.0) (2022-11-01)

### ⚠ BREAKING CHANGES

- **proto:** remove service `client_portal/accounts/id/subscriptions/subscription_id/integrations/black_kite/config/v1`
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/license_batches/batch_id/quantity_changes/v1`
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/license_batches/v1`
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/licensing_id/v1`

### Features

- **proto:** add service `client_portal.accounts.id.subscriptions.subscription_id.supplier_overviews.v1` ([c9a2bba](https://github.com/whitehawkcec/whitehawk-proto/commit/c9a2bba7dff514dd595cbd691c8bbc797dfe6476))
- **proto:** remove service `client_portal/accounts/id/subscriptions/subscription_id/integrations/black_kite/config/v1` ([899de28](https://github.com/whitehawkcec/whitehawk-proto/commit/899de28fcffb25c1c505fb8598516f7b15a2a926))
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/license_batches/batch_id/quantity_changes/v1` ([600adfd](https://github.com/whitehawkcec/whitehawk-proto/commit/600adfdf53ce05d1f762606ab8f295efc66eb113))
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/license_batches/v1` ([7ee2df0](https://github.com/whitehawkcec/whitehawk-proto/commit/7ee2df0bf60931ded0dcd9097dbd31e69a57a25d))
- **proto:** remove unused service `client_portal/accounts/id/subscriptions/subscription_id/licensing_id/v1` ([4320dc6](https://github.com/whitehawkcec/whitehawk-proto/commit/4320dc61a97216b266754580eecdd0a41fd3aab2))

## [0.46.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.45.0...0.46.0) (2022-10-28)

### ⚠ BREAKING CHANGES

- **java:** remove `grpc-netty-shaded` dependency

### Features

- **java:** remove `grpc-netty-shaded` dependency ([cd47d60](https://github.com/whitehawkcec/whitehawk-proto/commit/cd47d602b523f759327d3753bb40d002020112fc))

## [0.45.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.44.0...0.45.0) (2022-10-26)

### ⚠ BREAKING CHANGES

- **proto:** remove deprecated/unused messages from subscription v1
- **proto:** remove BS config v1 messages
- **proto:** remove BK config v1 messages

### Features

- **proto:** add singleton resource for getting account heatmap ([8f42306](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8f42306f53a99a97adb5f78fc35293ba971a0f3b))
- **proto:** add v2 `Heatmap` message ([8687152](https://github.com/WhitehawkCEC/whitehawk-proto/commit/86871527d5b4b83e3f5ba9dac65481e09d421357))
- **proto:** remove BK config v1 messages ([869d686](https://github.com/WhitehawkCEC/whitehawk-proto/commit/869d6860a05a521b1bd42e98be1e56cf8aca7a7f))
- **proto:** remove BS config v1 messages ([d19ecbb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d19ecbb951a3408c117d2b4ce20b65e6247690b8))
- **proto:** remove deprecated/unused messages from subscription v1 ([ac8aa59](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ac8aa59af7afffa4a48c87730a3f6a17ddf27403))

## [0.44.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.43.1...0.44.0) (2022-10-24)

### ⚠ BREAKING CHANGES

- **proto:** move categories to bundle set

### Features

- **proto:** move categories to bundle set ([bc64790](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bc64790ef67de512d04a4c7df2345f65a51832a8))

### [0.43.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.43.0...0.43.1) (2022-10-24)

### Bug Fixes

- c1 asset domain could be null ([06d35ee](https://github.com/WhitehawkCEC/whitehawk-proto/commit/06d35eedb3bd17f304b1bc68ace3e42866685d6f))

## [0.43.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.42.2...0.43.0) (2022-10-24)

### ⚠ BREAKING CHANGES

- c1 asset id is auto increment int

### Bug Fixes

- c1 asset id is auto increment int ([c7c32d9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c7c32d9cfb33dc4a1799ffbdf61b60a990c9ab47))

### [0.42.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.42.1...0.42.2) (2022-10-24)

### [0.42.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.42.0...0.42.1) (2022-10-20)

### Features

- **proto:** add `SyncType` ([6337ee1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/6337ee155fcec8777deee4c696149bc2f4561a96))

## [0.42.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.41.3...0.42.0) (2022-10-20)

### ⚠ BREAKING CHANGES

- use correct package name

### Bug Fixes

- use correct package name ([cd097e1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cd097e1b64743649a1e92687d513970847ad9941))

### [0.41.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.41.2...0.41.3) (2022-10-20)

### Features

- add `mapped_asset_id` ([b9ecec5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b9ecec510dc098f44bbfb85483a64f26014da6f3))
- add `mapped_target_name` ([5c76407](https://github.com/WhitehawkCEC/whitehawk-proto/commit/5c764078fc011f806947e3b59f9e9d603750a1cd))
- add service for BK syncs ([03f92ac](https://github.com/WhitehawkCEC/whitehawk-proto/commit/03f92ac3fcd7d66ba191883fa70a07637050d82a))
- add service for C1 syncs ([4ebb739](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4ebb739aa9730531246cd7f6ae52a07092be5f0e))
- add service for cross data syncs ([dc60517](https://github.com/WhitehawkCEC/whitehawk-proto/commit/dc6051789d116d5cc95974874e4122aedc9b3c6d))
- add service for SW syncs ([45a3b3c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/45a3b3c2ea97d0df09586ba8bf7f2c7dc10ff1ac))
- add single resource for BK latest sync ([2e35a02](https://github.com/WhitehawkCEC/whitehawk-proto/commit/2e35a02a2b55f449d73538856ac83e415eff1bcf))
- add single resource for C1 latest sync ([ff7cccd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/ff7cccd86cb706c911aad820f4d8ac9e1ef3b9bd))
- add single resource for SW latest sync ([340cfec](https://github.com/WhitehawkCEC/whitehawk-proto/commit/340cfec60c96e575115835749bc5f822dd7a0948))
- **proto:** add service to manage account black kite ecosystem companies ([c38403b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c38403b020e1e08f319c22c411738540175f68b2))

### [0.41.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.41.1...0.41.2) (2022-10-20)

### Features

- include account id on c1 create request as well ([0948f34](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0948f3430a48c2420f845db25ebeb749258ffb96))

### [0.41.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.41.0...0.41.1) (2022-10-20)

## [0.41.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.5...0.41.0) (2022-10-20)

### ⚠ BREAKING CHANGES

- remove `created_at` and `created_by` fields

### Bug Fixes

- remove `created_at` and `created_by` fields ([b47df84](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b47df843963b8ad02d00067ffb3364202e867c6c))

### [0.40.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.4...0.40.5) (2022-10-19)

### Features

- add grpc support for busineess reports ([8fd984f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8fd984f8937185068200f16cc1a3ef32958c5241))

### [0.40.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.3...0.40.4) (2022-10-18)

### Features

- **proto:** add list service for SW targets ([a28ce9d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a28ce9d5592f7f2123e6b8480afd8d51114f4846))

### [0.40.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.2...0.40.3) (2022-10-18)

### [0.40.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.1...0.40.2) (2022-10-14)

### Features

- add list service for cyber one assets ([0f2e4de](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0f2e4de6e977b52ac1315fc084f2a5f924e0dde2))
- add list service for supply wisdom assets ([32467fd](https://github.com/WhitehawkCEC/whitehawk-proto/commit/32467fd905342d3622acdf5e018be6ca32965353))

### [0.40.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.40.0...0.40.1) (2022-10-14)

### Features

- **proto:** add target name to SW config ([00d7b52](https://github.com/WhitehawkCEC/whitehawk-proto/commit/00d7b526946659796c7ce87a8a4060409a361955))

## [0.40.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.39.1...0.40.0) (2022-10-14)

### ⚠ BREAKING CHANGES

- **proto:** remove unused `BlackKiteEntity` message

### Features

- **proto:** prefer to use `domain` message ([04c0515](https://github.com/WhitehawkCEC/whitehawk-proto/commit/04c0515c8c5f2ad8506af28c4ac62d8a217b4b78))
- **proto:** remove unused `BlackKiteEntity` message ([186609b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/186609b5faab8f9ca56aca0de107cdb1e2039464))

### [0.39.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.39.0...0.39.1) (2022-10-13)

### Features

- **proto:** add `BlackKiteEcosystem` message ([0447f2e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0447f2eb3498176162c25df5b35e8095be174c81))
- **proto:** add list service for BK ecosystem ([0336ea9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/0336ea91e880974d6c0761a51b900bf544195d61))
- **proto:** add necessary `id` to C1 config ([328f1a0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/328f1a0e5b334c9391e13d96547c24dc5d4eea8c))
- **proto:** add necessary `id`s to BK config ([3305912](https://github.com/WhitehawkCEC/whitehawk-proto/commit/3305912fc827c11e3c18165dd7f3ce6cbcd52ef3))

## [0.39.0](https://github.com/whitehawkcec/whitehawk-proto/compare/0.38.6...0.39.0) (2022-10-13)

### ⚠ BREAKING CHANGES

- **proto:** remove service to manage scorecard licensing packs
- **proto:** remove service to manage scorecard licensing quantity changes
- **proto:** remove service to get account subscription scorecard licensing id

### Features

- **proto:** add licensing messages ([f5193c1](https://github.com/whitehawkcec/whitehawk-proto/commit/f5193c1b1596fb8a1259c1024a991ff16e6101c3))
- **proto:** add service to get account subscription licensing id ([fdee83b](https://github.com/whitehawkcec/whitehawk-proto/commit/fdee83b48a1c880ba9a7d6d2411755a31c11efef))
- **proto:** add service to manage licensing pack quantity ([062237c](https://github.com/whitehawkcec/whitehawk-proto/commit/062237cf0ec17092a4afdcf9f7e21c3d85a85c55))
- **proto:** add service to manage licensing packs ([c1c80b7](https://github.com/whitehawkcec/whitehawk-proto/commit/c1c80b74ca58d376f81c7a5852228f2fef3cab76))
- **proto:** remove service to get account subscription scorecard licensing id ([8944bf0](https://github.com/whitehawkcec/whitehawk-proto/commit/8944bf0c60507261ec08934c1b4191a51b251795))
- **proto:** remove service to manage scorecard licensing packs ([3e79037](https://github.com/whitehawkcec/whitehawk-proto/commit/3e7903733a68b13f8db884ebfc4ea0dfe6fb0d84))
- **proto:** remove service to manage scorecard licensing quantity changes ([3056451](https://github.com/whitehawkcec/whitehawk-proto/commit/305645183593ab594452fa44b86d921f4b58d21c))

### [0.38.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.38.5...0.38.6) (2022-10-12)

### Features

- remove rpc read from jobs v1 ([bbeabc5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bbeabc50bbceef07a39eb1ec1f1bfc57ebd6e026))

### [0.38.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.38.4...0.38.5) (2022-10-12)

### Features

- remove read request from job to job_id ([fd968c5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/fd968c5654542642ac071ce2f9879bfd567851ee))

### [0.38.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.38.3...0.38.4) (2022-10-12)

### Features

- job read as separate service ([dbad06f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/dbad06f58489f29b98747aa235d6d8aabb3ea24b))

### [0.38.3](https://github.com/whitehawkcec/whitehawk-proto/compare/0.38.2...0.38.3) (2022-10-11)

### [0.38.2](https://github.com/whitehawkcec/whitehawk-proto/compare/0.38.1...0.38.2) (2022-10-11)

### Features

- **proto:** add `LicensePack` ([bee9ebf](https://github.com/whitehawkcec/whitehawk-proto/commit/bee9ebf55bbc2bd6d2d8151940dc39015a20f0f2))
- **proto:** add service to get account subscription's scorecard licensing id ([8030b58](https://github.com/whitehawkcec/whitehawk-proto/commit/8030b586267e16c59054058952b224e2b1a997a4))
- **proto:** add service to manage scorecard licensing pack quantity changes ([892b75f](https://github.com/whitehawkcec/whitehawk-proto/commit/892b75fac732029073e64f277c094888445f8472))
- **proto:** add service to manage scorecard licensing packs ([2b6baea](https://github.com/whitehawkcec/whitehawk-proto/commit/2b6baea280629bf471d304f799d7b2279e6d326c))

### [0.38.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.38.0...0.38.1) (2022-10-11)

### Features

- **proto:** add `BlackKiteEntity` message ([4128b0c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4128b0c99864ef70f1355db0b293d8be4a149040))
- **proto:** add list service for BK entities ([1c0139d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1c0139dd61ca647d0a607c60ae8fdcf8254c757b))

## [0.38.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.7...0.38.0) (2022-10-07)

### ⚠ BREAKING CHANGES

- **proto:** add industries and bundle template type

### Features

- **proto:** add industries and bundle template type ([d88bb4c](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d88bb4cc04585609d46bf97fded109b8e7b5a10d))
- **proto:** prefer to use `slug` ([c3837a4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c3837a468ca206586fe0af6e23a83ff776022f8d))
- **proto:** prefer to use `slug` ([cbf19d3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cbf19d37c9f41e96feee8b4e017619da9b6d8c8a))
- **proto:** prefer to use `slug` ([68d10b1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/68d10b109a96ed7bafdfbab4f0c63fd99cdc5af4))
- **proto:** prefer to use `slug` ([b511c9e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b511c9e33648cabb1ccf88c4961226466c88e59c))
- **proto:** remove unused resource `AccountId` ([c7ddca5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c7ddca54c15c33fd48adbc2fb6fdc4edcc830beb))
- **proto:** use correct terminology ([721b0b0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/721b0b078b8e87c17e457a1a28ba0b3166010a4c))

### [0.37.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.8...0.37.9) (2022-10-07)

### Features

- **proto:** use correct terminology ([721b0b0](https://github.com/WhitehawkCEC/whitehawk-proto/commit/721b0b078b8e87c17e457a1a28ba0b3166010a4c))

### [0.37.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.7...0.37.8) (2022-10-07)

### Features

- **proto:** prefer to use `slug` ([c3837a4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c3837a468ca206586fe0af6e23a83ff776022f8d))
- **proto:** prefer to use `slug` ([cbf19d3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/cbf19d37c9f41e96feee8b4e017619da9b6d8c8a))
- **proto:** prefer to use `slug` ([68d10b1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/68d10b109a96ed7bafdfbab4f0c63fd99cdc5af4))
- **proto:** prefer to use `slug` ([b511c9e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/b511c9e33648cabb1ccf88c4961226466c88e59c))
- **proto:** remove unused resource `AccountId` ([c7ddca5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/c7ddca54c15c33fd48adbc2fb6fdc4edcc830beb))

### [0.37.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.6...0.37.7) (2022-10-06)

### Features

- add `SupplyWisdomConfig` message ([8bfdfa9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8bfdfa9535439f9cfa56acdaaa52c47e8267ed13))
- **proto:** add bitsight config v2 message ([342fc85](https://github.com/WhitehawkCEC/whitehawk-proto/commit/342fc85f475381db3e15088880ddd0b46d2b56cd))
- **proto:** add service for account BS config ([57ef4df](https://github.com/WhitehawkCEC/whitehawk-proto/commit/57ef4dfab37584ee82e5fa6fea9feb92a8254e3a))
- **proto:** add service for account SW config ([7f1c1f4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/7f1c1f413a67f0f303516eeefff6522262102e53))

### [0.37.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.5...0.37.6) (2022-10-06)

### Bug Fixes

- **proto:** change input parameter ([8fda035](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8fda035596bc8c3d75e4b702599b021f5dcd73ba))

## [0.37.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.11...0.37.0) (2022-10-06)

### ⚠ BREAKING CHANGES

- use rating service type 1 and 2 instead of name

### Features

- add one time as frequency enum value ([f822730](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f8227301c459afa560b0c9cf5e310de41de92661))
- add sixty day as freqeuncy ([59ecacc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/59ecacc2a62d60784837303eb0d91dd203cbc50c))
- add weekly to frequecy enum ([9c9cd24](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c9cd2496121e019cccd8994ce5b46af0402880e))
- **proto:** add `AccountId` message ([46185ea](https://github.com/WhitehawkCEC/whitehawk-proto/commit/46185ea0fa80d5efd0cc5b6bdc23aeff4eedb23a))
- **proto:** add `CyberOneConfig` message ([be024ed](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be024ed85dcf4eace2190fc7083e66393773d568))
- **proto:** add service for account BK config ([786eb59](https://github.com/WhitehawkCEC/whitehawk-proto/commit/786eb59c5a6fb433583c631aee5457833b8efe27))
- **proto:** add service for account C1 config ([4035585](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4035585f4badbb8aa6c1be2c8cac292ef3714d45))
- read assets by targetname and accountId ([555b8a9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/555b8a9e11a463e9f077570329ec6b075ec5cbfb))
- read assets by targetname and accountId ([595b8b4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/595b8b4a76630d9192859b8696121879760176cb))
- use rating service type 1 and 2 instead of name ([399528f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/399528f81a16f8aa37e577812147dc730cdba624))

### Bug Fixes

- **proto:** change input parameter ([8fda035](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8fda035596bc8c3d75e4b702599b021f5dcd73ba))

### [0.37.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.4...0.37.5) (2022-10-06)

### Features

- **proto:** add `AccountId` message ([46185ea](https://github.com/WhitehawkCEC/whitehawk-proto/commit/46185ea0fa80d5efd0cc5b6bdc23aeff4eedb23a))
- **proto:** add `CyberOneConfig` message ([be024ed](https://github.com/WhitehawkCEC/whitehawk-proto/commit/be024ed85dcf4eace2190fc7083e66393773d568))
- **proto:** add service for account BK config ([786eb59](https://github.com/WhitehawkCEC/whitehawk-proto/commit/786eb59c5a6fb433583c631aee5457833b8efe27))
- **proto:** add service for account C1 config ([4035585](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4035585f4badbb8aa6c1be2c8cac292ef3714d45))

### [0.37.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.3...0.37.4) (2022-10-06)

### Features

- read assets by targetname and accountId ([555b8a9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/555b8a9e11a463e9f077570329ec6b075ec5cbfb))
- read assets by targetname and accountId ([595b8b4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/595b8b4a76630d9192859b8696121879760176cb))

### [0.37.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.2...0.37.3) (2022-10-06)

### Features

- add one time as frequency enum value ([f822730](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f8227301c459afa560b0c9cf5e310de41de92661))

### [0.37.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.1...0.37.2) (2022-10-06)

### Features

- add weekly to frequecy enum ([9c9cd24](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9c9cd2496121e019cccd8994ce5b46af0402880e))

### [0.37.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.37.0...0.37.1) (2022-10-06)

### Features

- add sixty day as freqeuncy ([59ecacc](https://github.com/WhitehawkCEC/whitehawk-proto/commit/59ecacc2a62d60784837303eb0d91dd203cbc50c))

## [0.37.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.10...0.37.0) (2022-10-06)

### ⚠ BREAKING CHANGES

- use rating service type 1 and 2 instead of name

### Features

- **proto:** add read service ([da3aea1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/da3aea188584094a51a6cf03f2a1fe2c62ee9716))
- use rating service type 1 and 2 instead of name ([399528f](https://github.com/WhitehawkCEC/whitehawk-proto/commit/399528f81a16f8aa37e577812147dc730cdba624))

### [0.36.11](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.10...0.36.11) (2022-10-06)

### Features

- **proto:** add read service ([da3aea1](https://github.com/WhitehawkCEC/whitehawk-proto/commit/da3aea188584094a51a6cf03f2a1fe2c62ee9716))

### [0.36.10](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.9...0.36.10) (2022-10-05)

### Features

- **proto:** consistent variable name ([12cf100](https://github.com/WhitehawkCEC/whitehawk-proto/commit/12cf10095a02008dd056aac3a4f9cd74618256df))

### [0.36.9](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.8...0.36.9) (2022-10-05)

### Features

- **proto:** rename `CyberRiskScorecardToCyberOne` ([1cf76f3](https://github.com/WhitehawkCEC/whitehawk-proto/commit/1cf76f37c493bc41a9be0577cff5fcf3ca3508ca))

### [0.36.8](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.7...0.36.8) (2022-10-05)

### Features

- no errors on buf lint ([40ee0bb](https://github.com/WhitehawkCEC/whitehawk-proto/commit/40ee0bb3c9a1737702ebd7de8d843ff36a2e5389))

### [0.36.7](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.6...0.36.7) (2022-10-05)

### Features

- add accounts id for job request ([d45dfc9](https://github.com/WhitehawkCEC/whitehawk-proto/commit/d45dfc9735130c71fd7c7d16f0bc9342e6700ce3))
- **proto:** add `job_id` to `CreateRequest` ([f9c29f4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f9c29f46788584f9e3d5fe43de025609295f3e1d))
- use slug instead of string ([a15e2f4](https://github.com/WhitehawkCEC/whitehawk-proto/commit/a15e2f433e78d585947f103cfaf0f8164c56468b))

### [0.36.6](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.5...0.36.6) (2022-10-05)

### [0.36.5](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.4...0.36.5) (2022-10-05)

### [0.36.4](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.3...0.36.4) (2022-10-05)

### [0.36.3](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.2...0.36.3) (2022-10-05)

### [0.36.2](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.1...0.36.2) (2022-10-05)

### Features

- shcedule use range and frequency ([bb1cb0e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/bb1cb0eb9c3e907b0b240deefc9f167afa86fea9))

### [0.36.1](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.36.0...0.36.1) (2022-10-05)

### Bug Fixes

- **proto:** reverse `source_id` and `target_id` ([271ba4d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/271ba4d5cc209790dc2a086cec5675eace752ba4))

## [0.36.0](https://github.com/WhitehawkCEC/whitehawk-proto/compare/0.35.2...0.36.0) (2022-10-05)

### ⚠ BREAKING CHANGES

- **proto:** add services for `Read` and `List`
- **proto:** create request uses new `Job`

### Features

- **proto:** add message for `AccountInfo` ([f58303b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/f58303b5d1c2a23dae1d87845971a1b6987fa09c))
- **proto:** add message for `BitsightCompanyInfo` ([828c978](https://github.com/WhitehawkCEC/whitehawk-proto/commit/828c978ab501704b89ec18c1b52c9dfd663cfd85))
- **proto:** add message for `CyberOneAsset` ([9e9b69d](https://github.com/WhitehawkCEC/whitehawk-proto/commit/9e9b69d5e39e3e8b9dbbc170a73d315a2641b2b6))
- **proto:** add message for `SupplyWisdomAsset` ([719451b](https://github.com/WhitehawkCEC/whitehawk-proto/commit/719451b1de8163a85fb6353c0824b7b5bd78be9b))
- **proto:** add message for `SupplyWisdomTarget` ([44e35f5](https://github.com/WhitehawkCEC/whitehawk-proto/commit/44e35f57470ff37dc1462fdd18869d544d5c865c))
- **proto:** add messages for `Job` ([e1edecf](https://github.com/WhitehawkCEC/whitehawk-proto/commit/e1edecf82427bd924008422015833b218b9b839c))
- **proto:** add services for `Read` and `List` ([8a0bee2](https://github.com/WhitehawkCEC/whitehawk-proto/commit/8a0bee28aa1d1f9d017e29e3785618746be503dc))
- **proto:** create request uses new `Job` ([4dc790e](https://github.com/WhitehawkCEC/whitehawk-proto/commit/4dc790ec89a2e1e7306fd17a896e55bfcdff9fc4))

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
