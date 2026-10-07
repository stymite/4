# LearnHub

React Native (Expo) learner app: sign up / log in, browse books from the Open Library API, details, favorites persisted in local storage, settings menu and notifications.

- User stories: [USER_STORIES.md](USER_STORIES.md)
- Screenshots: [evidence/](evidence/)
- Design boards: `evidence/figma-evidence1.png`, `evidence/figma-evidence2.png` (composed from the app screens, not exported from Figma)

## Code map (`app/`)

| Feature | File |
| --- | --- |
| Sign up | `app/src/screens/SignupScreen.js`, `app/src/AuthContext.js` |
| Log in | `app/src/screens/LoginScreen.js`, `app/src/AuthContext.js` |
| Home | `app/src/screens/HomeScreen.js` |
| Detail | `app/src/screens/DetailScreen.js` |
| Local storage | `app/src/storage.js`, `app/src/AppContext.js` |
| API integration | `app/src/api.js` |
| Settings menu | `app/src/components/SettingsMenu.js` |
| Settings screen | `app/src/screens/SettingsScreen.js` |
| Notifications | `app/src/notifications.js`, `app/src/screens/NotificationsScreen.js` |

## Run

```
cd app
npm install
npx expo start      # press w for web, or scan the QR code with Expo Go
```
