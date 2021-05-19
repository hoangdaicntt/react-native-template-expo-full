# :space_invader: React Native Template Expo + Typescript + More

<p>
  <a href="https://travis-ci.org/hoangdaicntt/react-native-template-expo-full">
    <img alt="Build Status" src="https://img.shields.io/travis/hoangdaicntt/react-native-template-expo-full.svg" target="_blank" />
  </a>
  <a href="https://github.com/hoangdaicntt/react-native-template-expo-full#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/hoangdaicntt/react-native-template-expo-full/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" target="_blank" />
  </a>
  <a href="https://github.com/hoangdaicntt/react-native-template-expo-full/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
</p>

> The standard react-native pattern with Expo and other essential dependencies.

## :star: Features

- Use the expo baseflow
- Use the typescript
- Add other dependencies: Redux, React Navigation, React-native SVG

## :arrow_forward: Usage

```sh
npx react-native init MyApp --template react-native-template-expo-full
```


#### List of additional dependencies

| Dependencies  |  Version | Android  | Ios  | Web  |
|---|---|---|---|---|
| @react-navigation  | 5.12.8  | :white_check_mark:  | :white_check_mark:  |   |
| axios  |  0.21 | :white_check_mark:  | :white_check_mark:  |   |
| @react-native-async-storage  | 1.15.1  | :white_check_mark:  | :white_check_mark:  |   |
| react-native-svg  | 12.1.1  | :white_check_mark:  | :white_check_mark:  |   |
| expo-ads-admob  | 10.0.4  | :white_check_mark:  | :white_check_mark:  |   |
| react-native-firebase (analytics,auth,messaging)  | ....  | :white_check_mark:  |   |   |
| react-native-modal  | ....  | :white_check_mark:  | :white_check_mark:  |   |
| react-native-webview  | ....  | :white_check_mark:  | :white_check_mark:  |   |
| react-native-modalize  | ....  | :white_check_mark:  | :white_check_mark:  |   |
| react-native-fast-image  | ....  | :white_check_mark:  | :white_check_mark:  |   |
| @react-native-google-signin  | ....  | :white_check_mark:  | :white_check_mark:  |   |
| expo-facebook  | 11.0.5  | :white_check_mark:  | :white_check_mark:  |   |
| expo-font  | 11.0.5  | :white_check_mark:  | :white_check_mark:  |   |
| expo-av  | 11.0.5  | :white_check_mark:  | :white_check_mark:  |   |

## Setup
### 1. expo-ads-admob
- cd android/app/src/main/AndroidManifest.xml
- change "ca-app-pub-xxxxxxxxxxxxxxxx~yyyyyyyyyy" with admod ID

### 2. react-native-firebase
- Update google-services.json file
- cd android && ./gradlew signingReport & update key to firebase

### 3. expo-facebook
- cd android/app/src/main/AndroidManifest.xml
- change android:value="fb0"

## :computer: Contributing

Contributions are very welcome. Please check out the [contributing document](CONTRIBUTING.md).

## :bookmark: License

This project is [MIT](LICENSE) licensed.
