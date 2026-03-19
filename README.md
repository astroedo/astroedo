# Edoardo Pessina

**Geoinformatics Engineer | Applied Deep Learning to Earth Observation and Climate Systems**

I bridge Environmental Engineering and Computer Science to build scalable Machine Learning models for Earth Observation. Currently pursuing an M.Sc. in Geoinformatics Engineering at Politecnico di Milano.

### Tech Stack
* **Languages:** Python, C, SQL, Matlab, R
* **ML/AI:** PyTorch, TensorFlow, Scikit-learn, TIMM
* **Earth Observation:** Google Earth Engine (GEE), GDAL, Rasterio, SNAP

---

## Key Projects

### Glacier Melting temporal classification 
* Technologies: CNN, Random Forest, MLP, GEE, Google Colab
* Details: Developed and applied three ML models on 40 years of Landsat data (1,178 samples) for temporal glacier classification.
* Results: Achieved 99.1% accuracy classifying imbalanced geospatial data, comparing 1D-CNN, MLP, and Random Forest architectures.
* Link: https://github.com/astroedo/Rutor-Glacier-Melting.git

### TerraMind Land Cover Scene Classification - Romania
* Technologies: Prithvi & TerraMind GFMs, TerraTorch, PyTorch Lightning, Google Colab
* Details: Fine-tuned Prithvi EO v2 and TerraMind v1 foundation models on Romania LUCAS ground truth data (100+ samples, 7-band HLS imagery) for 10-class land cover scene classification.
* Results: Successfully implemented and compared two state-of-the-art geospatial foundation models, demonstrating practical transfer learning for downstream classification tasks with limited training samples.
* Link: https://github.com/astroedo/TerraMind-Prithvi-LC-Comparison
  
### German air quality monitoring 
* Technologies: Python, QGIS, WebGIS
* Details: Processed 10+ years of pollution data, correlating $\text{NO}_2/\text{PM}2.5/\text{PM}10$ with land cover/population
* Results: Delivered an interactive WebGIS with bivariate mapping and zonal statistics for policy insights
* Link: https://astroedo.github.io/polimi-GIS2025/

### Transformer ntm Eng to ITA
* A complete PyTorch implementation of the Encoder-Decoder architecture (Vaswani et al.) without high-level libraries, featuring Multi-Head Attention, Sinusoidal Positional Encoding, and Pre-Layer Normalization.
* Replicated the original paper's optimization strategy using Mixed-Precision (FP16), Label Smoothing (ϵ=0.1), and a Learning Rate scheduler with Warmup and Inverse Square Root Decay.
* Integrated Beam Search decoding with length normalization and conducted rigorous quantitative evaluation using Corpus BLEU scores and Cross-Attention map visualizations.
