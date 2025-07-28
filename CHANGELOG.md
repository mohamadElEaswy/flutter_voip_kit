## 0.0.1

* Use iOS CallKit and Android's Telecom library to create and receive calls with native functionality. e.g. Calls pop up on user's lock screen.

## 0.0.2

* Update package details

## 0.0.3

* optionally pass UUID when starting a call
* actions to FlutterVoipKit only require call's uuid to be known

# 0.0.4

* Android works with V1 too
* setup instructions

# 0.0.5
* Updated for Android 11 (https://developer.android.com/about/versions/11/privacy/permissions?authuser=1) See new Android setup requirements in README

# 0.0.6
* Bug fixes and improvements

# 0.0.7
* **Major modernization update:**
  * Updated Dart SDK constraint to >=3.0.0 <4.0.0
  * Updated Flutter constraint to >=3.10.0
  * Updated path_provider dependency to ^2.1.2
  * Updated Kotlin version to 1.7.10
  * Updated Android Gradle Plugin to 7.3.0
  * Updated Gradle wrapper to 7.5
  * Updated compileSdkVersion and targetSdkVersion to 33
  * Replaced deprecated jcenter() with mavenCentral()
  * Added proper namespace declarations for Android
  * Added Java 8 compatibility settings
  * Updated example app dependencies (uuid to ^4.3.3, cupertino_icons to ^1.0.8)
  * **Note:** Java 21 compatibility issue identified - may need to use Java 17 or update Gradle version for full compatibility