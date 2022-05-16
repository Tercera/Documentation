# App Polish

These are tasks you're going to want to go through when you're winding down a project, before you call everything "done" you want to make sure the user experience is also done. Make sure:

- The keyboard clears any inputs -- on iOS _and_ Android
- Any filters, or search terms, or any preferences a user can set in the app are re-set when they leave the screen, or when a process is completed, or whenever in the user story the UI should be reset
- Any screen icons (tab icons for example) are focused when they should be, and not focused when they shouldn't be
- If there's supposed to be a splash screen, make sure it works
- The text inside the inputs isn't squished or cut off on different size phones
- If a button is supposed to be disabled under certain conditions (until a user enters username or password for ex) it works as expected
- When the app goes to background / is closed, it opens up with the data that's expected (`redux-persist` or local storage for ex)
- No essential parts of the app get cut off on tall, short, wide, narrow phones -- you'll have to test on various simulators/emulators. For example, do the tab icons get cut off on phones with no notch? Does the header show on phones that do a have a notch?
- Does text wrap where it's expected to do so? You'll want to check on phones that are tall, short, wide, narrow.
- Are the app icons set up as expected? Do they work on iOS and Android?
- Is there a loading screen or some sort of UI telling the user that something is happening and they have to just sit tight?
- Push notifications are working as expected - you get them, if you tap on them they take you to the right screen, etc.
- Any sensitive user information is being stored as [securely](https://reactnative.dev/docs/security) as [possible](https://github.com/mCodex/react-native-sensitive-info).
- There's a "connection error" or some other kind of error when there's no wifi signal.
- You have removed all `console.log`s, notes, commented out code, anything that does not belong in production should be deleted.
 
