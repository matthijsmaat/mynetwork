# Netwerk – UI prototype

A clickable, front-end-only prototype of a project/people network with messaging.
There is no server: all data is demo data stored in the browser (localStorage) on each device.

## Try it
- **Login**: anything works and logs you in as Matthijs.
- **Network**: drag a project or person to the middle (or double-tap it) to re-centre. Tap to select.
- **Buttons**: (de)select all · edit · + add · call (1 person) / Skype (several) · open/send messages.
- **Chat**: the reply arrow answers all addressees, tap "Me → …" to change recipients, and the camera adds a photo.
- "Simulated replies" (on the login screen) lets someone answer you after a few seconds, so badges and notifications can be tested.

## Publish on GitHub Pages
1. Create a repository and upload all files in this folder (index.html, manifest.json, sw.js, icons).
2. Go to Settings → Pages → Source: *Deploy from a branch* → `main` / root → Save.
3. Open `https://<username>.github.io/<repo>/` on your phone.
4. Install it: Android/Chrome → menu → *Install app*; iPhone/Safari → Share → *Add to Home Screen*.
