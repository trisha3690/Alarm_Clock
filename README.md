# Simple Alarm Clock

![Alarm Clock Preview](./Components/Preview.png)

A clean, user-friendly alarm clock web application built with HTML, CSS, and JavaScript. This project features a visually appealing interface with real-time clock display and customizable alarm settings.

## Features

- **Real-time Clock Display**: Shows the current time in a 12-hour format with AM/PM indicator
- **Alarm Setting**: Set alarms with hour, minute, and AM/PM selection
- **Audio Alert**: Plays an audio sound when the alarm time is reached
- **Button Functionality**: Option to stop the alarm after it's set

## Tech Stack

- HTML5
- CSS3
- JavaScript (No frameworks)

## Project Structure

```
/
├── index.html           # Main HTML structure
├── style.css            # Styling for the application
├── script.js            # Application logic and functionality
└── Components/          # Assets directory
    ├── clock.png        # Clock image
    ├── logo.png         # Favicon/logo image
    ├── preview.png      # Preview image of my project
    └── alarm.mp3        # Alarm sound file
```

## How It Works

1. The application displays the current time in real-time with updates every second
2. Users can select the hour, minute, and AM/PM from dropdown menus
3. Upon clicking "Set Alarm", the application:
   - Validates the input selections
   - Disables the time selection fields
   - Monitors for the alarm time match
4. When the alarm time matches the current time, an audio alert plays
5. Users can stop the alarm by clicking the "Stop Alarm" button

## Usage

1. Open `index.html` in any modern web browser
2. Select your desired alarm time using the dropdown menus
3. Click "Set Alarm" to activate
4. When the alarm triggers, click "Stop Alarm" to deactivate

## Custom Styling

The application uses a clean white interface with blue accents. The styling includes:
- Responsive design for various screen sizes
- Cursive font family for a friendly appearance
- Shadow effects for depth
- Disabled state styling for better user experience

## License

This project is open source and available for personal and educational use.
