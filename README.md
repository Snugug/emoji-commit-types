# emoji-commit-types

List of Emoji commit types, for semantic releases and great profit.

## Emoji

:new: `:new:`
- description: A new feature
- title: Features
- level: minor

:bug: `:bug:`
- description: A bug fix
- title: Bug Fixes
- level: patch

:memo: `:memo:`
- description: Documentation only changes
- title: Documentation
- level: patch

:art: `:art:`
- description: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- title: Code Styles
- level: patch

:gem: `:gem:`
- description: Changes that affect the user styling but not functionality
- title: User Styles
- level: minor

:dizzy: `:dizzy:`
- description: A code change that neither fixes a bug nor adds a feature
- title: Code Refactoring
- level: patch

:racehorse: `:racehorse:`
- description: A code change that improves performance
- title: Performance Improvements
- level: minor

:white_check_mark: `:white_check_mark:`
- description: Adding missing tests or correcting existing tests
- title: Tests
- level: patch

:wrench: `:wrench:`
- description: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- title: Builds
- level: patch

:green_heart: `:green_heart:`
- description: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- title: Continuous Integrations
- level: patch

:nut_and_bolt: `:nut_and_bolt:`
- description: Other changes that don't modify src or test files
- title: Chores
- level: patch

:crystal_ball: `:crystal_ball:`
- description: Experimental change to the codebase that may be changed later
- title: Experiments
- level: patch

:lock: `:lock:`
- description: A code change that improves security
- title: Security Improvements
- level: minor

:fire: `:fire:`
- description: Changes that have the net result of removing unneeded code but does not affect functionality
- title: Code Removals
- level: minor

:shirt: `:shirt:`
- description: A code change that fixes linting issues
- title: Lint Fixes
- level: minor

:boom: `:boom:`
- description: A code change that results in backwards-incompatible code
- title: Breaking Changes
- level: major

## Spec

Exports an object with a `types` key whose value is an object whose keys are type names and whose values are objects with key-value pairs such as `description` as string, optional `title` as string, etc. See [index.json](index.json). Any alternatives should follow the same spec.

## Etc.

Can be used with [kentcdodds/validate-commit-msg](https://github.com/kentcdodds/validate-commit-msg#types).
