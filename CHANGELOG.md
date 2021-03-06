# CHANGELOG

`OpenLocate-iOS` adheres to [Semantic Versioning](http://semver.org/).

## [1.2.1](https://github.com/OpenLocate/openlocate-ios/tag/1.2.1)

#### Fix

- Tweak scheme name so it doesn't overlap with the Example app

## [1.2.0](https://github.com/OpenLocate/openlocate-ios/tag/1.2.0)

#### Added

- Add ability to collect location data while in foreground
- Add ability to only collect location data with "While In Use" location authorization

## [1.1.1](https://github.com/OpenLocate/openlocate-ios/tag/1.1.1)

#### Fixed

- Fix duplicate location data being sent.

## [1.1.0](https://github.com/OpenLocate/openlocate-ios/tag/1.1.0)

#### Added

- Add ability to send location data to mulitple URL endpoints
- Add ability to set the location data transmission interval via `Configuration` class
- Change default transmission interval to 6 hours instead of 8 hours

#### Fixed

- Fix duplicate location data being sent. (#71)

---

## [1.0.0](https://github.com/OpenLocate/openlocate-ios/tag/1.0.0)

#### Added

- A CHANGELOG to the project documenting each official release.
- iOS 9 Support
- Server communication is now done on a background thread
- Add ability for more location updates via Background Fetch
- Add ability for more location updates via Circular Regions (Geofence)

#### Fixed

- Removed miscellaneous project warnings

---

## 0.1.0

Initial release!
