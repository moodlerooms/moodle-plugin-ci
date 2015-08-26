# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

The format of this change log follows the advice given at [Keep a CHANGELOG](http://keepachangelog.com).

## [Unreleased]
### Added
- `moodle-plugin-ci install` command.  This does all of the setup for testing.
- `moodle-plugin-ci behat` command.  Runs plugin Behat features.
- `moodle-plugin-ci phpunit` command.  Runs plugin PHPUnit tests.
- `moodle-plugin-ci phplint` command.  Lints PHP files in the plugin.
- `moodle-plugin-ci codechecker` command.  Run Moodle Code Checker on the plugin.
- `moodle-plugin-ci phpcpd` command.  Run PHP Copy/Paste Detector on the plugin.
- `moodle-plugin-ci phpmd` command.  Run PHP Mess Detector on the plugin.
- `moodle-plugin-ci jshint` command.  Run JSHint on the Javascript files in the plugin.
- `moodle-plugin-ci shifter` command.  Run YUI Shifter on plugin YUI modules.
- `moodle-plugin-ci csslint` command.  Lints the CSS files in the plugin.

[Unreleased]: https://github.com/moodlerooms/moodle-plugin-ci/commits/master