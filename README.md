# GlaucoXAI: Enhancing Glaucoma Diagnosis with Explainable AI Using Vision Transformers and Deep Learning Techniques

Glaucoma is a leading cause of irreversible blindness worldwide. This project introduces an explainable deep learning framework for early and accurate glaucoma diagnosis using retinal fundus images. The system leverages Vision Transformers (ViT) along with other CNN-based architectures, integrated with Grad-CAM for interpretability.

## 📌 Objective

To create a trustworthy AI system for glaucoma classification that supports clinical decision-making through accurate predictions and transparent explanations.

## 🧠 Key Features

- Advanced deep learning models: CNN, VGG16/19, Xception, InceptionResNetV2, Vision Transformers
- Preprocessing: Green channel extraction, CLAHE, Gaussian blur, Canny & Sobel filters
- Data augmentation for robust generalization
- Explainability using Grad-CAM to highlight model focus areas
- ViT achieved **92% accuracy** on the test set

## 📁 Dataset

- Source: [Kaggle - Fundus Glaucoma Detection Data](https://www.kaggle.com/datasets/sabari50312/fundus-pytorch)
- Total Images: 17,242
  - Training: 8,621
  - Validation: 5,747
  - Testing: 2,874
- Labels:
  - `0`: Normal
  - `1`: Glaucoma

## 🧪 Preprocessing Techniques

- Green channel extraction
- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Gaussian Blur
- Canny & Sobel edge detection
- Data augmentation: rotation, scaling, flipping, noise, contrast changes

## 🏗️ Models Implemented

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| CNN              | 76%      | 79%       | 76%    | 73%      |
| VGG16            | 85%      | 86%       | 85%    | 85%      |
| VGG19            | 86%      | 86%       | 86%    | 86%      |
| InceptionResNetV2| 82%      | 81%       | 82%    | 81%      |
| Xception         | 87%      | 87%       | 87%    | 87%      |
| **ViT (Best)**   | **92%**  | **91%**   | **91%**| **91%**  |

## 🔍 Explainable AI (Grad-CAM)

Grad-CAM is used to visualize the regions in the retinal image that influenced the model's predictions. This enhances interpretability and helps clinicians validate the AI’s focus during classification.


## 📂 Example Project Structure

## 📚 Citation
```
@conference{beciticon2024,
  author={Natra Tza and Mill Haniar Hoer and Suda Nwoar and Mohunod Arnur and Rhiperra Chowar and Alh'ukido},
  title={Enhancing Glaucoma Diagnosis with Explainable AI Using Vision Transformers and Advanced Deep Learning Techniques},
  booktitle={2024 IEEE International Conference on Biomedical Engineering, Computer and Information Technology for Health (BECITICON)},
  year={2024},
  address={Dhaka, Bangladesh},
  organization={IEEE}
}
```

## 🧑‍⚕️ Authors

- Naima Tasnia  
- Md. Hamid Hosen  
- Sadia Nawar  
- Mohammed Amran  
- Rituparna Chowdhury  
- Altaf Uddin

## 📬 Contact

For any queries, reach out to [mdhamidhosen4@gmail.com](mailto:mdhamidhosen4@gmail.com)

---

**License:** CC BY 4.0  