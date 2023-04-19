# Fragment Life Methods for Android Applications

- This repository contains an Android application that demonstrates the various lifecycle methods of a fragment. The application features a UI with buttons that allow users to click on a fragment and observe the lifecycle callbacks.

## Overview
- Fragments in Android are modular sections of an activity that can be reused across multiple activities. Like activities, fragments also go through various stages during their lifetime, and it is important for developers to understand these stages to ensure proper handling of resources and data. This application demonstrates the various lifecycle methods of a fragment, including:

1. onAttach(): Called when the fragment is attached to the activity.
2. onCreate(): Called when the fragment is first created.
3. onCreateView(): Called when the fragment's UI is being created.
4. onActivityCreated(): Called when the fragment's activity has been created.
5. onStart(): Called when the fragment is becoming visible to the user.
6. onResume(): Called when the fragment will start interacting with the user.
7. onPause(): Called when the system is about to start resuming a previous activity.
8. onStop(): Called when the fragment is no longer visible to the user.
9. onDestroyView(): Called when the fragment's view is being destroyed.
10. onDestroy(): Called before the fragment is destroyed by the system.
11. onDetach(): Called when the fragment is detached from the activity.

## How to Use
1. Clone or download the repository from GitHub.
2. Open the project in Android Studio.
3. Build and run the project on an emulator or a physical device.
4. Click the "Fragment" button to add a fragment and observe the lifecycle callbacks.
5. close the fragment and observe the lifecycle callbacks.

## Technologies Used
* Java
* Android Studio
