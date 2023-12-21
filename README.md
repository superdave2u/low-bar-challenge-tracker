# Low Bar Challenge Tracker

## Overview

The Low Bar Challenge Tracker is a weight tracking application designed to encourage users to achieve their weight loss goals in a competitive yet supportive environment. The application allows users to record their weight and view their progress over time. A unique feature of this app is the "Low Bar" challenge, where users aim to beat their lowest weight from the previous week.

## Infrastructure

This application is built using AWS Amplify, which provides a robust backend including authentication, a GraphQL API, and a DynamoDB database. The frontend is developed with Vue.js, for a responsive and interactive user experience.

### Key Components

- **AWS Amplify**: Manages backend resources such as authentication, API, and database.
- **DynamoDB**: Stores user data and weight entries.
- **GraphQL**: Facilitates data retrieval and manipulation between the frontend and backend.
- **Vue.js**: Powers the frontend user interface.

## Use Cases

1. **User Weight Tracking**: Users can log their weight regularly.
2. **Weekly Target Calculation**: The application calculates a weekly target weight for each user.
3. **Progress Tracking**: Users can view their weight loss journey over time.
4. **Scoreboard Display**: A scoreboard shows all users' current targets and their success in meeting previous targets.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
