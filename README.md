# Emoji Asteroids

A small playable asteroids game where the ship, bullets and asteroids are represented with emoji icons: 🍆 for the ship, 💧 for bullets and 🍑 for asteroids.

## Running

Open `index.html` in a modern web browser. Use the left/right arrows to rotate
and the up arrow to accelerate. Hold the down arrow to brake; keep holding to
thrust backwards. Press the space bar to shoot. Shots disappear after traveling about half the screen.

Your score increases whenever a 🍑 is destroyed, which triggers a brief brown
explosion effect. Lives are shown as 🍆 icons in the upper-right corner. If you
lose all three lives a game over screen appears. Once every 🍑 is gone a "Level
complete" message pops up. Press `Enter` to continue after losing a life or to
restart after finishing the level or after game over.

## Reverting to an earlier version

If later changes break the game, you can return to a previous commit by running:

```bash
git reset --hard <commit>
```

Replace `<commit>` with the hash you want to restore, such as `192930d` for the bullet‑range version.
