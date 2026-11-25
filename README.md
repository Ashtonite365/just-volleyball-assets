# just-volleyball-assets

Unofficial original cosmetics for Just Volleyball: ball textures, courts, player models, and accessories.

**This is an unofficial fan project.** It is not affiliated with, endorsed by, or supported by the developers of Just Volleyball. Every file here is an original asset. Do not add copyrighted lookalikes, other people's faces, or any official game files (the executable, `.pck`, or extracted official textures or models).

This repository is public so joining players can auto-download a missing texture or model without signing in. Auto-download is for textures and models only — never code.

## Manifest (machine-readable)

Mods should embed this URL and look up packs by their 4-character id:

```
https://raw.githubusercontent.com/Ashtonite365/just-volleyball-assets/main/manifest.json
```

Each item in `manifest.json` includes:

- `id` — 4-character pack id (for example `1006`)
- `type` — `ball`, `outfit`, `stage`, `model`, `accessory`, or `net`
- `version` — semver string for that pack
- `sha256` — SHA-256 of the item's `pack.zip`
- `download_url` — raw GitHub URL for that zip
- `files` — per-file `path`, `sha256`, and `download_url` if a client prefers loose files

Pin a commit SHA instead of `main` if you need a frozen revision:

```
https://raw.githubusercontent.com/Ashtonite365/just-volleyball-assets/<commit>/manifest.json
```

## Install by hand

1. Have the unofficial core loader installed (see [just-volleyball-core](https://github.com/Ashtonite365/just-volleyball-core)).
2. Close Just Volleyball.
3. Copy a pack folder, or unpack its `pack.zip`, into `mods/resources/packs/<folder>/`.
4. Ball packs appear in the in-game ball picker. Outfit packs are worn when their id is listed in `equipped.json`.
5. Do not overwrite your `picker.json` or `equipped.json` unless you intend to.

## Published packs

| id | name | type | path |
|----|------|------|------|
| 1006 | Galaxy | ball | `balls/1006_galaxy/` |
| 1010 | Fire & Lava | ball | `balls/1010_fire_lava/` |
| 1011 | Beach Ball | ball | `balls/1011_beach/` |
| 1012 | Classic Tri-Colour | ball | `balls/1012_tricolor/` |
| 1013 | Neon Synthwave | ball | `balls/1013_neon_synthwave/` |
| 1014 | Watermelon | ball | `balls/1014_watermelon/` |
| 1015 | Retro Leather | ball | `balls/1015_retro_leather/` |
| 1001 | Crimson Candy Outfit | outfit | `outfits/1001_crimson_candy/` |
| 1002 | Champion Cap | accessory | `accessories/1002_champion_cap/` |
| 1003 | Flame Tail | accessory | `accessories/1003_flame_tail/` |
| 1022 | Orbit Deck | stage | `courts/1022_orbit_deck/` |
| 1025 | Community Dojo | stage | `courts/1025_community_dojo/` |
| 1026 | Quantum Realm | stage | `courts/1026_quantum_realm/` |
| 1027 | Midnight Neon Gym | stage | `courts/1027_midnight_neon_gym/` |
| BEA0 | Plump Bean | model | `models/BEA0_plump_bean/` |

Further packs will be added here as they are published.

Related repositories:

- Core / loader: https://github.com/Ashtonite365/just-volleyball-core
- Mods: https://github.com/Ashtonite365/just-volleyball-mods
