# Monster House (PS2) — April 15, 2006 Prototype Patch

**Author:** otaviop  
**Game:** Monster House (PlayStation 2)  
**Build date:** April 15, 2006  
**Executable:** `SCPS_123.45`  
**Game serial:** `SCPS-12345`  
**PCSX2 CRC:** `1753EB1F`

## Overview

This patch restores the performance of the early Monster House PS2 prototype and introduces several improvements:

- Fixes the severe 1–2 FPS slowdown.
- Enables 60 FPS gameplay.
- Adds proper 16:9 widescreen camera support.
- Corrects object culling for the wider field of view.
- Disables frame blur (ghosting).
- Disables HDR bloom.
- Disables debug printf output.

The patch was tested with the April 15, 2006 prototype in PCSX2.

**Important:** This patch is designed specifically for the prototype executable identified above. It is not compatible with the commercial PS2 release.

## Installation Instructions

### 1. Download the patch

Download the `.pnach` file from this repository.

### 2. Find your PCSX2 cheats folder

Open PCSX2 and use the option to open its data directory:

1. Open PCSX2.
2. Open the **Tools** menu.
3. Select **Open Data Directory**.
4. Find the folder named `cheats`.

Depending on your PCSX2 installation, the data directory may be in a different location.

### 3. Copy the patch file

Copy the downloaded `.pnach` file into the `cheats` folder.

**Important:** The filename must match the game's CRC:

`1753EB1F.pnach`

If necessary, rename the downloaded file to this exact name.

### 4. Enable cheats in PCSX2

1. Open PCSX2 settings.
2. Go to **Emulation**.
3. Enable **Enable Cheats**.
4. Save the settings if prompted.

### 5. Configure widescreen

For the intended 16:9 presentation:

1. Open **Settings > Graphics**.
2. Find the **Aspect Ratio** setting.
3. Select **16:9**.

The patch adjusts the game's camera and culling behavior. The PCSX2 aspect ratio must also be set to 16:9.

### 6. Start the game

Start the April 15, 2006 Monster House prototype.

PCSX2 should automatically recognize the patch when the game CRC matches `1753EB1F` and cheats are enabled.

## Troubleshooting

**The patch is not being detected:**
- Check that the file is inside the PCSX2 `cheats` folder.
- Make sure the filename is exactly `1753EB1F.pnach`.
- Confirm that cheats are enabled.
- Verify that you are running the correct prototype build.

**The game still runs slowly:**
- Confirm that the patch is enabled.
- Check that the game CRC is `1753EB1F`.
- Make sure you are not using the commercial release.

**The image does not look correct in widescreen:**
- Check that PCSX2's Aspect Ratio setting is set to 16:9.

## Compatibility

| Item | Supported version |
|---|---|
| Game | Monster House (PS2) |
| Build | April 15, 2006 prototype |
| Executable | SCPS_123.45 |
| CRC | 1753EB1F |
| Emulator | PCSX2 |

## Credits

**Patch development:** otaviop

## Disclaimer

This project is intended for game preservation, research, and compatibility improvement.

This repository does not distribute the original game, ISO images, BIOS files, or copyrighted game assets. You must provide your own legally obtained game files.
