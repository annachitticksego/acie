# ACIE Visual Architecture and Design System

The visual identity of ACIE is defined by the presentation standard on [annachittick.com](https://annachittick.com). It pairs dark architectural stone with warm parchment cream, soft alabaster typography, and a decisive ACIE blue accent.

---

## 1. Brand Marks and Logo Assets

Located in the [`assets/`](assets/) directory:

* [`assets/acie-logo.svg`](assets/acie-logo.svg): Official ACIE monogram glyph (`#FFFFFF`) set on the primary obsidian ground (`#08090d`).
* [`assets/acie-logo.png`](assets/acie-logo.png): High resolution `1024x1024` PNG rendering of the ACIE monogram on obsidian ground.
* [`assets/acie-logo-light.svg`](assets/acie-logo-light.svg): Transparent background SVG with white glyph (`#FFFFFF`) for dark surfaces.
* [`assets/acie-logo-dark.svg`](assets/acie-logo-dark.svg): Transparent background SVG with obsidian glyph (`#08090d`) for cream or light surfaces.

---

## 2. Color Palette

| Role | CSS Variable | Hex | Usage |
| :--- | :--- | :--- | :--- |
| **Ground (Primary Dark)** | `--ground` | `#08090d` | Primary background across the House, hero frames, and dark editorial rooms |
| **Cream (Light Surface & Headings)** | `--cream` | `#f4eee0` | Display headings on dark ground, and background surface for private advisory and light gallery panels |
| **Body (Primary Copy on Dark)** | `--body` | `#e6e8f0` | Main editorial body text on dark obsidian ground |
| **ACIE Blue (Signature Accent)** | `--blue` / `--acie-blue` | `#8ab8d6` | Text links, link underlines (`2px` thickness), interactive focus states, and subtle signal highlights |

---

## 3. Typography (`annachittick.com` Approved Standard)

Google Fonts stylesheet:
```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@900&family=Mate:ital@0;1&family=Yantramanav:wght@300;400;500&display=swap">
```

### Display Headings (`--display`)
* **Font Family:** `'Big Shoulders Display'`
* **Weight:** `900` (Black)
* **Treatment:** Uppercase, tight letter spacing (`-0.02em` to `-0.035em`), line height `1.02` to `1.05`.
* **Scale:**
  * Masthead (`h1`): `clamp(4rem, 14vw, 14rem)`
  * Page Title: `clamp(56px, 7vw, 104px)`
  * Section Heading (`h2`): `clamp(3rem, 5.5vw, 5rem)`

### Editorial Body Copy (`--editorial`)
* **Font Family:** `'Mate'` (Regular `400` and Italic `400i`)
* **Treatment:** Line height `1.65`, comfortable reading measure (`43ch` to `60ch`), base copy size `20px` (`1.25rem`) on desktop and `18px` on mobile.
* **Doorway & Editorial Lead Scale:** `clamp(2rem, 3.4vw, 2.75rem)` with `1.25` line height.

### Labels, Eyebrows, and UI Metadata (`--label`)
* **Font Family:** `'Yantramanav'`
* **Weights:** `300`, `400`, `500`
* **Treatment:** Size `0.875rem` (`14px`), line height `1.5`, letter spacing `0.06em`, used for eyebrows, navigation signatures, captions, and structural metadata.

---

## 4. Layout and Spatial Principles

* **Contrast of Rooms:** Deep obsidian chambers (`#08090d`) alternate with warm cream rooms (`#f4eee0` with `#08090d` text) to create physical transitions between public architecture and private counsel.
* **Link Styling on Light Panels:** Links on cream surfaces use `#08090d` text with a `2px` solid `#8ab8d6` (`--acie-blue`) underline offset by `0.25em`.
* **Proportion and Restraint:** Generous vertical rhythm (`64px` to `128px` section padding), `4%` horizontal gutters, `12px` media radius, and unhurried visual hierarchy.
