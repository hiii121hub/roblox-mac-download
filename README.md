# Roblox Mac download shortcut

A GitHub Pages page that automatically requests the Mac installer from
https://setup.rbxcdn.com/mac/Roblox.dmg. A visible button provides a manual fallback.

Safari may ask the visitor to allow downloads. The visitor must open the downloaded
disk image and run the installer themselves. The page cannot silently install apps.

The installer is downloaded directly from Roblox's CDN; no installer binary is
stored or repackaged in this repository. The download does not require visiting
the roblox.com website. Installation and playing still require Roblox's services.

## Hosting

Publish the `main` branch, root directory, using GitHub Pages.

## Local preview

Run `python3 -m http.server 8000` in this directory and open
http://localhost:8000. Opening the page requests an installer download.

Independent project, not affiliated with Roblox Corporation. Roblox belongs to
its respective owner.
