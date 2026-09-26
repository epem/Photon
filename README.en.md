<p align="center"><img src="assets/photon-cover.png" alt="Photon — image editor for Windows" width="100%"></p>

<p align="center"><a href="README.md">Русский</a> · <strong>English</strong></p>
<p align="center">
  <a href="https://github.com/epem/Photon/releases/latest"><img src="https://img.shields.io/github/v/release/epem/Photon?style=flat-square&label=Photon&color=1374ff" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/Windows-x64-171f2b?style=flat-square&logo=windows" alt="Windows x64">
  <img src="https://img.shields.io/badge/Interface-RU%20%2F%20EN-171f2b?style=flat-square" alt="Russian and English interface">
</p>

<h1 align="center">Your images. Your ideas. Your Photon.</h1>
<p align="center">Layers, masks, retouching and color in one editor.<br>Made for the community. Free to use, with no subscription or app account.</p>
<p align="center"><a href="https://github.com/epem/Photon/releases/latest"><strong>Download for Windows →</strong></a> &nbsp; · &nbsp; <a href="https://github.com/epem/Photon/issues">Report a bug</a> &nbsp; · &nbsp; <a href="https://t.me/nrgit">Community</a></p>

![The real Photon interface: landscape, typography and five editable layers](assets/photon-editor.png)

*An actual app screenshot. The picture and type are separate layers; the demo landscape was generated with AI.*

## From a photo to a composition

| What you want to do | What Photon offers |
|---|---|
| Build a composition | Layers and groups, blend modes, layer and clipping masks, transforms and layer effects. |
| Clean up an image | Brush, eraser, clone stamp, healing, selections and content-aware fill. |
| Shape the color | Curves, levels, color balance, exposure, HSL, gradient maps and Camera Raw. |
| Add your idea | Editable text, shapes, gradients, guides and snapping. |
| Isolate a subject | Subject selection and background removal with local models. |
| Keep the result | `.comp` projects, image and RAW import, PSD/PSB import, transparent PNG and JPEG export with a quality preview. |

Image processing and models run on your computer. Internet access is used for update checks, downloads and bug reports you choose to send.

## Install

Open the **[latest release](https://github.com/epem/Photon/releases/latest)** and choose an **Asset**:

| File | How to use it |
|---|---|
| `Photon-Windows-x64-….msi` | Setup wizard with a Start menu shortcut. Since 0.1.9: Photon artwork, RU/EN terms and folder selection. |
| `Photon-Windows-x64-….zip` | Extract the **entire** folder and run `Photon.exe`. No installation needed. |
| `….sha256` | The matching package's checksum. Not needed to launch the app. |

Built for **Windows x64**, checked on Windows 11. The .NET runtime and required libraries are included. Dedicated ARM64 and 32-bit Windows builds are not available yet.

The 0.1.9 installer uses a Russian-language wizard. Keep the suggested folder or click **Обзор (Browse)** to choose your own; subsequent updates remember that location. The original Photon cover appears on the welcome and completion screens, with an optional link to the [NRG community](https://t.me/nrgit). The app itself supports English and Russian.

**`Source code (zip)` and `Source code (tar.gz)` are not installers.** GitHub adds these links automatically. This repository contains documentation, artwork and an issue template; the application's source code is not published here.

## Your first five minutes

1. Create a canvas or import a picture. Drop a file **on the tab strip** to open a separate document, or **on the canvas** to add it as a layer.
2. Build your composition with layers. A mask hides part of a layer while preserving its original pixels.
3. Adjust color and detail. Check the preview before applying changes.
4. Save your work as a `.comp` project, then export a finished PNG or JPEG.

A `.comp` folder is the complete project. Keep and move the whole folder together.

## Make it yours

**Edit → Settings** offers Russian or English, keyboard shortcuts, layer panel width, grids, guides, snapping, JPEG quality and automatic update checks. You can preview the language immediately; Cancel restores your previous settings.

| Action | Default shortcut |
|---|---|
| Brush / eraser | `B` / `E` |
| Move / transform | `V` / `Ctrl+T` |
| Undo / redo | `Ctrl+Z` / `Ctrl+Shift+Z` |
| Fit canvas / actual pixels | `Ctrl+0` / `Ctrl+1` |
| Pan | Hold `Space` |
| Brush size | `[` / `]` |

Open **Keyboard Shortcuts** for the full list and remapping. Hover over numeric fields or sliders and turn the mouse wheel to adjust them; hold `Shift` for larger steps.

## Found a bug?

**Direct reporting is available from Windows version 0.1.8.** Open **Help → Report a Bug**.

1. Give the problem a short title and describe the steps that reproduce it.
2. Optionally include a screenshot. Photon previews **only its editor window**; review it before sending. Screenshots are off by default.
3. Click **Send report**. The text, technical details and selected screenshot are sent together. No GitHub account is needed.
4. Once delivery is confirmed, click **Open issue** to see your report on GitHub.

**Reports and attachments are public.** Diagnostics include the Photon and Windows versions, selected tool, canvas size and layer count. A screenshot can show your artwork; leave out personal information you do not want to publish. Cloudflare relays the report without keeping its own archive; GitHub retains the issue and screenshot.

If the connection drops, use **Check status** to look up the original report. Closing the form keeps its draft while that editor remains open; it is not retained after the application exits.

In the previous form with an **Open GitHub** button, confirm submission in your browser using a GitHub account. **Other ways to report** lets you open the GitHub form or copy the text; you can save a PNG next to the screenshot preview. If Photon will not launch or does not yet have the report form, **[open an issue directly](https://github.com/epem/Photon/issues/new?template=bug_report.md)**.

For slowdowns, include canvas size, layer count, the selected tool and the action that feels slow. Keep personal images and projects out of public reports unless you intend to share them.

## Updates and current limits

**Help → Check for Updates** checks this repository's stable releases. Photon verifies the downloaded file's SHA-256 and offers to save projects before launching the installer. Extract portable ZIP updates to a separate folder. The built-in updater is available from 0.1.6 onward.

Photon is actively being developed. PSD/PSB import has limits, primarily supporting 8-bit RGB documents; full compatibility with every Photoshop feature is not claimed. Large-project performance depends on available memory, graphics hardware and effects. Windows packages do not yet have a publisher signing certificate.

---

<p><img src="assets/nrg.png" width="76" alt="NRG" align="left"></p>

**Take it. Create.**

This editor is a gift to the community from **NRG**. For your photos, collages and bold experiments.

**[t.me/nrgit →](https://t.me/nrgit)**
