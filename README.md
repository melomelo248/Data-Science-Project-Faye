# Data-Science-Project-Faye
This is a repo for my Msc Data Science project.

It consists of the following folders:

### 1. `Image-pre/`
Preprocessing pipeline for raw image data.
- **image_prepare.ipynb**: Scripts for loading, cleaning, and normalizing images before feeding them into models (resizing, normalization, augmentation, etc.).

---

### 2. `MobileNetv2/`
Contains experiments using the **MobileNetV2** CNN model.
- **MobileNetv2.ipynb**: Scripts for training, feature extraction and downstream analysis with MobileNetV2.

---

### 3. `DINOv3/`
Contains scripts and notebooks for feature extraction and analysis using the **DINOv3** self-supervised vision transformer model.
- **DINOv3.ipynb**: Implements feature extraction and downstream experiments with DINOv3.

---


### 4. `Tabular Data/`
Experiments focusing on extracted features converted into tabular format.
- **EDA-Extract_Feature.ipynb**: Exploratory data analysis (EDA) for the tabular dataset.  
- **feature_joint.ipynb**: Merge by FoV and calculate statistical values, such as mean, standard deviation, etc. 
- **feature_train.ipynb**: Train an XGBoost classifier and perform downstream similarity and SHAP analysis.

---

##  Other Files
- **.DS_Store**: Auto-generated system file (can be ignored or removed from version control).

---

##  Usage
1. Start with **Image-pre** to prepare your dataset.  
2. Run either **DINOv3** or **MobileNetv2** notebooks to deal with image data.  
3. Use **Tabular Data** notebooks for extracted features analysis, model training, and evaluation.  

---

##  Requirements
- Python
- Jupyter Notebook  
- TensorFlow, PyTorch  
- scikit-learn, pandas, numpy, matplotlib  

---  
