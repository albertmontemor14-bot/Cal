# Calculus Adventure: The Math Kingdom

A pixel-style web adventure game inspired by Terraria. Explore the Math Kingdom, swing your sword at slimes, and keep your hearts up.

## Play it

- **On your computer:** open `index.html` in your browser.
- **On the web (GitHub Pages):** in your repo go to **Settings → Pages**, choose the `main` branch and the `/ (root)` folder, then save. The game will be at `https://<your-username>.github.io/<repo-name>/`.

## Controls

| Action | Keyboard | Phone |
| --- | --- | --- |
| Move | A / D or arrow keys | ◀ ▶ buttons |
| Jump | W, Up arrow, or Space | Jump button |
| Sword | J, X, or click the screen | Sword button |

## Project structure

```
index.html        title screen (home)
game.html         the game
css/home.css      title screen styles
css/game.css      game styles (background, character, hearts)
js/game.js        character, sword, health, slime enemy
js/sound.js       sound effects (made with the Web Audio API)
js/music.js       background music player
audio/            the two music tracks
```

## Notes

- Sound effects are generated in the browser, so they need no audio files.
- The music in `audio/` belongs to its original creators. Check you have the right to share it before making the repository public.
