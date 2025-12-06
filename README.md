# Birthday Website

This is a single-page, interactive birthday website you can open directly in your browser.

## How to run

- Make sure `birthday.html` is in this folder (`E:\Test`).
- Double-click `birthday.html` or right-click it and choose **Open with** → your browser (Chrome, Edge, etc.).

## How to personalize

- **Name**: Open `birthday.html` in a text editor and replace `Emily` with your friend's name (in the `<title>` and hero heading).
- **Story text**: Search for the bracketed placeholders like `[your place here]` and replace them with your real memories and details.
- **Photos**: Replace the `background-image: url('...')` values with your own photo URLs or local image paths.
- **Music (optional)**:
  - Put an MP3 file (for example `song.mp3`) in the same folder.
  - In `birthday.html`, find the `<audio id="bgMusic">` section and set the `src` to your file name, e.g.:
    - `<source src="song.mp3" type="audio/mpeg" />`
  - Then click the **Music** pill button in the navbar to toggle it on/off.


