# Kadence Color Palette Generator

A browser-based tool for generating color palettes that map directly to the [Kadence Theme color system](https://www.kadencewp.com/help-center/docs/kadence-theme/how-to-use-the-kadence-theme-color-palette/). Pick a seed color and get a full, ready-to-use palette organized into the four Kadence color groups.

## Color Groups

The generated palette mirrors the Kadence Theme's four color roles:

| Group | Slots | Purpose |
|---|---|---|
| **Accents** | Accent, Accent–Alt, Accent–Complement | Brand colors, interactive elements, hover states |
| **Contrast** | Strongest Text, Strong Text, Medium Text, Subtle Text | Text hierarchy from headings to placeholders |
| **Base** | Subtle Background, Lighter Background, White/Offwhite | Page layout and section backgrounds |
| **Notices** | Success, Info, Alert, Warning, Rating | System feedback and status messages |

## Features

- **Seed color picker** — choose any hex color as your starting point
- **Color harmonies** — Monochromatic, Analogous, Triadic, Split complement
- **Background modes** — Cool gray, Warm gray, or Tinted (hue-derived)
- **Live contrast preview** — see text and button colors rendered on white
- **WCAG checker** — AA/AAA pass/fail badges for text colors against white
- **Export JSON** — copies palette as JSON, ready to import into Kadence
- **Copy all hex** — copies every hex value to clipboard at once

## Usage

Open `index.html` in any browser — no build step or dependencies required.

1. Click the color swatch or hex value to open the color picker
2. Choose a harmony mode and background style
3. Review the contrast preview and WCAG badges
4. Click **Export JSON** to copy the palette for use in Kadence

### Applying in Kadence

In WordPress, go to **Customizer → Colors & Fonts → Colors** and paste the exported JSON values into the corresponding palette slots. Changes apply globally across all Kadence Theme settings and Kadence Blocks.

## Reference

Based on the official Kadence Theme documentation:  
[How to Use the Kadence Theme Color Palette](https://www.kadencewp.com/help-center/docs/kadence-theme/how-to-use-the-kadence-theme-color-palette/)
