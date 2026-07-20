# Optical Piano

A light-powered plywood piano for kids (10–13). The phone sits inside a dark box, camera facing up. Each piano key is a lever that uncovers a hole in the lid; the camera detects which hole lit up and plays the matching note. No electronics — the phone is the sensor, computer, and speaker.

This repo hosts the web app (PWA). Open it on a phone over HTTPS, tap **Start camera & sound**, then **Calibrate**: it learns the hole positions from ten presses and you're playing. Chords work. Everything runs on-device; no video ever leaves the phone.

## Files

- `index.html` — the entire app (camera capture, calibration, light detection, Web Audio synth)
- `sw.js` — service worker for offline use
- `manifest.webmanifest`, `icon-*.png` — installable PWA metadata

## Hosting

Served with GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
