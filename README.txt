NMAX V2 Garage — PWA FINAL

This package uses the EXACT icon image supplied by the user.

Files:
- index.html
- manifest.webmanifest
- icons/icon-1024.png
- icons/icon-512.png
- icons/icon-192.png
- icons/icon-180.png
- icons/icon-32.png

The existing Google Apps Script backend is kept unchanged.
The current Code.gs already uses XFrameOptionsMode.ALLOWALL, so the
PWA shell can embed the working Apps Script web app.

Deployment:
1. Upload this folder to an HTTPS static host (AppDeploy or GitHub Pages).
2. Open the resulting HTTPS URL in Chrome on Android.
3. Remove the old home-screen shortcut first.
4. Open the new URL.
5. Chrome menu -> Add to Home screen / Install app.
6. The installed shortcut should use the supplied NMAX V2 Garage icon.

Important:
Do NOT open the Google Apps Script /exec URL directly when installing the
PWA. Install from the new static-host URL because that URL owns the manifest
and icon files.
