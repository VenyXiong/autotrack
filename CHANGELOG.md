# Changelog

This document lists the changes between each minor and patch versions. For changes between major versions, see the [Upgrade Reference](/docs/upgrading.md)

### 2.2.0 (2017-03-28)

- Update the `eventTracker` `ga-on` attribute to accept multiple (comma-separate) event types.
- Update the `hitFilter` option to be invoked with the DOM event associated with the interaction (when applicable).

### 2.1.1 (2017-03-15)

- Remove `.babelrc` to prevent conflicts when using `babel-loader`.

### 2.1.0 (2017-03-06)

- Fix a double-pageview bug on pageload after session timeout (#150).
- Add a visibleThreshold option to pageVisibilityTracker (#148).

### 2.0.4 (2017-02-24)

- Fix CI build failure.

### 2.0.3 (2017-02-24)

- Fix incorrect package version.

### 2.0.2 (2017-02-23)

- Fix errors accessing localStorage in some browsers (#145).

### 2.0.1 (2017-02-06)

- Fix incorrect Closure Compiler externs.

### 2.0.0 (2017-02-02)

- See the [Upgrade Reference](/docs/upgrading.md) for a full list of changes.

## 1.1.0 (2016-10-18)

- Add impressionTracker methods to observe and unobserve elements (#111)

### 1.0.4 (2016-10-15)

- Prevent the withTimeout callback from firing twice

### 1.0.3 (2016-09-18)

- Update dom-utils for better shadow DOM support

### 1.0.2 (2016-09-18)

- Fix the autotrack warning and upgrade language
- Update dom-utils for better shadow DOM support

### 1.0.1 (2016-08-10)

- Upgrade dependencies to get third-party fixes

### 1.0.0 (2016-06-30)

- See the [Upgrade Reference](/docs/upgrading.md) for a full list of change.

### 0.6.5 (2016-04-13)

- Fix a history change bug in IE11 (#57)

### 0.6.4 (2016-03-30)

- Ensure only http(s) links are considered outbound (#44)
- Remove unnecessary caught errors (#42)
- Move the gaplugin assignment to the provide call (#36)
- Refactor tests to make fewer full page requests (#35)

### 0.6.3 (2016-03-15)

- Update the generated license text

### 0.6.2 (2016-03-07)

- Add a check to ensure the form action exists (#28)

### 0.6.1 (2016-02-26)

- Allow sourcing autotrack.js before the snippet (#24)

### 0.6.0 (2016-02-26)

- Remove the sessionDurationTracker (#21)

### 0.5.0 (2016-02-18)

- Make outbound link/form logic configurable (#3)

### 0.4.0 (2016-02-04)

- Initial public release
