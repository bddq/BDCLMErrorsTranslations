BDCLMErrorsTranslations
===================================

This repo will help developers to get the best translation for any CoreLocation Manager errors.

### How to use ?
Just import each _BDCLMErrors.strings_ files in your localized .lproj project folders.

In your code you can now use `NSLocalizedStringFromTable(@"Deferred mode does not support distance filters.", @"BDCLMErrors", nil);` with the provided message for the error.


### Notes
Each keys are the english message provided by Apple in the SDK documentation. Corresponding CLLocationManager error codes are in comments in .strings files

### Todo
- An example app.
- Add more translations.