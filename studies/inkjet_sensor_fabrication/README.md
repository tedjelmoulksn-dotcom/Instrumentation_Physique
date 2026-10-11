# Inkjet Sensor Fabrication — Dimatix

[Original laboratory report](docs/dimatix_inkjet_report.pdf) · 21 PDF pages · French · group work by Asmae Mernissi, Chaima Jouini, Tedj El Moulk Sinacer and Sadio Ba.

## Experimental workflow

The study introduces the Dimatix DMP-2800-series materials printer and Dimatix Drop Manager. It follows cartridge preparation and filling, machine startup, cartridge installation, printing-parameter entry, drop ejection observation and pattern selection before printing on paper.

The report illustrates the equipment and software steps with photographs and screenshots. It describes three parallel vector lines, each 20 mm long and 1 mm wide, with 1 mm spacing. `Preview Drops` displays how the vector pattern is discretised into deposited droplets.

## Drop-spacing comparison

| Drop spacing | Resolution listed in the report | Observed pattern behaviour |
| --- | --- | --- |
| 20 µm | 1270 dpi | Dense overlap and continuous filling; possible excess ink |
| 50 µm | 508 dpi | Distinct, regularly distributed drops and intermediate filling |
| 90 µm | Approximately 282 dpi | Reduced overlap and less continuous lines |

The nominal resolution follows `dpi = 25400 / spacing_in_micrometres`. The report also records head-angle adjustment as part of the operating procedure. Pattern continuity depends on overlap and ink/substrate wetting as well as spacing; these observations describe this laboratory session rather than a universal optimum.

## Engineering relevance

The experiment connects process preparation and deposition geometry to the continuity of printed structures intended for sensor fabrication. It documents the printing workflow and visual pattern quality; electrical sensor performance is a separate characterization step. Ink-property answers in the original report are coursework notes, not a substitute for the cartridge manufacturer's operating specifications.
