# My Hot Rod releases

Built copies of the My Hot Rod engine laboratory, and the update manifests the installed apps read. No source code, keys or other secrets are kept here; the source lives in a separate private repository.

Each release holds:

- `My-Hot-Rod-<version>.apk` and `update.json`: the Android app. Installed copies read `releases/latest/download/update.json` and only accept an APK signed with the app's own key.
- `My-Hot-Rod-Setup-<version>.exe`, `My-Hot-Rod-<version>-windows.zip` and `windows.json`: the Windows app. Installed copies read `releases/latest/download/windows.json` and check each download's size and SHA-256.

**First install:** open the [latest release](../../releases/latest). On a phone, download the `.apk` and open it. On Windows, run the Setup `.exe` (if SmartScreen warns about an unknown publisher, choose More info, then Run anyway). After that, both apps update themselves.

Releases are published once a day at noon when the source changed, or on request, from the workstation that holds the signing key.
