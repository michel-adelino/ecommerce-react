E-commerce React app built with Firebase and TypeScript.

![Firebase Deploy](./assets/firebase-deploy-badge.svg)

![Screenshot 1](./static/screeny1.png)
![Screenshot 2](./static/screeny2.png)
![Screenshot 3](./static/screeny3.png)
![Screenshot 4](./static/screeny7.png)

---

## Run Locally

### 1. Install Dependencies

`yarn install`


### 2. Create a New Firebase Project
Sign in to your Google account and create a new Firebase project [here](https://console.firebase.google.com/).

Create a `.env` file in the project root directory and add your Firebase configuration:

`FIREBASE_API_KEY=your-api-key`
`FIREBASE_AUTH_DOMAIN=your-auth-domain.firebaseapp.com`
`FIREBASE_DB_URL=https://your-database-url.firebaseio.com`
`FIREBASE_PROJECT_ID=your-project-id`
`FIREBASE_STORAGE_BUCKET=your-storage-bucket.appspot.com`
`FIREBASE_MSG_SENDER_ID=your-sender-id`
`FIREBASE_APP_ID=your-app-id`


After setting up the configuration, create a **Cloud Firestore** database and start it in **test mode**.

### 3. Run Development Server
`yarn dev`

---

## Build the Project
`yarn build`


---

## Admin Product Management (CRUD)
1. Navigate to `/signup` on your local or deployed site.  
2. Create a new account.  
3. In your Firestore **users** collection, update the `role` field for this user from `USER` to `ADMIN`.  
4. Re-login to apply changes.

Firebase Admin integration will be added in a future update.

---

## Features

- Admin CRUD operations  
- Firebase Authentication  
- Provider Authentication  
- Account creation and profile management


