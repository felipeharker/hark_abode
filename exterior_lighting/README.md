# Exterior perimeter lighting

Roof-edge lighting linework, footage, light runs and product list for the contractor, 2026-11-25. All lengths are in feet-inches.

| File | What it is |
| --- | --- |
| `roof_edge_lighting.pdf` | Footage takeoff: page 1 is the plan, page 2 the front elevation |
| `light_runs.pdf` | How the four Enbrighten chains run from the two outlets: page 1 is the front, page 2 the plan |
| `product_sheet.pdf` | What to buy, what it costs, and which box feeds which run |
| `exterior_lighting.3dm` | Rhino 8 model in feet, with the `PLAN::*`, `ELEV::*` and `RUNS::*` layers and five layouts. Local only, not in the GitHub repo |
| `scripts/build_linework.py` | Builds the geometry and lays out the lights. The inputs are at the top of each section. Local only |
| `scripts/layout_export.py` | Builds the layouts and writes the three PDFs. Prices and product links are in its product-sheet section. Local only |

## Footage

| Run | Length |
| --- | --- |
| A: eave left of the gables | 22'-8" |
| B: upper gable, left side | 17'-0" |
| C: upper gable, right side (visible part only) | 4'-8" |
| D: garage gable, left side | 14'-7" |
| E: garage gable, right side | 14'-7" |
| **Front total** | **73'-6"** |
| West side | 69'-0" |
| Rear | 102'-7" |
| East side | 81'-7" |
| **Grand total** | **326'-8"** |

B, D and E were measured on site. A and C are estimated from the photos. The sides and rear assume a 1'-6" overhang past the brick and a 7'-0" garage door; neither was measured, so check both on site.

## Light runs

The lights are Enbrighten VIBE WiFi Eternity Eave Lights with black cord. A strand is 16'-6" long with 12 lights, about 1'-4 1/2" apart. Strands chain end to end from a power supply, and a chain only runs one way from its power supply.

The two outlets are at the front-east and front-west corners, at the eave. Each outlet feeds two power supplies. The two chains at an outlet leave in opposite directions: one along the front, one down the side.

| Run | Outlet | Path | Lit length | Strands | Lights | Trim off the end |
| --- | --- | --- | --- | --- | --- | --- |
| E1 | East | West along the front: A, B, C | 44'-4" | 3 | 32 | 4 lights |
| E2 | East | South down the east side | 81'-7" | 5 | 60 | none |
| W1 | West | East along the front: E, D | 29'-2" | 2 | 21 | 3 lights |
| W2 | West | South down the west side | 69'-0" | 5 | 52 | 8 lights |
| **Total** | | | **224'-1"** | **15** | **165** | |

The rear, 102'-7", is not lit.

How the layout follows the house:

- **Each gable gets its own chain.** The garage gable sits forward of the upper gable and lower, so W1 covers only the garage gable and E1 covers the wing eave and the upper gable.
- **A light sits at each gable peak.** The rest are spaced 1'-4 1/2" from it, so both sides of a gable match.
- **Every chain starts at its outlet.** No cable runs through the attic.
- **W2 is spaced 1'-4".** At 1'-4 1/2" it would need 9 lights cut off, and the limit is 8.

Limits from the manuals (models 82729 and 82730) and the product pages:

- 150'-0" of strands per power supply at full brightness, 200'-0" at reduced brightness. The longest chain here is 82'-6".
- Only the last strand of a chain can be cut: 8 lights off at most, 4 left at least. A cut strand cannot be reconnected. Seal the cut end with the silicone cap.
- The power supply, lights and cords are not for soffits, attics or other enclosed spaces. Mount the power supplies on the wall by the outlet.
- The outlets need GFCI protection.
- The 10'-0" extension cable goes between two strands. The cable's product page says it cannot connect to the power supply's lead cord; the kit manual says it can. This layout does not need a cable, so it does not depend on either.

## Products

Prices are from enbrightenme.com on 2026-11-25, before tax and shipping.

| Item | Model | Qty | Each | Total |
| --- | --- | --- | --- | --- |
| [Eternity Eave Lights, 36 Lights, 50ft. Black Cord](https://enbrightenme.com/products/enbrighten-wifi-vibe-color-changing-permanent-outdoor-eternity-eave-lights-36-lights-50ft-black-cord) | 82729 | 3 | $159.99 | $479.97 |
| [Eternity Eave Lights, 72 Lights, 100ft. Black Cord](https://enbrightenme.com/products/enbrighten-wifi-vibe-color-changing-permanent-outdoor-eternity-eave-lights-72-lights-100ft-black-cord) | 82730 | 1 | $249.99 | $249.99 |
| **Total** | | | | **$729.96** |
| With code BLACKFRIDAY, 20% off, shown on the product pages that day | | | | $583.97 |

Each 50ft. kit holds 3 strands, a power supply and one 10'-0" extension cable. The 100ft. kit holds 6 strands, a power supply and one cable. Together that is 15 strands and 4 power supplies, which is exactly what the four runs use.

Not needed for this layout:

| Item | Model | Each | Why |
| --- | --- | --- | --- |
| [Extension Light Strand, 16.5ft. Black](https://enbrightenme.com/products/enbrighten-wifi-vibe-eternity-eave-lights-extension-light-strand-16-5ft-black) | 82732 | $52.99 | The kits hold exactly 15 strands |
| [Extension Cable, 10ft. Black](https://enbrightenme.com/products/enbrighten-wifi-vibe-eternity-eave-lights-extension-cable-10ft-black) | 82734 | $14.99 | 4 come in the kits, and no chain has a gap to bridge |

Which box feeds which run:

| Run | Box |
| --- | --- |
| E1 | 50ft. kit no. 1: its power supply and all 3 strands |
| W1 | 50ft. kit no. 2: its power supply and 2 strands. The third strand goes to W2 |
| W2 | 50ft. kit no. 3: its power supply and 3 strands, plus 1 strand from kit no. 2 and 1 from the 100ft. kit |
| E2 | 100ft. kit: its power supply and 5 strands. The sixth strand goes to W2 |

Lighting the rear as well means carrying E2 and W2 around the back corners until they meet: 16 strands for the sides and rear instead of 10, at 132'-0" per chain. The cheapest order for that is one 50ft. kit and three 100ft. kits, $909.96.

## What was checked across the four products

| | 50ft. kit | 100ft. kit | Extension strand | Extension cable |
| --- | --- | --- | --- | --- |
| Model | 82729 | 82730 | 82732 | 82734 |
| Product line | VIBE WiFi Eternity Eave Lights | same | same | same |
| Cord color | Black | Black | Black | Black |
| Lights | 36 on 3 strands | 72 on 6 strands | 12 on 1 strand | none |
| Lights per 16'-6" strand | 12 | 12 | 12 | |
| Light type | RGBWIC | RGBWIC | RGBWIC | |
| Rated output | 26.5 W at 30 V DC | 52.5 W at 30 V DC | not stated | |
| Watts per light | 0.74 | 0.73 | not stated | |
| In stock on 2026-11-25 | Yes | Yes | Yes | Yes |

- The extension strand's page says it "connects directly to Enbrighten VIBE 50ft. and 100ft. Eternity Light sets".
- The extension cable's page lists the sets it fits by model: 81102, 81103, 82729, 82730, 85103 and 85102.
- Both kits' power supplies carry the same top rating: 78.8 W, for up to 200'-0" of strands.

Not published, so not confirmed:

- Lumens per light, for any of the four. The match in brightness rests on the same light type and the same watts per light.
- The cord length between two lights. 1'-4 1/2" is 16'-6" divided by 12 lights. Measure one strand before laying out.
- That the wing eave meets the upper gable closely enough for E1 to step from A to B on one 1'-4 1/2" length of cord. Check this on site.
