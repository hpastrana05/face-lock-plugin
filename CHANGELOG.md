# Changelog

All notable changes are documented here. Releases follow Semantic Versioning.

## 1.0.0 - 2026-08-16

- Publish the first stable release of Face Lock Screen.
- Provide automatic Howdy face unlock with password and fingerprint fallback.
- Include media information, a large clock, and high-contrast lock-screen text.
- Validate compatibility with Omarchy 4.x.

## 0.1.5 - 2026-08-16

- Rename the repository and package to `face-lock-plugin`.

## 0.1.4 - 2026-08-16

- Use fixed near-white informational text with crisp black outlines.
- Remove soft text-shadow effects that reduced clarity.
- Place face-authentication status on a compact dark contrast pill.

## 0.1.3 - 2026-08-16

- Rename the displayed plugin to Face Lock Screen.

## 0.1.2 - 2026-08-16

- Improve foreground readability with opaque lock text, heavier weights,
  outlines, and stronger shadows without changing the wallpaper effect.

## 0.1.1 - 2026-08-16

- Match Omarchy's stock wallpaper blur and remove the additional dim overlay.

## 0.1.0 - 2026-08-16

- Fork the Omarchy 4 Media Lock Screen implementation.
- Add isolated Howdy face authentication through `omarchy-lock-face` PAM.
- Keep password and fingerprint authentication available in parallel.
- Add interactive setup and removal helpers.
- Add face-authentication state to the lock UI and IPC status output.
