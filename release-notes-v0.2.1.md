# Privacy Lens 0.2.1

A fix for how notifications are shown.

## Fixed

- **Notifications no longer show "Denied" when they might be on.** On some phones, such as Samsung
  Galaxy phones on Android 13, apps that have never asked for notification permission still send
  notifications, and Android doesn't let other apps tell "never asked" apart from "turned off". These
  apps now show as **Requested**, with a note explaining why. Tap an app to see its real notification
  settings.

Everything else is the same as [0.2.0](release-notes-v0.2.0.md), including the known limitations.

## Install

Installs over 0.2.0 and keeps your history.

## File

| File | SHA-256 |
|---|---|
| `privacy-lens-0.2.1.apk` | `da2600868c73adb27d0ce5ea014d1c7da94a614ea75e6fb684f10ca119d9e34c` |

Signing certificate SHA-256: `4f139e0012fa788c6c88d53d4e3071349a553253abb4b200c13b519f919e70b6`
