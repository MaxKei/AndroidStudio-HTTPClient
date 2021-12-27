# AndroidStudio-HTTPClient
<br>
Required configuration:
<br>
In MainActivity.java: 
<br>
Change `http://10.0.2.2:3000/` 
to your IP-Address, unless your webserver is localhost. <br>
` localhost:3000 -> Android recognize localhost as: 10.0.2.2 `
<br>
<br>

##### In AndroidManifest.xml
<br>
add `android:usesCleartextTraffic="true"`to AndroidManifest.xml<br>



File location: [MainActivity.java](https://github.com/KushMax/AndroidStudio-HTTPClient/blob/master/app/src/main/java/com/example/clienttonodejs/MainActivity.java): AndroidStudio-HTTPClient/app/src/main/java/com/example/clienttonodejs/MainActivity.java<br>
File location: [AndroidManifest.xml](AndroidStudio-HTTPClient/app/src/main/AndroidManifest.xml): AndroidStudio-HTTPClient/app/src/main/AndroidManifest.xml<br>
File location: [activity_main.xml](https://github.com/KushMax/AndroidStudio-HTTPClient/blob/master/app/src/main/res/layout/activity_main.xml): AndroidStudio-HTTPClient/app/src/main/res/layout/activity_main.xml<br>

<br>

Code is adapted from: 
[Android AsyncTask HTTP GET request Tutorial](https://medium.com/@JasonCromer/android-asynctask-http-request-tutorial-6b429d833e28) and
[Minimal clien-server example for Android and Node.js](https://suragch.medium.com/minimal-client-server-example-for-android-and-node-js-343780f28c28)<br>
