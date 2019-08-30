# `react-native-maps-directions-example`

Example app that uses [`react-native-maps-directions`](https://github.com/bramus/react-native-maps-directions).

Nothing fancy, mainly just created to help out users who are having troubles with setting up their Google Maps Directions API Key.
Please refer to the [`react-native-maps-directions`](https://github.com/bramus/react-native-maps-directions) instructions on how to obtain and configure such an API Key.

## Installation

- Clone this repo

	```bash
	git clone git@github.com:bramus/react-native-maps-directions-example.git
	```

- Install dependencies

	```bash
	yarn install
	```

- Adjust `App.js` and enter your Google Maps Directions API Key there:

	```js
	const GOOGLE_MAPS_APIKEY = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX';
	````

## Running the app

There are some NPM Scripts provided to run this app.

- `yarn start`: starts a Metro Bundler
- `yarn ios`: launches the iOS Simulator and compiles the iOS app
