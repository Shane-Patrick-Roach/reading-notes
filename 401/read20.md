# Android Fundamentals


## Basics of Android
---

- Android apps can be written using Kotlin, Java, and C++ languages.
- An android package which is an archive file with an `.apk` suffix contains the contents of an android app that are required at runtime and it is the file that android powered devices use to install the app.
- Android system implements the ***principle of least priveledge***. That is each app by default has aaccess only to the components that it required to do its work and no more.


## What are app components?
---

- An app component are the essential building blocks of an android app. 
- Each component is an entry point through which the system or a user can enter your app. 

### Four different types of app components

1. Activities
2. Services
3. Broadcaast recievers
4. Content providers

### What is an acitivity?

- An activity is the entry point for intertacting with the user. It represents a single screen with a user interface. For example an email app might have one activity that shows a list of new emails, another activity to compose an emal and other for reading emails.

### What are services?

- A service is a general purpose entry point for keeping an app running in the background for all kinds of purposes.
- Does not provide a user interface.
- For example a service mught play music in the background while the user is in a different app. 

### What is a broadacast reciever?

- A BR is a component that enables the system to deliver events to the app outside of a regular user flow. Allowing the app to respond to systemwide broadcast announcments. 

### What are Contents Providers?

- A CP manages aa shared set of app data that you can store in the file system, in a database, on the web, or on any persisten storage locaation tha your app can access.


## Manifest File
---

- Before android system can start an app components, the system must know that the component exists by reading the apps manifest file. `androidManifest.xml`
- Your app must declare all its components in this file, which must be at the root of the app project directory.

## Resources/Citations

---

- [Android fundamentals](https://developer.android.com/guide/components/fundamentals)
