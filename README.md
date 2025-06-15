# mango-project
Mango Project: Thermal Image Analysis, Segmentation, and Damage Classification This project processes thermal and RGB images of mangoes for segmentation, damage classification, clustering, and feature analysis using classical computer vision and deep learning techniques.
🚀 Key Components
🔍 1. Mango Segmentation
Uses color thresholding (HSV masking) and Mask R-CNN or YOLOv8 segmentation.

Saves isolated mango images with transparent backgrounds or masks.

🔧 2. Deep Learning Models
Mask R-CNN (via TensorFlow Model Zoo) and YOLOv8 for semantic segmentation.

Uses Roboflow API to fetch custom datasets for mango detection.

📊 3. Feature Extraction & Clustering
Extracts RGB, HSV, LBP texture, edge strength, and temperature gradient features.

Performs KMeans clustering and visualizes clusters with PCA and t-SNE.

Saves cluster-labeled results and visual summaries.

📈 4. Damage Classification
Categorizes mango condition using HSV color range thresholds.

Supports No Damage, Minor, Moderate, and Severe Damage.

📦 5. Validation & Visualization
Validates segmentation masks by comparing against thermal-RGB pairs.

Saves feature CSVs and summary plots.

Uses seaborn/matplotlib for bar plots, box plots, and scatter charts.
