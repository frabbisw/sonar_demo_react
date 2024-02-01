<p align="center">
  <img alt="banner" src="https://github.com/vanGalilea/react-native-testing/assets/25864161/fd4d5148-4c8d-4fbc-8ebf-367d72da4fcb">
</p>

## No More Hacks and Headaches <> Learn How to Test Your Components Before Your Users Will 

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=vanGalilea_react-native-testing&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=vanGalilea_react-native-testing)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=vanGalilea_react-native-testing&metric=coverage)](https://sonarcloud.io/summary/new_code?id=vanGalilea_react-native-testing)
[![Unit Testing](https://github.com/vanGalilea/react-native-testing/actions/workflows/unit-testing.yml/badge.svg)](https://github.com/vanGalilea/react-native-testing/actions/workflows/unit-testing.yml)
[![E2E Testing](https://github.com/vanGalilea/react-native-testing/actions/workflows/e2e-testing.yml/badge.svg)](https://github.com/vanGalilea/react-native-testing/actions/workflows/e2e-testing.yml)

### Covered Examples 🎞
- 👆 [Clicking buttons and asserting onPress' outcome](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/Counter.test.tsx).
- 📲 [Filling a simple login form and asserting successful submission](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/LoginSubmission.test.tsx).
- 🎣 [Custom hook testing (number of alternatives)](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/CounterUsesCustomHook.test.tsx).
- 📡 [Mocking fetch calls](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/LoginSubmission.test.tsx#L36).
- 🧭 [Navigating through screens with React Navigation](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/LoginSubmission.test.tsx#L13).
- 🚟 [Navigating through screens with Expo Router](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-expo-app/__tests__/app/index.test.tsx).
- 🔚 [E2E feel due to real navigation throughout screens](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/Home.test.tsx).
- 📥 [Handling and mocking providers](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/src/test/test-utils.tsx).
- 📹 [Mocking external lib.'s components](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/Video.test.tsx).
- 🎭 [Mocking and interacting with RN's Modal component](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/Modal.test.tsx).
- 🧾 [Handling with a screen with RN's FlatList component](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/FlatList.test.tsx).
- 📡 [Using MSW to mock api calls and handling loading/errors](https://github.com/vanGalilea/react-native-testing/blob/main/apps/rn-cli-app/__tests__/ListWithFetch.test.tsx).

### Tools in use 🛠️
- [Jest](https://jestjs.io/)
- [React Native Testing Library](https://callstack.github.io/react-native-testing-library/)
- [Maestro](https://maestro.mobile.dev/)

### Setup and requirements 📋
- [RN- Setting up the development environment](https://reactnative.dev/docs/environment-setup)
- [Installing Maestro](https://maestro.mobile.dev/getting-started/installing-maestro)

## Getting Started 🚀
- Clone the repo ` git clone git@github.com:vanGalilea/react-native-testing.git`
- Run `yarn` to install dependencies
- Explore RN CLI app and/or Expo app's tests and source code that are relevant to your use case.


## RN CLI application
### How to run the tests 🏃‍♀️
- Run `cd apps/rn-cli-app` to navigate to the app folder
- Run `yarn test:unit` to run the unit tests 
- Run `yarn test:unit:dev` to run the unit tests in dev/watch mode
- Run `yarn test:unit:coverage` to run the tests and generate a coverage report

Make sure you have built and run the app in dev mode before running the e2e tests.
- Run `yarn test:e2e` to run the e2e tests
- Run `yarn test:e2e:dev` to run the e2e tests in dev/watch mode
- Run `yarn test:e2e:record` to run the e2e tests and record a video of the tests

### How to run the app 📱
- Run `cd apps/rn-cli-app` to navigate to the app folder
- Run `npx pod-install` to install iOS dependencies
- Run `yarn start` to start the metro bundler
- Click `i` to run the app on iOS simulator or `a` to run it on Android emulator

## Expo application
### How to run the tests 🏃‍♀️
- Run `cd apps/rn-expo-app` to navigate to the app folder
- Run `yarn test:unit` to run the unit tests

### How to run the app 📱
- Run `cd apps/rn-expo-app` to navigate to the app folder
- Run `yarn start` to start the metro bundler
- Click `i` to run the app on iOS simulator or `a` to run it on Android emulator

### Inspiration, resources and further reading 📚
- 📑 A blog by [Steve Galili]([url](https://github.com/vanGalilea)) on ["Where and How to Start Testing Your React Native App"](https://medium.com/@stevegalili/where-and-how-to-start-testing-your-react-native-app-%EF%B8%8F-and-how-to-keep-on-testin-ec3464fb9b41)
- 👏 Inspired by [Kent C. Dodds'](https://testingjavascript.com/) workshop [Test React Components with Jest and React Testing Library](https://github.com/testing-library/react-testing-library). 
For more info check [Epic React](https://epicreact.dev/).
- 📕 [React Native Testing Library](https://callstack.github.io/react-native-testing-library/)
- 🧑‍🔬️ [Jest](https://jestjs.io/)
- ️⚛️ [React Native](https://reactnative.dev/)
- 🗺 [React Navigation](https://reactnavigation.org/)
- 🛰 [MSW](https://mswjs.io/)

### Impression of the project 📸
https://github.com/vanGalilea/react-native-testing/assets/25864161/cdb6cdc7-7b28-4ecd-819f-52dd3c3d76c8

