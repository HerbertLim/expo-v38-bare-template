# A React Native Template project ejected from Expo SDK v38

This is a React Native temaplate or Expo bare workflow project, which is ejected from Expo SDK v38. Among many templates from Expo, `expo-template-tabs` is used because it provides a good starting point for a new React Native project, especially for beginners, such as:

- react-navigation's BottomTabNavigation with two tabs 
- Typescript
- Well structured source tree helps maintaining soure codes
- Sample custom hooks for color scheme gives good insight for using React Hooks.

Example Android package name and iOS bundle identifer is `com.ecoa.expobare.v38`. You may have to change them.

## Running on simultors
`$ npm run android`, or `$ npm run ios`

## Running on real devices
If you haven't run any React Native app on real device, please visit [React Native's official document "Running on Device"](https://reactnative.dev/docs/running-on-device) first.

Steps to run in Android:

- Connect Android device to your computer 
- In Android Studio, open `./android` folder
- Select your Android device
- Press `Run app` button

Steps to run in iOS:

- Open with ./ios/expov38bareworkflow.xcworkspace with xCode
- In xCode, select `TARGETS` and then `Signing & Capabilities` tab
  - Select your team and register your test iOS device, then a Signing Certificate will be issued
- Press Start button to build and run this app