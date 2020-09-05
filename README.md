# ErrorsList

E1
FirebaseError: Firebase: Firebase App named '[DEFAULT]' already exists (app/duplicate-app).

Solution

if (!firebase.apps.length) {
  firebase.initializeApp(fConfig);
}

