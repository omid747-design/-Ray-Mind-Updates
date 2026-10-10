# Ray Mind 0.0.2 MVP

- Added More navigation with a saved Reduce animations preference and app version.
- Check for updates uses this public repository without GitHub sign-in.
- Downloaded APKs are checked for SHA-256, app ID, newer version code, Android compatibility, and the installed signing certificate before opening Android’s installer.
- Android may ask you to allow installs from Ray Mind and always asks before installation.
- Ideas, drafts, and photos stay on the phone; update requests contain no user content.

Android 8.0+; debug-signed MVP with the same signing certificate as 0.0.1.
Install over the existing app to retain its data. Do not uninstall or clear data.
Build, lint, policy unit tests, browser UI flows, APK signature and bundled assets pass.
Physical-device camera/SQLite and update-in-place validation remain outstanding.
