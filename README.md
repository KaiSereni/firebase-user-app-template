# Template for Firebase Apps with User Data

## Quickstart
* Install Python
* Install npm
* Install firebase-tools (`npm i -g firebase-tools`)
* Login with firebase-tools (`firebase login`)
* Create a Firebase project and enable billing
* Put your project ID in [.firebaserc](./.firebaserc)
* Put your project name in [package.json](./package.json)
* Create an app in Firebase project settings and put the config in [firebase.tsx](./src/app/firebase.tsx)
* Create a venv called `venv` in `./functions`, activate it, then install the requirements.txt
* Run `npm i` in the root
* To start the emulator, run `npm run emulate`. To deploy, run `firebase deploy`.
* Emulator UI is at `localhost:4000`, site is at `localhost:5002`.