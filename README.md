# Q-municate

[Q-municate](https://q-municate.com)  is an open source code chat application with wide range of communication features available (such as one-to-one messaging, group chat messaging, file transfers, notifications, Facebook signup and audio/video calls).

We are please to present you with an out of the box chat application. You can customize this application depending of your needs.
[QuickBlox](https://quickblox.com) is used for the backend.

Find the source code and more information about Q-municate in our Developers section: http://quickblox.com/developers/q-municate

# Q-municate Web
This description was written by the QuickBlox Web team in order to fully explain how you can build a communication javascript app with the Quickblox API.

Q-municate is designed for all developers, including beginners, as we move from simple to more complex implementation.
Enjoy and please get in touch if you need any assistance.

## Live demo

*Web - [Live app](https://qm.quickblox.com/)
*iOS - [App Store](https://itunes.apple.com/us/app/q-municate/id909698517?mt=8)
*Android - [Google Play](https://play.google.com/store/apps/details?id=com.quickblox.q_municate)
*WP - [Microsoft Store](https://www.microsoft.com/en-us/store/apps/q-municate-messenger/9nblggh5jqnb)

## Software Environment
* The web component is based on the QuickBlox platform
* The user interface is in English
* No crashes or exceptions are allowed
* The app immediately reacts to any user action or give notifications about each action which requires time to be processed
* User information is kept safely and securely.
* User's password is encoded and kept in the local storage.
* The App should work correctly in the following browsers:
   - Chrome 13+
   - Firefox 4+
   - Opera 17+
   - Safari 6.1+ (without audio, video calls)  
   - IE 10+ (without audio, video calls)

Q-municate is a fully fledged chat application using the Quickblox API.

## How to build your own Chat app
You can build your own chat app using Q-municate as a basis in just 5 minutes! All you need is to:

#### 1. Register a QuickBlox account
If you don't have one yet, just register your account at [https://admin.quickblox.com/register](https://admin.quickblox.com/register)

![Register your account](http://quickblox.com/developers//images/7/70/Register_your_account.jpg)

You can read more about how to create an account [here.](https://quickblox.com/developers/5_Minute_Guide#Create_your_QuickBlox_account)

#### 2. Login to QuickBlox admin panel
Login into admin panel at [https://admin.quickblox.com/signin](https://admin.quickblox.com/signin)
You can read more about how to sign in to admin panel [here.](https://quickblox.com/developers/5_Minute_Guide#Sign_in_to_the_admin_panel)

#### 3. Create a new app.
If you don't have an app yet, you can follow a detailed guide about app creation at [here.](https://quickblox.com/developers/5_Minute_Guide#Create_an_app_in_the_admin_panel)

#### 4. Get app credentials
Click on the app title in the list to reveal the app details. You are going to need App ID, Authorization key and Authorization secret later in our Q-municate source code.
[Info about app](https://quickblox.com/developers//images/e/e3/Info_about_app.jpg)

#### 5. Launch the Q-municate app
Just follow our platform-based guide [below.](https://quickblox.com/developers/Q-municate#Get_the_source)

## Setup environment
If you want to build your own app using Q-municate as a base, please do the following:

1. Install [nodeJS](https://nodejs.org/en/download/) and [Ruby](https://www.ruby-lang.org/en/downloads) before start.
2. Download the project from [GitHub](https://github.com/QuickBlox/q-municate-web/archive/master.zip).
3. Run <code>npm install -g bower</code> in your terminal as an administrator.
4. Run <code>gem install compass</code> in your terminal as an administrator.
5. Run <code>npm install -g grunt-cli</code> in your terminal as an administrator.
6. Run <code>bower install</code> to install all additional packages in your terminal.
7. Run <code>npm install</code> to install all additional packages in your terminal as an administrator.
8. Copy the credentials (App ID, Authorization key, Authorization secret) and your Facebook App ID ([How to generate and save Facebook application ID](https://quickblox.com/developers/How_to_generate_and_save_Facebook_application_ID)) into your Q-municate project code in ```config.js```.

[Js_qm_project](https://quickblox.com/developers//images/9/95/Js_qm_project.png)

## Build and run
1. Run <code>grunt build</code> or <code>grunt</code> (build with jshint verification) in your terminal to build Q-municate (q-municate-web/dist).
2. Run <code>grunt serve</code> in your terminal to open Q-municate in a browser window (https://localhost:9000).

[Gruntserve](https://quickblox.com/developers//images/7/7b/Gruntserve.jpg)

<!-- ### Important - how to build your own Chat app</h3>

If you want to build your own app using Q-municate as a base, please do the following:

 1. Download the project from here (GitHub)
 2. Run <code>sudo npm install -g bower</code> in your terminal
 3. Run <code>sudo gem install compass</code> in your terminal
 4. Run <code>sudo npm install -g grunt-cli</code> in your terminal
 5. Run <code>bower install</code> to install all additional packages in your terminal
 6. Run <code>sudo npm install</code> to install all additional packages in your terminal
 7. [Register a QuickBlox account](http://admin.quickblox.com/register) (if you don't have one yet).
 8. Login to the [QuickBlox admin panel](http://admin.quickblox.com/signin)
 9. Create a new app
 10. Click on the app title in the list to reveal the app's credentials:
   ![App credentials](http://files.quickblox.com/app_credentials.png)
 11. Create Facebook Application for ability connecting via Facebook
 12. Copy the credentials (App ID, Authorization key, Authorization secret) and your Facebook App ID into your Q-municate project code in <code>config.js</code><br />
 13. Run <code>grunt build</code> in your terminal to build Q-municate
 14. Run <code>grunt serve</code> in your terminal to run Q-municate


### Additional: how to build desktop version

 1. Download nw.js dependent to your system(Win, OS X, Linux) [NW.js](http://nwjs.io/).
 2. Add in 'package.json' after 'engines' section next lines:

 ```javascript
   "window": {
     "toolbar": false,
     "width": 1000,
     "height": 800
   },
   "main": "app/index.html"
   ```
 3. Run: $ /path/to/nw .  (suppose the current directory contains 'package.json'). Read more https://github.com/nwjs/nw.js#quick-start about OS X and Windows
 4. [How to package app](https://github.com/nwjs/nw.js/wiki/How-to-package-and-distribute-your-apps).

 -->
# License
Apache License
Version 2.0
