## android-support-v7-appcompat

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/24.1.1/appcompat-v7-24.1.1.aar`

**Requires:**<br/>
- `Android 7.0 (API 24) SDK Platform`
- [dandar3/android-support-v4](https://github.com/dandar3/android-support-v4)
- [dandar3/android-support-vector-drawable](https://github.com/dandar3/android-support-vector-drawable)
- [dandar3/android-support-animated-vector-drawable](https://github.com/dandar3/android-support-animated-vector-drawable) (optional)

**References**:
- https://developer.android.com/topic/libraries/support-library/revisions.html
- https://developer.android.com/topic/libraries/support-library/features.html#v7-appcompat

**Issue**:<br/>
 > _Android AAPT Problem (1 item)_<br/>
 > `abc_alert_dialog_button_bar_material.xml` <br/>
 > `removing attribute http://schemas.android.com/apk/res/android:layoutDirection from ...`<br/>
 >
 > _Solution_:<br/>
 > Set Eclipse `Preferences` > `Android` > `Build` > `Build output` to `Normal` or `Silent` instead of `Verbose`.<br/>
 > @see https://code.google.com/p/android/issues/detail?id=164673#c18

**SVN checkout:**<br/>
- https://github.com/dandar3/android-support-v7-appcompat/tags/24.1.1