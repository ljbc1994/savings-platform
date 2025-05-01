# Sample Savings Platform List

## Project Setup

In order to get everything up and running, please follow these steps:

1. Clone this repo
2. Install dependencies

   ```bash
   npm install
   ```
3. Start the app for ios

   ```bash
    npm run ios
   ```
4. Start the app for android

   ```bash
    npm run android
   ```

## The Task

You've been given a PR to review by a junior engineer. The PR is a POC application for showing a list of saving accounts. It does not currently connect with any APIs.

### Out of scope (you can assume these things are ok)

- How the build / typescript / prettier is configured

### Requirements

The requirements for the final application are given below. For each one, can you find an example of where the requirement has been met, and an example of where it hasn't?

- TypeScript should be used to ensure data integrity.
- Basic accessibility standards should be met.
- The UI should display within the screen.
- The app should be responsive and highly performant, there is an excessive number of re-renders. How do we fix this?

### Additionally

- The app will connect to an api to get the list of savings, and like it does now it will poll regularly to ensure it has the latest savings. How should the data be managed once this is in place? Are there any alternatives to polling and what would be the benefits?
- We want to show the bank details on a separate screen, what would be the best way to get this information and display it on the page?

### Finally

What other problems / opportunities for improvement can you spot?
