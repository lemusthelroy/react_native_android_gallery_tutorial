# React Native Android Gallery Tutorial

This document is to act as a guide in setting up your development environment for the React Native Android Gallery Tutorial.

## Step 1 - Install / Switch to Correct Node Version

Currently (10/01/2020), React Native will only run on at least V.10 but no greater than V.12.9.

If you prefer having the most up to date version of node on your machine, and would like to toggle Node versions when using React Native. Following the following steps:-

- **Windows** - Use [NVM-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades) to be able to switch between versions at will. You will need to unistall Node and npm for this to work.
- **macOS/Linux** - Use [n](https://github.com/tj/n) to be able to switch between versions at will.

## Step 2 - Follow the Docs - _React Native CLI Quickstart_

To date, we have chosen not to use Expo to build our app with React Native, instead following the **React Native CLI Quickstart** route.

You should therefore follow the setup steps outlined in the React Native document, which is fairly easy to follow - [https://facebook.github.io/react-native/docs/getting-started](https://facebook.github.io/react-native/docs/getting-started).

Make sure you follow the step to create your virtual device.

## Step 3 - Get your virtual device running

It is best not to have more than one virtual device running at the same time.

## Step 4 - Yarn Install

Run `yarn` to install all of the packages for this application

## Step 5 - Start the App

Run `yarn react-native run-android` or `yarn start`

## Gotchas

- If your packager server (Metro Bundler) keeps crashing or you keep getting messages like 'Ensure that the packager server is running' on the emulator. Run `yarn react-native start` in separate terminal or in detached mode.
