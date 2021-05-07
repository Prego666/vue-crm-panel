# Simple Vue 2 CRM App

[Demo](https://vue-admin-panel-oio.web.app/)

## Project setup
```
npm install
```

## Firebase settings
1.  Register in [firabase](https://firebase.google.com/)
2.  Add new project in the [console](https://console.firebase.google.com/).
3.  Create new Realtime Database and Authentication with Email/Password.
4.  Add your firebaseConfig object in src/main.js:
```js script
  firebase.initializeApp({
    yourFirebaseConfig
  })
```


### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
