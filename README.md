# Beta Client Auth Pages

This folder is ready for GitHub Pages.

## What this is

- `allowed_ids.txt` is the file your client should download.
- `index.html` is an optional landing page.
- After upload, you will not need `BetaClientAuthPanel.bat` anymore.

## Create the GitHub Pages repo

1. Create a new public GitHub repository.
2. Recommended name: `betaclient-auth`
3. Upload all files from this folder into that repository.

## Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to `Settings`.
3. Open `Pages`.
4. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
5. Save.

## Your final URL

Your file URL will be:

`https://ggddffg903-ui.github.io/betaclient-auth/allowed_ids.txt`

Example:

`https://alex.github.io/betaclient-auth/allowed_ids.txt`

## Update the client config

Open:

`C:\Users\user\AppData\Local\Temp\BetaClientAuth\config.properties`

Replace `allowed_ids_url` with:

`https://ggddffg903-ui.github.io/betaclient-auth/allowed_ids.txt`

## Add new IDs later

You can add IDs without your PC being on:

1. Open the GitHub repository.
2. Open `allowed_ids.txt`.
3. Click the pencil icon `Edit`.
4. Add one ID per line.
5. Commit changes.

GitHub Pages will keep serving the updated file.
