## Running the example

- clone the repository
- `yarn install` at main directory
- `cd Example/`
- `yarn install` again

### !Warning!
This daemon requires a lot of workers. 
This solved by this:

https://stackoverflow.com/questions/53930305/nodemon-error-system-limit-for-number-of-file-watchers-reached

**Do not use a lot of workers and watchers. It freezes a system**

And it requires installing NDK 21 via Android Studio


### Running on iOS

- `cd ios && pod install && cd ..` - to install pods
- `react-native run-ios` - to run the app

### Running on Android

- [install NDK in version 21.3.6528147 or higher](https://developer.android.com/studio/projects/install-ndk)
- `react-native run-android` - to run the app

**Note:** Android compiles fairly long due to native dependencies. To shorten consecutive builds, load the project into android studio and run it from there. Same applies to iOS so you can use XCode for running the example.

**Important:** You will need to have an Android or iOS device or emulator connected as well as react-native-cli package installed globally.
