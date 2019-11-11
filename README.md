# React Firebase Web App
Firebase abstracts away the need to worry about the backend and administration portal, giving full freedom to explore the possibilities on the frontend.

React is the most versatile CSS UI creation tool by far, allowing for general interface to be made virtually on any device and any platform. Now with the worries of backend removed.

### See my other repos for implementations on other plaforms
**electron-firebase:** [https://github.com/darknesszy/electron-firebase](https://github.com/darknesszy/electron-firebase)
**NativeFirebase:**
# Installation
Repo is open sourced and can be pulled from Github
## Install dependencies
    npm install
    npm install -g firebase-tools
## Firebase credentials
The firebase app key can be located from your firebase project page.
Create a file named **keystore.ts** in the **/src** directory and copy the following in
```js
    export const firebaseKey = {
        apiKey: /* ...API KEY */,
        authDomain: /* ...DOMAIN */,
        databaseURL: /* ...DATABASE */,
        projectId: /* ...PROJECT ID */,
        storageBucket: /* ...STORAGE */,
        messagingSenderId: /* ...SENDER ID */,
        appId: /* ...AP ID */
    }
```
# Usage
## Running the app
    npm start