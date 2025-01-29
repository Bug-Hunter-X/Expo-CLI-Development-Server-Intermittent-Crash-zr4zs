# Expo CLI Development Server Intermittent Crash

This repository demonstrates a bug where the Expo CLI development server crashes intermittently without providing any error messages. The application also becomes unresponsive on the device/simulator.

## Bug Description

The Expo development server randomly crashes during development, making it difficult to track the root cause. No error messages or stack traces are logged to the console. The application on the connected device or simulator becomes unresponsive as well.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `expo start` to start the development server.
4. Observe that after some time, the development server crashes and the application becomes unresponsive.

## Solution

The solution involves improving error handling within the application's code and potentially updating Expo's CLI to increase logging.

This example repository might not contain the specific root cause, as it's an intermittent issue. It highlights the need for better error handling to help identify potential causes of such random crashes.