# Drink Water Reminder

A mobile app idea for reminding people to drink water throughout the day, built with **React Native**.

> **Status:** just started. The `frontend/` folder is a fresh React Native 0.63 project (still the default starter screen) and `backend/` is an empty placeholder. No reminder features have been implemented yet.

## Structure

```
drink-water-reminder/
├── frontend/   # React Native app (Android & iOS)
└── backend/    # Reserved for a future API
```

## Running the app

Requirements: Node.js, Yarn, and a working [React Native environment](https://reactnative.dev/docs/0.63/environment-setup) (Android Studio and/or Xcode).

```bash
cd frontend
yarn install
yarn start            # Metro bundler
yarn android          # in another terminal: run on Android
yarn ios              # or run on iOS (macOS only)
```

## Roadmap

- [ ] Configure daily water goal
- [ ] Scheduled reminder notifications
- [ ] Log water intake and show daily progress
- [ ] Back-end to sync data
