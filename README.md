# TSA Week 2 — Phnom Penh monthly precipitation

- Source supplied by instructor: `POWER_Point_Monthly_20150101_20251231_011d56N_104d93E_LST.csv`.
- Table: 2015–2025, 11 rows × 12 monthly observations = 132 months; `ANN` is an annual total, not another month.
- Named location: Phnom Penh, approximately 11.56° N, 104.93° E from supplied filename (precise NASA metadata absent).
- Presumed NASA POWER parameter: `PRECTOTCORR_SUM` (corrected precipitation sum) based on the user-provided API request; cannot be independently determined from the table alone.
- **Units not present in the provided CSV**; confirm from original full NASA header/parameter dictionary before describing figures as millimeters. No conversion applied to observed values.
- Dataset is a gridded model/reanalysis product, not an on-site gauge observation.
- Source API documentation: https://power.larc.nasa.gov/docs/services/api/temporal/monthly/
- Source parameter dictionary: https://power.larc.nasa.gov/docs/tutorials/parameters/
- Textbook activity basis: Hyndman & Athanasopoulos, Forecasting: Principles and Practice, Chapter 2, Sections 2.1–2.5.
- The original CSV was copied unchanged. The Colab notebook embeds that exact source table so students can use Run all without uploading a file.
