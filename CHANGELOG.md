## [1.3.4](https://github.com/scribd/terraform-aws-datadog/compare/v1.3.3...v1.3.4) (2020-11-03)


### Bug Fixes

* use proper provider source for datadog ([6f292e7](https://github.com/scribd/terraform-aws-datadog/commit/6f292e7d0b2c277c9751dce1c9806c47b1f22b89))

## [1.3.3](https://github.com/scribd/terraform-aws-datadog/compare/v1.3.2...v1.3.3) (2020-11-03)


### Bug Fixes

* make minimum terraform version requirement an actual minimum ([f39e5e6](https://github.com/scribd/terraform-aws-datadog/commit/f39e5e69bf80b47cd56ce44f4e38e54d114289b9))
* use a range of versions to limit the required versions ([d98714a](https://github.com/scribd/terraform-aws-datadog/commit/d98714af4bc1ffe55d9483eaaf0d8032d8501826))

## [1.3.2](https://github.com/scribd/terraform-aws-datadog/compare/v1.3.1...v1.3.2) (2020-10-29)


### Bug Fixes

* Add cloudtrail:LookupEvents IAM rights ([#19](https://github.com/scribd/terraform-aws-datadog/issues/19)) ([bba2d91](https://github.com/scribd/terraform-aws-datadog/commit/bba2d9104715b5559a8edf8bc8cd445313abaacb))

## [1.3.1](https://github.com/scribd/terraform-aws-datadog/compare/v1.3.0...v1.3.1) (2020-10-25)


### Bug Fixes

* Add missing IAM permissions for new version of log forwarder  ([#18](https://github.com/scribd/terraform-aws-datadog/issues/18)) ([b741a4b](https://github.com/scribd/terraform-aws-datadog/commit/b741a4b565b8ce54b545521700ff7406495df34f))

# [1.3.0](https://github.com/scribd/terraform-aws-datadog/compare/v1.2.1...v1.3.0) (2020-09-02)


### Features

* **log forwarding:** support DdSite option + upgrade default CF template version used ([1e0f7bc](https://github.com/scribd/terraform-aws-datadog/commit/1e0f7bc88f6fef7e0ab3ffc4c11a83daed60e09b))

## [1.2.1](https://github.com/scribd/terraform-aws-datadog/compare/v1.2.0...v1.2.1) (2020-08-10)


### Bug Fixes

* use name_prefix instead of static name to avoid ([36a8077](https://github.com/scribd/terraform-aws-datadog/commit/36a8077e4c527c47be04b423b1bdee0e0bc721fe))

# [1.2.0](https://github.com/scribd/terraform-aws-datadog/compare/v1.1.0...v1.2.0) (2020-07-02)


### Features

* **aws integration:** add options to specify ignored regions and tags to filter out EC2 instances ([#10](https://github.com/scribd/terraform-aws-datadog/issues/10)) ([452a995](https://github.com/scribd/terraform-aws-datadog/commit/452a995d60b06fcef38a41e3b2445097b27e71f6))

# [1.1.0](https://github.com/scribd/terraform-aws-datadog/compare/v1.0.0...v1.1.0) (2020-06-29)


### Features

* add DdApiKey dummy value for CF stack ([c6c7ddd](https://github.com/scribd/terraform-aws-datadog/commit/c6c7ddd201ca921362cfe995544661f8e23d2989))
* **CF:** use datadog supplied CF stack template ([1ecdb22](https://github.com/scribd/terraform-aws-datadog/commit/1ecdb2211b40ac8ceb4299c2f24ed603c1801942))

# 1.0.0 (2020-04-27)


### Bug Fixes

* Also set conditional for ForwarderRole ([d0ecc10](https://github.com/scribd/terraform-aws-datadog/commit/d0ecc10f3bba66be1e236486d4a6fa8b440cf9d4))
* use AWS Secrets Manager instead of supplying API Key parameter ([647e8e9](https://github.com/scribd/terraform-aws-datadog/commit/647e8e9dd8d8d0dc953f64c86fed25ceebf1fead))


### Features

* add EXCLUDE_AT_MATCH env variable to datadog ([05bae6a](https://github.com/scribd/terraform-aws-datadog/commit/05bae6aa446ff485c1f231adcb72623944cbd11f))
* Update AWS DD Forwarder to v3.5.0 ([797da3a](https://github.com/scribd/terraform-aws-datadog/commit/797da3a8a50cbd9b3f09677fc3e1639ffbad7187))

# CHANGELOG

<!--- next entry here -->

- Initial public release
