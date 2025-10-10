## Animated Countdown GIF Generator (Windows)

This Windows program generates animated GIFs showing an animated countdown from a specified number of seconds. The graphics it produces are similar to a stopwatch face with moving arc that decreases its length from 100% to 0 over the countdown period. For example, the following graphic shows a snapshot of a GIF shortly after it began counting down from 5 seconds:

![Alt text](images/1.gif)

Fonts, shadows, colors, border widths, arc width, "zooming" text, and an animated sparkle at the end of the arc are all configurable.

The GIFs are transparent so they can be used as overlays on screens, photos, movies, etc.

You may also choose the size of the GIF and the FPS (frames per second) rate. High frames per second generate smoother countdowns but produce larger file sizes and increase generation time.

The Maximum Seconds value determines the beginning value for the countdown sequence. For example, if you set the value at 5:

- A single GIF count down from 5 to 0 will be generated if the "Generate a single GIF" is checked. 
- A series of five GIFs will be generated if the "Generate a series of GIFs" is checked. One GIF will count down from 5, then another GIF will count down from 4, etc. This is useful if you have a need for different countdown values dependent on your needs.

The GIFs are stored in the directory of your choice with the filename "Countdown_XX.gif" where XX is the beginning countdown number.

Settings are saved when you exit and reloaded when you begin the program again.

The settings file is located in the folder APPDATA\Roaming\CountdownGIFGenerator. For example, if the user is "admin," the folder path and filename is:

C:\Users\admin\AppData\Roaming\CountdownGIFGenerator\countdown_gif_generator_settings.json

If you want to reset all settings to defaults, simply delete the .json file.

Note that you can choose settings that cause the graphic elements to overlap and/or fall outside the GIF width. If this happens, simply readjust settings to prevent it.

# Usage Example

The settings in the screenshot result in the GIF below it:
![Alt text](images/2.png)

File stored in C:\Users\admin\Countdown_05.gif:

![Alt text](images/3.png)

# Installation
Download and run CountdownGIFGeneratorSetup.exe from the "Releases" link at the right hand side of the page.
The setup file is not digitally signed so you will likely get a warning when installing. It has been scanned with multiple anti-virus programs and is virus-free.
The SHA256 hash value for the file is provided for you to check against the downloaded version for additional secuirty.
