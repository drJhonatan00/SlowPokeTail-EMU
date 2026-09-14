# SlowPokeTail

## Custom UI and Performance Mod for Citra on Android

**SlowPokeTail** is an unofficial modification of the **Citra emulator for Android**, developed with a focus on a customized visual identity, resource optimization, and an improved user experience on mobile devices.

The project combines interface redesign, asset replacement and processing, texture-loading fixes, and APK structure adjustments intended to provide a more stable and efficient experience on devices using the **ARM64** architecture.

> **Status:** Experimental and educational project.

---

## Key Features

### Interface and visual identity

- Redesigned application interface with a custom visual identity.
- Replacement of standard graphics, icons, and visual elements.
- Adjustments to Android layouts and resources for a more consistent presentation.
- A cleaner visual organization designed for mobile displays.

### Asset and texture optimization

- Image downsampling to reduce memory and VRAM usage.
- Texture resolution standardization to **150 × 150 pixels**, where applicable.
- Removal of ICC color profiles and unnecessary metadata.
- Processing of 32-bit PNG images while preserving transparency and visual compatibility.
- Reduction of packaging issues associated with the **Android Asset Packaging Tool (AAPT)**.

### Rendering fixes

- Handling of missing, corrupted, or magenta-rendered textures.
- Standardization of formats and resolutions to improve resource-loading compatibility.
- Adjustments intended to reduce visual glitches during interface rendering.

### APK repackaging

- Recompilation of the application structure after modifications are applied.
- Use of **ZipAlign** to align APK data according to recommended Android practices.
- Resource organization focused on more efficient loading and reduced storage overhead.

> Actual performance and compatibility may vary depending on the device, Android version, game, and graphics configuration.

---

## Technology and Tools

| Area | Technologies and tools |
|---|---|
| Target platform | Android — ARM64 |
| APK modification | MT Manager, APK Editor |
| Interface and resources | XML, Android layouts, and resource files |
| Image processing | 32-bit PNG, downsampling, and metadata removal |
| Packaging | APK recompilation and ZipAlign |

---

## Installation

1. Go to the repository's [Releases](../../releases) section.
2. Download the desired APK version.
3. On your Android device, allow installation from unknown sources if required by the system.
4. Install the APK by following the instructions displayed on the device.
5. Launch the application and verify that the installed version works correctly on your device.

### Recommendations

- Back up your original installation before applying any modification.
- If Android prevents the installation or update because of a different signing key, remove incompatible versions only after making the necessary backup.
- Download files only from the project's official sources.
- Compatibility is not guaranteed for every device, game, or Android version.

---

## Troubleshooting

### The APK cannot be installed

Check whether an earlier version signed with a different key is installed on the device. If so, uninstall the previous version only after completing any necessary backup, then try again.

### Textures are still missing or magenta

This issue may be related to the game, graphics configuration, Android version, or device compatibility. Try another project version and confirm that the APK was downloaded correctly.

### The application is unstable

SlowPokeTail is an experimental project. Try lowering the resolution or graphics quality, closing other applications running in the background, and testing the APK in a clean installation.

---

## Legal Disclaimer

**SlowPokeTail** is an independent, unofficial, non-commercial project created for educational purposes, including the study of Android resource optimization, interface customization, and application modification.

This project is not affiliated with or officially endorsed by the developers of **Citra**. All rights relating to the original emulator, its trademarks, source code, and other components belong to their respective authors and rights holders.

Do not distribute copyrighted content, games, BIOS files, encryption keys, or third-party resources without proper authorization. Users are responsible for ensuring that their use of the application and its resources complies with the laws applicable in their jurisdiction.

---

## Contributing

Suggestions, bug reports, and contributions are welcome. When opening an issue, please include the following information whenever possible:

- device model;
- Android version;
- SlowPokeTail version;
- game or screen where the issue occurred;
- graphics settings in use;
- a detailed description and, when possible, screenshots or logs.

---

## License

Review the license files and notices included in this repository for the terms applicable to SlowPokeTail and its third-party components.
