# Privacy

Snipra is designed to work locally.

## Desktop application

- Screenshots are processed in memory and are copied or saved only when requested.
- Settings are stored in `%AppData%\Snipra\settings.json`.
- Error logs, when needed, are stored in `%AppData%\Snipra\error.log`.
- OCR uses the local Windows OCR component.
- Snipra has no analytics, telemetry, user accounts, cloud gallery, or remote API.
- The only external link is the optional `tips.tips` support page, opened in the default browser after an explicit click.

## Browser extension

- Captures only the visible area of the active HTTP/HTTPS tab after a user action.
- Saves the image through the browser Downloads API.
- Does not upload, analyze, or retain screenshots.
- Requests only `activeTab` and `downloads`.

## Contact

For privacy questions, open a GitHub issue without including private screenshots or personal data.
