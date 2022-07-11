# flutter_google_places_hoc081098 changelog

## 1.1.0 - Jun 20, 2022

- Update dependencies
  - `google_api_headers: ^1.3.0`.
  - `rxdart: ^0.27.4`.
  - `rxdart_ext: ^0.2.2`.

- Update `Flutter` constraint to `'>=2.8.0'`.

## 1.0.1 - Jan 24, 2022

- Change Dart SDK constraint to `>=2.14.0 <3.0.0` and Flutter constraint to `>=2.5.0`.

- Update dependencies to latest release
    - `rxdart: ^0.27.3`
    - `google_api_headers: ^1.1.1`
    - `http: ^0.13.4`

- Add `insetPadding` and `backArrowIcon` field (thanks to [@corentingiraud](https://github.com/corentingiraud)).
    - `insetPadding`: used to configure the padding around the dialog in overlay mode.
    - `backArrowIcon`: used to configure the back arrow icon.

- Refactor internal implementation.

- Internal: migrated from `pedantic` to `lints` and `flutter_lints`.

## 1.0.0-nullsafety.5 - Sep 23, 2021

- Set Flutter constraint `>=2.2.0`.

## 1.0.0-nullsafety.4 - Jul 29, 2021

- Add `Color? cursorColor` param to `PlacesAutocomplete.show` and `PlacesAutocompleteWidget`:

## 1.0.0-nullsafety.3 - Jul 29, 2021

- Update dependencies to latest release
    - `rxdart: ^0.27.1`
    - `google_api_headers: ^1.1.0`

- Add two params to `PlacesAutocomplete.show` and `PlacesAutocompleteWidget`:
    - `InputDecoration? textDecoration`
    - `TextStyle? textStyle`

## 1.0.0-nullsafety.2 - May 9, 2021

- Update dependencies to latest release
    - `google_maps_webservice: ^0.0.20-nullsafety.5`
    - `http: ^0.13.3`
    - `rxdart: ^0.27.0`
    - `listenable_stream: ^1.1.0`

## 1.0.0-nullsafety.1 - Apr 02, 2021

- Add `headers` param to `PlacesAutocomplete.show`, `PlacesAutocompleteWidget`, `PlacesAutocompleteField`
  and `PlacesAutocompleteFormField`.
- Change `apiKey` to nullable string (when using a proxy to request Google APIs, the `apiKey` is added on the proxy
  itself, consequently the `apiKey` should be `null`) (thanks to [@corentingiraud](https://github.com/corentingiraud)).

## 1.0.0-nullsafety.0 - Mar 18, 2021

- Initial version of `flutter_google_places_hoc081098`. Forked
  from [fluttercommunity/flutter_google_places](https://github.com/fluttercommunity/flutter_google_places).
- Opt into **null safety**.
- Sdk constraints: `>=2.12.0 <3.0.0`.
- Compatible with **flutter 2.0.0 stable**.
- Updated dependencies to latest release.
- Refactoring by using **RxDart** for more power.
- Fixed many issues.
- Applied [pedantic](https://pub.dev/packages/pedantic).
- Refactored example, migrated it to Android v2 embedding.

----------

# [fluttercommunity/flutter_google_places](https://github.com/fluttercommunity/flutter_google_places/blob/master/CHANGELOG.md) changelog

## 0.2.8

- Fix pub.dev complaints
    - Remove unsecure links
    - Replace deprecated `autovalidate` bool with `AutovalidateMode`
    - Formatted with dartfmt

## 0.2.7

- Add expected label behaviour to PlacesAutocompleteField (PR #108)
- Auto select text (PR #109)
- Add to support app restricted API keys (PR #136)
- Replaced deprecated `ancestorStateOfType` method (PR #141)
- Updating rxdart version in pubspec.yaml (PR #143)

## 0.2.6

- Fix error on select place
- Fix bug where `controller.text` is not properly updated
- Fix issue when close the widget and "_queryBehavior" is trying to add text

## 0.2.5

- Updates rxdart to 0.24.0
- Updates google_maps_webservice to 0.0.16

## 0.2.4

- Added support for flutter web
- Update rxdart
- Add overlayBorderRadius parameter
- Add startText parameter

## 0.2.3

- Update rxdart and google_maps_webservice

## 0.2.0

- Better text theme for text input
- Allow proxyUrl with `proxyBaseUrl` and override http client with `httpClient`

## 0.1.4

- Rename footer to logo to be less confusing

## 0.1.3

- Update rxdart

## 0.1.2

- Fix dark mode

## 0.1.1

- Fix icons quality
- Fix input border when custom theme

## 0.1.0

- Update sdk and fix warnings

## 0.0.5

- Fix usage of radius

## 0.0.4

- Open widgets to create your own UI
- Add onError callback

## 0.0.3

- Add padding for overlay on iOS

## 0.0.2

- Update google_maps_webservice to ^0.0.3
- Fix placeholder position
- Fix keyboard clipping on overlay

## 0.0.1

- Initial version
