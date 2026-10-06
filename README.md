# Romotiq releases

Signed, notarised macOS builds of Romotiq. Nothing else lives here — the
application source is private.

**[Download the latest Mac installer](https://github.com/DPWelsh/romotiq-releases/releases/latest/download/Romotiq-latest-arm64.dmg)**

Apple Silicon · macOS 15 or newer. Romotiq is an invite-only beta: using
the app requires an active invite code. Already invited? Your personal
email link downloads the installer and activates it on your Mac. If you need
access, **[apply at romotiq.xyz](https://romotiq.xyz/#beta)**.

Open the downloaded DMG, drag Romotiq to Applications, and open it there.
Use the **Activate** button in your invitation, or paste your invite code
when the app asks.

Every build here is:

- signed with a Developer ID certificate and notarised by Apple, so it opens
  without a warning,
- Apple Silicon only, macOS 15 or newer,
- published as a versioned DMG and ZIP with matching `.sha256` files. For a
  checksum check, download the versioned file and its sidecar from the release
  page, then run `shasum -a 256 -c <file>.sha256`. The latest installer alias
  has the same bytes as that release's versioned DMG.

Already installed? Use **Romotiq → Check for Updates…**. The updater uses a
small patch when one is available. The ZIP and delta files here are for the
updater; the DMG above is the installer.
