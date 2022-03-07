# Installation Steps

## Using npm

Run commands

1) ```npm install```


2) ```npm run dev```


## Or using yarn

Run commands 

1) ```npm install --global yarn```

2) ```yarn install```

3) ```yarn run dev```

## Setup Local Environment and Firebase Config with Amazon

You need to setup a few keys for this project to be setup correctly otherwise you won't see any products or ... .

- [GOOGLE_ID]
- [GOOGLE_SECRET]
- NEXTAUTH_URL=http://localhost:3000

For that, you can create a .env.local file in your project as [shown in docs](https://nextjs.org/docs/basic-features/environment-variables#loading-environment-variables)

and in firebase.js you need add your firebaseConfig like this:
 
  apiKey: '',
  authDomain: '',
  projectId: '',
  storageBucket: '',
  messagingSenderId: '',
  appId: ''
