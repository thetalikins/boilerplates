# React and Redux Boilerplate

#Usage
Copy the contents of this directory into your fresh app directory when you wanna build a react-and-redux app.  Then, within that app directory:

```
npm install
npm run build
npm start
```

This will open up the app at `localhost:3000`

# Knowing it works

The basic boilerplate should show a peachpuff page with indigo text that says, 'Welcome to Charlietown.  This is who it is all about: charlie.'  If you inspect it using the redux developer tools, you'll see there is a property within the state called `theGoodMan` whose value is charlie.  

You can send a dispatch to change the nickname of theGoodMan.  The dispatch will look like so:
```
type: 'CHANGE_NICKNAME',
nickname: 'whatever nickname you wanna put here'
```

When dispatched, charlie should change to your new nickname.  This will confimr that you have a working app whose components are built in redux, that are aware of state, and you can dispatch actions.

# Gotchas

The index.html page is all coded up for the app `charlietown`, you'll wanna change the meta tags for whatever your new app is called.
