Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/23.1.0/appcompat-v7-23.1.0.aar`

Requires (to compile):<br/>
`Android 6.0 (API 23) SDK Platform`

Requires library:</br>
* [dandar3/android-support-v4](https://github.com/dandar3/android-support-v4)

Subversion checkout URL:<br/>
* https://github.com/dandar3/android-support-v7-appcompat/tags/23.1.0

References:
* https://developer.android.com/tools/support-library/index.html#revisions
* https://developer.android.com/tools/support-library/features.html#v7-appcompat

Known issues:
* Android AAPT Problem (2 items):
  * `abc_alert_dialog_material.xml` <br/>
`removing attribute http://schemas.android.com/apk/res/android:textAlignment ...`<br/>
`removing attribute http://schemas.android.com/apk/res/android:layoutDirection from ...`<br/>

Solutions:
* Force use of SDK Build Tools 21.1.2 with AppCompat library project in project.properties.<br/>
  @see https://code.google.com/p/android/issues/detail?id=164673#c11 and  https://developer.android.com/tools/revisions/build-tools.html
 
or

* Set Eclipse `Preferences` > `Android` > `Build` > `Build output` to `Silent` or `Normal` instead of `Verbose`.<br/>
  @see https://code.google.com/p/android/issues/detail?id=164673#c18
