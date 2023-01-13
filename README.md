# JarTestApplication

Step:

+ Assemble model `lib`.

+ Copy the assemble result `lib.jar` to `app/libs/lib.jar`.

+ Click `Run 'app'` or `Shift + F10` to start app directly, it works fine.

+ Assemble model `app`.

+ Install the assemble result `app-debug.apk` to an Android phone.

+ Launch the app, then it crash.

### Environment

+ Android Studio: 4.2.2 or 2021.3.1

+ JDK: Android Studio built-in JDK

### Solution

[gradle.properties#L27](https://github.com/sgpublic/JarTestApplication/blob/590a9dde238d2f3e1f0b1ab2a5d3ba0537af2e4d/gradle.properties#L27)