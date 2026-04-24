# Wallpapers

Wallpaper assets + per-set configuration consumed by `nix-season-wallpaper`.

## Layout

- `wallpapers/widescreen/`: ultrawide JPEGs.
- `wallpapers/normal/`: 16:9-cropped JPEGs.

## Gallery

<div>
  <img src="wallpapers/normal/spring_1.jpg" width="220" alt="Spring 1" />
  <img src="wallpapers/normal/spring_2.jpg" width="220" alt="Spring 2" />
  <img src="wallpapers/normal/spring_3.jpg" width="220" alt="Spring 3" />
</div>
<div>
  <img src="wallpapers/normal/summer_1.jpg" width="220" alt="Summer 1" />
  <img src="wallpapers/normal/summer_2.jpg" width="220" alt="Summer 2" />
  <img src="wallpapers/normal/summer_3.jpg" width="220" alt="Summer 3" />
</div>
<div>
  <img src="wallpapers/normal/autumn_1.jpg" width="220" alt="Autumn 1" />
  <img src="wallpapers/normal/autumn_2.jpg" width="220" alt="Autumn 2" />
  <img src="wallpapers/normal/autumn_3.jpg" width="220" alt="Autumn 3" />
</div>
<div>
  <img src="wallpapers/normal/winter_1.jpg" width="220" alt="Winter 1" />
  <img src="wallpapers/normal/winter_2.jpg" width="220" alt="Winter 2" />
  <img src="wallpapers/normal/winter_3.jpg" width="220" alt="Winter 3" />
</div>

## Config

- `config/seasons.json`: festival definitions per season (names/dates; festival name becomes part of the wallpaper key like `winter_<festival>`).
- `config/defaults.json`: global defaults:
  - `festivalPadding.before` / `festivalPadding.after`: extend festival windows by N days.
  - `numberedPositions`: default crop positions for numbered wallpapers by count.
- `config/positions.json`: per-wallpaper override for crop position (`left`/`center`/`right`) keyed by wallpaper key.
- `config/styles.json`: season -> style string to expose in resolver metadata.

## License

- Wallpaper images and configuration (`wallpapers/`, `wallpapers-raw/`, `config/`) are licensed under CC0 1.0 Universal (see `LICENSE-CC0`).
- Scripts and other code (for example `scripts/`) are licensed under the MIT License (see `LICENSE`).
