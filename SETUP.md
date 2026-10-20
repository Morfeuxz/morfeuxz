# MORFEU / GitHub profile README V4

## Publish

1. Make sure your GitHub username is `Morfeuxz`.
2. Create a **public** repository named exactly `Morfeuxz` (if it does not already exist).
3. Upload the *contents* of this folder, including the `.github` directory, into the repo root.
4. GitHub will render the root `README.md` on your profile.

## Add your Denji pixel-art GIF later

1. Find a GIF you are allowed to use, and save it as `assets/denji-action.gif`.
2. In the root `README.md`, find this exact line:

   `<img align="right" width="230" src="./assets/denji-placeholder.svg" alt="Reserved space for a Denji pixel-art action GIF" />`

3. Replace it with:

   `<img align="right" width="230" src="./assets/denji-action.gif" alt="Denji from Chainsaw Man in a pixel-art action animation" />`

4. Commit **both** your GIF and the edited README. Use a reasonably small GIF (ideally under 5 MB), or optimize it first. The placeholder keeps the page intact until then. You can adjust `width="230"` to fit the GIF.

## Enable the contribution snake

1. In **Actions**, select `Generate contribution snake` and click **Run workflow**.
2. Make sure the action can write to the repo (repository Settings → Actions → General → Workflow permissions; access varies).
3. Verify that an `output` branch exists with `github-contribution-grid-snake-dark.svg`.
4. Remove the `<!--` and `-->` markers around the snake section in `README.md`.

## Notes

- Stats, top languages, typing SVG, and visitor counter load from third-party endpoints; their uptime isn't controlled by this repository.
- Top languages represent detected languages in public repositories, **not proficiency**.
- The projects section intentionally presents future plans, not imaginary completed work.
- Your email and phone aren't published in this README.
- The header is editable at `assets/header.svg`.
