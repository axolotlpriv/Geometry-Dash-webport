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

The webport has its own mod loader with these mods built in. Open the mod list with the **Mods** button on the main menu or the puzzle button next to the pause button in levels. `Tab` opens the Eclipse Menu (see below). Every mod can be turned on and off, and its settings are kept in your browser.

| Mod | What it does |
| --- | --- |
| Eclipse Menu | The Eclipse mod menu with its own interface: about 150 hacks and options, labels, a replay bot, a recorder and keybinds. See below. |
| Click Between Frames | Clicks count at the moment you press instead of at the start of the next frame, so they land on the right physics step. |
| Jukebox | Replace any song with a NONG, either an MP3 from your device or a download from Song File Hub. |
| FPS & Visuals | Unlock or cap the frame rate, render resolution, an FPS counter, anti-aliasing, brightness, contrast and saturation, sharp scaling and no camera shake. |
| Extra LDM | Low detail mode on every level, and optionally no decorations, glow, particles, pulsing or shader effects, so busy levels run faster. |
| Click Sounds | A click sound (built-in or your own file) every time you click in a level, plus a custom or muted death sound. |
| Rainbow Icons | Your icon's colors cycle through the rainbow while you play. |
| Level Thumbnails | Pictures of levels in level lists, from the [Level Thumbnails](https://levelthumbs.prevter.me/) project. |
| Auto Pause | Pauses the level when you switch to another tab or window. On by default. |
| Hide Cursor | Hides the mouse pointer while you play a level. |
| Globed | Globed's multiplayer with Globed's own menus: the Globed button on the main menu, the Global Room, public and private rooms (passcodes, player limits, hidden rooms, invites, kicking, teams, follower rooms and pinned levels), player counts in level lists, status icons (paused, practicing, talking), other players in the same level with their names, progress markers and a ping overlay, a player list and emotes in the pause menu, voice chat, Death Link, the room game modes (below), and Globed's settings. See below. |
| Mobile Controls | On phones and tablets: a text bar that opens the on-screen keyboard when you tap a text field in the game, left/right buttons in platformer levels, and landscape lock in fullscreen. |

### Globed

Press the **Globed** button (the globe next to the settings buttons) on the main menu and **Connect**. Everyone online starts in the Global Room; use **Create Room** or **Join Room** to play with friends, or share your room's ID (click the room name to copy it). When you're in the same level as someone in your room, you see their icon and name, and their progress under the progress bar. The room owner can turn on **Death Link** in the room settings: when anyone dies, everyone in the level dies. Hold `V` to talk in voice chat (your browser asks for your microphone the first time) and press `B` to deafen; in platformer levels, players further away are quieter. In the pause menu, **Emotes** shows an emote above your icon (you can put favorites on keys in the Globed mod settings) and **Players** lists everyone in the level.

Globed's servers only accept the desktop mod, so the web port runs its own server: the first player to connect hosts it in their browser, and if they leave, someone else takes over automatically. This means you can only play with other people using the webport, and the other players (and whoever hosts the server) can see your IP address. Features that need Globed's own servers (moderation, featured levels, Discord roles) aren't either.

The room game modes all turn on safe mode in the level, like in Globed:

* **Collision:** players bump into each other and can stand on each other.
* **2-Player Mode:** open the pause menu's **Players** list and press the link button next to someone (choosing whether you play as Player 1 or 2). In a 2-player level you each control your own icon, and you die together.
* **Switcheroo:** the room owner opens the pause menu's Switcheroo button, picks how players are chosen, and presses Start. Players take turns controlling the same run at random intervals; the others follow along (a force-switch key can be set in the Globed settings).

### Eclipse Menu

Press `Tab` to open and close it (you can change the key in its Keybinds window). On phones and tablets, tap the round Eclipse button; drag it to move it. It looks and works like Eclipse 1.9.4: the Tabbed and Sidebar layouts, the ImGui, MegaHack, MegaOverlay, Gruvbox and OpenHack styles, Eclipse's themes and fonts, search, options behind the arrow next to a toggle, and right-click (or long-press) on any toggle or button to give it a key. Phones get the Sidebar layout by default.

* **Global:** speedhack, audio speed, pitch shift, FPS bypass, transition speed, safe mode and auto safe mode, Click Between Frames/Steps, no short numbers, transparent lists, show taps, lock cursor, vertical sync and more.
* **Level:** accurate percentage, show hitboxes (custom colors, fill, trail, on death), show triggers, StartPos switcher and smart StartPos, layout mode, no glow/particles/shaders/mirror, auto LDM, practice coins, 0% practice completion, random seed, pause countdown, confirm popups and the rest of Eclipse's level options.
* **Player:** noclip (with accuracy and death limits and tint), show trajectory, frame stepper, autoclicker, auto kill, click teleport, jump hack, respawn delay, trail and wave trail options, shipcopter and more.
* **Bypass and Creator:** unlock icons, vaults, shops, main levels and paths, practice music sync, music customizer, level copy, verify and level edit, character filter/limit, free scroll, editor UI hiding and more.
* **Labels:** Eclipse's label system with its presets and expressions (`Attempt {attempt}`), fonts, colors, corners and events.
* **Shortcuts, Bot and Internal Recorder:** restart, practice and checkpoint shortcuts, replays you can record, play back and export, and video recording of the game (saved as a WebM file).

A few options only work in the desktop mod and are shown greyed out: Discord Rich Presence, Physics Bypass, Swift Click, Custom Object Bypass, Default Song Bypass, Slider Limit, Smooth Editor Trail, Inject DLL and Clipsy.

Cheats like noclip and speedhack turn on safe mode automatically (Auto Safe Mode), so they can't save progress.

**Why not Geode?** This port runs the Windows game converted to WebAssembly ahead of time. Geode and Geode mods are Windows programs that patch the game's machine code, so they can't run here. The webport's mod loader hooks the same game functions Geode mods use, but mods have to be written for the webport. Globed is rebuilt the same way (with Globed's own sprites), but it can't reach Globed's servers, as explained above.

## Troubleshooting

**Blank screen:** Reload the page using `Ctrl + F5`.

**The game gets stuck loading on the first visit:** Check your Internet connection and try again.

**The game won't load offline:** Make sure you're opening the downloaded `index.html` file and that you've already opened it once with an Internet connection and let the game finish loading.

**Low performance:** The game draws at the size of your window, so a smaller window runs faster. You can also lower **Render resolution** in the FPS & Visuals mod and turn on the Extra LDM mod. Closing other applications or trying another browser can help too.

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
* **Eclipse Team** (ninXout, prevter, maxnut, Firee, SpaghettDev and contributors): Eclipse Menu, whose interface, themes, translations, label presets and assets the web version uses (Eclipse Public License 2.0; the Rubik, Poppins and Roboto fonts are under the SIL Open Font License).

Geometry Dash belongs to its respective creator. This is an unofficial fan port and is not affiliated with or endorsed by RobTop Games.
