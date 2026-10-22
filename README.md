# victron-mppt-fan-mount

3D-gedruckte Lüfter-Abstandshalter für Victron SmartSolar MPPT und Orion-Tr.
Remix des [Victron MPPT Koeler M](https://www.etsy.com/de/listing/4346932600/victron-mppt-koeler-m) (PetersIndustries) – **nur private Nutzung, nicht weitergeben/verkaufen.**

## Größen

| Größe | Lüfter | Platte (mm) | Höhe | Lochabstand Regler (X × Y) | Victron-Soll | Datei |
|---|---|---|---|---|---|---|
| M  | Arctic P12 Pro (120) | 190 × 140 | 51 | 176,0 × 71,5 | 176 × 71,5 | `stl/MPPT150_120fan - Size M.stl` |
| L  | Arctic P12 Pro (120) | 248,5 × 170,7 | 50 | 226,5 × 100,7 | 250/60–70: 226,5 × 100,7 · 150/60–70 Tr: 228 × 101 | `stl/MPPT150_120fan - Size L.stl` |
| XL | Arctic P14 Pro (140) | 295 × 204 | 50 | 268,6 × 144,1 | 268 × 144 | `stl/MPPT250_140fan - Size XL.stl` |

Kompatible Modelle: siehe [`MPPT_Size.txt`](MPPT_Size.txt).

Lüfter-Lochabstand: M/L 105,0 mm · XL 125,0 mm (Standard 140er: 124,5).

## Bekannte Punkte

- **Mutterfallen** sind größer als die Victron-Schrauben (Victron: M/L → M5, XL → M6; Falle: M ≈ SW 10, L/XL ≈ SW 13,5). Unterlegscheibe oder Tasche anpassen.
- **L bei 150/60–70:** −1,5 / −0,3 mm zum Victron-Maß, durch Ø8,8-Durchgang mit M5 abgedeckt.
- **L-Lüftertasche** 25 mm tief (M/XL 27 mm).
- Nicht gegen Victron-Zeichnung geprüft: 100/30, Orion-Tr (M), 150/60–70 MC4 (L).

## Fusion 360

- `fusion/MPPT150_120fan - Size M.f3d` – M
- `fusion/MPPT150.f3d` – vermutlich L
- `fusion/MPPT250.f3d` – vermutlich XL

## Quellen (Victron-Maßzeichnungen)

- [100/50 · 150/35 · 150/45](https://www.victronenergy.com/upload/documents/BS-SS-MPPT-100-50-150-35-150-45.pdf)
- [150/60 & 150/70 Tr](https://www.victronenergy.com/upload/documents/DimensionDrawing-SmartSolar-150_60A-&-150_70-Tr.pdf)
- [250/60–70 Tr](https://www.victronenergy.com/upload/documents/SmartSolar-MPPT-250V-60-70-Tr.pdf) · [250/60–70 MC4](https://www.victronenergy.com/upload/documents/SS-MPPT-250-60-70-MC4.pdf)
- [150/250-85/100 Tr](https://www.victronenergy.com.au/upload/documents/SmartSolar-MPPT-150-250-85-100-Tr-(dimensions).pdf)
