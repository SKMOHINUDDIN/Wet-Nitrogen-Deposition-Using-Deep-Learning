# Wet-Nitrogen-Deposition-Using-Deep-Learning
A reproducible Python pipeline to estimate wet nitrogen deposition using a single deep-learning model. The code ingests gridded emissions and meteorological drivers, aligns them with observation networks, trains a neural network, and produces annual global maps (e.g., 1990–2019) with evaluation against independent stations.

Highlights

1. Single-model DL (e.g., Keras/TensorFlow MLP with ReLU dense layers)

2. Global 0.1° raster outputs with proper georeferencing (GeoTIFF)

3. Robust data prep: masking, reprojection, and year-wise stacking

4. Region-wise evaluation (USA/EU/China, etc.) with metrics (R², RMSE, NSE, Pbias)

5. Simple, config-driven runs (one command to train & predict)

   
Contact Sekh Mohinuddin for any query: sekh0001@as.edu.tw, d12249003@ntu.edu.tw
