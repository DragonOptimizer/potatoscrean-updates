# potatoscrean updates

Signed update files for the potatoscrean Android app. This repository holds no source code.

* `latest.json`: the newest version, its download address, size and SHA-256.
* `potatoscrean-<version>.apk`: the release, signed with the app's original release key.

The app checks `latest.json` once a day and installs a newer version only if its checksum matches and it is signed with the same key as the installed app.
