# Slurpy Blurb

A 2D side-scrolling arcade game built in **Unity 6** with **C#**. Guide the bird through an endless stream of pipes, score a point for every gap you clear, and see how long you can last.

This was my first Unity project. I built it to learn the engine's core systems: 2D physics, prefabs and spawning, scene management, UI and audio.

## Features

- **Physics-based flight**: flapping and gravity run on Unity's `Rigidbody2D`, and the bird bounces off obstacles when it crashes
- **Endless obstacles**: pipes spawn at random heights and scroll past at a steady speed
- **Scoring and game over**: score counter with sound feedback, plus a game-over screen with instant restart
- **Main menu**: play, settings and quit panels with a shared UI overlay
- **Settings**: volume slider driven by an `AudioMixer`
- **Pause menu**: press `Esc` to pause and resume at any time
- **Ambient background**: clouds spawn at random heights, intervals and speeds
- **Sound effects** for menus, game start, scoring and crashing

## Controls

| Key | Action |
|---|---|
| `Space` | Flap |
| `Esc` | Pause / resume |

## Running the project

1. Install **Unity 6000.0.27f1** (or a newer Unity 6 release) through Unity Hub.
2. Clone this repository and open the `Slurpy Blurb` folder in Unity Hub.
3. Open `Assets/Scenes/Main Menu.unity` and press **Play**.

## Project structure

```
Slurpy Blurb/Assets
├── Scenes/    Main Menu and gameplay scenes
├── Scripts/   Gameplay, spawning, UI and audio logic
├── Prefabs/   Pipe, cloud and UI panels
├── Sprites/   Bird, pipe and background art
└── Audio/     Sound effects
```

## Credits

The core gameplay loop and some of the art (the pipe and cloud sprites) come from [Game Maker's Toolkit's Unity beginner tutorial](https://youtu.be/XtQMytORBmM). I added the main menu, settings, pause menu, volume control, cloud system, sound effects and crash behaviour on top of it.
