# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixes
- Update OneSignal-Android-SDK with latest version from upstream [RNMT-3314](https://outsystemsrd.atlassian.net/browse/RNMT-3314)
- Use android support versions 26.1.+ when compileSDK is prior to version 28 [RNMT-3266](https://outsystemsrd.atlassian.net/browse/RNMT-3266)

## [2.4.5-OS3] - 2019-09-10
### Fixes
- Fixed compatibility with plugins that make use of Google Services [RNMT-3264](https://outsystemsrd.atlassian.net/browse/RNMT-3264)

## [2.4.5-OS2] - 2019-04-12
### Changes
- **BREAKING:** Update used version of Android support libraries to 28 [RNMT-2726](https://outsystemsrd.atlassian.net/browse/RNMT-2726)
- Update usage of compile to implementation in gradle dependencies [RNMT-2655](https://outsystemsrd.atlassian.net/browse/RNMT-2655)

## [2.4.5-OS1] - 2019-03-26
### Additions
- Update prepare_drawables hook to compute resource paths based on cordova engine from project [RNMT-2651](https://outsystemsrd.atlassian.net/browse/RNMT-2651)

## [2.4.5-OS] - 2018-12-06
### Changes
- Merge upstream (2.4.5) into OutSystems branch

[Unreleased]: https://github.com/OutSystems/OneSignal-Cordova-SDK/compare/2.4.5-OS3...HEAD
[2.4.5-OS3]: https://github.com/OutSystems/OneSignal-Cordova-SDK/compare/2.4.5-OS2...2.4.5-OS3
[2.4.5-OS2]: https://github.com/OutSystems/OneSignal-Cordova-SDK/compare/2.4.5-OS1...2.4.5-OS2
[2.4.5-OS1]: https://github.com/OutSystems/OneSignal-Cordova-SDK/compare/2.4.5-OS...2.4.5-OS1
[2.4.5-OS]: https://github.com/OutSystems/OneSignal-Cordova-SDK/compare/2.3.2-OS2...2.4.5-OS
