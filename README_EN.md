# 42 Istanbul Campus Map (GoldSource)

This project is a near-real-scale replica of the 42 Istanbul campus created for games using the GoldSource engine (Half-Life 1, Counter-Strike 1.6, etc.). The map aims to reproduce the campus architecture and atmosphere within the GoldSource environment.

## About
The map is a detailed digital model of the 42 Istanbul campus, optimized for the GoldSource engine. It can be used both for editing and for playing/testing in compatible games.

---

## Repository Contents (current filenames)

- `istanbul_42.rmf` — editable RMF project file (Rich Map Format). Open with Valve Hammer Editor or J.A.C.K.
- `istanbul_42.bsp` — compiled BSP map file; place into Half-Life / Counter-Strike `maps/` folder to play.
- `TexturesWadFiles.rar` — archive containing WAD textures used by the map.
- `TexturesWadFiles/` (directory) — directory with texture files (if present in the repo).
- `HLTextureTools_V165.zip` — tools for managing and editing textures.
- `vluzacn_s_zhlt_v34.zip` — modern ZHLT/VHLT compiler tools for compiling RMF → BSP.
- `temp/` — temporary or test files (contents may vary).

Note: Some archives (e.g., zip/rar files) contain external tools; follow the tool-specific README or usage instructions after extraction.

---

## How to Use / Develop

1. Requirements
   - An RMF editor such as Valve Hammer Editor (older versions) or J.A.C.K.
   - ZHLT/VHLT compilers (a pack is provided as `vluzacn_s_zhlt_v34.zip`).

2. Install Textures
   - Extract `TexturesWadFiles.rar` and install or point your editor to the texture paths.
   - Configure textures in Hammer/J.A.C.K. texture browser.

3. Open Project
   - Open `istanbul_42.rmf` in your editor and make edits as needed.

4. Compile
   - Use the tools inside `vluzacn_s_zhlt_v34.zip` (e.g., hlcsg, hlbsp, hlvis or VHLT equivalents) to compile the RMF into a `.bsp` file.

5. Test
   - Copy the generated `istanbul_42.bsp` to your Half-Life / Counter-Strike `maps/` folder.
   - In game console: `map istanbul_42` to load the map.

---

## License & Third-party Assets
Some textures or tools included may come from third-party sources. Check licenses and permissions before reusing or redistributing any third-party content.

---

This project is developed by the 42 Istanbul Game Design and Development Club.
