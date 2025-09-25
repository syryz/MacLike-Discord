# MacLike Discord Theme

![Version](https://img.shields.io/badge/version-1.0.0-blue)   ![Discord_Client](https://img.shields.io/badge/Supports-BetterDiscord%20|%20Vencord-7289DA)   [![Discord](https://img.shields.io/badge/Discord-WAM_Project-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/MyxaEQxjFT)

A clean, minimalist Discord theme aiming to create a more native, macOS-like experience.

---

## Preview
![MacLike Theme Preview](https://github.com/syryz/MacLike-Discord/blob/main/assets/Preview.png?raw=true)

## Features

* **Native Window Controls**: macOS-style "traffic light" window controls (close, minimize, maximize).
* **Translucency**: Incorporates a subtle background blur (mica/acrylic effect) on various UI elements for depth.
* **Mac-style Sidebar**: Replicates a native macOS app look
* **Rounded Corners**: Consistent use of corner radii

---
## Installation

A Discord client mod is required. BetterDiscord or Vencord is recommended.
### BetterDiscord
1.  Download the `MacLike.theme.css` file from the [latest release](https://github.com/syryz/MacLike-Discord/releases/latest).
2.  Open Discord settings.
3.  Navigate to the `Themes` tab in the BetterDiscord section.
4.  Click the `Open Themes Folder` button.
5.  Move the downloaded `MacLike.theme.css` file into the opened folder.
6.  Return to Discord and enable `MacLike` from the theme list.
### Vencord
1.  Download the `MacLike.theme.css` file from the [latest release](https://github.com/syryz/MacLike-Discord/releases/latest)
2.  Open Discord settings.
3.  Navigate to the `Vencord` tab and select the `Themes` sub-tab.
4.  If using QuickCSS, copy and paste the contents of `MacLike.theme.css` to the editor.
5.  Alternatively, follow steps 4-6 above (same as BetterDiscord).

## Customization
- Open the CSS file through QuickCSS or navigating to the themes folder and opening the `MacLike.theme.css` file with a text editor.
- Edit the sidebar background and blur to your liking!
- Turn off the window border if unwanted.
### Enable Translucency
1. Install [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone).
2. Add new rule > Add process rule.
3. Enter `Discord`.
4. Set the Backdrop Type to `Acrylic` and switch on `Extend frame into client area` and `Enable blur behind`.
5. Go to Discord settings.
6. In the BetterDiscord or Vencord settings page, check `Enable window transparency.`
7. Fully restart Discord.


---
## Planned Features
- [ ] **Font Integration**: Replacing the default font with SF Fonts
- [ ] **Animations**: Replicate macOS-style UI animations and transitions (context menu)
- [ ] **Theme Settings Plugin**: Streamline customization options

### Known Issues
- Switching between light and dark themes removes transparency.

### Credits
- Inspiration from macOS apps
- Part of the WAM project

Created by *syrys*
