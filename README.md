Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/22.1.0/appcompat-v7-22.1.0.aar`

Requires (to compile):<br/>
`Android 5.1 (API 22) SDK Platform`

Subversion checkout URL:<br/>
https://github.com/dandar3/android-support-v7-appcompat/tags/22.1.0

Known issues:
* Android AAPT Problem (3 items):
  * `abc_alert_dialog_material.xml` <br/>
`removing attribute http://schemas.android.com/apk/res/android:layout_marginEnd from ...`<br/>
`removing attribute http://schemas.android.com/apk/res/android:layoutDirection from ...`<br/>
`removing attribute http://schemas.android.com/apk/res/android:textAlignment from ...`<br/>

Solutions:

* Force use of SDK Build Tools 21.1.2 with AppCompat library project in project.properties.

  @see https://code.google.com/p/android/issues/detail?id=164673#c11 and  https://developer.android.com/tools/revisions/build-tools.html
 
or

* Set Eclipse `Preferences` > `Android` > `Build` > `Build output` to `Silent` or `Normal` instead of `Verbose`.
  @see https://code.google.com/p/android/issues/detail?id=164673#c18
