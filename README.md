
# CuisineQuest
It's a Food Recipe Search App where utilize the "Forkify" API from https://forkify-api.herokuapp.com/ to fetch and display recipes. 

<br>

## Features

- SplashScreen: A brief introduction to the app with a visually pleasing start.
- Registration Screen: Allows new users to create an account using Firebase Authentication.
- Login Screen: Enables existing users to sign in to their accounts.
- HomeScreen: The main interface of the app where users can search recipe and show the details of recipe.
- ProfileScreen: Allows users to view and edit their profile information stored in Firebase Realtime Database.

## Libraries Used

- Navigation Component
- Retrofit
- Kotlin Coroutines
- Firebase
- LiveData
- DataBinding

<br>

## Architecture

This application implements the MVVM (Model-View-ViewModel) architecture pattern, ensuring a separation of concerns and easier maintenance. It uses the Navigation Component for managing UI navigation, Retrofit for network calls, Coroutines for asynchronous tasks, and Firebase for user authentication and data storage. LiveData is used for observing data changes, and DataBinding for binding UI components in layouts to data sources.

## Design Patterns

Various design patterns are employed throughout the application, such as Repository for data operations and Singleton for Retrofit instance management.

## Prerequisites

- Android Studio Arctic Fox | 2020.3.1 Patch 2 or higher
- Min SDK version 27 (Oreo) or higher

<br>

## Getting Started

1. **Clone the repository:**

```bash
   git clone https://github.com/jaygohel109/CuisineQuest.git
```


2. **Open the project in Android Studio:**
   
   Launch Android Studio and select 'Open an Existing Project', then navigate to the cloned repository.


4. **Configure Firebase:**
   
   - Go to the Firebase Console.
   - Add a new project or use an existing one.
   - Register your application with Firebase, download the google-services.json file, and place it in the app/ directory.
   - Build the project:
   - In Android Studio, select 'Build' from the top menu, then 'Rebuild Project'.
   - Wait for the build to finish.


4. **Run the application:**
   
   - Connect an Android device or use the Android emulator.
   - Press 'Run' (the green play button) in Android Studio.

<br>

## ScreenShot


## Thank You
   

  
