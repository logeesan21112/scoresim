<div align="center">
  <h1>ScoreSim</h1>
  <p>A cricket score tracking mobile application built with React Native and Expo.</p>

  ![React Native](https://img.shields.io/badge/React_Native-0.81.5-61DAFB?style=flat&logo=react)
  ![Expo](https://img.shields.io/badge/Expo-54.0.32-000020?style=flat&logo=expo)
  ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat&logo=javascript)
  ![AsyncStorage](https://img.shields.io/badge/AsyncStorage-2.2.0-4A90E2?style=flat)
</div>

---

## About

ScoreSim is a mobile application for cricket fans to track live scores and upcoming matches. It allows users to register and login, browse upcoming international cricket matches, view live scoreboards with batting and bowling statistics, and manage their profile — all in a clean and responsive mobile UI.

---

## Features

- User registration and login with local storage
- Upcoming matches list with team flags and match time
- Live score view with batting and bowling scorecards
- Accordion style expandable scoreboard per team
- Run rate calculation per innings
- Bottom tab navigation with Matches, Live, Profile and Logout
- Custom reusable components — Button, TextInput, Header
- Support for 8 international cricket teams with flag assets

---

## Screenshots

<div align="center">

<table>
<tr>
<td align="center"><b>Login</b></td>
<td align="center"><b>Register</b></td>
</tr>
<tr>
<td><img src="ADD_YOUR_SCREENSHOT_LINK_HERE" width="100%"/></td>
<td><img src="ADD_YOUR_SCREENSHOT_LINK_HERE" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Upcoming Matches</b></td>
<td align="center"><b>Live Score</b></td>
</tr>
<tr>
<td><img src="ADD_YOUR_SCREENSHOT_LINK_HERE" width="100%"/></td>
<td><img src="ADD_YOUR_SCREENSHOT_LINK_HERE" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Profile</b></td>
<td align="center"></td>
</tr>
<tr>
<td><img src="ADD_YOUR_SCREENSHOT_LINK_HERE" width="100%"/></td>
<td></td>
</tr>
</table>

</div>

---

## Tech Stack

**Mobile**
- React Native 0.81.5
- Expo SDK 54
- React Navigation (Native Stack and Bottom Tabs)
- AsyncStorage
- Expo Vector Icons
- JavaScript ES6

---

## Project Structure

```
scoresim/
├── assets/
│   ├── flags/
│   │   ├── australia.png
│   │   ├── england.png
│   │   ├── india.png
│   │   ├── newzealand.png
│   │   ├── pakistan.png
│   │   ├── southafrica.png
│   │   ├── srilanka.png
│   │   └── westindies.png
│   ├── icon.png
│   ├── logo.png
│   └── splash-icon.png
├── common/
│   └── config.js
├── components/
│   ├── Matches/
│   │   ├── Accordion.js
│   │   ├── Batting.js
│   │   ├── Bowling.js
│   │   ├── MatchCard.js
│   │   └── ScoreBoard.js
│   ├── Button.js
│   ├── CustomHeader.js
│   └── CustomTextInput.js
├── navigation/
│   └── BottomTabs.js
├── screens/
│   ├── Main/
│   │   ├── LiveScore.js
│   │   └── UpcomingMatches.js
│   ├── Login.js
│   ├── Profile.js
│   └── Register.js
├── App.js
├── app.json
├── index.js
└── package.json
```

---

## Getting Started

### Prerequisites
- Node.js 18+
- Expo Go app on your phone or Android emulator
- npm or yarn

### Run the Application

1. Clone the repository
```
git clone https://github.com/logeesan21112/scoresim.git
```

2. Navigate to the project folder
```
cd scoresim
```

3. Install dependencies
```
npm install
```

4. Start the development server
```
npx expo start
```

5. Scan the QR code with **Expo Go** app on your phone or press `a` for Android emulator

---

## Author

**Logeesan R.**
- GitHub: [@logeesan21112](https://github.com/logeesan21112)
- Email: r.logeesan21112@gmail.com

---

## License

This project is open source and available under the MIT License.