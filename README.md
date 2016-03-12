Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/23.2.1/appcompat-v7-23.2.1.aar`

Requires (to compile):<br/>
`Android 6.0 (API 23) SDK Platform`

Requires library:</br>
* [dandar3/android-support-v4](https://github.com/dandar3/android-support-v4)

Subversion checkout URL:<br/>
* https://github.com/dandar3/android-support-v7-appcompat/tags/23.2.1

References:
* https://developer.android.com/tools/support-library/index.html#revisions
* https://developer.android.com/tools/support-library/features.html#v7-appcompat
* https://plus.google.com/+AndroidDevelopers/posts/BZgzpAqkd8G
* https://android-developers.blogspot.com/2016/02/android-support-library-232.html

Known issue:
* Android AAPT Problem (1 item):
  * `abc_alert_dialog_button_bar_material.xml` <br/>
`removing attribute http://schemas.android.com/apk/res/android:layoutDirection from ...`<br/>

Solution:
* Set Eclipse `Preferences` > `Android` > `Build` > `Build output` to `Normal` or `Silent` instead of `Verbose`.<br/>
  @see https://code.google.com/p/android/issues/detail?id=164673#c18