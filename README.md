# SDL2 Examples

[![Build Status](https://api.travis-ci.org/jaiyalas/sdl2-examples.png?branch=master)](https://travis-ci.org/jaiyalas/sdl2-examples)
[![MIT](http://b.repl.ca/v1/license-MIT-blue.png)](https://en.wikipedia.org/wiki/MIT_License)
[![Haskell](http://b.repl.ca/v1/language-haskell-orange.png)](http://haskell.org)

Implementing SDL2 tutorial lessons on [lazyfoo.net](http://lazyfoo.net/tutorials/SDL/) using [SDL2 haskell binding](https://hackage.haskell.org/package/sdl2). (Some of them have been implemented on [haskell-game/sdl2examples/lazyfoo](https://github.com/haskell-game/sdl2/tree/master/examples/lazyfoo).) The plan is to implement 34 selected lessons out of the 55 lessons from the original lazyfoo's tutorial.

以 [sdl2 的 haskell binding](https://hackage.haskell.org/package/sdl2) 實作[lazyfoo.net](http://lazyfoo.net/tutorials/SDL/) 中之課程題目。  (其中部分已實作在 sdl2 haskell binding 的 repository - [haskell-game/sdl2examples/lazyfoo](https://github.com/haskell-game/sdl2/tree/master/examples/lazyfoo) 中。) 計畫是實作其中 34 個選定的課程來實作。

## Required Packages (必須套件)

System:

* sdl2 - 2.0.3
* ghc - 7.10.2

Hackages:

* sdl2 - 2.1.1
* linear - 1.19.1.3


## How to Build and Execute (編譯與執行)

```bash
> cabal configure
> cabal build
> cabal run #n
```

where `#n` is the number of lesson.

其中 `#n` 是 lesson 的代號。

## Lessons (課程清單)

### Basic (基礎)

+ [X] Lesson 01 - Hello SDL
+ [X] Lesson 02 - Getting an Image on the Screen
+ [X] Lesson 03 - Event Driven Programming
+ [X] Lesson 04 - Key Presses
+ [X] Lesson 05 - Optimized Surface Loading and Soft Stretching
+ [X] Lesson 07 - Texture Loading and Rendering
+ [X] Lesson 08 - Geometry Rendering
+ [X] Lesson 09 - The Viewport
+ [X] Lesson 10 - Color Keying
+ [X] Lesson 11 - Clip Rendering and Sprite Sheets
+ [ ] Lesson 12 - Color Modulation
+ [ ] Lesson 13 - Alpha Blending
+ [ ] Lesson 14 - Animated Sprites and Vsync
+ [ ] Lesson 15 - Rotation and Flipping
+ [ ] Lesson 16 - True Type Fonts
+ [ ] Lesson 17 - Mouse Events
+ [ ] Lesson 18 - Key States
+ [ ] Lesson 30 - Scrolling
+ [ ] Lesson 31 - Scrolling Backgrounds
+ [ ] Lesson 38 - Particle Engines
+ [ ] Lesson 39 - Tiling
+ [ ] Lesson 40 - Texture Manipulation
+ [ ] Lesson 41 - Bitmap Fonts
+ [ ] Lesson 42 - Texture Streaming
+ [ ] Lesson 43 - Render to Texture

### Others (進階/其他)

+ [ ] Lesson 21 - Sound Effects and Music
+ [ ] Lesson 22 - Timing
+ [ ] Lesson 23 - Advanced Timers
+ [ ] Lesson 24 - Calculating Frame Rate
+ [ ] Lesson 25 - Capping Frame Rate
+ [ ] Lesson 26 - Motion
+ [ ] Lesson 27 - Collision Detection
+ [ ] Lesson 28 - Per-pixel Collision Detection
+ [ ] Lesson 29 - Circular Collision Detection

### Ignored (不打算做)

+ Lesson 06 - Extension Libraries and Loading Other Image Formats
+ Lesson 19 - Gamepads and Joysticks
+ Lesson 20 - Force Feedback
+ Lesson 32 - Text Input and Clipboard Handling
+ Lesson 33 - File Reading and Writing
+ Lesson 34 - Audio Recording
+ Lesson 35 - Window Events
+ Lesson 36 - Multiple Windows
+ Lesson 37 - Multiple Displays
+ Lesson 44 - Frame Independent Movement
+ Lesson 45 - Timer Callbacks
+ Lesson 46 - Multithreading
+ Lesson 47 - Semaphores
+ Lesson 48 - Atomic Operations
+ Lesson 49 - Mutexes and Conditions
+ Lesson 50 - SDL and OpenGL 2
+ Lesson 51 - SDL and Modern OpenGL
+ Lesson 52 - Hello Mobile
+ Lesson 53 - Extensions and Changing Orientation
+ Lesson 54 - Touches
+ Lesson 55 - Multitouch
