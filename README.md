# Quetta Hotel Android App

A simple offline Android WebView billing app. It supports editable menu items and prices, order totals, local sales history, date-filtered reports, CSV export, and a printable receipt view.

## Build
The GitHub Actions workflow builds a debug APK when code is pushed or when manually run from the Actions tab. The generated artifact is named `Quetta-Hotel-APK`.

## Notes
- Minimum Android version: Android 6.0 (API 23); Android 10 is supported.
- Sales and menu data are stored locally on the device/browser storage. Export CSV backups regularly.
- Receipt printing opens Android's available print flow; Bluetooth thermal printer support depends on the exact printer model and Android print service and must be tested.
