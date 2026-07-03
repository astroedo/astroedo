# Edoardo Pessina

**Geoinformatics Engineer | Applied Deep Learning to Earth Observation and Climate Systems**

I bridge Environmental Engineering and Computer Science to build scalable Machine Learning models for Earth Observation. Currently pursuing an M.Sc. in Geoinformatics Engineering at Politecnico di Milano.

### Tech Stack
* **Languages:** Python, C, SQL, Matlab, R
* **ML/AI:** PyTorch, TensorFlow, Scikit-learn, TIMM
* **Earth Observation:** Google Earth Engine (GEE), GDAL, Rasterio, SNAP

---

## Key Projects

### Transformer NMT: English to Italian Translation
* A complete PyTorch implementation of the Encoder-Decoder architecture (Vaswani et al.) without high-level libraries, featuring Multi-Head Attention, Sinusoidal Positional Encoding, and Pre-Layer Normalization.
* Replicated the original paper's optimization strategy using Mixed-Precision (FP16), Label Smoothing (ϵ=0.1), and a Learning Rate scheduler with Warmup and Inverse Square Root Decay.
* Integrated Beam Search decoding with length normalization and conducted rigorous quantitative evaluation using Corpus BLEU scores and Cross-Attention map visualizations.
* Link: https://github.com/astroedo/Transformer-nmt-en-it

### ESA Phi-Lab GeoFM Challenge — Embed2Heights
* Technologies: PyTorch, Geospatial Foundation Models (TerraMind, AlphaEarth, Tessera, THOR), Mixed-Precision Training (AMP), Google Colab
* Details: Designed a multi-modal fusion network (SE-UNet, ASPP, cross-attention, dual bin-classification height heads) combining embeddings from 4 GFMs for joint land cover segmentation and nDSM height regression on 256×256 satellite patches.
* Results: Scored 0.4130 on the challenge leaderboard; diagnosed and fixed a silent FP16 overflow that blocked training, and built a crash-safe pipeline (RAM/SSD caching, auto-resume, TTA, multi-seed ensembling) for preemptible GPUs.
* Link: https://github.com/astroedo/ESA-GeoFM-Challenge

### Glacier Melting temporal classification 
* Technologies: CNN, Random Forest, MLP, GEE, Google Colab
* Details: Developed and applied three ML models on 40 years of Landsat data (1,178 samples) for temporal glacier classification.
* Results: Achieved 99.1% accuracy classifying imbalanced geospatial data, comparing 1D-CNN, MLP, and Random Forest architectures.
* Link: https://github.com/astroedo/Rutor-Glacier-Melting.git
  
### German air quality monitoring 
* Technologies: Python, QGIS, WebGIS
* Details: Processed 10+ years of pollution data, correlating $\text{NO}_2/\text{PM}2.5/\text{PM}10$ with land cover/population
* Results: Delivered an interactive WebGIS with bivariate mapping and zonal statistics for policy insights
* Link: https://astroedo.github.io/polimi-GIS2025/


