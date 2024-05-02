# Music_Management_System
This Java program is designed to manage a collection of music albums and their corresponding tracks. 
It allows users to add, delete, and edit albums and tracks, print details about them, and persist data to a file.

## Classes and Their Responsibilities

1. **Main**: Initializes the application and starts the main menu.

2. **Album**: Represents a music album. Includes functionality to calculate the total duration of the album based on its tracks.

3. **Track**: Represents a single track in an album. Tracks are editable for title, MP3 file name, duration in minutes, and seconds.

4. **Menu**: Handles the user interface and input from the console. It presents various menus for managing albums and tracks, and provides a manual.

5. **Function**: Manages the core functionalities such as adding, deleting, and editing albums and tracks. It also handles file operations for loading and saving albums.

## Key Features

- **Album and Track Management**: Add new albums and tracks, delete existing ones, and edit their details.
- **Data Persistence**: Load and save albums to a file.
- **Manual Reading**: Access manuals in different languages.
- **Input Validation**: Ensures all inputs for times and selections are within expected ranges.

### Main Menu
```
___Music management___
[1] Album management
[2] Track management
[3] Manual
[0] Exit program
Enter index of your choice:
```

### Adding an Album
1. Select "Album management" from the main menu.
2. Choose "add Album" and follow the prompts to input the album title, artist, and the tracks.

### Editing a Track
1. Navigate to "Track management" from the main menu.
2. Select an album and then choose a track to edit. Follow the prompts to update the track details.

### Exiting the Program
Choose "Exit program" from the main menu to save all changes and close the application.

## Conclusion
This program offers a comprehensive solution for managing a music collection, with support for detailed information about albums and tracks. The user-friendly console interface makes it accessible for both novice and experienced users.

