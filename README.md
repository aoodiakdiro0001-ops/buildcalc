# 🏗️ BuildCalc — Renovation & Construction Estimator (MIT)

Interactive cost estimator: area + finish + rooms → material quantities,
labor and total budget. UI in EN/TR/AR. Static single file + README.

## Model (rule-of-thumb, waste included)

Inputs: project (renovation/new build), area m², finish
(Economy/Standard/Deluxe/Super-deluxe), rooms, bathrooms, city factor,
currency (TRY/USD/EUR at real 2026 rates).

- **Quantities:** cement bags, sand/gravel m³, concrete + rebar + bricks
  (new build), tiles + laminate with waste %, paint liters (walls+ceiling,
  2 coats), doors/windows counts, kitchen meters, bathroom sets,
  electrical/plumbing points.
- **Costs:** 2026-indicative TRY unit prices, labor 35%, contingency 10%,
  city multiplier, timeline estimate. Save/print/export history.

## Money & contact

- `CONFIG.ads` footer slot (contractor/decor = high CPC).
- `CONFIG.aff` affiliate slots (Koçtaş/Bauhaus/IKEA/Trendyol/Hepsiburada)
  with REF badges — paste real URLs.
- Donate: BTC + USDT-TRC20 + IBANs.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd buildcalc
python3 -m http.server 8080
```

## License

MIT. Estimates only — always get 3 contractor quotes.
