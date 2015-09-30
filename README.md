# Fabric iOS SDK

![platform iOS](https://img.shields.io/badge/platform-iOS-lightgray.svg)
![language Objective-C](https://img.shields.io/badge/language-Objective--C-blue.svg)

![Fabric iOS](https://flock.fabric.io/images/fabric_logo.png)

This private repo has been created to manually manage the [Fabric](https://fabric.io) framework. Unfortunately, the authors of Fabric do not provide access to a public repo, so we are linking this repository as a git submodule in order to manage the dependancy for the higi iOS app.

## Installation Instructions

- Add this repo as a submodule by running the following command in the terminal from the project root:

`git submodule add https://github.com/higish/ios-fabric.git ./Vendor/Fabric`

- Add the framework and bundle to your Xcode project. 

## Setup

- Follow the instructions in the [reference documents](https://docs.fabric.io/ios/fabric/getting-started.html)
- **NOTE: Be sure to follow instructions for advanced setup instructions as our submodule initialization does NOT put the framework in the project root!**


