# Privacy

Privacy Lens is built to work entirely on your phone.

- **No internet.** The app doesn't have the internet permission, so it can't send anything anywhere.
- **No account, no analytics, no ads.**
- **What it reads:** the list of installed apps, the permissions each one asks for and whether
  they're allowed, and which apps have special access (accessibility, device admin and similar).
  It needs Android's "see all apps" permission to do this.
- **What it stores:** the current permission state of your apps and a history of changes, in a
  private database inside the app. Settings are stored the same way.
- **Notifications:** only if you turn on alerts or the weekly summary. They're created on the phone.
- **Export:** a CSV file is written only when you ask, to the place you choose in the system file
  picker. The app has no storage permission.
- **Deleting your data:** Settings → *Reset baseline and history* clears the history. Uninstalling
  the app deletes everything it stored.

Questions: open an issue on this repository.
