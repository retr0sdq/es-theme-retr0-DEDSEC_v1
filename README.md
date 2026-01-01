# DEDSEC Theme for ArkOS / EmulationStation

**"Join us. We are DedSec."**

A high-contrast, glitch-aesthetic theme for handheld devices running ArkOS or EmulationStation (FCAMOD). Inspired by the visual style of *Watch Dogs 2*, this theme focuses on raw pixel art, neon accents, and a "hacked" UI experience.

This theme is a comprehensive modification designed to turn your handheld into a DedSec terminal.

## Features
* **DedSec Aesthetic:** High-contrast monochrome background with neon cyan and magenta accents.
* **Massive Carousel:** Custom-tuned system carousel with oversized active icons (2.1x scale) and smaller, faded side icons for depth.
* **Pixel Art Badges:** Unique, square pixel-art badges for "Last Played," "Favorites," and "Options" that seamlessly blend with retro console icons.
* **Legibility First:** Uses the `PixeloidSans` font for crisp text at any resolution.
* **Dynamic Visuals:** Optional "glitch" slideshow background support (see Pro Tips).
* **Aspect Ratio Support:** Includes layouts for 4:3, 1:1, and 16:9 screens.

## Installation
1.  Download the ZIP file from the Releases page or click the green "Code" button > "Download ZIP".
2.  Extract the folder to the themes directory on your SD card:
    * **ArkOS:** `/EASYROMS/themes/`
3.  On your device, press **Start** > **UI Settings** > **Theme** and select **es-theme-retr0-DEDSEC_v1**.

## Pro Tips
* **Enable the Clock:** The theme is designed with a dedicated clock widget in the top right.
* **Collection Badges:** Ensure "Last Played" and "Favorites" are enabled in UI settings to see the custom DedSec badge icons.
* **Slideshow Mode:** To enable the background glitch slideshow:
    1.  Create a folder named `wallpapers` inside the `_art` folder.
    2.  Add your own glitch/DedSec images there.
    3.  Uncomment the `<slideshow>` section in `theme.xml`.

## Trivia
The aesthetic is heavily inspired by the "DEDSEC" hacker group from Ubisoft's *Watch Dogs 2*. The color palette (Cyan `00FFFF`, Magenta `FF00FF`, and Black) mimics the raw CMYK printing style often used in the game's street art and propaganda. The "Last Played" icon featuring a clock was custom-generated to fit the lore of "time lost" in cyberspace.

## Issues
I primarily test on R36S
If you notice alignment issues on other aspect ratios, please file an issue with a screenshot, and I will do my best to patch it.

## Credits & Licenses
* **Base Logic:** Originally based on the clean structure of the "Replica" theme by dani7959.
* **Fonts:** `Pixeloid Sans` by GGBotNet.
* **Icons:** Custom generated pixel art and vectorized console logos.
* **Inspiration:** *Watch Dogs 2* (Ubisoft).

*You may fork this theme, but please credit the original repository. Join the swarm.*
