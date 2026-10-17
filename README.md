# HumanConnect AI — Web App Prototype

A responsive, single-page front-end prototype using the HumanConnect AI coral, white, and midnight-blue theme.

## Run it
- Open `index.html` in a modern browser to explore the interface.
- For webcam access, browsers generally require HTTPS or `localhost`. If opening the file directly blocks camera access, use a local server:
  - Python installed: run `python -m http.server 8000` in this folder
  - Open `http://localhost:8000`
- Allow camera permission when prompted.

## Included
- Responsive dashboard-style interface
- Webcam preview start/stop (browser permission required)
- Sample label buttons for demonstrating the result panel
- Browser text-to-speech
- Copy result, clear result, and session-only activity history
- Accessible labels, responsive layout, and privacy note

## Important limitation
This is a **front-end prototype**. It does **not** contain a trained sign-language recognition model. The sample buttons are manually selected demo labels, not predictions from the camera. Real recognition requires selecting a target sign language, obtaining a suitable dataset with appropriate permissions, training/evaluating a model, and integrating it with the interface. Do not present this prototype as a fully working translator.

## Deployment
The static front end can be deployed on GitHub Pages. If you later add a Python inference backend, host that backend separately and connect it through an API.
