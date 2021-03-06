# AndroidStudio-HTTPClient

A Simple HTTTP Request client, that's requesting a string from a nodejs webserver.<br>
![Tux, the Linux mascot](ScreenshotOfApp.png)
#### Libraries:<br>
import android.os.AsyncTask;<br>
import android.os.Bundle;<br>
import android.view.View;<br>
import android.widget.Button;<br>
import android.widget.TextView;<br>
import androidx.appcompat.app.AppCompatActivity;<br>
import java.io.BufferedReader;<br>
import java.io.IOException;<br>
import java.io.InputStreamReader;<br>
import java.net.HttpURLConnection;<br>
import java.net.URL;<br>

#### Required configuration:

##### In MainActivity.java: 
Change `http://10.0.2.2:3000/` 
to your IP-Address, unless your webserver is localhost. <br>
Remember`localhost:3000 -> Android recognize localhost as: 10.0.2.2` <br>
Check/edit ID for button: `Button contactServerButton = findViewById(R.id.button1);`<br>
##### In AndroidManifest.xml<br> 
add `android:usesCleartextTraffic="true"`<br>
add `<uses-permission android:name="android.permission.INTERNET" />`<br>

##### In activity_main.xml<br>
Check/edit ID button: `android:id="@+id/button1"`

File location: [MainActivity.java](https://github.com/KushMax/AndroidStudio-HTTPClient/blob/master/app/src/main/java/com/example/clienttonodejs/MainActivity.java): AndroidStudio-HTTPClient/app/src/main/java/com/example/clienttonodejs/MainActivity.java<br>
File location: [AndroidManifest.xml](https://github.com/KushMax/AndroidStudio-HTTPClient/blob/master/app/src/main/AndroidManifest.xml): AndroidStudio-HTTPClient/app/src/main/AndroidManifest.xml<br>
File location: [activity_main.xml](https://github.com/KushMax/AndroidStudio-HTTPClient/blob/master/app/src/main/res/layout/activity_main.xml): AndroidStudio-HTTPClient/app/src/main/res/layout/activity_main.xml<br>

<br>

Code is adapted from: 
[Android AsyncTask HTTP GET request Tutorial](https://medium.com/@JasonCromer/android-asynctask-http-request-tutorial-6b429d833e28) and
[Minimal clien-server example for Android and Node.js](https://suragch.medium.com/minimal-client-server-example-for-android-and-node-js-343780f28c28)<br>
