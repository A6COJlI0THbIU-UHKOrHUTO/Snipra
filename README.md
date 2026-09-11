<p align="center">
  <img src="docs/assets/logo.png" width="128" height="128" alt="Snipra logo">
</p>

<h1 align="center">Snipra</h1>

<p align="center">A fast, local screenshot utility for Windows.</p>

<p align="center">
  Windows 10/11 · No cloud · No account · No telemetry
</p>

<p align="center"><a href="../../releases/latest"><b>Download the latest release</b></a></p>

[Русская версия](README.ru.md)

## Features

- Current monitor, active window, window picker, delayed capture, and all monitors.
- Crop, pencil, marker, lines, arrows, shapes, text, blur, cover, and spotlight.
- Independent **Copy** and **Save** actions.
- PNG/JPEG output to a folder chosen on first launch.
- Separate full-resolution documents for multi-monitor captures.
- Local text recognition through Windows OCR.
- Eight interface languages and light/dark themes.
- Chrome/Edge extension for visible-page capture.

## Install

1. Open the [latest Release](../../releases/latest).
2. Download `Snipra-win-x64.zip`.
3. Compare its SHA-256 value with `SHA256SUMS.txt`.
4. Extract the archive and run `Snipra.exe`.
5. Choose the screenshot folder on first launch.

Snipra is portable and self-contained. Windows may show a SmartScreen warning until the executable is code-signed.

## Browser extension

Download `Snipra-browser-extension.zip`, extract it, then load the folder as an unpacked extension in Chrome or Edge developer mode. It requests only `activeTab` and `downloads`.

## Privacy

Screenshots, settings, and OCR stay on the device. There are no accounts, analytics, telemetry, cloud uploads, or background network requests. Read [PRIVACY.md](PRIVACY.md) for details.

## Support

Use the issue templates for reproducible bugs and screenshot-focused feature requests. Remove personal data from screenshots and logs. Security reports should follow [SECURITY.md](SECURITY.md).

## License

Official binaries are freeware; see [LICENSE.txt](LICENSE.txt). The desktop source code is private and is not published in this repository. Browser extensions contain readable JavaScript by design; the freeware license does not grant reuse or modification rights.

## Support development

Snipra is fully free and donations never unlock features. Optional support: [tips.tips](https://tips.tips/ru/000483530).
