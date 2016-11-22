Getting Started with Firebase - Democode

To deploy this demo-app on your own server, follow these steps:
* Install the firebase tools: `npm install -g firebase-tools`
* Login into your google account: `firebase login`
* Create a new project on firebase.google.com
* Activate the Google authentication method
* Clone or download this repository
* Change the name of the project in `.firebaserc` in line 3
* Copy the javascript-snippet with the project configs from console.firebase.google.com into `public/index.html` (press `Add Firebase to my web app`)
* Start the development-server using `firebase serve`
* Deploy your project using `firebase deploy`
