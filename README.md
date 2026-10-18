# Elevion Tech WebP Converter

Convert JPG, PNG, GIF, BMP, TIFF and other images to WebP on your own Windows PC. Images are converted on your computer and are never uploaded.

## Download

**[Download the latest installer](https://github.com/sdhanushka/WebP-Converter/releases/latest)**: `ElevionTechWebPConverter-Setup-1.0.1-x64.exe`

Requires Windows 10 or 11 (64-bit).

## Install

1. Run the setup file and follow the wizard.
2. If Windows shows **Windows protected your PC**, click **More info**, then **Run anyway**. The installer isn't code-signed yet, so Windows doesn't recognise the publisher.
3. Open **Elevion Tech WebP Converter** from the Start menu, or from the desktop shortcut if you chose to create one.

Setup installs Microsoft's WebView2 Runtime if your PC doesn't already have it, which needs an Internet connection. After that, the app works offline.

## Features

- Drag and drop images (up to 200 MB each), or import a whole folder, including subfolders, on **Batch Convert**.
- Choose quality, lossless compression, transparency and GIF/APNG animation, and resize by width and height.
- Save WebP files next to the originals or in a folder you choose. Existing files are not overwritten unless you turn that on.
- Dark, light or system theme. Your settings are remembered.

## Check the download (optional)

Each release includes a `.sha256` file. To confirm your download is intact, run this in PowerShell in the folder where you saved it:

```powershell
Get-FileHash .\ElevionTechWebPConverter-Setup-1.0.1-x64.exe -Algorithm SHA256
```

The hash shown should match the one in the `.sha256` file.

## Uninstall

Go to **Settings > Apps > Installed apps**, find **Elevion Tech WebP Converter** and choose **Uninstall**. Your converted images and saved preferences are kept.

## Privacy

Conversion happens entirely on your computer, and the app's interface runs only on your own machine (127.0.0.1). No images are sent to Elevion Tech or any online service. The About page links to the Elevion Tech website.

This repository hosts the Windows installer only.

---

© 2026 Elevion Tech · [elevion-tech.com](https://elevion-tech.com/)
