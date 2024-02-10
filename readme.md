# Luster  ⚡

<br />

| ![Luster 01](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster01.jpeg) | ![Luster 02](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster02.jpeg) | ![Luster 05](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster05.jpeg) |
|---|---|---|
| ![Luster 06](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster06.jpeg) | ![Luster 03](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster03.jpeg) | ![Luster 04](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster04.jpeg) |
| ![Luster 07](https://github.com/bellacristsantos/solo-project-codeworks/blob/main/client/src/assets/Luster07.jpeg) |   |   |



## :bulb: Development Process
<br />

Luster is a music event application that takes the stress out of finding the perfect event. With Luster, users can easily check out upcoming music events, hop straight to the event page to grab tickets, and even save their favorite artists. The application allows users to customize the events feed by choosing different locations to discover new events. After setting the preferred dates, users gain access to all upcoming events. Another feature is an event detail page that provides information about the venue and redirects to the event's ticket page for easy ticket purchase. The application also displays a list of artists, allowing users to track when the next show is happening on the favorite artists' page.

I worked independently on this project, developing the concept based on the challenge of solving a real problem and creating a solution that I can use in my daily life. After brainstorming and using UX processes such as desk research, I created the UI Design along with the User-flow to better understand how each page should be connected to ensure a great user experience. The next step was to develop the frontend focused on mobile with React Native and understand the API’s documentation, including obtaining the API Key and other necessary steps to fetch data.

<br />

## :gear: Tech Stack
<br />


Figma, React Native, Expo, Native Base, Node, Express, along with the integration of Spotify and Ticketmaster APIs.

<br />

## Getting started
<br />

### 1. Obtain API Keys
<br />

  Requirements

   * Get your Spotify API Key, follow the instructions on their website: https://www.alphavantage.co/support/](https://developer.spotify.com/documentation/web-api/tutorials/getting-started

   * Get your Ticketmaster API Key, follow the instructions on their website: https://taddy.org/developers/intro-to-taddy-graphql-api](https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/

### 2. Clone the repository
```
  git clone git@github.com:bellacristsantos/solo-project-codeworks.git

```

### 3. Install dependencies

  ```
    npm install
  ```

### 4. Configure your environment
```
  cd .secret.example 

    Edit server/.secret.js
    # 1. Obtain a clientId, a clientSecret and a redirectUri from Spotify API and replace in server/.secret with yours Spotify Credentials.
    # 2. Obtain an API Key from Ticketmaster API and replace apiKey in server/.secret with your apiKey.
    # 3. Install the Expo GO app: https://apps.apple.com/br/app/expo-go/id982107779 or https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en_US
```

### 5. Run the project
```
  * Starts the client
    npm start

  * To open the app your device that has Expo Go already installed:

    On your Android device, press Scan QR Code on the Home tab of the Expo Go app and scan the QR code you see in the terminal.
    On your iPhone or iPad, open the default Apple Camera app and scan the QR code you see in the terminal.
    You can open the project on multiple devices simultaneously. Go ahead and try it on both phones at the same time if you have them handy.
  ```


