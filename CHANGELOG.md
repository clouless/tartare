<a name="1.2.1"></a>
## [1.2.1](https://github.com/telefonicaid/tartare/compare/v1.2.0...v1.2.1) (2017-04-07)


### Bug Fixes

* Built-in reporters are not being loaded on Windows (Fixes #38) ([bea24fa](https://github.com/telefonicaid/tartare/commit/bea24fa)), closes [#38](https://github.com/telefonicaid/tartare/issues/38)



<a name="1.2.0"></a>
# [1.2.0](https://github.com/telefonicaid/tartare/compare/v1.1.3...v1.2.0) (2016-11-02)


### Bug Fixes

* Support any field in the Typescript declaration of the Variant interface ([c90e9c1](https://github.com/telefonicaid/tartare/commit/c90e9c1))

### Features

* Add support for third party reporters ([@sumeet70](https://github.com/sumeet70)) ([ddba1ab](https://github.com/telefonicaid/tartare/commit/ddba1ab))



<a name="1.1.3"></a>
## [1.1.3](https://github.com/telefonicaid/tartare/compare/v1.1.2...v1.1.3) (2016-10-03)


### Bug Fixes

* TypeScript declarations do not support the variant argument in scenarios ([288e676](https://github.com/telefonicaid/tartare/commit/288e676))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/telefonicaid/tartare/compare/v1.1.1...v1.1.2) (2016-09-27)


### Bug Fixes

* Improve TypeScript declarations ([29980ce](https://github.com/telefonicaid/tartare/commit/29980ce))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/telefonicaid/tartare/compare/v1.1.0...v1.1.1) (2016-09-19)


### Bug Fixes

* Documentation points to a non-working location for typings installation ([977e144](https://github.com/telefonicaid/tartare/commit/977e144))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/telefonicaid/tartare/compare/v1.0.3...v1.1.0) (2016-09-19)


### Bug Fixes

* `this` is not working on steps when the function is wrapped into a promise ([d722313](https://github.com/telefonicaid/tartare/commit/d722313))

### Features

* Add declarations to use Tartare with TypeScript ([ca80350](https://github.com/telefonicaid/tartare/commit/ca80350))



<a name="1.0.3"></a>
## [1.0.3](https://github.com/telefonicaid/tartare/compare/v1.0.2...v1.0.3) (2016-09-09)


### Bug Fixes

* When steps or hooks return promises, Tartare is not waiting for them to be resolved ([ab400a3](https://github.com/telefonicaid/tartare/commit/ab400a3))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/telefonicaid/tartare/compare/v1.0.1...v1.0.2) (2016-07-13)


### Bug Fixes

* Some hooks throw error when used with protractor-tartare (Fixes #35) ([d605df2](https://github.com/telefonicaid/tartare/commit/d605df2)), closes [#35](https://github.com/telefonicaid/tartare/issues/35)



<a name="1.0.1"></a>
## [1.0.1](https://github.com/telefonicaid/tartare/compare/v1.0.0...v1.0.1) (2016-07-08)


### Bug Fixes

* Hooks belonging to features, scenarios or variants marked as minorBug are sometimes executed (Fixes #34) ([f334806](https://github.com/telefonicaid/tartare/commit/f334806)), closes [#34](https://github.com/telefonicaid/tartare/issues/34)



<a name="1.0.0"></a>
# [1.0.0](https://github.com/telefonicaid/tartare/compare/v0.9.0...v1.0.0) (2016-05-05)


### Features

* Add a new `interactive` option to allow disabling interactive features ([e2b58f5](https://github.com/telefonicaid/tartare/commit/e2b58f5))
* Allow setting Tartare options through env vars. ([015c658](https://github.com/telefonicaid/tartare/commit/015c658))
* Support reporter-specific parameters for the gherkin-md reporter (output and bugidLink) ([8eea5b9](https://github.com/telefonicaid/tartare/commit/8eea5b9))



