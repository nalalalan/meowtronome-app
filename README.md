# meowtronome

Static AO Labs metronome for `https://meowtronome.aolabs.io/`.

The beat sound is generated in the browser with Web Audio: each tick uses a short pitched "meow" envelope, so the app has no external sound file dependency.

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
