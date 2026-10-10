# Sky Glide — by Zaib

A hand-drawn paper plane flying game for mobile browsers.
Hold to lift and release to glide. Fly through 5 worlds, dodge obstacles, chain near misses into combos, and unlock new planes.

**Play:** https://wahidzeb.github.io/sky-glide/

## Features
- **5 worlds, 20 levels:** Classroom, Sunny Park, City Rooftops, Stormy Skies and Outer Space. Each world has its own art, music, obstacles and physics. Space has low gravity, and the storm world has gusts and rain downdrafts.
- **Endless mode:** fly through all five worlds in a row. Torn-paper transitions mark each new world, the speed keeps rising, and your best distance is saved.
- **3 hidden stars per level** (60 total). Clear a level to unlock the next one. Clear a world's 4th level to unlock the next world.
- **Obstacles:** pencils, book stacks, swinging lamps, desk fans (updrafts), thrown paper balls, spinning rulers, trees, birds, kites, hot-air balloons, frisbees, towers, swinging crane hooks, clotheslines, helicopters, storm clouds with lightning, wind turbines, hail, asteroids, satellites, UFO tractor beams, comets and black holes.
- **Power-ups:** Shield, Magnet, Slow-mo, and Boost (Boost smashes through obstacles).
- **Scoring:** near-miss bonuses, combo multipliers up to x8, screen shake, hit-stop, particles and a pencil-dash trail.
- **Hangar:** 7 plane designs with different lift, glide, control and hearts, plus perks like a bigger magnet, longer power-ups or +50% coins.
- **14 goals** that pay out bonus coins.
- **Menus:** pause menu, settings (sound, music, vibration, screen shake, graphics quality, reset progress), how-to-play and a results screen.
- **Audio:** all sound effects and music are generated live with WebAudio, so there are no asset files.
- **Saving:** progress is saved in `localStorage`.

## Controls
| Action | Touch | Keyboard / mouse |
|---|---|---|
| Lift | Hold anywhere | Hold Space / ↑ / W, or hold the mouse button |
| Glide | Release | Release |
| Pause | Pause button (top right) | P / Esc |

## Tech
- One self-contained `index.html` (Canvas 2D + vanilla JS) with no external dependencies.
- Mobile-first: fullscreen, works in portrait and landscape, no scrolling or zooming, respects safe areas, uses delta-time updates and pauses when the tab is hidden.
- The menus leave an empty space reserved for a possible future ad banner (`.adslot`). No ads are included.

Game by **Zaib**.
