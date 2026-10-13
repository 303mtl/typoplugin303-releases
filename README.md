# TYPOPLUGIN303

Downloads and automatic updates for TYPOPLUGIN303 on macOS. Only the finished app lives here. The source code stays private.

## What it does

Type a word and watch it react to the music. It runs in block, grid, slice, glitch and scroll modes, so your text pulses, breaks apart and scrolls in time with the track. Live Syphon output sends the picture straight into Resolume for your VJ rig.

## Download

[Get the latest version](https://github.com/303mtl/typoplugin303-releases/releases/latest)

## Installing

Open the dmg and drag the app onto your Applications folder. The first time you open it, macOS will block it, because the app is not notarised by Apple. Go to System Settings, then Privacy and Security, scroll to the bottom and click Open Anyway, then confirm.

If macOS says the app is damaged instead, open Terminal once and run this line:

```
xattr -dr com.apple.quarantine "/Applications/TYPOPLUGIN303.app"
```

After that first launch you never have to do it again. When a new version comes out, the app tells you on startup and updates itself with one click.

You need an Apple Silicon Mac (M1 or newer) on macOS 14 Sonoma or later.
