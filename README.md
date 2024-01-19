# Welcome to WanderWisely 👋

A ReactJS TripAdvisor Web App made with the RapidAPI's TravelAdvisor API and Google Maps API
![Screenshot from 2024-01-19 15-34-27](https://github.com/nishchay-veer/WanderWisely/assets/99465982/137fe3fc-dea7-42aa-bd87-87ead118696d)



<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/nishchay_veer" target="_blank">
    <img alt="Twitter: nishchay_veer" src="https://img.shields.io/twitter/follow/nishchay_veer.svg?style=social" />
  </a>
</p>

### ✨ [Live Preview](https://wander-wisely.vercel.app/)

## Install
Run the Command to Install all dependencies.
```sh
npm install
```

## Usage

Create API Credentials/Keys from the following Providers

* [Google Maps](https://console.cloud.google.com/) "Enabling the Specific Services: Maps Javascript API & Places API"
* [Travel Advisor (Rapid API)](https://rapidapi.com/apidojo/api/travel-advisor/)

Create a `.env` file in your root directory, create the variables as seen below filling in your API Keys appropriately
```sh
VITE_TRAVEL_API_KEY=TRAVEL-ADVISOR-APIKEY-HERE
VITE_GOOGLE_MAP_API_KEY=GOOGLE-MAP-APIKEY-HERE
```
Locate and Append the Google Map API Key onto the Script Tag in the `index.html` file as seen below
```sh
<script src="https://maps.googleapis.com/maps/api/js?v=3.exp&libraries=geometry,drawing,places&key=GOOGLE-MAP-APIKEY-HERE"></script>
```
Now run the command to start the development server.
```sh
npm run dev
```
Your project should start running on `http://localhost:3000`

## Author

👤 **Nishchay Veer**

* Twitter: [@nishchay_veer](https://twitter.com/nishchay_veer)
* LinkedIn: [@nishchay-veer](https://linkedin.com/in/nishchay-veer)


## Show your support

Give a ⭐️ if this project helped you!
