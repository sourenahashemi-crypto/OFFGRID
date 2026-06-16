# Security Policy

## Supported versions

OFFGRID is a single-page browser app. The current supported version is the latest version in this repository.

## Reporting a vulnerability

If you find a security issue, especially one involving API keys, browser storage, or unsafe handling of uploaded XML/TXT data, report it privately through GitHub security reporting if available, or open a private channel with the maintainer.

Please include:

- What you found.
- How to reproduce it.
- Why it matters.
- Any suggested mitigation.

## Notes

- API keys are stored only in the browser's `localStorage`.
- Uploaded files are parsed locally in the browser.
- The app should never require a backend to function.
