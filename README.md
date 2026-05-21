# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound is `assets/meow-silas.ogg`, an unchanged real cat recording from Wikimedia Commons `Meow.ogg`. `assets/meow-silas.mp3` is a browser-compatibility transcode of the same recording.

The dancing cat uses `assets/cat-dance-fluid.mp4` / `assets/cat-dance-fluid.webm`, generated from an AO Labs 16-frame photorealistic in-between sprite sheet and motion-interpolated for fluid playback.

- Source: https://commons.wikimedia.org/wiki/File:Meow.ogg
- Author/uploader: Dan Crosby / Dcrosby
- License: Creative Commons Attribution-Share Alike 3.0 Unported

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
