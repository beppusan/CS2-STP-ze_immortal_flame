# CS2 Immortal Flame Stripper

[![Status: Alpha](https://img.shields.io/badge/Status-ALPHA-red?logo=github)](https://github.com/beppusan/CS2-STP-ze_immortal_flame)

This repository provides *StripperCS2 configurations* and additional *assets* (e.g., sounds) to extend the map ze_immortal_flame for CS2 ([Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3292773390)).

> [!IMPORTANT]
> This project is a community-driven initiative and is ***not*** an official release by the original map authors or map porters.

> [!NOTE]
> Feel free to use these assets and scripts on your server, whether it is a training server or a regular online server.

## Prerequisites

Before you begin, make sure you have the following installed and configured:

- [Metamod:Source](https://www.metamodsource.net/downloads.php/?branch=master)
- [CS2Fixes](https://github.com/Source2ZE/CS2Fixes)
- [StripperCS2](https://github.com/Source2ZE/StripperCS2)

Additionally, you need a plugin to precache the soundevent file to ensure proper music playback.

> [!WARNING]
> I **NEVER** recompile the map, regardless of any requests. Even if a workshop for integrating extra assets exists (or will be created), using it is entirely at your own risk.

## Installation

1. Clone or download this repository

   ```bash
   git clone https://github.com/beppusan/CS2-STP-ze_immortal_flame.git
   ```

2. Move or copy all contents from the `stripper` folder into the `StripperCS2/maps` directory.

3. Copy all contents from the `assets` folder into your asset workshop.

4. Create a custom plugin for precaching the soundevent file and ensure it is properly loaded.

> [!TIP]
> I plan to create a soundevent precacher as a [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp) plugin in a future update.

5. Run your server and switch to the map `ze_immortal_flame`

## Roadmap

![roadmap](https://github.com/user-attachments/assets/d069b7ad-dd20-42d9-86ae-4cdb7f05f791)

## License

Configuration files and assets in this repository are released under the [MIT License](LICENSE).

### Acknowledgments

We would like to express our sincere gratitude to the original map authors and map porters, as well as to the developers behind Metamod:Source, CS2Fixes, and StripperCS2. Their contributions and dedication have made this project possible.
