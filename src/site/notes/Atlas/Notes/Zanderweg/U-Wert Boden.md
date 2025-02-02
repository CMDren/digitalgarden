---
{"dg-publish":true,"permalink":"/atlas/notes/zanderweg/u-wert-boden/","tags":["gardenEntry"]}
---


# U-Wert Berechnung für Bodenaufbau

## Bodenaufbau:
- **Betonplatte:** 15 cm
- **EPS (1980):** 3 cm
- **Estrich (Athernit o. Ä.):** 3 cm
- **Vergussmasse:** 5 mm

## Materialeigenschaften (Wärmeleitfähigkeit λ in W/mK):
- **Beton:** 2.0 W/mK
- **EPS (1980):** 0.045 W/mK
- **Estrich:** 1.4 W/mK
- **Vergussmasse:** 1.0 W/mK

## Wärmeübergangswiderstände:
- **Innen (R_si):** 0.17 m²K/W
- **Außen (R_se):** 0.04 m²K/W

## Wärmewiderstände der Schichten (R = d / λ):
| Material         | Dicke (m) | λ (W/mK) | R (m²K/W) |
|-----------------|-----------|----------|-----------|
| **Beton**       | 0.15      | 2.0      | 0.075     |
| **EPS (1980)**  | 0.03      | 0.045    | 0.667     |
| **Estrich**     | 0.03      | 1.4      | 0.021     |
| **Vergussmasse**| 0.005     | 1.0      | 0.005     |
| **Summe R**     |           |          | **0.938** |

## Gesamter Wärmewiderstand:
$$
R_{\text{gesamt}} = R_{\text{innen}} + \sum R_i + R_{\text{außen}}
$$

$$
R_{\text{gesamt}} = 0.17 + 0.938 + 0.04 = 1.148 \, \text{m²K/W}
$$

## U-Wert Berechnung:
$$
U = \frac{1}{R_{\text{gesamt}}} = \frac{1}{1.148} = 1.02 \, \text{W/(m²K)}
$$
