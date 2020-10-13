# smarta-system
Kursen tillämpad programmering och smarta system.<br>
Här finns relevanta resurser för kursen. Utöver det finns ett referens-projekt som kan vara intressant att kolla på.<br><br>
**Github till referensprojekt:** <https://github.com/abbjetmus/happy-visit><br>
**Länk till referensprojektets hemsida:** <https://happy-visit-c8747.web.app/#/><br>

Before running Quasar reference application
Firebase from Google is used to authenticate and store some data in realtime. Since we don’t want to check-in keys for firebase to the repository we use a quasar extension called dotenv. So install the extension by running.
<br><br>
```$ quasar ext add @quasar/dotenv```
<br><br>
Follow the prompts, and when the last prompt entitled: "Name of your Common Root Object", be sure to name it "firebaseConfig". This will be the object that is stored in process.env object and will be loaded into Fireabse's initializeApp method. (/src/boot/firebase.js).
You will need to create the two files that you specified during the prompts. Named ".env.dev", and ".env.prod". Once these files are created paste the API keys from the Firebase console into those files. Be sure to remove all spaces, colons, and commas. It should look like this: 
```apiKey="AIzaSyAWK_j2342342dfgsdfgdsfgdfg"
authDomain="example.firebaseapp.com"
databaseURL="https://example.firebaseio.com"
projectId="example"
storageBucket="example.appspot.com"
messagingSenderId="6084123123123"
appId="1:6084234234:web:12312312312"
```

Also, be sure to add these files to your .gitignore file. By no means are your keys hidden as they are public on your frontend application, but it's just good practice not to check in your env files.

## Vue.js
[Vue.js dokumentationssida](https://vuejs.org/v2/guide/)

## Vuex
[Vuex dokumentationssida](https://vuex.vuejs.org/)

## Vue Router
[Vue Router dokumentationssida](https://router.vuejs.org/)

## Quasar
### Dokumentation
[Quasar dokumentationssida](https://quasar.dev/start/pick-quasar-flavour)

### Youtube
[Quasar - Make Apps With Danny](https://www.youtube.com/channel/UC6eR_ndNgaTeE5t2Ud4ZiHw)

### Artiklar
[Quasar - Firebase Tutorial - 3 delar](https://dev.to/quasar/to-the-stars-with-quasar-firebase-initial-service-structure-1fcf)

## Firebase
[Firebase dokumentationssida](https://firebase.google.com/)

## Firestore
[Firestore dokumentationssida](https://firebase.google.com/docs/firestore)

Hur man jobbar i och strukturerar upp data i Firestore m.m.: <https://www.youtube.com/playlist?list=PLl-K7zZEsYLluG5MCVEzXAQ7ACZBCuZgZ><br>
Kolla speciellt på första videon.

## Firebase Hosting
Era applikationer kommer hostas dvs göras åtkomliga via internet genom att läggas upp på Firebase Hosting.
Följande länk förklarar hur man hostar en Quasar app.
[Firebase Hosting a Quasar App](https://medium.com/@venkyvb/deploy-a-quasar-app-to-firebase-hosting-cf7b26fdc31d)

## VueFire
[VueFire dokumentationssida](https://vuefire.vuejs.org/)

## VuexFire
[VuexFire dokumentationssida](https://vuefire.vuejs.org/vuexfire/)
