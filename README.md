# RepLab Media

Self-recorded exercise videos for the RepLab app, served as a Render static site.
Each file here is public at `<CDN address>/<path in this repo>`, for example
`https://replab-media.onrender.com/exercises/dumbbell-lateral-raise.mp4`.

The older CDN (`replab-videos.onrender.com`, repo `Wmartin23/replab-videos`) still serves the
promo video, the program PDFs and the Will's Hypertrophy lateral raise demo. Leave it running.

## Folders

- `exercises/` — one demo video per exercise in the RepLab exercise library

## Video rules

- MP4 (H.264), 60 seconds or shorter
- Under 25 MB (GitHub's website upload limit; 100 MB max if pushed with git)
- File name: lowercase, hyphens, no spaces, matching the exercise name
  - `Dumbbell Lateral Raise` → `dumbbell-lateral-raise.mp4`
  - `Barbell Bench Press` → `barbell-bench-press.mp4`
- Keep the name once it's linked. Renaming or deleting a file breaks the link in the app.

## Add a video

1. Open this repo on GitHub.
2. Open the `exercises` folder.
3. Click **Add file**.
4. Click **Upload files**.
5. Drag in the video.
6. Click **Commit changes**.
7. Wait for the Render deploy to show **Live** (1–2 minutes).
8. Open the video's address in a browser to check it plays.

## Link it to an exercise

1. Open `/admin` on the RepLab website.
2. Go to the **Exercise Library** video manager.
3. Search for the exercise.
4. Paste the video's full address.
5. Save.

## Render settings

- Service type: Static Site
- Build command: (empty)
- Publish directory: `.`
