# Firebase Function Kit test install

This is a bare project that was initialized with the following commands:
```
firebase init
firebase functions:kits:install --package @firebase-function-kits/firestore-bigquery-export@latest
```
The options chosen during both commands were fairly typical, mostly the defaults. I did tell `firebase init` to initialize functions.

The effects of the `firebase functions:kits:install` command were, as far as I can tell:
* The entire `function-kits/firestore-bigquery-export` directory was created, including installing its dependencies
* A section was added to `firebase.json` to deploy the function kit

I ran it under the emulator but haven't actually tested the functions.

This project mainly exists to illustrate what function kits do, since they're
not yet really documented. The
[`firestore-bigquery-export`](https://www.npmjs.com/package/@firebase-function-kits/firestore-bigquery-export)
kit is the only existing one that I'm even aware of.