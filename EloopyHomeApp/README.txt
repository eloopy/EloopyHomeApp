Narwhal3 Android Studio project skeleton
---------------------------------------
Instructions:
1. Open Android Studio (Narwhal 3 or later).
2. Choose "Open" and select the folder: /mnt/data/Narwhal3
3. Android Studio may ask to upgrade Gradle or the Kotlin plugin: accept the recommended versions.
4. If a Gradle wrapper is missing, Android Studio will prompt to download the Gradle distribution automatically. That's normal.
5. Replace app/src/main/res/drawable/logo.png with your logo file (same name 'logo.png') if you want.
6. Build and Run on a device that supports biometric (fingerprint) authentication or an emulator configured accordingly.
Notes:
- The app requests INTERNET permission in the Manifest.
- The Apps Script URL used by the app is:
  https://script.google.com/macros/s/AKfycbwUL2GkSwAGMo7H8MJD1rDY-zXEjUr1jg8WEr0zB4EEX2QrQI6XDWQHofbgk5seVl_O5w/exec?password=letmesee
- Server responses: if response body == "0", an 'Access denied' alert is shown. Otherwise the response is saved under SharedPreferences key 'saved_ip'.
- Buttons are placeholders; implement camera/music behavior as needed.
