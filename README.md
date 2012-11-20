webkit-developer-tools-dark-theme
=================================

Obsidian Dark theme for Chrome Developer Tools

## Install

Copy Custom.css into:

* Mac OSX 
```sh
  ~/Library/Application Support/Google/Chrome/Profile 1/User StyleSheets/Custom.css
```
* Windows 
```cmd
  %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\Custom.css
```
* Ubuntu 
```sh
  ~/.config/chromium/Default/User StyleSheets/Custom.css
```


## Build

* Download & install [NodeJS](http://nodejs.org/download/)
* Install Stylus
```sh
  npm install stylus -g
```
* Compile to css
```sh
  stylus < Custom.styl > path\to\Custom.css
```
