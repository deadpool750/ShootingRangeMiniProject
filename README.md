# Recoil Training Shooting Range

A Unity first-person shooting range game inspired by **Counter-Strike: Source** recoil practice.

The player can move around a shooting range, shoot an AK-style weapon, control recoil, reload manually, interact with an ammo box, and shoot static or moving targets.

## Features

- Main menu scene and training range scene
- First-person movement with WASD
- Mouse look
- Jumping
- AK-style weapon model
- Camera recoil and visual weapon recoil
- Limited ammo system
- Manual reload
- Circular reload progress indicator
- Ammo box interaction
- Shots and hits counter
- Bullet holes on surfaces
- Static and moving targets
- Physics props using Rigidbodies, Colliders, and impulse forces
- Textured 3D models and environment assets

## Controls

| Key / Input | Action |
| `WASD` | Move |
| `Mouse` | Look around |
| `Left Mouse Button` | Shoot |
| `Space` | Jump |
| `R` | Reload |
| `E` | Replenish ammo when looking at ammo box |
| `T` | Restart training scene |
| `Esc` | Return to main menu |

## Ammo System

The weapon starts with:

```text
30 bullets in magazine
90 bullets in reserve
