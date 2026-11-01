# BLUEVERSE — Play. Create. Share.

A responsive front-end prototype for a game discovery and creator platform.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari).
3. No build step is required. An internet connection is only needed for the Google Fonts import; the site otherwise runs locally.

## Included
- Blue-themed responsive game discovery page with 999 generated game listings.
- Category filters and search.
- A playable crystal-collecting movement demo (keyboard arrows / A-D, plus on-screen buttons).
- Demo account creation and login, username, and a forgot-password information flow.
- Creator Studio with visual tools, theme settings, asset placement, a code editor and publish flow.
- Local demo chat panel.

## Important prototype limits
This is a front-end demo, not a production online game service:
- The 999 catalog entries are generated sample listings. The included play experience is a small reusable demo, not 999 unique finished games.
- Accounts, projects, chat and published entries are stored only in the current browser using local storage. They are not shared between devices or users.
- The password is hashed before local storage, but local browser storage is not a secure production authentication system.
- Forgot password cannot send email. Publishing does not make a game public on the internet.
- The code editor saves code as text and does not execute custom code.
- The game characters are stylized illustrations, not photorealistic people.

## To make it a real public platform
You would need a hosted backend, secure authentication, database, moderation/reporting tools, file storage, game runtime/sandboxing, and multiplayer networking. Never collect real users' passwords in a static website.
