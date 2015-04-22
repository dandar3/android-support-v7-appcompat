Eclipse library project based on:<br/>
`ANDROID_SDK/extras/android/m2repository/com/android/support/appcompat-v7/22.1.0/appcompat-v7-22.1.0.aar`

Requires (to compile):<br/>
`Android 5.1 (API 22) SDK Platform`

Subversion checkout URL:<br/>
https://github.com/dandar3/android-support-v7-appcompat/tags/22.1.0

Known issues:
* Android AAPT Problem (3 items):
  ** `abc_alert_dialog_material.xml`
  "removing attribute http://schemas.android.com/apk/res/android:layout_marginEnd from <ImageView>"
  "removing attribute http://schemas.android.com/apk/res/android:layoutDirection from <LinearLayout>"
  "removing attribute http://schemas.android.com/apk/res/android:textAlignment from <android.support.v7.internal.widget.DialogTitle>"
  See https://code.google.com/p/android/issues/detail?id=164673
