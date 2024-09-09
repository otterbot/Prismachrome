# Prismachrome muOS Overlays

Someone had brought up to me the idea of creating an overlay with a bezel in every color fo the rainbow, but because I'm extra, I took it a step further and made a slightly fancier variation.

Including in this repository are both grid overlay and non-grid overlay with a bezel in each of the following colors:

Red
Orange
Yellow
Green
Blue
Indigo
Violet

Additionally, these come in a Gameboy Advance SP and a Gameboy micro variant.

# Gameboy Advance SP Overlays:
Grid
![alt_text](https://github.com/otterbot/Prismachrome/blob/main/Samples/GBASP%20-%20Grid.png?raw=true)

No Grid
![alt_text](https://github.com/otterbot/Prismachrome/blob/main/Samples/GBASP%20-%20No%20Grid.png?raw=true)

# Gameboy micro Overlays:
Grid
![alt_text](https://github.com/otterbot/Prismachrome/blob/main/Samples/micro%20-%20Grid.png?raw=true)

No Grid
![alt_text](https://github.com/otterbot/Prismachrome/blob/main/Samples/micro%20-%20No%20Grid.png?raw=true)

# File Placement

NOTE: You can put these wherever you want, so long as you are able to easily navigate to them within retroarch's settings and so long as they're not with any sensitive files that are crucial to retroarch or your Anbernic device. Otherwise, it may be best to use my recommended defaults locations.

Move the **OtterBot** folder to `mmc > MUOS > retorach > overlays`

# Gameboy Advance SP/Gameboy micro Configuration
Open a GBA game, then the Quick Menu, and go back to the main menu. Then go to `Settings > Video > Scaling`.

Integer Scale: **Off**

Aspect Ratio: **Custom**

Custom Aspect Ratio (X Position): **0**

Custom Aspect Ratio (Y Position): **0**

Custom Aspect Ratio (Width): **640**

Custom Aspect Ratio (Height): **426**

Bilinear Filtering: **OFF**

Crop Overscan: **ON**

# Gameboy Advance SP/Gameboy micro Usage
While playing a game, open the quick menu and go to `On-Screen Overlay > Overlay Preset`.

Select **Parent Directory** until you get to the directory that contains the folder named **OtterBot**. Then go to `OtterBot > gba > Prismachrome` and pick the overlay you'd prefer.

Go back to the Quick Menu and then go to **Overrides**.

If you want the selected bezel for all GBA games, select **Save Content Directory Overrides**.

If you want the selected bezel for just the current GBA game, select **Save Game Overrides**.
