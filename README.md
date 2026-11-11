# M35 Galaxy AI Unlock

Experimental KernelSU module for **Samsung Galaxy M35 5G (SM-M356B / m35x, Exynos 1380)**.

**Developer:** saver420  
**Support:** [Telegram @saver2022](https://t.me/saver2022)  
**Tested:** One UI 9 / Android 17

## Features
- Enables the Galaxy AI floating-feature flags included in the module.
- Enables Image Clipper, Object Eraser, Smart Select and Photo Remaster flags.
- Changes the animation type from LowEnd to HighEnd when the expected XML entry is present.
- Applies the SM-S928B model-property spoofing used by the developer's tested script.
- Uses a systemless bind mount rather than overwriting `/system/etc/floating_feature.xml`.

## Requirements
- Samsung Galaxy M35 5G, model SM-M356B.
- KernelSU and the utilities required by the module.

## Installation
1. Download the ZIP from [Releases](../../releases).
2. Open KernelSU Manager → Modules → Install from storage.
3. Select the ZIP and reboot when prompted.
4. Check the supported Galaxy AI features.

## Important
This is an experimental device-specific modification. Model spoofing may affect device identification in apps and services. Compatibility with other devices or firmware versions is not guaranteed. Keep KernelSU Safe Mode available in case you need to disable the module.

## Support
For questions and bug reports: [@saver2022](https://t.me/saver2022)

Made by **saver420**.
