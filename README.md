# Face Blur

Blur the faces you choose in your videos. Everything happens in your own browser: videos are never uploaded.

## Put it online with GitHub Pages (about 5 minutes)

1. **Unzip** `face-blur.zip` on your computer. You get a folder called `face-blur`.
2. **Create a repository.** Sign in at github.com, click **+** (top right) and then **New repository**.
   - Repository name: choose one, for example `face-blur`. This becomes part of your web address.
   - Choose **Public**. GitHub Pages is free for public repositories. Only the app's code is public, never your videos.
   - Click **Create repository**.
3. **Upload the files.** On the new repository page, click **uploading an existing file**.
   Open the `face-blur` folder, select **everything inside it** (including the `model` folder) and drag it onto the page.
   Use Chrome or Edge, because they keep the `model` folder intact. Wait until all files are listed, then click **Commit changes**.
4. **Turn on Pages.** Go to **Settings**, then **Pages** in the left menu.
   Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**. Click **Save**.
5. **Open your app.** After a minute or two, the page shows your address:
   `https://YOUR-USERNAME.github.io/face-blur/`
   Open it on your phone. Tip: use "Add to Home Screen" so it works like an app.

## Check it worked

The repository should contain `index.html`, `face-api.esm.js`, `README.md`, `LICENSE-face-api.txt` and a `model` folder with 6 files.
If the page says "Face detection could not load", the `model` folder is probably missing. Upload it again.

## Saving videos

- **iPhone:** tap **Save video**, then **Save Video** in the share sheet to put it in Photos.
- **Android:** tap **Save video** and choose where to save or share it. Or use **Download file**.
- **Computer:** the video is downloaded to your Downloads folder.

## Credits

Face detection uses [face-api](https://github.com/vladmandic/face-api) by Vladimir Mandic (MIT licence, see `LICENSE-face-api.txt`), built on TensorFlow.js.
