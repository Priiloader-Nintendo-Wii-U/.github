<div align="center">

# Priiloader

### Boot and Recovery Utility for Nintendo Wii

A pre-System Menu homebrew utility offering configurable boot behavior, System Menu patches, and recovery options.

[Official GitHub Repository](https://github.com/DacoTaco/priiloader) · [Latest Release](https://github.com/DacoTaco/priiloader/releases) · [Wii Hacks Guide](https://wii.hacks.guide/priiloader-usage)

</div>

## Product Overview

Priiloader is an open-source system utility for Nintendo Wii, developed by DacoTaco and contributors. Based on Preloader 0.30, it modifies the console's boot sequence so that Priiloader starts before the Wii System Menu.

This early boot position allows it to provide alternative startup options, launch homebrew applications, apply System Menu patches, and help recover from certain software-level failures.

The latest stable release listed by the official repository is **Priiloader 0.10.0**, also identified as Version Kappa.

## Technical Architecture

Priiloader integrates into the Wii's NAND-based boot process and executes before the System Menu.

Its main functions include:

- **Boot Integration:** Places Priiloader before the System Menu in the startup sequence.
- **System Menu Loading:** Loads the normal System Menu or an alternative startup target.
- **Hacks Engine:** Applies configurable patches to supported System Menu versions.
- **Binary Loader:** Starts compatible DOL and ELF applications.
- **Title Launcher:** Launches supported installed titles and channels.
- **Recovery Interface:** Provides access to alternative boot targets when certain System Menu-level problems occur.

## Key Features

- Starts before the Wii System Menu.
- Provides an alternative boot menu.
- Configurable autoboot behavior.
- Launches the Homebrew Channel.
- Supports BootMii IOS launching.
- Loads compatible DOL and ELF files.
- Launches supported installed titles and channels.
- Applies configurable System Menu hacks.
- Includes update-blocking and region-related patches.
- Supports password protection for menu access.
- Supports SD and USB access.
- Supports compatible Wii, Wii Mini, and Wii U vWii configurations.

## Module Overview

| Component | Function |
|---|---|
| Boot Integration | Starts Priiloader before the System Menu |
| Autoboot Manager | Selects the startup target |
| Hacks Menu | Enables and disables supported System Menu patches |
| Binary Loader | Loads DOL and ELF files |
| Title Launcher | Starts installed Wii titles and channels |
| BootMii IOS Integration | Provides a BootMii IOS startup option |
| Device Access | Reads compatible SD and USB storage |

## Supported Platforms

- Nintendo Wii.
- Nintendo Wii Mini.
- Nintendo Wii U in vWii mode.

Priiloader does not modify the native Wii U System Menu. Its vWii functionality applies to the Wii compatibility environment.

## Compatibility Information

| Specification | Details |
|---|---|
| Application | Priiloader |
| Latest stable release listed | 0.10.0 |
| Release name | Version Kappa |
| Release date | September 9, 2023 |
| Original platform | Nintendo Wii |
| Additional support | Wii Mini and vWii |
| System integration | Pre-System Menu |
| Application formats | DOL and ELF |
| Storage access | SD and USB |
| License | GPL |
| Developer | DacoTaco and contributors |

Priiloader can help with certain user-level bricks, including banner-related problems. It cannot recover every failure, particularly problems involving a damaged System Menu IOS, Boot2, or NAND corruption.

## Technical Specifications

| Specification | Details |
|---|---|
| Project name | Priiloader |
| Repository | DacoTaco/priiloader |
| Version | 0.10.0 |
| Architecture | PowerPC-based Wii environment |
| Application category | System utility |
| Installation target | Wii NAND |
| Boot position | Before System Menu |
| Configuration | Priiloader settings and hacks |
| Binary support | DOL and ELF |
| Source language | C and C++ |
| License | GPL |

## Installation Guide

1. Identify the exact console type: original Wii, Wii Mini, or Wii U vWii.
2. Install and verify a working homebrew entry point.
3. Read the official Priiloader installation documentation.
4. Download the release package from the official GitHub repository.
5. Extract the installer files to the appropriate SD card or USB application directory.
6. Launch the Priiloader installer through the Homebrew Channel or another supported homebrew entry point.
7. Carefully verify the detected console environment and installation target.
8. Follow the installer's instructions.
9. Restart the console and verify that Priiloader appears before the System Menu.
10. Configure autoboot and optional System Menu patches as needed.

The installation modifies the console's NAND and boot sequence. Follow the platform-specific guide carefully, especially when working with vWii or Wii Mini hardware.

## FAQ

### What is Priiloader?

Priiloader is a boot-level homebrew utility that starts before the Wii System Menu and provides recovery, boot configuration, and system patching options.

### Does Priiloader replace the System Menu?

No. It starts before the System Menu and can launch it or another configured target.

### Can Priiloader recover a bricked Wii?

It can help recover certain user-level problems, such as banner bricks. It cannot repair every type of brick, including failures involving critical IOS or NAND corruption.

### Does Priiloader support Wii U?

It supports the Wii U's vWii environment, not the native Wii U operating system.

### Does Priiloader support Wii Mini?

Yes. The project documents Wii Mini support, although some options are unavailable on that hardware.

### Can it launch homebrew applications?

Yes. It can launch the Homebrew Channel and compatible DOL and ELF binaries.

### What is the latest stable version?

The latest stable release listed by the official GitHub repository is version 0.10.0, released September 9, 2023.

### Where can I download Priiloader?

Use the official DacoTaco GitHub repository and its releases page.

## SEO Keywords

Priiloader, Nintendo Wii Priiloader, Wii boot utility, Wii recovery tool, Wii brick protection, Wii homebrew, Priiloader 0.10.0, Wii System Menu hacks, Wii autoboot, Wii BootMii IOS, Wii DOL loader, Wii ELF loader, Wii Mini homebrew, vWii Priiloader

<div align="center">

---

**Priiloader** · Nintendo Wii Boot and Recovery Utility

[Official GitHub Repository](https://github.com/DacoTaco/priiloader)

</div>
