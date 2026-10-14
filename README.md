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

## Fonts

`fonts/` holds Space Grotesk (Regular, Bold) for headings and Source Sans 3 (Regular, Semibold) for text. Install all four on every computer that edits the Word and PowerPoint templates; without them Office substitutes other fonts and the layout changes.

## Digital

| Folder | File | Size | Where it goes |
| --- | --- | --- | --- |
| `digital/linkedin/` | `KUEM_LinkedIn_Company-Cover_4200x700_SL` / `_EN` | 4200 × 700 px | Company page › Edit page › Cover image. LinkedIn shows it at 1128 × 191 px; the bottom-left corner stays empty because the logo overlaps it there. |
| | `KUEM_LinkedIn_Logo_400x400` | 400 × 400 px | Company page › Edit page › Logo. |
| | `KUEM_LinkedIn_Personal-Banner_1584x396_SL` / `_EN` | 1584 × 396 px | Personal profiles of KUEM employees › Background photo. The left side stays free for the profile photo. |
| `digital/google/` | `KUEM_Google_Business-Profile-Logo_720x720` | 720 × 720 px | Google Business Profile › Photos › Logo (Google shows it round; the K stays clear of the edge). Also suits other square avatar fields. |
| | `KUEM_Google_Workspace-Logo_320x132` | 320 × 132 px, transparent | Google Workspace Admin › Account › Account settings › Personalization › Custom logo. |
| `digital/youtube/` | `KUEM_YouTube_Profile-Picture_800x800` | 800 × 800 px | YouTube Studio › Customization › Branding › Picture (shown round). |
| | `KUEM_YouTube_Watermark_150x150` | 150 × 150 px | YouTube Studio › Customization › Branding › Video watermark. |
| `digital/email-signature/` | `KUEM_Email-Signature_SL.html` / `_EN.html` | | The signature for Outlook and other clients. Open the file in a browser, select all, copy, and paste into Outlook › Settings › Signatures; then replace the name, job title, phone and email. |
| | `KUEM_Signature-Logo_White_120x29@2x.png` (and `@3x`, `_Transparent`) | shown at 120 × 29 px | The logo the HTML signature loads from this repository. To embed it instead, insert the `@2x` PNG and set its size to 120 × 29 px. |

The signature uses Arial on purpose: Outlook for Windows ignores fallback fonts and would show Times New Roman wherever the brand font is not installed.

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
