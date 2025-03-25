# Music-Player

OVERVIEW

The music player code creates a robust and user-friendly application with a graphical interface using Tkinter. Users can log in, access a playlist of songs, and control audio playback with options such as play, stop, pause, resume, next, and previous. The code integrates seamlessly with a MySQL database to manage user credentials and song details. It provides an intuitive interface for adding and deleting songs, while users with an "admin" role have access to additional features such as viewing user lists. The music player utilizes the pygame library for audio playback and leverages Tkinter widgets for a visually appealing design. With a focus on user interaction and feedback, the code ensures a seamless and enjoyable experience for music enthusiasts, offering a personalized playlist management system through a well-organized and modular structure.

TECHNOLOGY USED

      * Tkinter
      
      * Pygame
      
      * MySQL connector

FEATURES

1)User Authentication and Authorization: 

The program requires users to log in, and it checks the credentials against a MySQL database. Different user roles, such as "admin" and "user," have different levels of access to features.

2)Graphical User Interface (GUI): 

The program utilizes the Tkinter library to create a user-friendly GUI. Users can interact with buttons, entry fields, and list boxes for managing songs and controlling playback.

3)Audio Playback with pygame: 

The program employs the pygame library to handle audio playback. Users can play, stop, pause, resume, and navigate through songs in a playlist.

4)Database Interaction: 

It interacts with a MySQL database to store user information (username, password, role) and details about songs (title, artist, genre, filepath).

5)Song Management: 

Users can add new songs to the playlist, delete selected songs, and view the list of available songs.

6)Admin Features: 

If a user has an "admin" role, additional features are available, such as viewing a list of users in the system.

7)File Dialog for Song Selection: 

The program allows users to select audio files for new songs through a file dialog.

8)Dynamic GUI Updates: 

The GUI updates dynamically based on user interactions, such as adding or deleting songs, providing real-time feedback through status labels.

9)Modular Code Structure: 

The code is organized into functions, making it modular and easy to understand. Each function serves a specific purpose, contributing to the overall functionality of the program.

10)Error Handling: 

The program includes basic error handling, such as displaying messages in case of login failure or when attempting to delete a song without selecting one.
