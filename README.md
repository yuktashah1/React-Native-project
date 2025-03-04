Running the Project
To get started with the ProductApp project, follow these steps:

1. Clone the Repository
First, clone the repository to your local machine:
git clone https://github.com/your-username/ProductApp.git
cd ProductApp

2. Install Dependencies
Install the project dependencies using either npm or yarn:
npm install
or
yarn install

3. Start the Development Server
Start the Expo development server:

npx expo start
This command will open a new tab in your default web browser with the Expo Developer Tools. You can also see the QR code in the terminal to scan with the Expo Go app on your mobile device.

4. Run on Mobile Device
To run the app on a mobile device, make sure you have the Expo Go app installed:

Expo Go for iOS
Expo Go for Android
Scan the QR code displayed in the Expo Developer Tools with the Expo Go app.

5. Run on Android Emulator
To run the app on an Android emulator, use the following command:

npx expo start --android

6. Run on iOS Simulator
To run the app on an iOS simulator (Mac only), use the following command:

npx expo start --ios

7. Run on Web
To run the app in a web browser, use the following command:

npx expo start --web

8. Reset Project
If you need to reset the project to its initial state, you can run:

npm run reset-project

This will move the current app directory to app-example and reset the project.

