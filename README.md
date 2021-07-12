# Firebase Codelab: FriendlyChat

[![Actions Status][gh-actions-badge]][gh-actions]

This is my complete version of the Firebase FriendlyChat App from codelabs. Function is to be able to use a login from either Google or Your email and you can create an account and start being able to message other people. I show in the demo I liked my personal google account as well as an account I made locally using my email address and created a screen name being my first and last name (but you can make that anything you want I suppose) and a password.
To get started open the codelab instructions:

 - [Build FriendlyChat Codelab](https://firebase.google.com/codelabs/firebase-android/)

![image](https://user-images.githubusercontent.com/60675989/125226793-bd632180-e29f-11eb-82ec-1dc38fdc041f.png)



## Instructions to Start the App:
Download or clone the repository locally onto your hardrive  
Build the project  
After it is build, type this command into your terminal "firebase emulators:start --project=demo-friendlychat" (you will be able to see realtime database)  
The command above will use the firbase.json file and start the emulator and will give you a local port whjich you can access the firebase emulator  (see status or authentication, cloud messaging, etc.)
Once cloned, you should be able to press the play button or go on the "Run" tab on the tool bar and press run 'build-android-start.app'  
** make sure your gradle is 6.7.1 or change it in the gradle-wrapper.properties to 6.7.1. I had to move the gradle-wrapper-properties file outside in the main FriendlyChat folder. **


## What is updated?
Everything is runnable (you can check). I even provided a demo of how it worked. Thank you for your patience for the assignment. I have been trying my best to keep up.  

Demo Link: https://www.youtube.com/watch?v=I-_bgoH61_U


## License
See [LICENSE](LICENSE)

[gh-actions]: https://github.com/firebase/codelab-friendlychat-android/actions
[gh-actions-badge]: https://github.com/firebase/codelab-friendlychat-android/workflows/Android%20CI/badge.svg
