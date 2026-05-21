# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound uses `assets/meow-cute-clean.ogg` and `assets/meow-cute-clean.mp3`, louder cute-meow derivatives of a real cat recording from Wikimedia Commons `Meow.ogg` with the low thump filtered out.

- Source: https://commons.wikimedia.org/wiki/File:Meow.ogg
- Author/uploader: Dan Crosby / Dcrosby
- License: Creative Commons Attribution-Share Alike 3.0 Unported

The cat dance visual is `assets/cat-dance-cutout.webp`, generated as an eight-pose photorealistic sprite sheet for this app and processed into a transparent cutout.

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
