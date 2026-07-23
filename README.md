#### Objective
- To understand the basic Android Studio project structure and modify the default text displayed in the Android application.

#### Introduction
- Android Studio is the official Integrated Development Environment (IDE) for Android application development. When a new Android project is created, it automatically generates a predefined folder structure containing source code, resources, configuration files, and build scripts. Understanding this structure is essential for developing Android applications. In this experiment, the default "Hello World!" text was replaced with the student's name and USN to become familiar with editing the application's user interface.

#### Scenario
- A new Android application was created using the Empty Views Activity template. The default TextView displaying "Hello World!" was modified to display the student's name and USN. This simple change demonstrates how to locate layout files and edit UI components in Android Studio.

#### Technologies Used
- Android Studio
- Kotlin
- XML (Layout Design)
- Android SDK

#### Project Structure
```
 MyApplication/
│
├── app/
│   ├── manifests/
│   │   └── AndroidManifest.xml
│   ├── kotlin+java/
│   │   └── MainActivity.kt
│   ├── res/
│   │   ├── layout/
│   │   │   └── activity_main.xml
│   │   ├── drawable/
│   │   ├── mipmap/
│   │   └── values/
│   └── build.gradle.kts
│
├── Gradle Scripts/
└── README.md

```

#### Folder Description
- MainActivity.kt	Contains the Kotlin code for the main activity.
- activity_main.xml	Defines the user interface of the application.
- AndroidManifest.xml	Contains application configuration and permissions.
- res	Stores layouts, images, strings, and other resources.
- Gradle Scripts	Used to manage project dependencies and build configuration.

Output
The application successfully displays the customized text:
Hello Maheep!
25MCAR0105


Status: ✅ Pass

(Use the screenshot you uploaded, as it clearly shows both your name and USN.)
