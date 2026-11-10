
<manifest xmlns:android="http://schemas.android.com/apk/res/android">

    <uses-permission android:name="android.permission.RECORD_AUDIO"/>
    <uses-permission android:name="android.permission.INTERNET"/>

    <queries>
        <package android:name="com.google.android.youtube"/>
        <package android:name="com.instagram.android"/>
        <package android:name="com.lemon.lvoverseas"/>
    </queries>

    <application
        android:theme="@android:style/Theme.Material.Light.NoActionBar"
        android:label="Jarvis Assistant"
        android:allowBackup="true">

        <activity
            android:name=".MainActivity"
            android:exported="true">

            <intent-filter>
                <action android:name="android.intent.action.MAIN"/>
                <category android:name="android.intent.category.LAUNCHER"/>
            </intent-filter>

        </activity>
    </application>

</manifest>

