# Gradle

Gradle commands for projects that have a `gradlew` file generated with `android project create -g -v X`.

Those are created with Android Studio. Find version used by studio: <http://stackoverflow.com/questions/25260172/how-to-check-the-gradle-version-in-android-studio>

They rely on the Android plugin for Gradle: <http://developer.android.com/tools/building/plugin-for-gradle.html> TODO source.

Ant is another possibility, which is generated by `adb create project`.

The examples under `samples/` also use Gradle.

List Gradle tasks

    ./gradlew tasks

Clean build and install:

    ./gradlew clean
    ./gradlew assembleDebug
    ./gradlew installDebug

## gradlew

Stands for Gradle Wrapper.

Deals for example with Gradle virtualization: this script can download and use a required version of Gradle for a given project, even if your distribution does not offer it.

<https://docs.gradle.org/current/userguide/gradle_wrapper.html>

## Gradle to Ant

<http://stackoverflow.com/questions/4454107/how-to-convert-an-eclipse-android-project-to-use-ant-for-build>

## Select device

Impossible apparently: <http://stackoverflow.com/questions/23960667/running-gradles-connectedandroidtest-on-a-specific-device>
