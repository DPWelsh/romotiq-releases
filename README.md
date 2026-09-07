# Romotion releases

Signed, notarised macOS builds of Romotion. Nothing else lives here — the
application source is private.

Download the current beta from **[romotion.xyz/download](https://romotion.xyz/download)**,
not from this page. That link is permanent; where the file is actually
stored is not, and the app's updater follows it.

Every build here is:

- signed with a Developer ID certificate and notarised by Apple, so it opens
  without a warning,
- Apple Silicon only, macOS 15 or newer,
- accompanied by a `.sha256` file you can check with
  `shasum -a 256 -c <file>.sha256`.

Updates arrive in the app itself, through **Check for Updates…** — a small
patch rather than the whole 64 MB.
