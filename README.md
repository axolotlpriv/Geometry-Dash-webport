# Geometry Dash webport

<p align="center">
  <img width="960" height="540" alt="Geometry Dash webport" src="https://github.com/user-attachments/assets/11517712-f46a-4d53-944b-2c0b6d92cae9" />
</p>

> A browser version of Geometry Dash that lets you play without installing anything.

## Play Online

**[Play Geometry Dash](https://gd-webport.pages.dev/)**

Open the link, wait for the game to load, and start playing.

The first load requires an Internet connection. To play offline, download index.html, open it in your browser once while online, and let the game finish loading. After that, you can open the same file without a connection. The online version at the link above always needs an Internet connection.

## Updating

The online version is updated whenever changes are published. Reload the page to get the latest version. If the changes don't appear, press `Ctrl + F5`.

### Using a downloaded copy?

Downloaded files and forks don't update automatically. To get the latest version, you can:

* **Play online:** Open the [webport](https://gd-webport.pages.dev/).
* **Download the latest file:** Open [index.html](index.html) in this repository, click the download icon, and open the file in your browser.

The version update notice is only displayed when an Internet connection is available.

You can delete older downloaded copies once you've switched to the new version.

## Requirements

* An up-to-date web browser.
* JavaScript enabled.
* A compatible computer, tablet, or smartphone.
* An Internet connection for the initial load and online features.

## Browser Compatibility

The webport is intended for modern browsers on both desktop and mobile devices.

| Browser                       | Compatibility    |
| ----------------------------- | ---------------- |
| Google Chrome                 | Supported        |
| Microsoft Edge                | Supported        |
| Mozilla Firefox               | Supported        |
| Brave                         | Supported        |
| Other Chromium-based browsers | Likely supported |

The game can also be played on mobile phones and tablets. Tap to jump, drag to scroll lists and move sliders, and use the pause button in the top-right corner. When you tap a text field (like level search), a text bar appears at the top so you can type with your phone's keyboard. Platformer levels show left and right buttons in the bottom-left corner. Performance and compatibility may vary depending on your device and browser.

## Game Information

| Feature               | Details               |
| --------------------- | --------------------- |
| Name                  | Geometry Dash webport |
| Type                  | Webport / HTML        |
| Geometry Dash version | 2.2081                |
| Platform              | Web browser           |
| Technologies          | HTML5, JavaScript     |

## Controls and Saving

* **Pause button:** While you're in a level, a pause button appears in the top-right corner. It does the same thing as pressing `Esc`.
* **Keybinds:** The keyboard button next to the pause button opens the keybinds menu. There you can add your own keys for jumping, moving, checkpoints and pausing. Your keybinds are kept in your browser.
* **Saving:** Your progress is saved when you pause, when you switch tabs or close the page, and about once a minute while you're in the menus. Saves are stored in your browser (IndexedDB, with a backup copy in local storage). Songs the game downloads aren't kept between sessions, but NONGs you add with Jukebox are.

## Mods

The webport has its own mod loader with these mods built in. Open the mod list with the **Mods** button on the main menu, the puzzle button next to the pause button in levels, or the `Tab` key. Every mod can be turned on and off, and its settings are kept in your browser.

| Mod | What it does |
| --- | --- |
| Eclipse Menu | Noclip, speedhack (with audio), show hitboxes, safe mode, respawn delay, no death effect, practice music hack, no mirror, no transitions, unlock all icons and colors, on-screen labels (FPS, CPS, attempts, percentage, noclip accuracy, clock) and toggle shortcuts. |
| Click Between Frames | Clicks count at the moment you press instead of at the start of the next frame, so they land on the right physics step. |
| Jukebox | Replace any song with a NONG, either an MP3 from your device or a download from Song File Hub. |
| FPS & Visuals | Unlock or cap the frame rate, an FPS counter, anti-aliasing, brightness, contrast and saturation, sharp scaling and no camera shake. |
| Globed | Play online with friends: create a room, share its 6-digit ID, and see each other's icons, names and deaths in the same level. Death Link (set by the room owner) makes everyone die when anyone dies. |
| Mobile Controls | On phones and tablets: a text bar that opens the on-screen keyboard when you tap a text field in the game, left/right buttons in platformer levels, and landscape lock in fullscreen. |

Cheats like noclip and speedhack turn on safe mode automatically, so they can't save progress. You can change this in the Eclipse Menu settings.

**Why not Geode?** This port runs the Windows game converted to WebAssembly ahead of time. Geode and Geode mods are Windows programs that patch the game's machine code, so they can't run here. The webport's mod loader hooks the same game functions Geode mods use, but mods have to be written for the webport. Globed's own servers only accept the real Globed mod, so the webport's Globed connects players directly to each other (peer to peer, through WebRTC). Everyone you play with needs to use the webport.

## Troubleshooting

**Blank screen:** Reload the page using `Ctrl + F5`.

**The game gets stuck loading on the first visit:** Check your Internet connection and try again.

**The game won't load offline:** Make sure you're opening the downloaded `index.html` file and that you've already opened it once with an Internet connection and let the game finish loading.

**Low performance:** Close other applications or try another browser.

**Changes aren't showing up:** Force a reload with `Ctrl + F5`.

**An old downloaded copy isn't working:** Try the online version or download the latest `index.html` file.

If the problem continues, it could be related to your browser or the service hosting the game.

## Offline Mode and Limitations

Offline mode applies only to the downloaded `index.html` file opened directly from your device's storage. It does not apply to the online version hosted on GitHub Pages, which always requires an Internet connection.

Keep these limitations in mind:

* **Online levels:** Searching for and accessing online levels requires an Internet connection.
* **New songs:** Downloading new songs requires an Internet connection.
* **Browser cache:** Offline play depends on the cached game files remaining available.
* **Cleared site data:** If you clear your browser's cache or site data, you may need to load the game online again.
* **Browser changes:** The cached files are not automatically shared between browsers. Open the game in the same browser you used for the initial load.
* **Version notices:** The update notice only appears when an Internet connection is available.

Offline availability depends on your browser retaining the necessary files. It is not guaranteed if the cache is cleared or the browser removes stored resources.

## Reporting Bugs

Found a bug while playing? You can report it in the repository's Issues section to help improve the game.

**[Report a Bug](https://github.com/Ale7208/Geometry-Dash-webport/issues)**

When reporting a bug, please explain what happened and, if possible, how to reproduce it. **If the bug is visual, please include a screenshot** to help identify the issue.

**Note:** I speak Spanish, so if your issue is written in another language, I will use a translator to understand and review it. However, reports in Spanish are preferred.

## Credits

* **RobTop Games:** Creator of the original Geometry Dash.
* **Bog:** Creator of the web port.
* **Ale7208:** Improvements and bug fixes.

Geometry Dash belongs to its respective creator. This is an unofficial fan port and is not affiliated with or endorsed by RobTop Games.
