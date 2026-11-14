# Potrero Map Challenge

A GitHub Pages-ready drag-and-drop study game based on the two Potrero, California maps supplied for Zone 27 A/B and Zone 27 B/C.

## Run locally
Open `index.html` in a modern web browser. No build tools or dependencies are required.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and the `assets` folder (keep the folder structure).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The URL will appear in the Pages settings.

## Game contents
- Round 1: Zone 27 A/B roads and landmarks
- Round 2: Zone 27 B/C roads and landmarks
- Round 3: Mixed review
- Drag-and-drop or tap-to-place controls
- Scoring, answer feedback, retry, and round reset

## Editing questions
Open `index.html` and edit the `rounds` array in the JavaScript section. Each item uses:
`[answer, clue, "ROAD" or "LANDMARK"]`

The game currently includes a starter set of six questions per round. Compare every answer against the uploaded map before using it as a formal test.
