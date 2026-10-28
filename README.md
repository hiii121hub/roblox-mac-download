# Power Point — Roblox Mac download shortcut

A GitHub Pages page that automatically requests the Mac installer from
https://setup.rbxcdn.com/mac/Roblox.dmg. It saves the unchanged installer bytes as
`Power Point.dmg` using a browser Blob download. A visible button allows retries.
If fetching fails, a direct download uses Roblox's original filename instead.

Power Point is a custom label, not Microsoft PowerPoint. The installed app still
identifies as Roblox. No bundle metadata or signature is modified.

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
