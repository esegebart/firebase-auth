# Firebase Authentication Using Email and Password

This was a project for University written in Java. The project was an outdated Firebase Authentication project using email and password to sign up a user
and sign in a user. The user was signed up through the application and the second user was created using the Firebase console. I was to
create a signIn method that was verified in the logcat with the onAuthStateChanged() method. If successful, the signInWithEmail will read
"success", if the login failed, the signInWithEmail will read "failure".

## Getting Started

This can be loaded into Android Studio and ran using the Android Emulator or Genymotion Emulator. This project was created and ran on
Android Studio Emulator using Pixel 2 API 28.

### Prerequisites

Android Studio 3.5.2
Firebase Console application should be created and already connected to the project.
**Note: If you are having trouble running the application, make sure that you have internet access created in your
AndroidManifest**
Android Emulator Pixel 2 API 28
Firebase-auth 19.2.0
Firebase-analytics 17.2.0

### Installing

1. Load the application into Android Studio.
2. Run the project.
3. Application will appear with an email and password textView for user information.
4. Two buttons should be there with Sign In and Sign Up.
5. Enter the email and password for the new user and click Sign Up.
6. This should reflect in the logcat with text like "D/EmailPassword: createAccount:johndoe@janeroe.com".
7. When signing in the new user, the logcat should say:
    onAuthStateChanged:signed_in:AibMhLXQEQfTyRrxyVB7IfAYgw13
    onAuthStateChanged:signed_in:johndoe@janeroe.com
    createUserWithEmail:onComplete:true
8. Using the Firebase Console > Authentication > USERS, a new user can be created and then able to be signed in on the applicaiton.
9. Refresh the Firebase Console page and the the Last Sign-In should display the current date. 

## Built With

* [Gradle](https://gradle.org/) - Build Management System
* [Google Mobile Services](https://www.android.com/gms/) - Google application/APIs
* [Android Studio](https://developer.android.com/AndroidStudio/download) - IDE
* [Firebase Console] (http://firebase.google.com/) Cloud Backend Services

## Authors

* **Elyse Segebart** - *Initial work* - [Esegebart](https://github.com/esegebart)

## Acknowledgments

* Firebase documentation (https://firebase.google.com/docs/auth/android/start)
