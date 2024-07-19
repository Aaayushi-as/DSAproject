
# Music Player Application

## Description
The Music Player Application is a console-based application that allows users to manage and play a list of tracks. Users can add, remove, and play tracks, as well as navigate to the previous or next track.

## Features
- **Add a Track**: Add a new track to the playlist.
- **List of Tracks**: Display the list of all tracks in the playlist.
- **Remove a Track**: Remove a specific track from the playlist.
- **Play a Track**: Play a specific track from the playlist and navigate to the previous or next track.

## Project Structure
```
music-player/
├── music_player/
│   ├── Intro_Input/
│   │   └── intro_input.java
│   ├── LinkedList/
│   │   └── Track_LL.java
│   └── main_class.java
└── README.md
```

## Usage
1. Upon running the application, you will be presented with a menu:
    ```
    ----- WELCOME TO MUSIC PLAYER APP -----
    
    -----------------------------------------
    1. ADD A TRACK
    2. LIST OF TRACKS
    3. REMOVE A TRACK
    4. PLAY A TRACK
    5. FOR EXITING
    ```
2. Enter the corresponding number for the action you want to perform.
3. Follow the prompts to add, list, remove, or play tracks.

## Example
```
----- WELCOME TO MUSIC PLAYER APP -----

-----------------------------------------
1. ADD A TRACK
2. LIST OF TRACKS
3. REMOVE A TRACK
4. PLAY A TRACK
5. FOR EXITING

ENTER THE INPUT: 1

ENTER TRACK: My Favorite Song
TRACK ADDED!!

-----------------------------------------
1. ADD A TRACK
2. LIST OF TRACKS
3. REMOVE A TRACK
4. PLAY A TRACK
5. FOR EXITING

ENTER THE INPUT: 2

1. My Favorite Song

-----------------------------------------
1. ADD A TRACK
2. LIST OF TRACKS
3. REMOVE A TRACK
4. PLAY A TRACK
5. FOR EXITING

ENTER THE INPUT: 4

1. My Favorite Song

ENTER THE TRACK NUMBER YOU WANT TO PLAY: 1

TRACK -> My Favorite Song IS PLAYING CURRENTLY

WANT TO CHANGE TRACK? Y(1)/N(0): 0
OK!! THANKS
```

**SCREENSHOT**
<img width="1001" alt="MUSIC-1" src="https://github.com/user-attachments/assets/34ecd175-3291-4077-a465-beed6f5b9ffe">
