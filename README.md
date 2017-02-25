## android-support-v7-appcompat

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/25.1.1/appcompat-v7-25.1.1.aar`

**Requires:**
- `Android 7.1 (API 25) SDK Platform`
- [dandar3/android-support-annotations](https://github.com/dandar3/android-support-annotations/tree/25.1.1)
- [dandar3/android-support-v4](https://github.com/dandar3/android-support-v4/tree/25.1.1)
- [dandar3/android-support-vector-drawable](https://github.com/dandar3/android-support-vector-drawable/tree/25.1.1)
- [dandar3/android-support-animated-vector-drawable](https://github.com/dandar3/android-support-animated-vector-drawable/tree/25.1.1) (optional)

**References:**
- https://developer.android.com/topic/libraries/support-library/revisions.html#25-1-1
- https://developer.android.com/topic/libraries/support-library/features.html#v7-appcompat

**Issue:**<br/>
 > _Android AAPT Problem (1 item)_<br/>
 > `abc_alert_dialog_button_bar_material.xml` <br/>
 > `removing attribute http://schemas.android.com/apk/res/android:layoutDirection from ...`<br/>
 >
 > _Solution_:<br/>
 > Set Eclipse `Preferences` > `Android` > `Build` > `Build output` to `Normal` or `Silent` instead of `Verbose`.<br/>
 > @see https://code.google.com/p/android/issues/detail?id=164673#c18

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-support-v7-appcompat/25.1.1/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/>
  https://github.com/dandar3/android-support-v7-appcompat/tags/25.1.1