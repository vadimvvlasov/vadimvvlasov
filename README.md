# ML Engineer | Computer Vision & Geospatial ML

Production ML pipelines for satellite imagery: from raw Sentinel-2/HLS to field boundary segmentation, crop classification, and cadastral integration.

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

## Tech Stack

**ML/CV:** Python, TensorFlow, PyTorch, ResUNet-A, Transformer Encoder, ESRGAN, Computer Vision, Semantic Segmentation

**Geospatial:** eo-learn, eo-flow, GDAL, Rasterio, GeoPandas, Sentinel-2, HLS (NASA), STAC, MapBiomas, GeoPackage

**Infra:** Apache Airflow, AWS (EC2, S3), Docker, GitLab CI/CD, memray

---

### Featured project

**[satellite-field-segmentation](https://github.com/vadimvvlasov/satellite-field-segmentation)**
— Field boundary detection from satellite imagery: ResUNet-A, geospatial postprocessing, GeoPackage output.

---

## Contact

- LinkedIn: linkedin.com/in/vadim-vlasov-181503b6
- CV: vadimvvlasov.github.io/cv/

---

📍 Open to remote worldwide &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/vadim-vlasov-181503b6/) &nbsp;·&nbsp; 🌐 [CV](https://vadimvvlasov.github.io/cv/)
