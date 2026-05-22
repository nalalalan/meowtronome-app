# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound currently uses the exact user-supplied `assets/hi.m4a` voice recording placed in this app's assets folder on May 21, 2026. The previous `assets/maaphh_fVz49SG0.mp3` sample remains in the assets folder.

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
