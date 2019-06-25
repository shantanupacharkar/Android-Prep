# Study Guide : Associate Android Developer Certification
Use the study guide to prepare for the Google Associate Android Developer Certification exam. This guide lists the competency areas and individual competencies against which you will be tested. There are also links to suggested web-based study resources. Note that these resources form only a small portion of what is available on the web, and we encourage you to do additional research.

- [Android core](#android-core)
- [User interface](#user-interface)
- [Data management](#data-management)
- [Debugging](#debugging)
- [Testing](#testing)


## Android core
Android is an operating system based on Linux and designed primarily for mobile devices. Android applications can be multitasking and are written in Java, Kotlin or C++.

To prepare for the AAD certification exam, Android developers should:

- [ ] Understand the architecture of the Android system
- [ ] Be able to describe the basic building blocks of an Android app
- [ ] Know how to build and run an Android app
- [ ] Display simple messages in a popup using a `Toast` or a `Snackbar`
- [ ] Be able to display a message outside your app's UI using `Notifications`
- [ ] Understand how to localize an app
- [ ] Be able to schedule a background task using `JobScheduler`

Resources
- [Android Developers -> Toasts](https://developer.android.com/guide/topics/ui/notifiers/toasts)
- [Android Developers -> Snackbar](https://developer.android.com/reference/android/support/design/widget/Snackbar)
- [Android Developers -> Localize your app](https://developer.android.com/guide/topics/resources/localization)
- [Android Developers -> Application fundamentals](https://developer.android.com/guide/components/fundamentals)
- [Codelabs -> Notifications](https://codelabs.developers.google.com/codelabs/android-training-notifications/index.html?index=..%2F..android-training#0)
- [Codelabs -> JobScheduler](https://codelabs.developers.google.com/codelabs/android-training-job-scheduler/index.html?index=..%2F..android-training#0)


## User interface
The Android framework enables developers to create useful apps with effective user interfaces. Developers need to understand Android’s activities, views and layouts to create attractive UIs that maximize usability and the overall user experience.

To prepare for the AAD certification exam, Android developers should:

- [ ] Understand the Android activity lifecycle
- [ ] Be able to create an `Activity` that displays a `Layout`
- [ ] Be able to construct a UI with `ConstraintLayout`
- [ ] Understand how to create a custom `View` class and add it to a `Layout`
- [ ] Know how to implement a custom app theme
- [ ] Be able to add accessibility hooks to a custom `View`
- [ ] Know how to apply content descriptions to views for accessibility
- [ ] Understand how to display items in a `RecyclerView`
- [ ] Be able to bind local data to a `RecyclerView` list using the Paging library
- [ ] Know how to implement menu-based navigation
- [ ] Understand how to implement drawer navigation

Resources
- [Codelabs -> Activities and intents](https://codelabs.developers.google.com/codelabs/android-training-create-an-activity/index.html?index=..%2F..android-training#0)
- [Codelabs -> Your first interactive UI](https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-a/index.html?index=..%2F..android-training#0)
- [Android Developers -> Build a responsive UI with ConstraintLayout](https://developer.android.com/training/constraint-layout/)
- [Android Tool Time - Building interfaces with ConstraintLayout in AS](https://www.youtube.com/watch?time_continue=9&v=XamMbnzI5vE)
- [Android Developers -> Custom view components](https://developer.android.com/guide/topics/ui/custom-components)
- [Android Developers -> Build more accessible custom views](https://developer.android.com/guide/topics/ui/accessibility/custom-views)
- [Android Developers -> Adding accessibility features to apps for blind and visually-impaired users](https://www.youtube.com/watch?v=1by5J7c5Vz4)
- [Android Developers -> setContentDescription()](https://developer.android.com/reference/android/view/View#setContentDescription(java.lang.CharSequence))
- [Codelabs -> Themes and final touches](https://codelabs.developers.google.com/codelabs/android-training-drawables-styles-and-themes/index.html?index=..%2F..android-training#5)
- [Android Developers -> Styles and themes](https://developer.android.com/guide/topics/ui/look-and-feel/themes)
- [Codelabs -> RecyclerView](https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view/index.html?index=..%2F..android-training#0)
- [Android Developers -> Create a list with RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)
- [Android Developers -> Create a navigation drawer](https://developer.android.com/training/implementing-navigation/nav-drawer)
- [Codelabs -> Menus and pickers](https://codelabs.developers.google.com/codelabs/android-training-menus-and-pickers/index.html?index=..%2F..android-training#0)
- [Codelabs -> User navigation](https://codelabs.developers.google.com/codelabs/android-training-provide-user-navigation/index.html?index=..%2F..android-training#0)

## Data management
Many Android apps store and retrieve user information that persists beyond the life of the app.

To prepare for the AAD certification exam, Android developers should:

- Understand how to define data using Room entities
- Be able to access Room database with data access object (DAO)
- Know how to observe and respond to changing data using LiveData
- Understand how to use a Repository to mediate data operations
- Be able to read and parse raw resources or asset files
- Be able to create persistent Preference data from user input
- Understand how to change the behavior of the app based on user preferences

Resources
- Codelabs -> Room, LiveData and ViewModel
- Codelabs -> Repository
- Codelabs -> Drawables, styles, and themes
- Codelabs -> Shared preferences
- Android Developers -> SharedPreferences.Editor
- Codelabs -> App settings

## Debugging
Debugging is the process of isolating and removing defects in software code. By understanding the debugging tools in Android Studio, Android developers can create reliable and robust applications.

To prepare for the AAD certification exam, Android developers should:

- Understand the basic debugging techniques available in Android Studio
- Know how to debug and fix issues with an app's functional behavior and usability
- Be able to use the System Log to output debug information
- Understand how to use breakpoints in Android Studio
- Know how to inspect variables using Android Studio

Resources
- Android Developers -> Debug your app
- Codelabs -> Add log statements to your app
- Android Dev Fundamentals -> Write and view logs with Logcat
- Codelabs -> Android Studio debugger


## Testing
Software testing is the process of executing a program with the intent of finding errors and abnormal or unexpected behavior. Testing and test-driven development (TDD) is a critically important step of the software development process for all Android developers. It helps to reduce defect rates in commercial and enterprise software.

To prepare for the AAD certification exam, Android developers should:

- Thoroughly understand the fundamentals of testing
- Be able to write useful local JUnit tests
- Understand the Espresso UI test framework
- Know how to write useful automated Android tests

Resources
- Android Developers -> Fundamentals of testing
- Codelabs -> Unit tests
- Codelabs -> Android Testing -> Unit testing with JUnit and Mockito
- Android Dev Fundamentals -> Automate UI tests
- Codelabs -> Android Testing -> Espresso for UI testing
