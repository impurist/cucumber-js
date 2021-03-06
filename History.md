# Cucumber.js changelog

## [v0.1](https://github.com/cucumber/cucumber-js/compare/v0.0.1...master)

### [v0.1.2](https://github.com/cucumber/cucumber-js/compare/v0.1.1...v0.1.2)

#### New features

* Add failure reporting to the progress formatter (#20 Julien Biezemans)



### [v0.1.1](https://github.com/cucumber/cucumber-js/compare/v0.1.0...v0.1.1)

#### New features

* Publish Cucumber.js to NPM as [`cucumber`](http://search.npmjs.org/#/cucumber) (Julien Biezemans)

#### Changed features

* Throw a clearer exception on missing feature argument (CLI) (Julien Biezemans)

#### Internals and tests

* Unify and clean up js-specific features and step definitions (#21 Julien Biezemans)



### [v0.1.0](https://github.com/cucumber/cucumber-js/compare/v0.0.1...v0.1.0)

#### New features

* Add cucumber.js executable (Julien Biezemans)
* Handle step failures (#6 Julien Biezemans)
* Add the progress formatter (#16 Julien Biezemans)
* Add support for pending steps (#18 Julien Biezemans)
* Add support for undefined steps (#19 Julien Biezemans)

#### Changed features

* Update web example to use the new progress formatter (Julien Biezemans)

#### Fixes

* Fix asynchronous step definition callbacks (#1 Julien Biezemans)
* Fix stepResult.isSuccessful call in ProgressFormatter (Julien Biezemans)
* Load Gherkin properly in browsers (Julien Biezemans)
* Remove calls to console.log in web example (Julien Biezemans)

#### Internals and tests

* Pass against core.feature in its new form, both with the Cucumber-ruby/Aruba pair and cucumber-js itself (Julien Biezemans)
* Refactor cucumber-features JS mappings (Julien Biezemans)
* Refactor js-specific features (Julien Biezemans)
* Rename PyString to DocString (#15 Julien Biezemans)
* Update Gherkin to 2.4.0 (Julien Biezemans)
* Modularize the project and use browserify.js to serve a single JS file to browsers. (#3 Julien Biezemans)
* Rename Cucumber.Types to Cucumber.Type (Julien Biezemans)
* Use progress formatter in cucumber-features (#17 Julien Biezemans)



## [v0.0](https://github.com/cucumber/cucumber-js/tree/v0.0.1)

### [v0.0.1](https://github.com/cucumber/cucumber-js/tree/v0.0.1)

* Emerge Cucumber.js with bare support for features, scenarios and steps. It does not handle several Gherkin elements nor failures yet. (Julien Biezemans)
