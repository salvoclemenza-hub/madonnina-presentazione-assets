# madonnina-presentazione-assets

Asset (immagini, screenshot, diagrammi) per la presentazione meeting strategico Madonnina del 28 aprile 2026.

Hostato come repo GitHub pubblico per servire URL `raw.githubusercontent.com` a Gamma API durante la generazione della presentazione.

## Struttura

- `screenshots/` — screenshot reali della webapp Madonnina (catturati con Playwright via mobile viewport 390×844)
- `stock/` — foto stock free-commercial scaricate da Pexels (licenza Pexels free, uso commerciale OK)
- `composites/` — immagini composite costruite con PIL/Pillow (split, side-by-side)
- `diagrams/` — diagrammi tecnici generati con matplotlib, palette coerente con design system app (forest green #1B4332)

## Licenza asset

- Screenshot: proprietari, In Campagna Srl
- Foto stock: Pexels License (free-commercial)
- Diagrammi: proprietari, generati ad hoc

## Riprodurre

Tutti gli asset sono generati dagli script in `madonnina-app/tools/guide/`. Vedi quel repo per la pipeline completa.
