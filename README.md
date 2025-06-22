 E-Waste Generation Classification
This project focuses on classifying types of e-waste using image classification with deep learning. The model leverages EfficientNetV2B0 for transfer learning and is trained on a custom dataset divided into train, val, and test sets.

📁 Project Structure
css
Copy
Edit
AICTE-Internship-main/
├── P3 - E-Waste Generation Classification/
│   ├── modified-dataset/
│   │   ├── train/
│   │   │   ├── battery/
│   │   │   ├── cable/
│   │   │   └── mobile/
│   │   ├── val/
│   │   │   ├── battery/
│   │   │   ├── cable/
│   │   │   └── mobile/
│   │   └── test/
│   │       ├── battery/
│   │       ├── cable/
│   │       └── mobile/
│   ├── main.py
│   └── README.md
🚀 Features
Transfer learning using EfficientNetV2B0

Categorical image classification

Training/validation performance visualization

Confusion matrix and classification report

Early stopping and learning rate scheduling

🧠 Model Workflow
Data loading using ImageDataGenerator

Model building with EfficientNetV2B0 (frozen base)

Model training on custom dataset

Model evaluation with accuracy, precision, recall, F1-score

Model saving/loading

📦 Dependencies
Install required libraries:

bash
Copy
Edit
pip install tensorflow matplotlib seaborn scikit-learn
🛠 How to Run
bash
Copy
Edit
python main.py
📊 Output
Console output of training and evaluation

Confusion matrix plot

Saved model as e_waste_classifier.h5

🖼 Example Classes
battery: Images of batteries and cells

mobile: Images of mobile phones

cable: Images of wires, USBs, and connectors

👥 Contributors
AICTE Internship Team – P3 Project Group
