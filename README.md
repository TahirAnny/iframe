# Ionic 7 Angular Firebase Authentication Project

This project is an authentication system built using **Ionic 7**, **Angular**, and **Firebase**. It includes user registration, login, password reset, and user authentication using Firebase Authentication.

## Features

- User Registration
- User Login
- Password Reset
- Email Verification (yet to implement)
- Firebase Authentication Integration
- Responsive UI using Ionic Framework

## Table of Contents
- [Project Setup](#project-setup)
- [Firebase Configuration](#firebase-configuration)
- [Running the Project](#running-the-project)
- [Project Structure](#project-structure)
- [Commands](#commands)
- [Dependencies](#dependencies)

## Project Setup

### Prerequisites

Make sure you have the following installed on your system:

1. **Node.js**: Download and install from [Node.js](https://nodejs.org/).
2. **Ionic CLI**: You can install it globally using npm:
   ```bash
   npm install -g @ionic/cli
3. **Angular CLI**: Install the Angular CLI globally:
   ```bash
   npm install -g @angular/cli
4. **Firebase Account**: Create a Firebase project at [Firebase Console](https://console.firebase.google.com/) and enable Firebase Authentication.
5. **Installing Dependencies**: To install all project dependencies, run the following command in the project's root directory:
   ```bash
   npm install

## Firebase Configuration

1. In the Firebase Console, create a new project or use an existing one.
2. Enable Email/Password authentication in the Firebase Console.
3. Generate your Firebase configuration by selecting **Project Settings > General > Your apps > Firebase SDK** snippet and select **Config**.
4. Add the Firebase configuration to your Angular environment file. Update **src/environments/environment.ts** with your Firebase config like so:
    ```bash
   export const environment = {
   production: false,
   firebaseConfig: {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_AUTH_DOMAIN",
        projectId: "YOUR_PROJECT_ID",
        storageBucket: "YOUR_STORAGE_BUCKET",
        messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
        appId: "YOUR_APP_ID"
      }
   };

## Running the Project

## Project Structure

## Commands
- `npm start`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run test`: Run the unit tests using Karma.
- `npm run lint`: Lint the project for code style issues.

## Dependencies
- Angular: ^18.0.0
- Ionic: ^8.0.0
- Firebase: For authentication.
- Capacitor: For accessing native device features.

For detailed information on each dependency, see the `package.json` file.