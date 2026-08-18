# Faster-Loadscreens

Faster loading screens for Skyrim (SE / AE / GOG / VR) and Fallout 4. SKSE/F4SE plugins that cut time spent on loading screens by tuning the loading loop, door prefetch and related game settings.

> Fork of [1001Bits/Faster-Loadscreens](https://github.com/1001Bits/Faster-Loadscreens).

## Layout

| Directory | Game | Notes |
| --- | --- | --- |
| `skyrim/` | Skyrim SE / AE / GOG / VR | SKSE plugin sources under `skyrim/src` |
| `fallout/` | Fallout 4 | F4SE plugin — see [`fallout/README.md`](fallout/README.md) |

## Building

Requirements: Visual Studio 2022 (C++ workload), CMake, vcpkg. See the per-game directories for details (the Fallout 4 variant is documented in `fallout/README.md`).

## License

See [LICENSE](LICENSE).
