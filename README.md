# quickshop-iOS

An iOS application for customers in an Amazon-Go like shop. 
Before shopping at Quickshop, you need to install this app and register as a member.

![Sign up](https://github.com/chowqianrui/quickshop-iOS/Images of App/Welcome to Quickshop.jpg) 

## What is Quickshop?
Quickshop is a fully automated store with a central server, facial and object recognition services and a blockchain to store transactions. 

Watch a [2-min video](https://drive.google.com/open?id=10WxXBZ6VBQkPQ_6jUOg-EpGc8D8tCP6v) to know how Quickshop works!

## How to see the application running on your iOS device? 
1. Git clone this project
2. Open ImagePicker.xcworkspace on xcode
3. Select Product -> Run, to run and build the project

## How this project came about?
A team of 4 awesome UBC Computer Engineering students (including me!) came up with Quickshop which was inspired by Amazon-Go. 

## Quickshop-iOS file structure: 
- FaceDetector.swift: This file contains functions that detects the location of parts of the face

- MyAccountViewController.swift: This view controller manages the display of the logged in user's profile picture and username

- ViewController.swift: This view controller manages the registration user interface (face counts, picture uplaod etc.)

- CheckAVAuthorizationStatus.swift: File for Permission to use Camera in iPhone

- Main.storyboard: visual representation of the user interface of an iOS application, showing screens of content and the connections between those screens

- Assets.xcassets: Catalog to store icons and shop logo

- Info.plist: a structured text file that contains essential configuration information for the bundled app executable

- LoginViewController.swift: This view controller manages the user interface of login page

- MainMenuViewController.swift: This view controller manages the user interface of the main menu display

- BlockchainViewController.swift: This view controller manages the webview of blockchain transaction history

- AlamofireHTTPCalls.swift: Contains Get and Post call functions with Alamofire

- CartViewController.swift: Current user cart display user interface is managed by this view controller
