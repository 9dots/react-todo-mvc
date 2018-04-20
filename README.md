# TodoMVC Project

Complete this project in [codesandbox.io](https://codesandbox.io). Feel free to add any npm dependencies you deem necessary.

To get started:

1. Go to [codesandbox.io](https://codesandbox.io)
2. Sign in with github
3. Create a new project
4. Use the import from github feature to import this repository
5. Add the functionality listed below
6. When you have finished send the link to: daniel.leavitt@9dots.org

If you have any questions or issues while working on this project you can email daniel.leavitt@9dots.org

## Functionality

### Add Firebase

Sign up for a free [firebase](https://firebase.google.com) account. Enable the firestore database and google authentication (check the firebase docs for details). Set up the project to use your firebase project.

**Important: Because of codesanbox constantly rebuilding initialize the firebase project in a try catch block!**

```js
try {
  firebase.initializeApp(config);
} catch (e) {}
```

### Add Authentication

Add a login page that gets rendered if the user is not yet logged in. The user should be able to login using Google. There should also be a way for logged in users to sign out.

### Store Todos in Database

The project should store all todos in the firestore database. Logged in users should only be able to see their own todos. A user that is logged out should be redirected to the login screen.
