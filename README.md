Built with React, Redux and hosted on firebase

[Live Demo](https://clone-e9372.web.app/)

## Steps to Setup firebase

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a new project (lets say project1) with your Google Account.
2. Add your app as a web app to firebase.  
    ![webapp register](https://imgur.com/kTsGVsG.png)
3. Click on next and proceed until you get `continue to the console` button
    ![step1](https://imgur.com/50b7VSE.png)
    ![step2](https://imgur.com/THZTiGl.png)

## Create a firestore DB

## Create an authentication to your app
1. Select Gmail AUthentication and AUthentication with Email and Other services

## Copy Firebase SDK
1. Go to your app settings and scroll down until you see Javascript SDK
2. Copy those configurations into `.env` file of your application or create a new file called `firebase.js` and paste into it.
