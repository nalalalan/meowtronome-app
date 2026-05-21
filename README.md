# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound uses `assets/meow-cute-clean.ogg` and `assets/meow-cute-clean.mp3`, short meow-yap derivatives of a real cat recording from Wikimedia Commons `Meow_domestic_cat.ogg` with the long tail and harsh upper band trimmed out.

- Source: https://commons.wikimedia.org/wiki/File:Meow_domestic_cat.ogg
- Author/uploader: Smser
- License: GNU Free Documentation License 1.2 or later

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
