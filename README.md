# Git Commit Msg

Just add this file within your git project .git/hooks

Based on the [karma-runner](https://karma-runner.github.io/6.4/dev/git-commit-msg.html)

- feat: for a new feature for the user, not a new feature for build script. Such commit will trigger a release bumping a MINOR version.
- fix: for a bug fix for the user, not a fix to a build script. Such commit will trigger a release bumping a PATCH version.
- perf: for performance improvements. Such commit will trigger a release bumping a PATCH version.
- docs: for changes to the documentation.
- style: for formatting changes, missing semicolons, etc.
- refactor: for refactoring production code, e.g. renaming a variable.
- test: for adding missing tests, refactoring tests; no production code change.
- build: for updating build configuration, development tools or other changes irrelevant to the user.
- conf:

