<b>Bling</b> 

Bling is a hybrid application for android platform that uses speech to text to update status to your favourite social networks.

<b>Technolgy Stack</b>

Apache Cordova / Phonegap
Eclipse
Android
HTML5, CSS3, JavaScript
Ant
Node.js

<b>SET UP</b>

To  set up this project in your machines follow the steps given below:

Pre-requisites : Eclipse | Android SDK | ADT Plugin .

1. Download the latest copy of Phonegap.
[http://phonegap.com/install/]
2. Install phonegap using Node.js as specified in the documentation in the above link
3. Create a new android project as usual.
4. In the root directory of your project create two new directories

	/libs
	assets/www
5. Copy cordova.js from your installed cordova to assets/www
6. Now use Ant to build a .jar file of the Cordoava project.


Handy Tips to build cordova.jar 

From cmd change directory to phonegap/lib/android/fromaework/

Now execute the following commands

android update project -p . -t android-17

Finally run 

ant jar

DONE!!!!



7. Copy cordova.jar from your installed cordova to /libs.
8. Copy xml from your installed cordova to /res.


You are now good to go !! 

<b>Happy Coding!</b>
