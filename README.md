# Drum Kit Project

This is a simple and interactive Drum Kit web application that allows users to play drum sounds by either clicking on the drum buttons or pressing designated keys on their keyboard. 
Each key corresponds to a specific drum sound, making it fun and easy to create beats.



## Features
- Interactive UI: Clickable buttons representing various drum instruments.
- Keyboard Support: Use keyboard keys (e.g., `w`, `a`, `s`, `d`, `j`, `k`, `l`) to play sounds.
- Responsive Feedback: Buttons light up briefly when clicked or when the corresponding key is pressed.
- Custom Sounds: Each button has a unique sound effect associated with it.

## Technologies Used
- HTML: Structure of the page.
- CSS: Styling for the layout and button animations.
- JavaScript: Logic for playing sounds, detecting keyboard input, and animations.

## How to Use
1. Clone or download this repository.
2. Open the `index.html` file in your web browser.
3. Press any of the specified keys on your keyboard (`w`, `a`, `s`, `d`, `j`, `k`, `l`) or click on the corresponding drum buttons to play a sound.

## Keyboard Key Mappings
 Key  Instrument        
 w    Crash Cymbal      
 a    Bass Drum         
 s    Tom-Tom 1         
 d    Tom-Tom 2         
 j    Snare Drum 1      
 k    Snare Drum 2      
 l    Snare Drum 3      

## How It Works
- The application listens for both click events on the drum buttons and keypress events on the document.
- When an event is detected, a sound associated with the clicked button or pressed key is played.
- A brief animation highlights the button for visual feedback.


