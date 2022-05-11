# Screen Checklist

In general, when you add/update functionality, you want to ensure that you don't _overwrite_ anything or _create bugs_. The best way to do that as a developer when you cannot count on a QA colleague to support you is to create a checklist to go through every time before you merge a PR.

The easiest way to maintain these checklists to create them as you go, so every time you add a feature or an update, add or update the checklist so that you don't overwrite/lose functionality and have to come back later to fix a "bug."

Here's an example of an *account screen* checklist:
- When you're on the account tab, the icon is focused
- Avatar, Name, Bio should display
- Logout button should log you out of app
- Edit button should open input to edit
- There's a loader if the content isn't yet loaded

Here's an example of a *search screen* checklist:
- When you type in the input to type a search term, the keyboard should pop up
- When you type in a search term you should see dynamic search suggestions below the input
- When you tap a suggested search term or hit enter on the keyboard, the search results should populate
- When you hit the X on the search input, the keyboard closes and the search is reset
- There's a loader if the content isn't yet loaded

Here's an example of a *home screen* checklist:
- Notifications are up to date
- Content is available in list form
- When you're on the home tab the home icon is focused
- The user has the content associated with their account loaded
- There's a loader if the content isn't yet loaded
