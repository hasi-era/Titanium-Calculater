<H2> Titanium-Calculater </H2>

<p> Simple Calculater for Titanium </p>

> Please Replace below code in your tiapp.xml:

```xml
<android xmlns:android="http://schemas.android.com/apk/res/android"/>...
```
> with below code

```xml
<android 
    xmlns:android="http://schemas.android.com/apk/res/android">
    <manifest>
      <application>
        <!-- Need to specify at least API level 11 for Titanium SDK 3.2.x and prior -->
        <activity android:configChanges="keyboardHidden|orientation" android:name="org.appcelerator.titanium.TiActivity" android:screenOrientation="portrait"/>
      </application>
    </manifest>
  </android>
  ```
