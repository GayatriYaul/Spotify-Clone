
# Spotify Clone

A fully functional Spotify clone built with React, Node.js, Express.js and MongoDB. This project aims to replicate the core functionalities of Spotify, allowing users to browse albums, play songs, and manage playback. 
It includes functionalities for creating, browsing, and removing albums, as well as uploading, viewing, and deleting songs.

## Features

- **Album Management**: Create, list, and delete albums.
- **Song Management**: Upload, list, and delete songs.
- **Play Music**: Users can play, pause, and skip tracks.
- **Responsive Design**: Mobile-friendly design for better accessibility.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Cloud Storage**: Cloudinary for image and song storage
- **Tools:** Git, Vite, VSCode
- **State Management**: Context API
- **Other Libraries**: Axios, React Router, React Toastify

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/nuricanbrdmr/Spotify-Clone-MERN-Website.git
    cd Spotify-Clone-MERN-Website
    ```

2. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```plaintext
    MONGO_URI=your_mongodb_uri
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```

3. Run the backend server:
    ```bash
    cd spotify-backend
    npm install
    npm start
    ```
4. Run the backend server:
    ```bash
    cd spotify-admin
    npm install
    npm run dev
    ```

5. Run the frontend:
    ```bash
    cd spotify-frontend
    npm install
    npm run dev
    ```

## Usage

1. Open your browser and navigate to `http://localhost:5173`.
2. Create new albums and songs on the Spotify Admin page.
3. Browse albums and songs, create playlists, and enjoy music.

## Screenshot

### Admin Add Song Page
![Screenshot_1](https://github.com/user-attachments/assets/a6068724-71a5-49ef-99d7-419c215f94ae)

### Admin Song List Page
![Screenshot_2](https://github.com/user-attachments/assets/5ffb918c-27ec-4db5-8855-81b83d1d5725)

### Home Page
![Screenshot_3](https://github.com/user-attachments/assets/b4ead4c4-d267-495a-ab57-7f9c5006b340)

### Album Page
![Screenshot_4](https://github.com/user-attachments/assets/33e1dcdb-f794-4b1e-82cc-3c588c4b23c1)

## References

I used [GreatStack YouTube channel](https://www.youtube.com/@GreatStackDev) to develop this project. Thank you for the useful content.
