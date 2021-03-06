fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
### bump_badge
```
fastlane bump_badge
```
Bump and badge.

----

## Android
### android build
```
fastlane android build
```
Build the release APK.
### android deploy
```
fastlane android deploy
```
Build the release APK, then upload to App Center.

----

## iOS
### ios certificates
```
fastlane ios certificates
```
Fetch certificates and provisioning profiles.
### ios deploy
```
fastlane ios deploy
```
Fetch certificats then build the release IPA and upload to App Center.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
