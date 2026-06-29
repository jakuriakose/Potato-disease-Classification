# 🌿 Potato Leaf Disease Classification Using Deep Learning

## 📌 About
A deep learning model that classifies potato leaf diseases 
into 3 categories using Convolutional Neural Networks (CNN), 
helping identify plant diseases early and accurately.

### Classes:
- Potato Early Blight
- Potato Late Blight
- Potato Healthy

## 🛠️ Tools & Technologies
- Python
- TensorFlow
- Keras
- CNN (Convolutional Neural Network)
- Matplotlib

## 🔄 Process
1. Loaded 2152 images from PlantVillage dataset
2. Split data: 80% training, 10% validation, 10% testing
3. Applied data augmentation (random flip & rotation)
4. Built CNN model with 6 Conv2D layers
5. Trained for 50 epochs with Adam optimizer
6. Evaluated on test data

## 📊 Results
| Dataset | Accuracy |
|---------|----------|
| Training | 99.6% |
| Validation | 94.3% |
| Test | 94.4% |

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Add PlantVillage dataset to the project folder
4. Run the notebook:
   potato_disease_classification.ipynb
