# MaestroTesting

Step 1: Install Node.js and npm
Ensure that you have Node.js and npm (Node Package Manager) installed on your machine. You can download and install them from the official website: Node.js

Step 2: Install React Native CLI
Open a terminal and run the following command to install the React Native CLI globally

Step 3: Install Java Development Kit (JDK)
React Native requires JDK to build Android applications. Download and install the latest version of JDK from the official Oracle website

Step 4: Install Android Studio
Download and install Android Studio from the official website: Android Studio

Step 5: Configure Android Environment Variables
Add the following environment variables to your system:

ANDROID_HOME: Path to your Android SDK directory
PATH: Append the tools and platform-tools directories inside the Android SDK to the PATH variable

Now after installing all the paths and pre-requisites Install the ignite boilerplate
write this code in terminal:
npx ignite-cli@latest new PizzaApp --yes

Install Maestro and Other Dependencies for Testing
Install Maestro and any other necessary dependencies for testing your React Native application:

Refer to Maestro Website for installation

Step 11: Write Maestro Tests
Create test files in your project with the .test.js extension, and write tests using Maestro. For example:

javascript
// __tests__/App.test.js
import React from 'react';
import { render } from '@testing-library/react-native';
import App from '../App';

test('renders correctly', () => {
  const { getByText } = render(<App />);
  const textElement = getByText('Welcome to React Native!');
  expect(textElement).toBeDefined();
});
Step 12: Run Maestro Tests
Execute Maestro tests using the following command:


npx maestro test
# This command will run all tests in your project.

![Screenshot (258)](https://github.com/rahuljethwa1411/MaestroTesting/assets/86496269/c96683ad-54df-4b00-bf85-7bc5a21027e3)
<img width="287" alt="image" src="https://github.com/rahuljethwa1411/MaestroTesting/assets/86496269/c06b179c-225c-4d98-90b3-0fa3263a3449">
<img width="725" alt="image" src="https://github.com/rahuljethwa1411/MaestroTesting/assets/86496269/535004b8-1e83-4ac9-815a-14726da03a08">
<img width="533" alt="image" src="https://github.com/rahuljethwa1411/MaestroTesting/assets/86496269/4d6043de-c1a0-4250-8d13-8bf19f1460af">




