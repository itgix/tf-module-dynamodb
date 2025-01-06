## [1.9.2](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.9.1...v1.9.2) (2023-12-06)


### Bug Fixes

* **delete-protection:** running the update-table command only if the value is different ([e04d8ac](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/e04d8acfee04c5643c8ac9d49f6a03b2f239287e))
* **empty:** empty change to trigger new module version ([31fa6a3](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/31fa6a3b53b483a2563651412f570913f972ac11))

## [1.9.1](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.9.0...v1.9.1) (2023-10-16)


### Bug Fixes

* **ENG-3213:** fix ttl_attribute usage with base module ([cebad89](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/cebad899d7586f918748ac77d86a384b11498d87))
* **ENG-3213:** make the attribute ttl_attribute as optional ([0212fa0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/0212fa0f9a3e6bc889e6cdf46396d20c06132617))
* **ENG-3213:** terraform format f ix ([e79d144](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/e79d144a34c63115704d100c9670c66931d6ffea))

# [1.9.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.8.2...v1.9.0) (2023-10-10)


### Bug Fixes

* **ENG-3213:** correct ttl_attribute typo ([264dd84](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/264dd84f97eb1c8526ea7ea4e6001c8ba5156227))


### Features

* **ENG-3213:** add support for optional TTL Attribute configuration if TTL_Enabled = True ([8465760](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/8465760fb20aaa0aba465402e60faaf02a5ee98f))

## [1.8.2](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.8.1...v1.8.2) (2023-09-27)


### Bug Fixes

* **replicas:** adding input variable for IAM role to assume for provisioner ([0f157bf](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/0f157bf4c95ae110d60343a2c1407fbe9dc6b184))

## [1.8.1](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.8.0...v1.8.1) (2023-09-26)


### Bug Fixes

* **replicas:** changing the interpreter in local-exec provisioner to shell ([ef658aa](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/ef658aa28bc067c265fbdedbf22676eb9b3bd504))

# [1.8.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.7.0...v1.8.0) (2023-09-26)


### Features

* **replicas:** adding custom provisioner to enable/disable delete protection to replicas ([04736c1](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/04736c155226089ec83d2ed48a4d8a46e6013629))
* **replicas:** adding missing null provider version ([f06da50](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/f06da507b8db01afc74b0455501bfead3f4a5bd2))
* **replicas:** executing provisioners for only global tables ([f77b007](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/f77b0074933963e6e9b7f48fd266c935057b4f7e))
* **replicas:** fixing the tf formating ([c2e9167](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/c2e91672270a20b02a212435b76182150ef2810c))

# [1.7.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.6.0...v1.7.0) (2023-09-11)


### Features

* **ED-7981:** Add delete protecion variable ([aa10e3e](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/aa10e3ec4b52e72a8add77348158943bfb9764d6))
* **ED-7981:** Update deletion protection to be optional ([bb73cb1](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/bb73cb16bd0f0593ea5c664bba9cade9d26a3ac7))
* **ED-7981:** Update README.md file ([5488772](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/5488772808b7d9948a4fefa3804fa67c6f28008f))

# [1.6.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.5.0...v1.6.0) (2023-09-06)


### Features

* **duplication-fix:** remove duplicate variables ([72bd48b](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/72bd48b386b9ad07285714cfa0740dd0e7d1fcb8))

# [1.5.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.4.0...v1.5.0) (2023-08-22)


### Features

* **OB-17529:** aws provider upgrade ([0572273](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/057227375df5aea5b7b741b6cd89e9b496861926))

# [1.4.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.3.0...v1.4.0) (2023-07-05)


### Features

* **CP-372:** Upgrade pre-commit and update readme ([5a0ba47](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/5a0ba47fe98a0623cac709a93a5bb4dea3842d9b))

# [1.3.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.2.0...v1.3.0) (2023-06-27)


### Bug Fixes

* **tflint:** one more fix ([5b16034](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/5b1603441c1b4df7ca458e38b0dcb6fe47827763))
* **tflint:** removing unused variable ([4a5a0b7](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/4a5a0b75accbac5f0cf96b9b7a5ae20c92e523c1))


### Features

* **global-tables:** adding stream_view_type value ([65cec65](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/65cec653bc5da8bd6c021905735f7f098676947b))
* **global-tables:** adding support for global tables ([070607d](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/070607db6dfe1afbf150097bba98955e2f57206e))
* **global:** fixing default value in readme ([00b8a9e](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/00b8a9e3ded74f95f050f030f5d08e7f7f033bd7))
* **global:** fixing tflint version ([91d2ba0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/91d2ba01c1f10f8070750d25147423d4d3ba3520))
* **global:** making table_type attribute optional ([8fb7d2b](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/8fb7d2b66ed25632cc97ca76bb867266575d4aa3))
* **global:** updating readme ([a362841](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/a362841b39e6d0e20fbdd44ee8cfb7400b58c67a))

# [1.2.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.1.0...v1.2.0) (2022-08-03)


### Features

* **module:** Update AWS provider version ([8c4d789](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/8c4d789cd2abf1125ccc12d9070618a1586b5d54))

# [1.1.0](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/compare/v1.0.0...v1.1.0) (2022-06-30)


### Features

* **ED-4621:** Update table name value to allow duplicated names ([b5ceef8](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/b5ceef88fa70e899bb66291120ad5af6c41f69ae))
* **ED-4621:** Update table name value to allow duplicated names ([b65207a](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/b65207a3ce6c40956911f1bb56f8cdf05ea0e1f2))

# 1.0.0 (2022-06-24)


### Features

* **ED-4622:** Added DynamoDB module ([40e85d6](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/40e85d6bcf05120702d7c87b4fa3ddb10e8328a5))
* **ED-4622:** Added DynamoDB module ([fe27a36](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/fe27a36250af3e417a33639d63597299f709df70))
* **ED-4622:** Added DynamoDB module ([f9dea48](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/f9dea480d01dd723a45a9d2c9f30bb3f65e814c2))
* **ED-4622:** Added DynamoDB module ([a4eeab4](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/a4eeab44f0d6d4b5464a7f0d66521c69ad05d736))
* **ED-4622:** Added DynamoDB module ([d637f6c](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/d637f6ca154f1c2064b0d007fb33c0944d8ede03))
* **ED-4622:** Create new DynamoDB module ([36837f4](https://gitlab.com/bango/modules/terraform/aws-dynamodb-table/commit/36837f4b169dd227aad2a27881fb7fa46fe6bbe8))
