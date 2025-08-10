# 🧬 Classification-of-Microscopic-Blood-Cell-Images
🔗 🌐 **Open Project in Your Browser**:  https://arrao10.github.io/Classification-of-Microscopic-Blood-Cell-Images/

### 📖 **Introduction**: 
Accurate classification of cells in peripheral blood smears is critical for diagnosing hematological diseases. This project develops and evaluates deep learning models—centered on modern **Convolutional Neural Networks (CNNs)** to classify microscopic blood cells by morphology into **8** categories: **Neutrophils**, **Eosinophils**, **Basophils**, **Lymphocytes**, **Monocytes**, **Immature Granulocytes**, **Erythroblasts** and **Platelets**. The objectives is a benchmark for model performance and is effective, reproducible practices for data preparation, architecture selection, training and evaluation. By leveraging high-quality image data and automated inference, the system aims to improve accuracy and efficiency, streamline routine review and support timely, precise clinical decision-making.

### 📂 **Dataset Details**: 
* **Name**: PBC_dataset_normal_DIB.zip <br>
* **Link**: https://data.mendeley.com/datasets/snkd93bnjr/1
* **Number of Classes of Blood cells**: **8** classes <br>
    - **Basophil**: **1218** images
    - **Eosinophil**: **3117** images
    - **Erythroblast**: **1551** images
    - **Ig**: **2895** images
    - **Lymphocyte**: **1214** images
    - **Monocyte**: **1420** images
    - **Neutrophil**: **3329** images
    - **Platelet**: **2348** images
* **Class Imbalance**: **Yes**
* **Format**: All images are in **.jpg** format to maintain uniformity.
* **Resolution**: All images are uniform **360 × 361 pixels**.

### ⚖️ **Class Imbalance Addressed with Weight Random Sampling**:
Weighted random sampling ensures that samples from underrepresented classes are more likely to be chosen during training by assigning higher sampling weights to these classes.

**Uses of Weight Random Sampling**: 
  - Balances class distribution in the training process when dealing with imbalanced datasets.
  - Prevents the model from being biased toward overrepresented classes.
  - Ensures each class contributes equally during training, improving model performance across all classes.
  - Weighted random sampling is applied only on Training dataset because the test dataset should reflect the real-world class distribution for an unbiased evaluation.
