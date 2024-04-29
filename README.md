# Weather-App-React-Native



## Get Started

install dev dependencies

### `npm install` or `yarn install`

## Then

go to https://www.weatherapi.com . create an account and get the api key then use that api key in constants/index.js file

## Then

Run The app

### `npm run start` or `yarn run start`

Runs your app in development mode.

Open it in the [Expo app](https://expo.io) on your phone to view it. It will reload if you save edits to your files, and you will see build errors and logs in the terminal.

#### `npm run android` or `yarn run android`

Like `npm start` / `yarn start`, but also attempts to open your app on a connected Android device or emulator. Requires an installation of Android build tools 

<br />

## Key decision

Building with React Native: I opted to develop the weather app using React Native due to its ability to create applications for both iOS and Android platforms. Additionally, my proficiency in mobile development is centered around React Native

  <br />

## Challenges

Handling Unavailable Locations: One significant challenge was managing responses when a location wasn't found. I implemented a mechanism where the application awaited a response for a searched location, but if it didn't exist, no response was returned. I just had to wait and wait. 


## Other  implementation

Data Caching: To enhance user experience, I implemented data caching. Whenever a location is searched, its data is stored in the async-storage for quicker access in subsequent searches


