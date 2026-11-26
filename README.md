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

Each pack folder has a `skin.json` whose first field is `source_url`, plus a `files` list with a raw download URL and sha256 for every texture (and other pack file). The same links are in `manifest.json`.

| id | name | path |
|----|------|------|
| `1001` | Crimson Candy Outfit | `outfits/1001_crimson_candy` |
| `1002` | Champion Cap | `accessories/1002_champion_cap` |
| `1003` | Flame Tail | `accessories/1003_flame_tail` |
| `1005` | Royal Court & Autumn Grass | `courts/1005_royal_court` |
| `1006` | Galaxy | `balls/1006_galaxy` |
| `1010` | Fire & Lava | `balls/1010_fire_lava` |
| `1011` | Beach Ball | `balls/1011_beach` |
| `1012` | Classic Tri-Colour | `balls/1012_tricolor` |
| `1013` | Neon Synthwave | `balls/1013_neon_synthwave` |
| `1014` | Watermelon | `balls/1014_watermelon` |
| `1015` | Retro Leather | `balls/1015_retro_leather` |
| `1020` | Sunset Pier | `courts/1020_sunset_pier` |
| `1021` | Inside a Monster | `courts/1021_inside_a_monster` |
| `1022` | Orbit Deck | `courts/1022_orbit_deck` |
| `1023` | Snow Court | `courts/1023_snow_court` |
| `1025` | Community Dojo | `courts/1025_community_dojo` |
| `1026` | Quantum Realm | `courts/1026_quantum_realm` |
| `1027` | Midnight Neon Gym | `courts/1027_midnight_neon_gym` |
| `1028` | Ocean Floor | `courts/1028_ocean_floor` |
| `BEA0` | Plump Bean | `models/BEA0_plump_bean` |
