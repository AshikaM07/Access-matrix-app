# Privacy Lens 0.2.0

First public release.

## What's in it

- **Permissions screen** with a list view (pick a permission, see who can use it) and a grid view
  (every app × every permission, tap an icon to filter).
- **Special access**: accessibility services, device admins, display over other apps, usage access,
  notification access and installing other apps.
- **History** of every change, grouped by day and tagged "after updating to …" or "not part of an
  update". Your first scan saves a baseline; after that only changes are recorded.
- **Scan screen** with live progress.
- **Settings**: light / dark / system theme, background scans every 6, 12 or 24 hours, scan when you
  open the app, show system apps, optional alerts and a weekly summary, CSV export, and reset.

## Known limitations

- **Requested, not on/off:** notification access and "install unknown apps" can only be shown as
  **Requested**. Android doesn't let other apps see whether they're turned on.
- **Android 10:** "display over other apps" and usage access also show as **Requested**, because
  Android 10 blocks other apps from reading them. Android 16 shows the real state. Versions in
  between weren't tested; they fall back to Requested if blocked.
- **No usage log:** Privacy Lens can't see *when* an app used the camera, microphone or location.
  Android only shows that to system apps.
- **Alerts need notifications:** on Android 13 and newer you'll be asked to allow notifications when
  you turn alerts on.
- **Not on the Play Store:** Play Protect may warn you when installing; tap **More details > Install
  anyway**.

## File

| File | SHA-256 |
|---|---|
| `privacy-lens-0.2.0.apk` | `bf3593495e02d45430a8e34c24781ccad4a5b0dead6b007959ff34abbc11fc78` |

Signing certificate SHA-256: `4f139e0012fa788c6c88d53d4e3071349a553253abb4b200c13b519f919e70b6`
