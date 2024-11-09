Spotify Clone

Project Overview

This project is a clone of the Spotify music player, built using HTML, CSS, and JavaScript. It replicates the basic functionality of a music player, including the ability to play, pause, and navigate through songs, along with a visually appealing layout. This project aims to demonstrate proficiency in front-end web development, focusing on creating a modern, responsive design with smooth interactivity.

Features

	•	Play and Pause Songs
	•	Skip to Next or Previous Song
	•	Song Progress Bar
	•	Song List Display with Play/Pause Button
	•	Sticky Footer with Icons
	•	Responsive Design for Different Screen Sizes
	•	Dynamic Song Information Display
	•	Use of Google Fonts for Typography

Tech Stack

	•	Frontend: HTML, CSS, JavaScript
	•	Fonts: Google Fonts (Ubuntu, Varela Round)

Installation

To run this project locally:
	1.	Clone the repository:

git clone https://github.com/your-username/spotify-clone.git


	2.	Navigate to the project directory:

cd spotify-clone


	3.	Open index.html in your browser to view the project.

File Structure

spotify-clone/
│
├── index.html           # Main HTML file
├── script.js            # JavaScript functionality
├── style.css            # CSS styles for layout and design
├── songs/               # Folder containing song files
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ...
├── covers/              # Folder containing cover images for songs
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...
└── bg.jpg               # Background image for the container

Functionality

1. Song Playback

	•	Play/Pause: Clicking the master play button toggles between playing and pausing the current song.
	•	Progress Bar: The song progress bar updates dynamically as the song plays. It can also be adjusted by the user to skip to different parts of the song.
	•	Play Next/Previous: The user can navigate between the next and previous songs in the playlist.
	•	Song Info Display: The current song’s title and cover image are displayed in the UI.

2. Interactive Song List

	•	The song list displays the song name and cover image.
	•	Each song has a play/pause button to toggle playback for that song.
	•	The song name is displayed next to the album cover.

3. Sticky Footer

	•	The footer contains music controls such as play/pause buttons, volume control, and other relevant icons.
	•	The footer stays fixed at the bottom of the page, even when scrolling.

CSS Styling Overview

1. Global Styles

	•	The body background color is set to antiquewhite, creating a warm, light tone for the page.
	•	The * selector ensures that all elements have no default margin or padding, ensuring consistency across browsers.

2. Layout and Design

	•	Navigation Bar: A sleek, black navigation bar with a centered brand logo.
	•	Main Container: The container housing the music player is black with white text, a border radius for rounded corners, and a background image (bg.jpg). This layout adjusts with margins and padding for a well-spaced, visually appealing look.
	•	Song List: Each song item is displayed in a white box with a border-radius, with the cover image and song name clearly visible.
	•	Sticky Footer: A fixed footer with icons, centered vertically and horizontally, offering essential controls.

3. Media Queries

	•	The media query ensures the design is responsive, changing the background color for smaller screen sizes (max-width: 1100px). This can be expanded for better mobile support.

JavaScript Functionality

	•	The JavaScript file (script.js) handles all the interactive functionality of the music player, including:
	•	Play/pause toggle for the entire player and individual songs
	•	Updating the progress bar as the song plays
	•	Changing the song when navigating forward or backward
	•	Updating the current song name and cover image dynamically

Key Variables

	•	songIndex: Keeps track of the current song being played.
	•	audioElement: The <audio> element used to play songs.
	•	masterPlay: The play/pause button.
	•	myProgressBar: The progress bar element to visualize song playback.
	•	gif: A GIF element that appears when a song is playing.
	•	masterSongName: Displays the current song’s name.
	•	songItems: Contains all song list items, dynamically updating each item with song names and covers.

Key Event Listeners

	•	Master Play Button: Toggles play/pause of the entire player and switches the icon between play and pause.
	•	Song Item Play Button: Handles the individual play/pause functionality for each song in the list.
	•	Progress Bar: Updates the song’s current time based on user interaction with the progress bar.
	•	Next and Previous Buttons: Navigate through the playlist.

Responsive Design

The design is mobile-friendly, thanks to the use of flexbox and media queries. The layout adapts to smaller screen sizes by adjusting font sizes, the progress bar width, and the background color.

Media Queries

	•	For screens with a maximum width of 1100px, the background color of the body changes to red for a visual effect (this can be customized further for better mobile design).

@media only screen and (max-width: 1100px) {
    body {
        background-color: red;
    }
}

Credits

	•	Fonts: Google Fonts (Ubuntu, Varela Round)
	•	Songs: The songs used in this project are placeholders and can be replaced with actual music files. Ensure that you have the correct licensing for music use.
	•	Cover Images: Placeholder images used. Replace with actual cover art for your songs.

Future Enhancements

	•	Add a playlist creation feature, allowing users to add and remove songs from their playlist.
	•	Implement volume control for the audio player.
	•	Add a shuffle and repeat functionality for song playback.
	•	Enhance responsiveness with more breakpoints for various devices.

License

This project is open-source and available under the MIT License. Feel free to contribute, modify, or use this project as needed.
