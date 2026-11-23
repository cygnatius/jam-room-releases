# Jam Room for Windows

1. Download `JamRoom-<version>-setup.exe` from [the latest release](https://github.com/cygnatius/jam-room-releases/releases/latest).
2. Double-click it. Windows may say "Windows protected your PC" because the app is not code-signed yet:
   click **More info**, then **Run anyway**.
3. Click **Next** and **Install**, then **Finish**. It installs for your Windows user only, so it needs no
   administrator password. It adds Jam Room to the Start menu and, if the box stays ticked, to the desktop.
4. Plug in your interface (a Focusrite Scarlett, or any other) before you start Jam Room.

Everything is inside the installer: the band's samples, the amps, the cabinets and the audio engine. Nothing
else needs installing. (On a Windows 10 PC without Microsoft Edge's WebView2, the installer adds it by itself.)

## First jam

- Open **Audio** at the bottom of the app. Jam Room picks a Focusrite on **ASIO** by itself; any other
  interface can be picked under Driver and Interface. Leave the sample rate at 48 kHz. Use a buffer of 128;
  go lower for less lag, or higher if you hear crackles.
- In the parts panel, set a seat on Lead guitar to **Input 1** (guitar) and a seat on Vocals to **Input 2**
  (microphone). Your guitar is played through that part's amp and pedals straight to the interface's outputs.
- Press Play.

## Removing it

Settings, Apps, Jam Room, Uninstall (or "Uninstall Jam Room" in the Start menu folder).

## Licence

Jam Room's desktop app is free software under the GNU GPL version 3 or later (it uses Steinberg's ASIO SDK
under GPLv3). The complete source for each release is attached to the release as `jam-room-<version>-source.zip`.
ASIO is a trademark and software of Steinberg Media Technologies GmbH.
