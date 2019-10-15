# vue-vuetify-firebase-calendar

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### Check out https://jsfanatik.github.io to learn more about the VueStacks initiative!

![alt text](https://raw.githubusercontent.com/jsfanatik/jsfanatik.github.io/master/assets/cal-screen.JPG)

![alt text](https://raw.githubusercontent.com/jsfanatik/jsfanatik.github.io/master/assets/cal-screen4.JPG)

### Описание

Проект реализует возможность создавать события привязанные к календарю, с сохранением информации в firebase
Компоненты - Vue, Vuetify, Firebase

### Addition Dependencies

### Setting Up Firebase

1. Set up a new project in Firebase with Database enabled.
2. Implement the following Firebase SDK scripts in main.js:

```
import firebase from "firebase";
firebase.initializeApp({
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: ""
});

export const db = firebase.firestore();
```
