# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound uses `assets/meow-warm.ogg` and `assets/meow-warm.mp3`, warmer lower-pitched derivatives of a real cat recording from Wikimedia Commons `Meow.ogg`.

- Source: https://commons.wikimedia.org/wiki/File:Meow.ogg
- Author/uploader: Dan Crosby / Dcrosby
- License: Creative Commons Attribution-Share Alike 3.0 Unported

The cat dance visual is `assets/cat-dance-sheet.webp`, generated as an eight-pose photorealistic sprite sheet for this app.

## Run Locally

```bash
npm start
```

Open `http://localhost:3034`.

## Deploy

This app is intended for GitHub Pages from the `main` branch root with `CNAME=meowtronome.aolabs.io`.

DNS needs one record:

| Type | Host | Answer |
| --- | --- | --- |
| CNAME | meowtronome | nalalalan.github.io |
