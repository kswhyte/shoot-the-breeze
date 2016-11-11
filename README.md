# Shoot The Breeze

In this project we set out to build a chat-box style app in which users could shoot the breeze with each other from a sign-in with google accounts on Firebase. Within each users account, upon sign-in, they are able to save up to 100 messages and view a list of users that are present in the chat room. Users are also able to filter through messages by message content, username, and date/time. They can sort messages by new or old, and can also sort messages by clicking a user that is present on the user-list. 

---
####Main Goals

All components must be tested using Enzyme - You do not need to test authentication.
App must be robustly tested using unit tests
Application must use Firebase to store chats
Webpack for build tools

---
###General Features:

An input field for typing messages
Input field has a character count
Character count is displayed next to input field
Submit and Clear buttons disabled appropriately
Submit and Clear are disabled when there is no content in the message input
Submit is disabled when the message is over 140 characters
List of users contributing to chatroom (based on the current messages being displayed)
User can filter by User by selecting user from list
User can filter/search for messages
User can sort in chronological or reverse chronological order
By default, messages are stored in chronological order
Chat messages display time stamp, user, and message

---
####Setup setups:

- Clone this repository.
- `npm install`
- Set up a new Firebase application.
- Replace the keys in `./lib/firebase.js`.
- Turn on Google authentication in the Firebase specification.
- Add the name of your project as the default in the .firebaserc file. This is the name you gave it in firebase, plus the string of characters that firebase appended, e.g. "shoot-the-breeze-aa5d9" 
- `npm start` or `npm test`.

---
If you're feeling chatty, maybe it's a good time to [Shoot the Breeze](https://shoot-the-breeze-b2fe6.firebaseapp.com/).
