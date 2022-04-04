# SAPUI5 with SQLite and a custom UI5 model inspector/control wrapped in an Android APK

Reference to SAPUI5's List example: https://sapui5.hana.ondemand.com/sdk/#/entity/sap.m.ColumnListItem/sample/sap.m.sample.Table </br>
</br>
Custom UI5 Model Inspector: https://github.com/mitch-b/ui5-model-inspector </br>
</br>

Learn how to implement SQLite storage on your Cordova (PhoneGap) Projects for storing data offline.
Article: https://codesundar.com/cordova-sqlite-storage/

<code>cordova platform add browser</code>: add for the browser platform. </br>
<code>cordova platform add android@9.0.0</code>: add for the Android platform. The version 9.0.0 works for me for running on Debian 10 in Crostini.</br>
<code>cordova plugin add cordova-sqlite-storage</code>: add the SQLite plugin. </br>
</br>
<code>cordova run browser</code>: run for the browser platform. </br>
<code>cordova build android</code>: build an Android apk. </br>
