# KUEM brand assets

Approved, ready-to-use KUEM brand applications. KUEM d.o.o., Kranj, Slovenia · [www.kuem.si](https://www.kuem.si)

The KUEM wordmark and K monogram are the property of KUEM d.o.o. Use them only for KUEM and only as supplied: never redraw, stretch, recolour, rotate, add effects or place anything inside the clear space (a quarter of the K height on every side). The fonts in `fonts/` are licensed separately under the SIL Open Font License (`fonts/OFL.txt`).

## File formats

Every artwork comes in the formats its use needs:

| Format | What it is | Use it for |
| --- | --- | --- |
| `.png` | Raster at the exact upload size, or 300 dpi for print items; transparent where the artwork has no background | Uploads, documents, previews |
| `.jpg` | The same raster flattened on white | Platforms that do not accept PNG |
| `.svg` | Vector, text converted to outlines, so it looks the same without the fonts | Websites, design tools, cutting and engraving |
| `.pdf` | Vector, fonts embedded, final size; print files include 3 mm bleed with the TrimBox at the final size | Printers and producers |
| `.ai` | The same vector file for Adobe Illustrator (a PDF-compatible `.ai`): opens with editable shapes and live text | Editing in Illustrator; install the fonts first |

Colours are the KUEM screen colours (sRGB): Carbon #161A1D, Concrete #E8E6E1, White #FFFFFF, Petrol #156B75, Petrol Light #4FA3AD, Signal Copper #F06432. Print and textile producers convert them with their own profile; ask for a printed or fabric proof before every first run.

## Logo

`logo/` holds the master artwork as vector SVG, every shape outlined and cropped to the artwork; add the clear space around it in your layout. Use these files; never retype the wordmark in a font.

| Folder | Files | Use |
| --- | --- | --- |
| `logo/wordmark/` | `KUEM_Wordmark_Carbon`, `_White`, `_Petrol`, `_Black` | The KUEM wordmark, the main logo. Carbon on White or Concrete; White on Carbon; Petrol for secondary use on White or Concrete; Black only where production allows one colour. At least 100 px wide on screen, 25 mm in print, 45 mm embroidered. |
| `logo/monogram/` | `KUEM_Monogram_Carbon`, `_White`, `_Petrol`, `_Black` | The K alone, for places where the wordmark would not be legible: favicons, app icons, profile pictures. Wherever the wordmark fits at 100 px wide or more, use the wordmark. At least 16 px. Never copper, and nothing added to it. |
| `logo/favicon/` | `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Website and web app icons. |

The company name, KUEM d.o.o., is written in text next to the logo, never built into it.

## Icons

`icons/` holds the 44 KUEM icons as SVG (`kuem-<name>.svg`), the same set as on www.kuem.si.

- Drawn on a 24 × 24 grid with a 2 px margin and a 2 px stroke, square caps and mitred joins, lines at 0°, 45° and 90°.
- Colour comes from `currentColor`, so an icon takes the colour of the text around it: Carbon or Petrol on light backgrounds, White on Carbon. Signal Copper only for alarms; in `kuem-decision.svg` the node marked `class="signal"` may be copper.
- Do not add fills, rounded caps or effects.

| Group | Icons |
| --- | --- |
| Meters | water-meter, gas-meter, heat-meter, electricity-meter |
| Field and connectivity | sensor, gateway, network, cellular, battery |
| Events | alarm, valve, leak |
| Sites | building, municipality, lighting, sewerage, location |
| Measurements | temperature, air, noise |
| Platform | platform, database, dashboard, decision |
| Topics | water, energy, environment, mobility, monitoring, chart, analytics, settings, maintenance, code, software, integration, check, people, presence, knowledge, document, dialog, shield, continuity |

## Fonts

`fonts/` holds Space Grotesk (Regular, Bold) for headings and Source Sans 3 (Regular, Semibold) for text. Install all four on every computer that edits the Word and PowerPoint templates; without them Office substitutes other fonts and the layout changes.

## Digital

| Folder | File | Size | Where it goes |
| --- | --- | --- | --- |
| `digital/linkedin/` | `KUEM_LinkedIn_Company-Cover_Dashboard_4536x768_SL` / `_EN` | 4536 × 768 px (PNG, JPG), plus 1512 × 256 copies | Company page › Edit page › Cover image. Upload the 4536 × 768 PNG; LinkedIn shows it at 1512 × 256 px or smaller. The dashboard figures are illustrative, not real readings. |
| | `KUEM_LinkedIn_Logo_400x400` | 400 × 400 px | Company page › Edit page › Logo. |
| | `KUEM_LinkedIn_Personal-Banner_1584x396_SL` / `_EN` | 1584 × 396 px | Personal profiles of KUEM employees › Background photo. The left side stays free for the profile photo. |
| `digital/google/` | `KUEM_Google_Business-Profile-Logo_720x720` | 720 × 720 px | Google Business Profile › Photos › Logo (Google shows it round; the K stays clear of the edge). Also suits other square avatar fields. |
| | `KUEM_Google_Workspace-Logo_320x132` | 320 × 132 px, transparent | Google Workspace Admin › Account › Account settings › Personalization › Custom logo. |
| | `KUEM_Google_Business-Profile-Logo_K_720x720`, `..._Logo_Wordmark_720x720` | 720 × 720 px | Google Business Profile › Logo; the K is recommended (the wordmark is too small to read at map-pin size). These files are above Google's 10 KB minimum file size. |
| | `KUEM_Google_Business-Profile-Cover_Dashboard_1920x1080_SL` / `_EN` | 1920 × 1080 px | Google Business Profile › Cover photo. The dashboard figures are illustrative, not real readings. |
| | `KUEM_Google_Business-Profile-Post_01`, `_03`, `_04` …`_1200x900_SL` / `_EN` | 1200 × 900 px | Google Business Profile › Add update (posts): 01 From device to decision, 03 Domplan, 04 Sombor gas. |
| `digital/google-play/` | `KUEM_Google-Play_Developer-Icon_512x512` | 512 × 512 px | Google Play Console › Developer page › Icon. |
| | `KUEM_Google-Play_Header_Dashboard_4096x2304_SL` / `_EN` | 4096 × 2304 px | Google Play Console › Developer page › Header image. The dashboard figures are illustrative. |
| `digital/github/` | `KUEM_GitHub_Organization-Avatar_500x500` (PNG, SVG) | 500 × 500 px | GitHub › Organization settings › Profile picture. |
| `digital/youtube/` | `KUEM_YouTube_Profile-Picture_800x800` | 800 × 800 px | YouTube Studio › Customization › Branding › Picture (shown round). |
| | `KUEM_YouTube_Watermark_150x150` | 150 × 150 px | YouTube Studio › Customization › Branding › Video watermark. |
| | `KUEM_YouTube_Watermark_Carbon_600x600` (or `_White-Transparent`) | 600 × 600 px | The video watermark at a higher resolution; Carbon recommended. |
| | `KUEM_YouTube_Banner_Dashboard_2560x1440_SL` / `_EN` | 2560 × 1440 px | YouTube Studio › Customization › Branding › Banner image. The text stays in the 1546 × 423 px area every device shows; the dashboard figures are illustrative. |
| | `KUEM_YouTube_Thumbnail_02_Route`, `_03_Reference` …`_3840x2160_SL` / `_EN`, `_Template-Carbon` / `-White` | 3840 × 2160 px, 1280 × 720 JPG copies | Video › Thumbnail. The templates are blank for new videos. Keep text out of the bottom-right corner, where YouTube shows the video length. |
| | `KUEM_YouTube_End-Screen_3840x2160_SL` / `_EN` | 3840 × 2160 px | The last 5–20 s of a video; add the end screen elements on the right in YouTube Studio. |
| `enlit/` | `KUEM_Enlit_Logo_512x512`, `KUEM_Enlit_Picture_1600x900_EN` | 512 × 512 px, 1600 × 900 px | KUEM's company page on enlit.world: logo and company picture. |
| `digital/email-signature/` | `KUEM_Signature-Logo_White_120x29@2x.png` (and `@3x`, `_Transparent`) | shown at 120 × 29 px | The logo of the first KUEM email signature. It stays here because signatures already sent load it from this repository; do not rename or remove it. New signatures are set centrally by KUEM in Microsoft 365, not copied from a file. |

## Office

| Folder | File | What it is |
| --- | --- | --- |
| `office/word/` | `KUEM_Dopis_A4_SL.dotx`, `KUEM_Letter_A4_EN.dotx` | Word templates for A4 letters: the wordmark on the first page, a smaller wordmark on following pages, the company footer on the first page and "2 / 3" page numbers after it. The address field fits windowed DL and C5/6 envelopes (DIN 5008 form B); fold marks at 105 and 210 mm, punch mark at 148.5 mm. Double-click a `.dotx` to start a new letter from it. |
| | `KUEM_Dopis_A4_SL.docx`, `KUEM_Letter_A4_EN.docx` | The same letter as an ordinary document, for tools that do not open templates. |
| | `KUEM_Letterhead_A4_SL` / `_EN` | The first page as artwork, for pre-printed letterhead paper or other tools. |
| | `KUEM_A4_Header_210x30`, `KUEM_A4_Footer_210x23_SL` / `_EN` | The header and footer as separate strips, in place on an A4 width (210 mm). |
| `office/powerpoint/` | `KUEM_Predloga_16x9_SL.potx`, `KUEM_Template_16x9_EN.potx` | PowerPoint templates, 16:9, with nine layouts: title, section, title and content, two content, title only, key figures, picture and text, closing, blank. Use them through File › New › Personal, or double-click. |
| | `KUEM_Predloga_16x9_SL.pptx`, `KUEM_Template_16x9_EN.pptx` | One example slide per layout. |

Presentation rules: one message per slide; titles say the conclusion; nothing smaller than 16 pt on a slide; charts start in Petrol, and Signal Copper marks only an exception or the decision. Slide numbers: Insert › Header & Footer › Slide number.

## Print

All print PDFs include 3 mm bleed on every side. Keep text and logos at least 5 mm inside the final edge.

| Folder | File | Final size | Notes |
| --- | --- | --- | --- |
| `print/business-card/` | `KUEM_Business-Card_85x55_SL_print.pdf` / `_EN_print.pdf` | 85 × 55 mm | Two pages: page 1 the Carbon front with the wordmark, page 2 the personal side. Matte or uncoated board, 350–400 g/m²; no gloss lamination. |
| | `KUEM_Business-Card_85x55_Front`, `_Back_SL`, `_Back_EN` | | Each side separately. Edit the name, function and contacts in the `.ai` file: name 10.5 pt Source Sans 3 Semibold, the rest 8.5 pt Regular, last line 9 mm above the bottom edge. |
| `print/table-flag/` | `KUEM_Table-Flag_150x250_SL` / `_EN` | 150 × 250 mm, portrait | A hanging desk flag on a T-shaped stand. Print both faces from the same file, with a blockout layer between them so neither side shows through mirrored. The sleeve for the crossbar is added above the top edge by the producer. |
| `print/flyer/` | `KUEM_Flyer_A5_SL_print.pdf` / `_EN_print.pdf` | A5, 148 × 210 mm | Two pages: page 1 front, page 2 back. Each side also separately (`_Front_`, `_Back_`). |

## Apparel

`apparel/KUEM_Apparel_Placement-Sheet_A3_SL` is the specification for the producer: positions and sizes on T-shirts, polo shirts, softshell jackets and caps.

| File | Size | Use |
| --- | --- | --- |
| `KUEM_Apparel_Chest_90mm_White` / `_Carbon` | 90 mm wide | Left chest: printed T-shirts, embroidered polo shirts and jackets. |
| `KUEM_Apparel_Back_200mm_White` / `_Carbon` | 200 mm wide | High on the back (180 mm for sizes S and smaller). |
| `KUEM_Apparel_Cap_85mm_White` / `_Carbon` | 85 mm wide | Front of caps, embroidered. |

The files are at 1:1 scale. Garments are Carbon with the White logo; the Carbon logo is for white garments. The logo is never embroidered or printed narrower than 85 mm, because the thin stroke of the M becomes too fine for thread. Embroiderers make their stitch file from the `.svg` or `.ai`, and a sample is approved before the first run.

## Release and checksums

This kit is released as `v1.0.0`, built from the KUEM visual identity release `v1.0.0`. `MANIFEST.sha256` lists the SHA-256 of every file in the kit. Check a download with:

```sh
sha256sum -c MANIFEST.sha256
```

Each release is a Git tag; earlier files stay available at their tags.
