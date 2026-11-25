# 80/20 Split

Phone web app for Riley, Trey and Camden: the weekly workout plan, a lift log, progress tracking and weigh-ins. Works on iPhone and Android in the browser and can be added to the home screen.

- **`docs/`** is the live app, served by GitHub Pages at https://rmurphin.github.io/split-tracker/
- **`gas/Code.gs`** is the script inside the private *80/20 Split Tracker* Google Sheet. The app sends a person's link code and gets back the lifts and weigh-ins; new entries are saved for that person only. No lifts, weights or link codes are stored in this repo.
- `docs/app.js` is a bundled build. The readable source and build tools are kept with Riley's Claude project.

Personal links are on the People tab of the sheet. To retire a link, clear that person's code and run **80/20 Split → Make link codes for anyone missing one**.
