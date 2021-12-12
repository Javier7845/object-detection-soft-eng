# Overview
This project lays out an application for Android based on artificial intelligence capable of recognizing the number of roses in an image given by the user, from either the phone's camera or gallery.
# Requirements
- Android Studio version Artic Fox 2020.3.1 Patch 3 or greater (for cloning and editing the app)
- Android 6.0 Marshmallow or greater (for installing and testing in an Android phone)
# Screenshots
     
|        Home Screen                |       Test Images                 |          Gallery Functionality    | 
:----------------------------------:|:---------------------------------:|:----------------------------------:
|![Alt text](/assets/app%20(5).jpeg)|![Alt text](/assets/app%20(4).jpeg)|![Alt text](/assets/app%20(1).jpeg)|

| Inference with Gallery Image      |       Camera Functionality        |    Inference with Camera Image    | 
:----------------------------------:|:---------------------------------:|:----------------------------------:
|![Alt text](/assets/app%20(6).jpeg)|![Alt text](/assets/app%20(3).jpeg)|![Alt text](/assets/app%20(2).jpeg)|

# Importing the Project on Android Studio
1. Clone or download this repository:

     ```
     git clone https://github.com/StadynR/object-detection-soft-eng
     ```
2. Open Android Studio
3. Click on File -> New -> Import Project
     - **First Time using Android Studio:** Click Open an existing Android Studio project
4. Search for the directory `final_revised` and select it.
5. If you get a Gradle Sync popup, click OK and wait for it to sync.
# Installation
## Install using Android Studio
1. Configure your phone to connect to Android Studio and build the app. See https://developer.android.com/studio/run/device for details.
2. Connect yout phone to your computer (with an USB cable or through Wi-Fi depending on how you configured your phone).
3. If everything was done correctly, you will see your phone's model name on the panel near the upper right corner.
     ![Model Name](/assets/model_name.png)
4. You can then install and run the app by selecting Run -> Run 'app', or by clicking the green play button right to your phone's model name. Don't disconnect your phone until the app is loaded.
## Install using the APK
1. Download the latest MDT.Rose.Counter.apk from the Releases page.
2. Copy the apk to your phone.
3. Search for the file and touch it to install it. If your phone asks for confirmation or permission to install the apk, accept.
# How to change the AI model
# Usage
Make sure the app is already installed in your phone.
1. Find the application on your cell phone and open it.
2. Tap Take a Picture to take a photo using your phone's camera or Gallery to choose a photo from your phone's gallery. Alternatively, you can touch the sample photos above the buttons to select them.
3. The inference of the image will be done automatically, and the result will be shown in the center of the screen.
4. You can then save the image using the Save Result button or start a new inference by repeating step 2. The photos saved from the app are stored in the Pictures/Inferences folder from your phone's internal storage.
# Troubleshooting
Bugs can be reported in the issue tracker on our GitHub repo: https://github.com/StadynR/object-detection-soft-eng/...
# License
This project is licensed under the MIT License. See the LICENSE file for the full license information.
