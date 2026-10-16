# Match the Members

A React Native learning project that turns member photos into a timed multiple-choice guessing game.

**Stack:** React Native, JavaScript, Expo, React Navigation.

### Gameplay
- View a photo and choose from four member names.
- Answer within a five-second round.
- Track correct answers and total attempts.
- Advance after answering or when time expires.

### Run locally
The repository uses Expo SDK 50 and includes a Yarn lockfile. Use an environment compatible with the checked-in dependencies.

Run `yarn install`, then `yarn start`. Open the app on a compatible device or simulator through the Expo development server. Additional scripts: `yarn ios`, `yarn android`, `yarn web`.

### Code map
- `App.js`: navigation and asset preloading.
- `screens/GameScreen.jsx`: rounds, answers, score, countdown.
- `screens/HomeScreen.jsx`: entry screen.
- `constants/`: member data and styles.
- `utils/`: array helpers.
- `assets/`: bundled images.

### Context
An MDB learning project. The source retains instructional comments and scaffold code.
