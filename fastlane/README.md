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
## iOS
### ios test
```
fastlane ios test
```
Run tests
### ios screenshots
```
fastlane ios screenshots
```
Take screenshots
### ios build
```
fastlane ios build
```
Build application
### ios upload
```
fastlane ios upload
```
Upload metadata, screenshots and binary
### ios beta
```
fastlane ios beta
```
Push a new beta build to Testflight
### ios release
```
fastlane ios release
```
Run tests, take screenshots, upload deliver file, upload app

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).