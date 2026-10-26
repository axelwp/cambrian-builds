# Creatures: builds

Playable builds of Creatures, a game about evolving a sea creature. Download the latest from
[Releases](https://github.com/axelwp/evolution-game-builds/releases/latest).

This repository only holds the downloads; the game is developed elsewhere.

## What you need

- **Steam (Required for Multiplayer)**, running and signed in. The game uses Steam for playing together and shows
  as **Spacewar** (Valve's free test app) while it runs. You don't need to own anything.
- **Windows** (64-bit) or **macOS** (Apple Silicon or Intel).

## Installing

**Windows:** unzip the whole folder and run `Creatures.exe` from inside it. Keep everything
in the folder together: the game won't start without the files beside it. Windows may warn
that the app is unrecognised: choose **More info → Run anyway**.

**macOS:** open the `.dmg` and drag Creatures to Applications (or run it from the disk image).
The app isn't notarized by Apple, so the first launch is blocked: right-click it and choose
**Open**, or go to **System Settings → Privacy & Security** and choose **Open Anyway**.

## Playing together

Press **Tab** in game to open the debug menu.

- **Host:** choose **Host on Steam**, then **Copy my Steam ID** and send it to your friends.
- **Join:** paste the host's Steam ID into the **Host's Steam ID** box and press **Join**.
  If you're Steam friends with the host, **Join a Steam friend** finds them for you, unless
  they're in invisible mode on Steam (then join by ID).

Everyone needs the **same release**: builds from different releases refuse to connect.
Windows and Mac players can join each other on the same release (cross-play is still being
tested, so a mixed session may not look quite the same on both).

## Reporting a problem

In the debug menu (Tab), **Copy log** or **Copy errors** copies what the game logged, with
the version at the top. Paste it into an issue with what you were doing.
