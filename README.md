# Virtual Mixer v1.0.2

Mix selected applications and your microphone into **Virtual Mix Output** for calls or recordings.

[Download the Windows version](https://github.com/killerprashant/virtual-mixer/releases/latest).

## Getting started

1. Extract the whole downloaded ZIP and run **Virtual Mixer v1.0.exe**. Keep the accompanying files together. The app shows v1.0.2.
2. Allow the Windows setup prompt if it appears.
3. **Virtual Mix Output** becomes available while the app is open. Choose it as the microphone in your call or recording app.
4. In **Audio Sources**, check the apps you want, such as NVDA and Brave. Their audio joins the mix immediately. Choose **Stream Everything** to include all sound from the selected playback device instead.
5. If you want to speak, enable **Include Microphone** and choose your microphone. You can turn it on or off and change microphones at any time.
6. Use **Ctrl+Q** or **File → Exit** when finished. Virtual Mix Output disconnects when the app exits.

There are no Start or Stop buttons. With no apps or microphone selected, the output stays available and sends silence. Saved app and microphone choices take effect when you launch the app.

You can add or remove apps at any time. Newly detected audio apps appear automatically; **Refresh Applications** refreshes the list.

## Keyboard controls

| Key | Action |
| --- | --- |
| Tab / Shift+Tab | Move between controls |
| Up / Down in Audio Sources | Move between apps |
| Space in Audio Sources | Add or remove the focused app from the stream |
| Ctrl+Up / Ctrl+Down in Audio Sources | Raise or lower that app's volume by 5% |
| Ctrl+R | Refresh applications |
| Ctrl+, | Open Settings |
| Ctrl+I | Read the current status |
| Ctrl+Alt+W | Hide the main window |
| Ctrl+Q | Exit the mixer |

**Source Volume** adjusts all selected application audio together. **Microphone Volume** adjusts only your microphone. Their mute controls work separately.

## Microphone and push to talk

Enable **Microphone Noise Removal** to reduce background noise. **Noise Removal Strength** adjusts the amount.

To use push to talk, open **Settings**, enable **Push to talk (microphone only)** and press **Set key**. Press the key or combination you want, then save with **OK**. Hold that key to speak; release it to mute your microphone. Application audio continues. The default key is **None**.

Enable **Hear My Microphone** and select your headphones to hear your processed microphone while streaming. Use headphones to avoid echo.

## Quick window and hiding

In **Settings → Quick controls**, choose the controls you want, enable the quick-window shortcut and use **Set key** to assign it. Its default key is **None**.

Press your shortcut to open the quick window while the main window is hidden. **Escape** closes the quick window and keeps streaming. You can also open it from **File → Quick controls** or the Virtual Mixer tray icon.

**Alt+F4** hides the main window by default. Restore it from the tray menu or the quick window's **File → Show main window**. Use **Ctrl+Q** to quit.

## Settings and updates

Your settings and app volumes save automatically and return on the next launch.

The app checks for updates on every launch by default. If a newer version is available, an update dialog opens. Choose **Download update**, then **Install and restart**. The mixer closes its audio session and restarts automatically. Your settings are kept.

Use **Help → Check for updates** to check manually. Automatic checks can be disabled in Settings. If you are already up to date or an automatic check cannot connect, it stays quiet.
