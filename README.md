# ORVIX Releases

This repository hosts ORVIX release distribution assets only (installer
binaries + signed update manifests). It does not contain source code.

Each release's assets:
- `ORVIX-Setup-X.Y.Z.exe` - the Inno Setup installer
- `update.json` - signed update manifest (Ed25519)
- `update.json.sig` - detached signature for `update.json`
