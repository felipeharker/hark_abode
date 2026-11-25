# Exterior perimeter lighting

Roof-edge footage, light runs and shopping list for the contractor, 2026-11-25. All lengths are in feet-inches.

| File | What it is |
| --- | --- |
| `exterior_lighting.pdf` | The whole document, five landscape pages: footage plan, footage front, light runs front, light runs plan, shopping list |
| `exterior_lighting.3dm` | Rhino 8 model in feet. Local only, not in the GitHub repo |
| `scripts/build_linework.py` | Builds the geometry and lays out the lights. Local only |
| `scripts/layout_export.py` | Lays out the five sheets and writes the PDF. Prices and product links are in its shopping-list section. Local only |

Every sheet has the same layout: title top left, page number top right, drawing on the left, table on the right. Sheets carry lengths and counts only, with no scale and no notes. The notes are below.

## Footage

| Edge | Length |
| --- | --- |
| A: eave left of the gables | 22'-8" |
| B: upper gable, left side | 17'-0" |
| C: upper gable, right side (visible part only) | 4'-8" |
| D: garage gable, left side | 14'-7" |
| E: garage gable, right side | 14'-7" |
| **Front** | **73'-6"** |
| West side | 69'-0" |
| Rear | 102'-7" |
| East side | 81'-7" |
| **Whole house** | **326'-8"** |

B, D and E were measured on site. A and C are estimated from the photos. The sides and rear assume a 1'-6" overhang past the brick and a 7'-0" garage door; neither was measured.

## Light runs

Enbrighten VIBE WiFi Eternity Eave Lights, black cord. A strand is 16'-6" long with 12 lights, about 1'-4 1/2" apart. The two outlets are at the front corners, at the eave. Each outlet feeds two power supplies, and its two chains leave in opposite directions.

| Run | Outlet | Path | Lit | Strands | Lights | Excess |
| --- | --- | --- | --- | --- | --- | --- |
| E1 | East | Front: A, B, C | 44'-4" | 3 | 32 | 5'-2" |
| E2 | East | East side | 81'-7" | 5 | 60 | 0'-11" |
| W1 | West | Front: E, D | 29'-2" | 2 | 21 | 3'-10" |
| W2 | West | West side | 69'-0" | 5 | 52 | 13'-6" |
| **Total** | | | **224'-1"** | **15** | **165** | **23'-5"** |

Excess is the strand length supplied minus the lit length. It comes off the end of the chain: 4 lights on E1, 3 on W1, 8 on W2. The rear is not lit.

- Each gable has its own chain, with a light at the peak and the rest spaced 1'-4 1/2" from it.
- W2 is spaced 1'-4", which keeps its cut at the 8-light limit.

Limits from the manuals (models 82729 and 82730):

- 150'-0" of strands per power supply at full brightness. The longest chain here is 82'-6".
- Only the last strand of a chain can be cut: 8 lights off at most, 4 left at least.
- The power supply, lights and cords are not for soffits, attics or other enclosed spaces.
- The outlets need GFCI protection.

## Shopping list

Prices are from enbrightenme.com on 2026-11-25, before tax and shipping.

| Item | Model | Qty | Strands | Power supplies | Each | Total |
| --- | --- | --- | --- | --- | --- | --- |
| [Eternity Eave Lights, 36 Lights, 50ft. Black Cord](https://enbrightenme.com/products/enbrighten-wifi-vibe-color-changing-permanent-outdoor-eternity-eave-lights-36-lights-50ft-black-cord) | 82729 | 3 | 9 | 3 | $159.99 | $479.97 |
| [Eternity Eave Lights, 72 Lights, 100ft. Black Cord](https://enbrightenme.com/products/enbrighten-wifi-vibe-color-changing-permanent-outdoor-eternity-eave-lights-72-lights-100ft-black-cord) | 82730 | 1 | 6 | 1 | $249.99 | $249.99 |
| **Total** | | **4** | **15** | **4** | | **$729.96** |
| With code BLACKFRIDAY, 20% off | | | | | | $583.97 |

Not needed: the [extension strand](https://enbrightenme.com/products/enbrighten-wifi-vibe-eternity-eave-lights-extension-light-strand-16-5ft-black) (82732, $52.99) and the [extension cable](https://enbrightenme.com/products/enbrighten-wifi-vibe-eternity-eave-lights-extension-cable-10ft-black) (82734, $14.99). The kits hold exactly 15 strands, and each kit includes one cable.

## Product check

All four items are the same line with black cord, 12 RGBWIC lights per 16'-6" strand, and about 0.73 W per light in both kits. The strand's page says it connects directly to the 50ft. and 100ft. sets, and the cable's page lists models 82729 and 82730.

Not published, so not confirmed:

- Lumens per light.
- The cord length between two lights. 1'-4 1/2" is 16'-6" divided by 12 lights.
- That the wing eave meets the upper gable closely enough for E1 to step from A to B on one length of cord.
