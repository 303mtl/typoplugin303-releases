# TYPOPLUGIN303

Downloads and automatic updates for TYPOPLUGIN303 on macOS and Windows. Only the finished app lives here. The source code stays private.

## What it does

Type a word and watch it react to the music. It runs in block, grid, slice, glitch and scroll modes, so your text pulses, breaks apart and scrolls in time with the track. Live Syphon (Mac) or Spout (Windows) output sends the picture straight into Resolume or TouchDesigner for your VJ rig.

## Download

**Mac:** [Get the latest version](https://github.com/303mtl/typoplugin303-releases/releases/latest) and download the `.dmg`.

**Windows:** [Download the zip](https://github.com/303mtl/typoplugin303-releases/releases/download/win-v1.0.2/TYPOPLUGIN303-win.zip) (about 145 MB).

## Installing on a Mac

Open the dmg and drag the app onto your Applications folder. The first time you open it, macOS will block it, because the app is not notarised by Apple. Go to System Settings, then Privacy and Security, scroll to the bottom and click Open Anyway, then confirm.

If macOS says the app is damaged instead, open Terminal once and run this line:

```
xattr -dr com.apple.quarantine "/Applications/TYPOPLUGIN303.app"
```

After that first launch you never have to do it again. When a new version comes out, the app tells you on startup and updates itself with one click.

You need an Apple Silicon Mac (M1 or newer) on macOS 14 Sonoma or later.

## Installing on Windows

Unzip the whole folder somewhere you can write to, like your Desktop or Documents, and keep the files together. There is no installer. Double click `TYPOPLUGIN303.exe`. Windows will warn you with "Windows protected your PC", because the app is not signed. Click More info, then Run anyway. Allow the microphone when Windows asks, that is your audio input.

For the output, press SPOUT OUTPUT in the STREAM section, then pick TYPOPLUGIN303 in Resolume under Sources, then Spout. In TouchDesigner use the Syphon Spout In TOP.

Like on the Mac, the app checks for new versions on startup and updates itself with one click. Your settings and everything it learned stay.

You need 64 bit Windows 10 or 11 and a graphics card with DirectX 11.
