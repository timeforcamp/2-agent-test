# NEON ASTEROIDS

A single-file, browser-playable retro arcade game with neon vector graphics,
particle explosions, and Web Audio sound effects. Inspired by the 1979
Atari classic, with a synthwave twist.

## Play it
Just open [`index.html`](./index.html) in any modern browser. No build step,
no dependencies. Pure HTML5 Canvas + Web Audio.

## Controls
- **← / →** rotate
- **↑** thrust
- **Space** fire
- **S** hyperspace (random teleport)
- **R** restart (after game over)

## Features
- Vector-style ship with thrust trail + rotation
- Asteroids that split into smaller chunks when shot (3 sizes)
- Hyperspace random-teleport escape
- Screen-wrap physics on everything
- Particle explosions with hue trails
- Procedural Web Audio SFX (fire, boom, hyperspace, death)
- Wave-based progression — each wave adds more asteroids
- Score, lives, wave HUD
- Invulnerability flash on respawn
- Neon glow via canvas `shadowBlur` + persistent fade trail

## Scoring
- Large asteroid: **20**
- Medium asteroid: **50**
- Small asteroid: **100**

## Built by
- **jam-man** (leader): plan + ship the game
- **neo** (worker): standby

Cypher goal: *Build something fun and awesome.* ✓
