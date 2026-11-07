# Privacy Lens 0.2.1

Clearer, more honest permission states.

## Fixed

- **Notifications no longer show "Denied" when they might be on.** On some phones, such as Samsung
  Galaxy phones on Android 13, apps that have never asked for notification permission still send
  notifications, and Android doesn't let other apps tell "never asked" apart from "turned off". These
  apps now show as **Requested**, with a note explaining why.
- **Denied only when it's certain.** If Privacy Lens has seen an app's notifications go from allowed
  to off, it shows **Not allowed** for that app (reinstalls don't count).
- **"Denied" is now "Not allowed".** For location, camera and microphone, "Not allowed" also covers
  apps set to **Ask every time**: Android doesn't tell other apps which one you chose. A note and a
  shortcut (*Privacy → Permission manager*) take you to Android's own page, which shows the exact
  setting.

Everything else is the same as [0.2.0](release-notes-v0.2.0.md), including the known limitations.

## Install

Installs over 0.2.0 and keeps your history.

## File

| File | SHA-256 |
|---|---|
| `privacy-lens-0.2.1.apk` | `2affad1f5cadd93dd4ac49c8e9c165477d7400d52c9623c8aaea2d4683564436` |

Signing certificate SHA-256: `4f139e0012fa788c6c88d53d4e3071349a553253abb4b200c13b519f919e70b6`
