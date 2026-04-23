## Vadim Vlasov — ML Engineer

ML Engineer specializing in **geospatial computer vision** for satellite imagery.
End-to-end pipelines: raw Sentinel-2/HLS → field boundary segmentation → crop classification → GeoPackage.

---

### Key results

| What | Numbers |
|---|---|
| Field segmentation model (ResUNet-A) | MCC = 0.91, 5+ countries |
| Production pipeline (Airflow + AWS) | 35,000+ EOPatches, ~12M km² |
| Transfer learning: global → local | Brazil MCC 0.77 → 0.89, Argentina MCC 0.87 |
| Postprocessing optimization | 33h → 20h (memray, malloc_trim, multiprocessing) |
| Crop classification (Transformer Encoder) | safra/safrinha, validated vs CONAB/SIDRA |

---

### Stack

`Python` `PyTorch` `TensorFlow` `Apache Airflow` `AWS (EC2 · S3 · Batch)`
`GDAL` `Rasterio` `GeoPandas` `eo-learn` `STAC` `Docker` `Sentinel-2`

---

### Featured project

**[satellite-field-segmentation](https://github.com/vadimvvlasov/satellite-field-segmentation)**
— Field boundary detection from satellite imagery: ResUNet-A, geospatial postprocessing, GeoPackage output.

---

📍 Open to remote worldwide &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/vadim-vlasov-181503b6/) &nbsp;·&nbsp; 🌐 [CV](https://vadimvvlasov.github.io/cv/)
