# Firebase email and password authentication for Android


Firebase email and password authentication can be used to enable users of your android app register/login on your app using the old fashion email and password style without you worrying much about building a backend to support the user authentication process.


Step 1: 
Create a new project on android studio or open an existing project you intend to add email/password authentication to.

Step 2: 
Click on Tool from android studio menu bar then select Firebase.

Step 3:  
The Firebase assistant wizard window will open. Select Authentication from the next list and follow the wizard to connect your app to Firebase (this requires internet connection)
-Select Authentication
-Connect to Firebase and then Add Firebase Authentication to your app
-create new project

Step 4:
Next, head to Firebase console (http://console.firebase.google.com/) navigate to your new app, and under the authentication tab, enable email/pass authentication.

Step 5:
Include Internet permission request in your Manifest file:
    <uses-permission android:name="android.permission.INTERNET" /> <!-- this line adds the required permission request -->

Step 6:
lets code our registration activity. This includes the layout xml file with our views and our Java class with the working code. In above code MainActivity.java is registration activity.

Step 7:   
Now that you are all done with the user registration feature, its time to code user login.
LoginActivity.java and activity_login.xml consists the code for user login.

Step 8:
And there you have it. A working email/password user registration and login activity for your android app. If you are wondering where your data is stored, the answer if on Firebase. You can find all registered users in the Firebase console.

Thank you for reading and don’t forget to clap :)


