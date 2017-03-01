# Send-Email-from-App-Silently

This app will take email address of sender from their device and will send email to the receiver silently.

Add this library in your libs folder

| File            | Summary + Labels                                                  |
| -------------   |:-------------:                                                    |
| [additionnal.jar](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/javamail-android/additionnal.jar) | javax.awt dependencies replacement                                |
| [mail.jar](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/javamail-android/mail.jar)        | JavaMail for Android (need activation.jar and additionnal.jar)    |
| [activation.jar](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/javamail-android/activation.jar)  | JAF for android (need additionnal.jar)                            |


You also need to put these permision in your **AndroidManifest.xml**

    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.INTERNET" />
    
If you want to retrive user's mail addres from their device, you will need to put this permission too in your **AndroidManifest.xml**

    <uses-permission android:name="android.permission.GET_ACCOUNTS" />
