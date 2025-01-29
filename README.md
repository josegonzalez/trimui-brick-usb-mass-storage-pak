# trimui-brick-usb-mass-storage.pak

A TrimUI Brick app wrapping the built-in USB Mass Storage app.

> [!WARNING]
> Usage of this app may result in SD card corruption. Use at your own risk.
>
> Instead, **Heavily consider installing** connecting your device via USB cable and
> installing `adb` (Android Debug Bridge) or using [WebADB](https://app.webadb.com/)
> in your browser for a drag and drop experience.

## Installation

1. Mount your TrimUI Brick SD card.
2. Download the latest release from Github. It will be named `USB.Mass.Storage.pak.zip`.
3. Copy the zip file to `/Tools/tg5040/USB Mass Storage.pak.zip`.
4. Extract the zip in place, then delete the zip file.
5. Confirm that there is a `/Tools/tg5040/USB Mass Storage.pak/launch.sh` file on your SD card.
6. Unmount your SD Card and insert it into your TrimUI Brick.

> [!NOTE]
> The device directory changed from `/Tools/tg3040` to `/Tools/tg5040` in `MinUI-20250126-0` - released 2025-01-26. If you are using an older version of MinUI, use `/Tools/tg3040` instead.
