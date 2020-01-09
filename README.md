<h1 align="center">
  <a href="https://facebook.github.io/react-native/">
    React Native
  </a>
</h1>

<p align="center">
  <strong>Learn once, write anywhere:</strong><br>
  Build mobile apps with React.
</p>

<p align="center">
  <a href="https://github.com/facebook/react-native/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="React Native is released under the MIT license." />
  </a>
  <a href="https://circleci.com/gh/facebook/react-native">
    <img src="https://circleci.com/gh/facebook/react-native.svg?style=shield" alt="Current CircleCI build status." />
  </a>
  <a href="https://ci.appveyor.com/project/facebook/react-native/branch/master">
    <img src="https://ci.appveyor.com/api/projects/status/g8d58ipi3auqdtrk/branch/master?svg=true" alt="Current Appveyor build status." />
  </a>
  <a href="https://www.npmjs.org/package/react-native">
    <img src="https://badge.fury.io/js/react-native.svg" alt="Current npm package version." />
  </a>
  <a href="https://facebook.github.io/react-native/docs/contributing">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=reactnative">
    <img src="https://img.shields.io/twitter/follow/reactnative.svg?label=Follow%20@lmnguyenbt" alt="Follow @lmnguyenbt" />
  </a>
</p>

# React Navigation

[![npm version](https://badge.fury.io/js/react-navigation.svg)](https://badge.fury.io/js/react-navigation) [![CircleCI badge](https://circleci.com/gh/react-navigation/react-navigation/tree/master.svg?style=shield)](https://circleci.com/gh/react-navigation/react-navigation/tree/master) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://reactnavigation.org/docs/contributing.html)

React Navigation is born from the React Native community's need for an extensible yet easy-to-use navigation solution based on Javascript.

## Installation

See: https://reactnavigation.org/docs/en/getting-started.html

## Documentation

* The best way to learn is to follow the [Getting started guide](https://reactnavigation.org/docs/getting-started.html). It guides you through the fundamentals of React Navigation.
* The documentation includes solutions for common use cases in the "How do I do ...?" section, such as [tab navigation](https://reactnavigation.org/docs/tab-based-navigation.html) and [Redux integration](https://reactnavigation.org/docs/redux-integration.html).
* If you need to build your own navigator, [there's a section for that](https://reactnavigation.org/docs/custom-navigator-overview.html) too.
* The [API reference](https://reactnavigation.org/docs/api-reference.html) lists all public APIs.
* The [Community Resources](https://github.com/react-navigation/react-navigation/blob/master/COMMUNITY_RESOURCES.md) document lists some other resources submitted to us by people who use React Navigation. Feel free to open a pull request to add your resource to the list.
* You can contribute improvements to the documentation [in the website repository](https://github.com/react-navigation/react-navigation.github.io).

## What to expect?
* Once the project is initialized, in the project directory run expo install react-navigation react-native-gesture-handler react-native-reanimated react-native-screens, and you're ready to go! You can now continue to "Hello React Navigation" to start writing some code.
* The libraries we will install now are react-native-gesture-handler, react-native-reanimated, and react-native-screens. If you already have these libraries installed and at the latest version, you are done here! Otherwise, read on.

## createStackNavigator
* By default the stack navigator is configured to have the familiar iOS and Android look & feel: new screens slide in from the right on iOS, fade in from the bottom on Android. On iOS the stack navigator can also be configured to a modal style where screens slide in from the bottom.
* To use this navigator, ensure that you have react-navigation and its dependencies installed, then install react-navigation-stack.

## createBottomTabNavigator
* A simple tab bar on the bottom of the screen that lets you switch between different routes. Routes are lazily initialized -- their screen components are not mounted until they are first focused.
* To use this navigator, ensure that you have react-navigation and its dependencies installed, then install react-navigation-tabs.

## createDrawerNavigator
* To use this navigator, ensure that you have react-navigation and its dependencies installed, then install react-navigation-drawer.

## Layout Simple

### Home
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/home.PNG)
#### Scan
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/scan.PNG)
#### Search
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/search.PNG)

### Feed
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/feed.PNG)

### Message
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/message.PNG)

### Cart
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/cart.PNG)

### Login
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/login.PNG)

### Sign In
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/sign-in.PNG)

### Account
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/account.PNG)
#### Account Info
![simple](https://raw.github.com/lmnguyenbt/react-native-navigation-v4/master/simple/account-info.PNG)
