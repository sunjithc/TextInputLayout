# TextInputLayout
TextInputLayout extends ViewGroup class. So which means that you have to wrap your EditText in a TextInputLayout.

![stack Overflow](https://github.com/sunjithc/TextInputLayout/blob/master/68747470733a2f2f692e696d6775722e636f6d2f533435366330582e676966.gif)

Import the Support Libraries

    dependencies {
      compile fileTree(dir: 'libs', include: ['*.jar'])
       compile 'com.android.support:design:22.2.0'
      compile 'com.android.support:appcompat-v7:22.2.0'
    }

Design the User Interface

    <android.support.design.widget.TextInputLayout
    android:id="@+id/usernameWrapper"
    android:layout_width="match_parent"
    android:layout_height="wrap_content">
    <EditText
        android:id="@+id/username"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="textEmailAddress"
        android:hint="Username"/>
    </android.support.design.widget.TextInputLayout>

edit the style.xml

    <style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
     </style>

![stack Overflow](https://github.com/sunjithc/TextInputLayout/blob/master/Implement-TextInputLayout-Using-Android-Design-Support-Library-Image.png)
