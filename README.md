# Cloudscape: Slow Flight

A slow, live flight through the clouds, right behind your Windows desktop icons.

**[Download the wallpaper ZIP](./cloudscape-slow-flight.zip?raw=true)** · [Get Lively from GitHub](https://github.com/lively-community/lively/releases/latest) · [Try the original Cloudscape](https://fishypants.github.io/cloudscape/)

<img src="https://raw.githubusercontent.com/Fishypants/cloudscape/3bd765e12016e016c66c17efe46278ca639da3a3/hero.jpg" alt="A wide view of mountains under billowing volumetric clouds" width="100%">

*Rendered by Fishypants’ original Cloudscape. The images on this page show the original renderer, not the new flight path.*

I saw Fishypants’ Cloudscape and thought: why can’t this just be my desktop? I added a slow four-minute camera loop and hid the controls. The clouds, terrain, and light are drawn live. It runs offline, with no video in the ZIP.

## Put it on your desktop

1. Open the [official Lively GitHub release](https://github.com/lively-community/lively/releases/latest). Under **Assets**, download the Windows setup `.exe`, not the source-code ZIP or the Microsoft Store listing. Run it, approve the Windows administrator prompt yourself if asked, then open Lively.
2. [Download `cloudscape-slow-flight.zip`](./cloudscape-slow-flight.zip?raw=true) and drag it into Lively **without unzipping it**.
3. Click **Cloudscape: Slow Flight**. Give the scene a moment to generate, then look at your desktop.

**Want to try it before installing?** Unzip it and open `index.html` in Edge or Chrome. Press **H** to show or hide the settings.

## More from the original renderer

| Sun shafts | Sunrise |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Fishypants/cloudscape/3bd765e12016e016c66c17efe46278ca639da3a3/sun-shafts.jpg" alt="Rays of sunlight breaking through thick clouds" width="100%"> | <img src="https://raw.githubusercontent.com/Fishypants/cloudscape/3bd765e12016e016c66c17efe46278ca639da3a3/sunrise.jpg" alt="Warm sunrise over clouds and a procedural mountain landscape" width="100%"> |

## If it runs slow or shows a blank screen

It starts at Medium quality and targets up to 30 fps. Try one monitor first and [pause the wallpaper when other apps cover the desktop](https://github.com/lively-community/lively/wiki/Performance). For a blank screen, test the browser preview first. The renderer needs WebGL 2 and `EXT_color_buffer_float`.

## Who made what

- **[Michael Cook (Fishypants)](https://github.com/Fishypants/cloudscape)** built the original procedural world and WebGL renderer, and made the images above. My part is the camera path, wallpaper defaults, and Lively packaging. The [original MIT license](./LICENSE.txt) is included.
- **The renderer’s technical references:** [Sébastien Hillaire’s sky and atmosphere paper](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14050) and Andrew Schneider’s volumetric cloud work at Guerrilla: [Horizon Zero Dawn (2015)](https://www.guerrilla-games.com/read/the-real-time-volumetric-cloudscapes-of-horizon-zero-dawn) and [Nubis (2017)](https://www.guerrilla-games.com/read/nubis-authoring-real-time-volumetric-cloudscapes-with-the-decima-engine).
- **[VB Srivastav’s Abyssal](https://developers.openai.com/showcase/abyssal-bioluminescent-ecosystem)** is a separate procedural underwater demo worth a look. No Abyssal code or assets are included here.
- **[Lively Wallpaper](https://github.com/lively-community/lively)** is the open-source app that puts it on the desktop.
