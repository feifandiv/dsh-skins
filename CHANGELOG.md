# Changelog

## 1.0.0

First public release.

- Two global skins in one bundle: **Ink** (charcoal, terracotta accent) and **Paper** (ivory paper, terracotta accent).
- Switcher as a row in **Settings → General** (`settings.general.item`), with an off switch that restores the shipped theme.
- Both skins carry a light and a dark palette, so the Appearance light/dark/system preference still applies.
- Reading-comfort layer shared by both skins: body text keeps the highest contrast, tool rows/timestamps/telemetry step back, hairlines fade, +1px content leading.
- Selectors sit one step above the base sheets, so a cold start cannot override the skin.
- Choice persists in `localStorage` (`dsh-skins:active`).
