# Spotify Web App

A simple web application built with TypeScript and React, utilizing the Spotify Web API for data access and music playback. **This application is optimized for desktop use only.**

## Features

- **Music Playback**: Stream music directly through the Spotify API.
- **Data Access**: Fetch user-specific data, such as recently played tracks and top tracks.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- [Spotify Developer Account](https://developer.spotify.com)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/anuranpaul/nashville.git
   cd nashville

   ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**

- Create a .env file in the root directory of the project:

    ```bash
    touch .env
    ```

- Add the following environment variables to the .env file:

    ```bash
    VITE_SPOTIFY_CLIENT_ID=your_spotify_client_id
    VITE_SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
    ```

- Replace your_spotify_client_id and your_spotify_client_secret with your Spotify API credentials.

4. **Get Spotify API Keys:**

- Go to the Spotify Developer Dashboard and log in with your Spotify account.
- Click on Create an App to generate a new application.
- Copy the Client ID and Client Secret from the app settings and paste them into your .env file.

5. **Run the Application:**

    ```bash
    npm run start
    ```
