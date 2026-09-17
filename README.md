# Stay Safe During a Storm — Presentation Build

This folder is ready to publish as a GitHub Pages site. It includes the complete review flow:

`Rope-matching playable (Chapter 1 / 2) → Part 1 video → plank-matching playable (Chapter 2 / 2) → Part 2 video → CTA`

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub, for example `build-to-escape-preview`.
2. Upload every file in this folder to the repository root. Keep the file names and folder structure unchanged.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. After GitHub finishes publishing, open the Pages URL shown on that screen.

## Notes

- The opening tap starts the rope-matching chapter. The following videos use the browser's user-gesture context when available and fall back to muted playback when required.
- This is a presentation build, not the AppLovin submission file. It contains full-quality video assets and is about 57 MB.
- The CTA currently opens the placeholder `https://example.com/build-to-escape`. Update that URL in `index.html` before presenting externally if a real store link is available.
