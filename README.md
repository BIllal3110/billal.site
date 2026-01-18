# billal3110.github.io

Update: Credly "Introduction to Cybersecurity" badge image replaced with the image URL you provided.

Change applied
- Credly badge <img> now uses: https://i.ibb.co/mKpBRqD/introduction-to-cybersecurity.png
  - This is used directly in `index.html` as the image source.

Recommended (more reliable)
- Download the image and save it in your repo at `images/credly-intro-cyber.png` and then update the `src` to `images/credly-intro-cyber.png`. That prevents broken images if the remote host removes or blocks hotlinking.

How to save the image locally:
1. Open this URL in your browser:
   - https://i.ibb.co/mKpBRqD/introduction-to-cybersecurity.png
2. Right-click → "Save image as..." → save into your site folder under `images/credly-intro-cyber.png`.
3. Update `index.html` if you want the local path (I can prepare that change for you).
4. Commit & push:
   ```bash
   git add images/credly-intro-cyber.png index.html
   git commit -m "Add Credly badge image and update index"
   git push
   ```

If you'd like, I can:
- Update `index.html` to point to the local image path and give you the exact commit-ready files.
- Fetch & optimize the image (resize and compress) and provide a zip you can upload.
- Apply the change directly in your repository (I can prepare a single commit if you want the files bundled).

Which would you like next?  
