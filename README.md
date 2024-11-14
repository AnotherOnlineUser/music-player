# Spotify Clone - Your Favourite Music is Here

This is a simple web-based music player inspired by Spotify. It allows users to play, pause, and navigate through a list of songs. The project includes a UI to display song information, and users can control the playback through the interface.

## Features

- Play/Pause music with a toggle button.
- Display the current song title and cover art.
- Navigate between songs using "Next" and "Previous" buttons.
- Progress bar to show song playback status.
- Smooth transitions for the play/pause button and progress bar.
- Supports multiple songs with unique covers.

## Technologies Used

- **HTML5** for the structure of the webpage.
- **CSS3** for styling the layout and making the page responsive.
- **JavaScript** for controlling the audio playback, song navigation, and dynamic updates to the UI.
- **Font Awesome** for icons.


## How to Run

1. Download or clone the repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. The music player should appear, and you can start playing the songs.

## How to Add New Songs

To add a new song, follow these steps:

1. Place the new song's MP3 file in the `/songs` folder.
2. Add the song details to the `songs` array in `script.js`:
   - Add a new object with the song's name, file path, and cover image path.
   - Example:
     ```javascript
     { songName: "New Song Name", filePath: "songs/new-song.mp3", coverPath: "covers/new-song.jpg" }
     ```
3. Ensure the cover image for the new song is added to the `/covers` folder.

## Known Issues

- The current version does not handle multiple users or user logins.
- Some song paths may overlap (ensure file paths are unique).

