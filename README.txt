# Birthday Love Website ❤️

A mobile-friendly interactive birthday surprise website. It includes:
- Animated envelope and letter
- Scratch-to-reveal card (touch or mouse)
- Four photo frames where the visitor can preview images
- Audio player for a song selected from the device
- Cake/candle interaction and floating hearts/confetti
- An on-page text editor for previewing personalized copy

## Preview locally
Open `index.html` in a browser. On some phones, opening a local HTML file may restrict some features; publishing it online is the best way to test it.

## Publish it free with GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a **public** repository named `birthday-surprise` (or any name).
3. Upload `index.html` from this folder to the repository's root.
4. Open the repository's **Settings → Pages**.
5. Under the build/deployment section, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait a few minutes. GitHub will show the live URL, usually:
   `https://YOUR-USERNAME.github.io/birthday-surprise/`
8. Open the link on your phone to test, then send it to your partner.

## Personalize the live site
- The on-page editor changes the current browser preview. To make permanent changes for all visitors, edit the relevant text directly in `index.html`, save, and upload the updated file to GitHub.
- To replace the photo frames with actual photos on the published site, upload image files into the repository (for example, `photo1.jpg`) and edit each frame in `index.html` to include an image such as `<img src="photo1.jpg" alt="Our memory">`. For best results, keep images reasonably compressed.
- To add a song to the published site, upload an audio file you have permission to share (for example, `song.mp3`) and change the audio element to `<audio id="audio" loop src="song.mp3"></audio>`. Browsers generally require the visitor to tap play before audio starts.
- Avoid uploading private images or anything you do not want publicly accessible: a public GitHub Pages website can be viewed by anyone with the link, and the repository itself is public.

## Note about photo/music preview
Choosing a photo or song on the live page previews it in your current browser only. It does not upload those files to the website or make them visible to your partner. Upload files to the repository and update `index.html` to publish them.
