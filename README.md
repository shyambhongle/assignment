# React Native (Expo)

This repository is for a test assignment on testing Automation. The app has three elements: two input fields and one submission button. Please write test cases for performing unit testing on this component. Below are the detailed steps on how to run the app.
All the elements have testid-

Input(username) = 'usernameInput'
Input(username) = 'passwordInput'
Button(submit) = 'signInButton'

<div style="display:flex;flex-direction:row">
<img src="https://raw.githubusercontent.com/alexanderhodes/react-native-expo-maestro-example/main/res/example-screenshot.png" alt="Screenshot Sign In" height="400" width="auto" style="marginRight: 16px">

## Running the app

Preparing the app and installing the dependencies.

```bash
# Use CMD in the file location to run this commands 
# Install npm in the system if not installed already
# Install dependencies
$ npm install
# Install ios pods (Only If running IOS verison)
$ npm run ios:pods
# Start app
$ npm start
# Start ios app
$ npm run ios
# Start android app
$ npm run android

#If want to run on web install below dependenices
$ npm install @expo/webpack-config
# Start Web app
$ npm run web
```

For running the app on android you will require to install expo go app from playtore on android. Scan the QR code genrated after running command for android(npm run android).

Documentation- https://docs.expo.dev/get-started/set-up-your-environment/

