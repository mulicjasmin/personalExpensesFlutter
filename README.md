# personalExpensesFlutter

A Basic Flutter project.

## Getting Started with Flutter

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

## macOS Setup

1. On https://flutter.dev/ go to "Get Started" and click on "macOS". On the next screen download the latest stable Flutter SDK az zip file. 

2. Copy extracted folder to wherever you want on your machine.

3. Go to your user folder and make sure that setting "show hidden files" is turned on. You will see there ".bash_profile" file. If you are on macOS Catalina or higher you will have ".zprofile" file. Edit the file so that you add 'export PATH="$PATH:[PATH_TO_FLUTTER_GIT_DIRECTORY]/flutter/bin"' at the bottom of your file, and change [PATH_TO_FLUTTER_GIT_DIRECTORY] with the path to flutter tool on your machine. That of course depends on where you dragged on extracted folder 
(Ex. 'export PATH=/Users/jasminmulic/development/flutter/bin:$PATH). Save the file and open normal terminal app on Mac or Linux. You should run 'flutter doctor' command to get at last something on the screen so to verify you've been successfull in installing Flutter on your machine.

4. Install Xcode by downloading it from AppStore. Then make sure you can use command-line tools by running command 'sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer' from the command line. Accept licence agreements.

5. Setup iOS simulator, or use real iOS device by refering to the official documentation.

6. If desired, for Android setup install AndroidStudio by referring to the official documentation. During installation of AndroidStudio, make sure you checked Android Virtual Device as component for installation. When installation finished, open AndroidStudio and open existing project as flutter app you just created or cloned. Open existing flutter project and go to 'Tools->AVD Manager' and add some device if no device in list. You can start desired device emulator by clicking on green 'Play' button. Quit running flutter process if there is and rerun "flutter run" command. For restart of the build use "r" character in your terminal window where app is being run.

7. If you want to install VisualStudioCode for MAC, you can do it too, and use this IDE instead of AndroidStudio. In this case, get 'Flutter' tool from marketplace after installation.

7. Create new flutter app by navigating into desired folder and running 'flutter create projectName' command or start existing project by running 'flutter run' command while inside project folder. You should be able to see that Flutter app on running iOS simulator. First run can take some time.

## Windows Setup

1. On https://flutter.dev/ go to "Get Started" and click on "Windows". On the next screen download the latest stable Flutter SDK az zip file. 

2. Extract downloaded zip file and copy 'flutter' folder from inside the zip file into any place on your machine. Edit environment variables for your account, under User Variables edit the Path variable so that you add new entry as path to your '/bin' folder from inside installed 'flutter' folder on your machine. Open cmd or Power shell and run 'flutter' command to get some output so that you verify flutter's installation was successful. Even better, you can run 'flutter doctor' to get more details about all processes you might need to have system be prepared to run your first flutter project.

3. Download Android Studio, make sure you check "Android Virtual Device" while installing the tool. Choose also Android SDK Platform and if available Intel HAXM. If having problems with HAXM installation or setup, no worries, it is not a requirement.

4. Run 'flutter doctor' and if having error message 'Unable to locate Android SDK', edit User Environment Variables by adding new user variable with variable name: 'ANDROID_SDK_ROOT' and variable value equal to the 'android-sdk' path on you machine.

5. Restart cmd or Power shell and rerun 'flutter doctor' command. If facing an error related to Android licences run the comand 'flutter doctor --android-licenses'. Accept everything you are asked for below, and by this Android tool chain is configured correctly. Ignore any other warnings stated below in terminal.

6. You can use real Android device for testing your flutter apps, and for that please efer to the offical documentation on the Flutter webpage.

7. Start Android Studio, click 'Configure', verify you have Android SDK installed, and please make sure selected item is the stable one with more than one characters in parantheses stated next to the SDK's name. 

8. Once that's finished, create new flutter app by navigating into desired folder and running 'flutter create projectName' command or start existing project by running 'flutter run' command while inside project folder.

9. Back to Android Studio, open existing flutter project, and go to 'Tools->AVD Manager' and add some device if no device in list. You can start desired device emulator by clicking on green 'Play' button. Quit running flutter process if there is and rerun "flutter run" command. For restart of the build use "r" character in your terminal window where app is being run.

#### For any problems in this part, please refer to the official documentation where you will find all needed informations for your setup.




