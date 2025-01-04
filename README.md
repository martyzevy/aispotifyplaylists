# AI-Generated Spotify Playlist Creator

This web application allows users to create customized Spotify playlists by describing their desired playlist characteristics. Simply enter a playlist name and description (e.g., genres, moods, or artists), and the application generates a Spotify playlist tailored to your input using the Spotify API and OpenAI API.

---

## Features
- **Custom Playlist Generation**:
  - Users provide a playlist description (e.g., "upbeat workout music" or "calm jazz for studying").
  - The app uses OpenAI to interpret the description and generate a list of songs.
- **Seamless Spotify Integration**:
  - Automatically creates a new Spotify playlist with the generated songs.
  - Uses the Spotify API for playlist creation and song addition.
- **User-Friendly Interface**:
  - Built with Flask, HTML/CSS, and JavaScript for an intuitive user experience.

---

## Technologies Used
- **Backend**: Python (Flask)
- **Frontend**: HTML/CSS, JavaScript
- **APIs**:
  - **Spotify API**: For playlist creation and song search.
  - **OpenAI API**: For interpreting playlist descriptions and generating song lists.
- **Other Libraries**:
  - `spotipy`: Spotify API wrapper.
  - `flask-cors`: To handle cross-origin requests.
  - `dotenv`: For secure environment variable management.

---

## How It Works
1. **Login**: Users authenticate via Spotify OAuth.
2. **Provide Input**: Enter a playlist name and a description (e.g., "chill indie songs for a rainy day").
3. **AI Processing**:
   - The OpenAI API generates a list of songs based on the description.
4. **Playlist Creation**:
   - The Spotify API creates a new playlist in the user's Spotify account and adds the generated songs.

---

## Live Demo
Try the live version here:  
[**AI Spotify Playlist Creator**](https://aispotifyplaylists.martinestrin.com/)

---

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   cd your-repo-folder
