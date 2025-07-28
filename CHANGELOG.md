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
  * **Kotlin upgrade to 1.8.22** (compatible with Java 17)
  * Updated Android Gradle Plugin to 8.0.2
  * Updated Gradle wrapper to 8.0
  * Updated compileSdkVersion and targetSdkVersion to 34
  * Replaced deprecated jcenter() with mavenCentral()
  * Added proper namespace declarations for Android
  * **Upgraded to Java 17 compatibility** (sourceCompatibility/targetCompatibility VERSION_17)
  * Updated example app dependencies (uuid to ^4.3.3, cupertino_icons to ^1.0.8)
  * Fixed deprecation warnings in test files
  * **Note:** Flutter 3.32.7 requires declarative plugins approach - see setup instructions