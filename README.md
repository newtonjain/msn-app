# MSN App in Cordova

An application built using Apache Cordova. Msn.com is imply launched in a web view.

## Important!
To learn more about Tools for Apache Cordova, visit this [link](https://taco.visualstudio.com/).

## Table of Contents
 - [Requirements](#requirements)
 - [Getting Started](#getting-started)
 - [File Structure of App](#file-structure-of-app)

## Requirements
1. node.js
2. Cordova - npm install cordova

## Getting Started

With VS Code:
* Clone this repository.
* Run `npm install` from the project root.
* Add android / iOS / windows platform to your project by running `cordova platform add <platform name>` in a terminal from your project root.
* Build the project by running gulp tsc and then `cordova build <platform name>`
* Deploy to device or emulator by running `cordova run <platform name>` or `cordova emulate <platform name>`
* Success


## File Structure of App

```
MSN-APP/
|
├── platforms/                         * Cordova generated native platform code
|
├── plugins/                           * Cordova native plugins go
|
├── resources/                         * Images for splash screens and icons
|
├── www/                               * Folder that is copied over to platforms www directory
│   │   
│   ├── js/                            * Contains JS files             
│   │    └── index.js                
│   │
│   ├── css/                           * Compiled CSS
│   │
│   ├── img/                           * App images
│   │
│   └── index.html                     * Main entry point
|
├── .gitignore                         * Example git ignore file
├── config.xml                         * Cordova configuration file
└── README.md                          * This file
```

