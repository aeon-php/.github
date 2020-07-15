# Contributing 🥰

If you are reading this we are already greateful for your time! 

## Development 💻

All requirements about dependencies are listed in composer.json file. Please make sure that 
your development environmnent meet all requirements about PHP and extensions.

## Tests & Metrics 📊

Before opening pull request please run whole test suite locally using `composer build`. 

Code Coverage & Type Coverage - we expect both metrics to stay at 100% level. 

## Coding Standards ⌨️

Coding standards across all aeon libraries are unified and automated, you just need execute `composer cs:php:fix` from CLI.

## Versioning 🗂

All aeon libraries are following https://semver.org/. Latest unreleased version is always represented by the default branch. 
For example if default branch is `2.x` it means that the next stable release is going to be `2.0.0` and current stable release is somewhere 
between `1.0.0` and `2.0.0`. 

Our plan is to support at least 3 stable versions at time. 
Bug fixes should be sent to the latest one and then if possible to the 2 older versions. 

## Changelog 📝

Don't forget to update CHANGELOG.md file according to [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) guidelines.  

## Questions 🔍

Feel free to open issue with any questions you have regarding development. 

