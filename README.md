# Progress-Bar
HTML Structure:
The HTML file sets up the basic structure with a div for the progress container and another div inside it for the progress bar itself. Additionally, a button is provided to start the progress.

CSS Styling:

The CSS file styles the body to center the content and gives a clean look.
The .progress-container class styles the outer container of the progress bar.
The .progress-bar class styles the inner progress bar, setting its initial width to 0 and giving it a smooth transition effect.
The button is styled for better visual appearance and user interaction.

JavaScript Functionality:

The JavaScript file contains the startProgress function, which increments the width of the progress bar from 0 to 100% over time.
An interval timer is used to update the width of the progress bar every 100 milliseconds, making the progress bar fill up gradually when the button is clicked.
