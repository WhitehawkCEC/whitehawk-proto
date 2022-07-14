# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

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
