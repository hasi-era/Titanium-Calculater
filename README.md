Titanium-Calculater

=========================================

Please Replace below code in your tiapp.xml:
<code>
<android xmlns:android="http://schemas.android.com/apk/res/android"/>
</code>
with below code

<android 
    xmlns:android="http://schemas.android.com/apk/res/android">
    <manifest>
      <application>
        <!-- Need to specify at least API level 11 for Titanium SDK 3.2.x and prior -->
        <activity android:configChanges="keyboardHidden|orientation" android:name="org.appcelerator.titanium.TiActivity" android:screenOrientation="portrait"/>
      </application>
    </manifest>
  </android>
  
