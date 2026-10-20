# Nuvio Sync — TizenBrew module (webview)

This is a **TizenBrew module wrapper** around the Nuvio Sync web build. TizenBrew
can only load modules; it cannot install `.wgt` applications.

- Module path: `alt-coder/nuvio-sync-module` (TizenBrew adds `gh/` itself)
- App name in TizenBrew: **Nuvio Sync (webview)**
- Runs in TizenBrew's webview: **HTML5 video only**
- No AVPlay, no HEVC/MKV native playback, no AVPlay sound-analysis waveform.
  The waveform editor still opens for manual delay adjustment.

For native AVPlay playback and the on-device waveform, install the WGT through
**TizenBrew Installer** (not the TizenBrew module list):

```
alt-coder/nuvio-sync
```

That installs **Nuvio Sync** (`NuvioSync01`) in the TV's Apps list.
