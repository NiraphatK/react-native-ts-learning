# React Native with TypeScript — ITE-434

This repository contains source code and exercises developed with **React Native** using **TypeScript**, created for the **Hybrid Application Development (ITE-434)** course. The focus is on building mobile applications that are maintainable, scalable, and cross-platform.

## Course Info

- **Course Code:** ITE-434
- **Course Title:** Hybrid Application Development
- **Level:** Undergraduate
- **Language:** TypeScript
- **Framework:** React Native

## Contents

- Project Structure and TypeScript Configuration
- Functional Components & Type Annotations
- State Management with `useState`, `useReducer`
- Navigation with React Navigation
- Props and Custom Types
- List Rendering with `FlatList`
- Form Handling and Validation
- Styling with `StyleSheet` and custom theming
- API Integration (with `fetch` or Axios + types)
- Assignments

## Tools & Technologies

- **TypeScript** — Typed superset of JavaScript
- **React Native** — Cross-platform app framework
- **Expo** — Simplified development workflow
- **VS Code** — Source-code editor

## Getting started

This repository uses **Expo SDK 51**. Use Node.js/npm and an Expo client or development build compatible with that historical SDK. The latest Expo Go client may not support it; upgrading Expo is a separate code change.

```bash
git clone https://github.com/NiraphatK/react-native-ts-learning.git
cd react-native-ts-learning
npm ci
npx expo start
```

Press `a` for a configured Android emulator, `i` for an iOS simulator on macOS, or use an SDK-compatible client on a device. The scripts in `package.json` also expose `npm run android`, `npm run ios`, and `npm run web`.

## Exercise index

- `App.tsx` is the active application entry point.
- `App1.tsx` and other root `App*.tsx` files are alternative exercises; they are not separate applications.
- `components/` contains reusable UI and component examples.
- `screens/` contains screen/navigation examples.
- `TypeScriptExample/` contains standalone TypeScript examples and compiled JavaScript.
- `services/`, `auth/`, and `redux-toolkit/` contain API and state-management exercises.

To try a different root exercise, back up your local changes and select its component from `App.tsx`. Some exercises require external APIs or a local backend; inspect their service URLs before running. This is a collection of course exercises, so not every alternative example is wired into the current app. No automated test script is defined; check the selected exercise in the emulator/device.
