# Integrating Firebase 3 with AngularFire2 into Angular2 & Ionic2

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/672f62a388844d3392eb0809d49937f5)](https://www.codacy.com/app/ciekawy/ionic2-angularfire-login?utm_source=github.com&utm_medium=referral&utm_content=ciekawy/ionic2-angularfire-login&utm_campaign=badger)

##Install
```
npm install
```

###Use your own Firebase Account
You will need to change the following code in `app.ts`
```
defaultFirebase({
    apiKey: "<your-key>",
    authDomain: "<your-project-authdomain>",
    databaseURL: "<your-database-URL>",
    storageBucket: "<your-storage-bucket>",
  })
```

##Integrate this project in your own project
Follow the instructions bellow that will teach you everything you need to know.
####[Installation & Setup](docs/install-and-setup-in-your-own-project.md)
####[Facebook Authentication](docs/facebook-authentication.md)

##This Application was tested with the following configuration
```
Your system information:

Cordova CLI: 6.0.0
Gulp version:  CLI version 3.9.1
Gulp local:   Local version 3.9.1
Ionic Framework Version: 2.0.0-beta.9
Ionic CLI Version: 2.0.0-beta.31
Ionic App Lib Version: 2.0.0-beta.17
ios-deploy version: 1.8.5
ios-sim version: 5.0.8
OS: Mac OS X El Capitan
Node Version: v5.6.0
Xcode version: Xcode 7.3.1 Build version 7D1014
```
