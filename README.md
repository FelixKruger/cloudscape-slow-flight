# Cloudscape: Slow Flight

I saw Fishypants' [Cloudscape](https://github.com/Fishypants/cloudscape) and wanted it as my desktop. I just wanted to look over and see myself drifting through the clouds, without having to fly the camera.

So I added a slow four-minute camera loop and hid the controls by default. Cloudscape still renders the clouds, terrain and light as you fly. The whole thing runs locally from one HTML file, and there's no video to download.

## Put it on your Windows desktop

1. Get the free [Lively Wallpaper installer from its official GitHub releases](https://github.com/lively-community/lively/releases/latest). Use the setup .exe under Assets, not the source-code ZIP or Microsoft Store listing. Run it, approve the Windows administrator prompt yourself if you choose to install it, then open Lively.
2. [Download `cloudscape-slow-flight.zip`](./cloudscape-slow-flight.zip?raw=true). Leave it zipped.
3. Drag the ZIP into the Lively window. Once the tile appears in the library, click it to apply it to your desktop. Give the scene a moment to generate.

Want to see it before installing anything? Unzip the download and open `index.html` in Edge or Chrome. Press **H** to show or hide the settings.

## Keep it light

It starts at Medium quality and targets up to 30 fps. If it feels heavy, try it on one monitor first and set Lively to [pause it when other apps cover the desktop](https://github.com/lively-community/lively/wiki/Performance). It requires WebGL 2 and the `EXT_color_buffer_float` extension. If you get a blank background, try the browser preview first to see whether the renderer starts there.

The ZIP, JavaScript syntax and camera path were checked. This doesn't establish that it renders on every Windows or GPU setup.

## Credits

- **[Michael Cook (Fishypants)](https://github.com/Fishypants/cloudscape)** made Cloudscape, including the procedural world and the renderer. [Try the original](https://fishypants.github.io/cloudscape/). My changes are the camera path, wallpaper defaults and Lively packaging. The [original MIT license](./LICENSE.txt) is included.
- **[VB Srivastav's Abyssal](https://developers.openai.com/showcase/abyssal-bioluminescent-ecosystem)** is the procedural, bioluminescent underwater demo I also wanted to shout out. No Abyssal code or assets are included here.
- **[Lively Wallpaper](https://github.com/lively-community/lively)** is the app that puts the scene behind your Windows desktop icons.
