# Ray Mind APK updates

Public APK distribution for Ray Mind. The source repository stays private.

Download the latest APK from [Releases](https://github.com/omid747-design/-Ray-Mind-Updates/releases/latest).
Android 8.0 or newer. Install over the existing Ray Mind app to preserve ideas,
drafts, and photos. These MVP builds use the original debug signing certificate.

Starting with 0.0.2, open **More → Check for updates** inside Ray Mind. Updates
are downloaded only on request, verified, and passed to Android’s installer.
Your notes and photos stay on your phone. No sign-in is needed for updates.

## Publication

Each version has APK, SHA256SUMS, release notes, and update.json under
`releases/vX.Y.Z/`. After verifying the package, version code, and original signer,
push main and its version tag. The workflow verifies the checksum, publishes the
release, then activates `main/update.json`. This feed must only describe a
successfully published release. Never commit source code, signing keys, or tokens.
Keep increasing versionCode and preserve the signing key for Android upgrades.
Actual Android installation and update-in-place testing are still outstanding.
