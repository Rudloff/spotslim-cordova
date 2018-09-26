# SpotSlim Cordova app

This is a port of [SpotSlim](https://github.com/Rudloff/spotslim) to Android using [Cordova](https://cordova.apache.org/).

It uses [Crosswalk](https://crosswalk-project.org/) to embed its own WebKit because older Android webviews to support EME correctly.

## Setup

```bash
yarn install
cordova prepare
cordova build
```

## "Failed to initialize player" error

If you get this error, it probably means that your version of Android does not include [Widevine](https://www.widevine.com/) so it can't play DRM content.
