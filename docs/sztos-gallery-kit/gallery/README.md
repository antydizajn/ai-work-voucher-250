# SZTOS Gallery Kit — gallery placeholders

This directory will hold 8 SZTOS-verified portraits served as `sztos_01.jpg` ... `sztos_08.jpg`
(file names referenced from `../index.html`).

Until binaries are placed here, the landing page falls back to inline SVG/CSS
placeholders (visible automatically via `<img onerror>` swap to `.ph` div).

**Recommended source binaries** (from `~/AI/ANTIGRAVITY/IMAGES/SZTOSY/` or
`~/AI/ANTIGRAVITY/REFERENCE_PHOTOS/SZTOSY/`):

| target              | source                                                                   |
| :-----------------  | :----------------------------------------------------------------------- |
| `sztos_01.jpg`      | `sztos_v6_1_si10_port_polaroid_softened_2026_06_02.jpg`                  |
| `sztos_02.jpg`      | `sztos_v9_office_317pm_fluorescent_polish_corpo_2026_06_02.jpg`          |
| `sztos_03.jpg`      | `sztos_v9_kitchen_823am_listopad_calendar_2026_06_02.jpg`                |
| `sztos_04.jpg`      | `sztos_v9_polish_canteen_pierogi_ruskie_2026_06_02.jpg` (or `sztos_v10_bar_mleczny_pierogi_2026_06_02.jpg`) |
| `sztos_05.jpg`      | `sztos_v4_server_svema_realism_2026_06_02.jpg`                           |
| `sztos_06.jpg`      | `sztos_v9_concert_basement_color_2026_06_02.jpg`                         |
| `sztos_07.jpg`      | `sztos_v9_street_polish_old_town_evening_2026_06_02.jpg` (or `sztos_v12_stary_rynek_multiref_2026_06_02.jpg`) |
| `sztos_08.jpg`      | `sztos_v3_cathedral_grimoires_analog_2026_06_02.jpg`                     |

To deploy with real images, copy/symlink and rename:

```bash
cd /Users/paulinajanowska/AI/ANTIGRAVITY/WORKSPACE/GOLD/autonomous_revenue/ai-work-voucher-250/docs/sztos-gallery-kit/gallery
SZ=~/AI/ANTIGRAVITY/IMAGES/SZTOSY
RP=~/AI/ANTIGRAVITY/REFERENCE_PHOTOS/SZTOSY
cp "$SZ/sztos_v6_1_si10_port_polaroid_softened_2026_06_02.jpg" sztos_01.jpg
cp "$SZ/sztos_v9_office_317pm_fluorescent_polish_corpo_2026_06_02.jpg" sztos_02.jpg
cp "$SZ/sztos_v9_kitchen_823am_listopad_calendar_2026_06_02.jpg" sztos_03.jpg
cp "$RP/sztos_v10_bar_mleczny_pierogi_2026_06_02.jpg" sztos_04.jpg
cp "$RP/sztos_v4_server_svema_realism_2026_06_02.jpg" sztos_05.jpg
cp "$SZ/sztos_v9_concert_basement_color_2026_06_02.jpg" sztos_06.jpg
cp "$RP/sztos_v12_stary_rynek_multiref_2026_06_02.jpg" sztos_07.jpg
cp "$RP/sztos_v3_cathedral_grimoires_analog_2026_06_02.jpg" sztos_08.jpg
```

**Privacy note from landing page:** the disclaimer block (`.gallery-disclaimer`)
explicitly states placeholders may be intentional — the kit is a premium
"prove-it-before-pay" via private link to avoid public reverse-prompting of
SZTOS scenes by competitors. Decision whether to ship binaries publicly
or keep placeholders + private preview is Paulina's.
