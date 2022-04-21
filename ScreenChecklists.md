In general, when you add/update functionality, you want to ensure that you don't _overwrite_ anything or _create bugs_. The best way to do that as a developer when you cannot count on a QA colleague to support you is to create a checklist to go through every time before you merge a PR.

Here's an example of an *account screen* checklist:
- When you're on the account tab, the icon is focused
- Avatar, Name, Bio should display
- Logout button should log you out of app
- Edit button should open input to edit

Here's an example of a *search screen* checklist:
- When you type in the input to type a search term, the keyboard should pop up
- When you type in a search term you should see dynamic search suggestions below the input
- When you tap a suggested search term or hit enter on the keyboard, the search results should populate
- When you hit the X on the search input, the keyboard closes and the search is reset
