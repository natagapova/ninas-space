# nina's space

this website was a birthday gift for my friend so don't take it seriously as a frontend project. it is still growing — i plan to keep updating it with new things over time.

## what lives here

- home — a welcome page with a little breathing widget
- meditations — calming videos to watch inside the page
- affirmations — loving reminders for slow breathing and soft thoughts
- games — mini pixel games for gentle distraction and joy

there is english and srpski, plus optional ambient sounds (rain, fire, wind, trees, lo-fi, and more).

## how to open it

no build step needed. just open `index.html` in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000

## files

```
index.html          home
meditations.html    meditations
affirmations.html   affirmations
games.html          games
app.js              text, translations, sounds, and game logic
styles.css          all the pink pixels
assets/             pixel art
```

most of the content lives in `app.js` — that's the place to edit when adding new meditations, affirmations, or little touches.

---

made with love and pink pixels.
