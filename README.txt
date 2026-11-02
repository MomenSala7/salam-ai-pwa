SALAM AI — CUSTOM INSTALL ICON PWA

What this does
- Keeps your existing Streamlit app as the application/backend.
- Provides a separate installable website shell with Salam AI branding.
- The installed shortcut uses the supplied Salam AI logo from the web app manifest.

IMPORTANT
The installable app URL will be the GitHub Pages URL, not the original
https://salam-uae.streamlit.app/ URL. The original Streamlit URL continues to work.
The Streamlit app is embedded in this wrapper and still requires internet access.

DEPLOY TO GITHUB PAGES
1. Extract this ZIP.
2. On GitHub, create a NEW public repository named: salam-ai-pwa
   (Do not replace or modify the existing salam-ai-mvp repository.)
3. Upload all files and the icons folder from this ZIP to the ROOT of the new repo.
   The root should contain index.html, manifest.webmanifest, service-worker.js,
   README.txt, and the icons folder.
4. In the new repository, open Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Select branch "main" and folder "/ (root)", then Save.
7. When GitHub Pages publishes the site, open:
   https://momensala7.github.io/salam-ai-pwa/
8. On Android, open that URL in Chrome > three-dot menu > Install app
   (or Add to Home screen). Install from this new URL, not the Streamlit URL.

If you already installed the old Streamlit shortcut, remove/uninstall it first,
then install from the new GitHub Pages URL. Browser icon caches can otherwise
keep showing the old icon.

To use a different repository name, replace "salam-ai-pwa" in the URL accordingly.
