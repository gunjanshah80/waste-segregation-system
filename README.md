# Waste Material Classification using CNN

## 📌 Project Overview

This project focuses on building a **Waste Material Classification System** using **Convolutional Neural Networks (CNNs)**. The aim is to automatically classify waste images into different categories such as **cardboard, glass, paper, plastic, metal, food waste, and other waste**.

As a trainer and learner, this project helped me understand how deep learning can be applied to real-world sustainability problems. Waste segregation is an important step in improving recycling efficiency, reducing landfill waste, and supporting cleaner environmental practices.

---

## 🎯 Objective

The main objective of this project is to develop an image classification model that can identify different types of waste materials using CNN-based deep learning techniques.

Through this project, the goal is to:

* Train a CNN model to classify waste images into multiple categories.
* Fine-tune the model to improve classification performance.
* Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
* Understand the role of Artificial Intelligence in sustainable waste management.
* Explore how computer vision can help automate recycling and waste sorting.

---

## 🌍 Business Value

Improper waste disposal is a major environmental concern. It increases landfill waste, causes pollution, and reduces the effectiveness of recycling systems. Manual sorting of waste is time-consuming, labour-intensive, costly, and prone to human error.

An AI-powered waste classification system can help solve these challenges by automating the waste segregation process.

### Key Business Benefits

* Automated waste sorting
* Reduction in manual labour and operational cost
* Improved recycling efficiency
* Better classification of recyclable and non-recyclable waste
* Support for smart and sustainable waste management systems
* Reduced environmental pollution

---

## ✅ Use Cases

This project can be useful in several real-world scenarios, such as:

* Smart recycling bins
* Automated waste sorting facilities
* Waste monitoring and reporting systems
* Municipal waste management
* Recycling plants
* Educational demonstrations on AI for sustainability

---

## 🗂️ Dataset Overview

The dataset contains images of common waste materials divided into seven categories.

### Waste Categories

The dataset includes the following classes:

1. Cardboard
2. Food Waste
3. Glass
4. Metal
5. Other
6. Paper
7. Plastic

### Dataset Details

* The dataset contains around **7000 raw images**.
* Images are organized into separate folders, where each folder represents one waste category.
* Each folder contains images belonging to that category.
* Items inside each category are not further sub-categorized.

For example, the `Food_Waste` folder may contain images of coffee grounds, tea bags, fruit peels, and similar items, but these are all treated as one class: `Food_Waste`.

---

## 🧠 Deep Learning Approach

This project uses a **Convolutional Neural Network**, which is commonly used for image classification tasks.

CNNs are effective because they can automatically learn important visual features from images, such as:

* Shapes
* Edges
* Textures
* Patterns
* Object-specific visual details

The model learns these features during training and uses them to classify new waste images into the correct category.

---

## 🏗️ Project Workflow

The project follows these major steps:

1. Load and organize the image dataset
2. Perform image preprocessing
3. Split the dataset into training and validation sets
4. Apply image augmentation to improve generalization
5. Build a CNN model
6. Train the model on waste images
7. Evaluate model performance
8. Analyze classification results using performance metrics
9. Test the model on new waste images

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📊 Model Evaluation Metrics

The trained model is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

These metrics help us understand not only how many predictions were correct, but also how well the model performs for each waste category.

---

## 📈 Expected Output

The model should be able to classify an input waste image into one of the following classes:

```text
Cardboard
Food_Waste
Glass
Metal
Other
Paper
Plastic
```

---

## 📁 Suggested Project Structure

```text
waste-material-classification/
│
├── dataset/
│   ├── Cardboard/
│   ├── Food_Waste/
│   ├── Glass/
│   ├── Metal/
│   ├── Other/
│   ├── Paper/
│   └── Plastic/
│
├── notebooks/
│   └── waste_classification_cnn.ipynb
│
├── models/
│   └── waste_classification_model.h5
│
├── images/
│   └── sample_predictions.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/waste-material-classification.git
cd waste-material-classification
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

For Mac/Linux:

```bash
source venv/bin/activate
```

### 4. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 5. Run the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then run:

```text
notebooks/waste_classification_cnn.ipynb
```

---

## 📦 Sample requirements.txt

```text
tensorflow
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 🔍 Learning Outcomes

By completing this project, I learned:

* How CNNs work for image classification
* How to preprocess image datasets
* How to train and evaluate a deep learning model
* How to use performance metrics like precision, recall, and F1-score
* How AI can be used for solving environmental and sustainability problems
* How computer vision can support automated recycling systems

---

## 👨‍💻 Author

**Gunjan Shah**
Senior Cloud Data Engineer

This project is part of my learning journey in Machine Learning, Deep Learning, Computer Vision, and AI-based sustainability solutions.

---

## 📜 License

This project is for educational and learning purposes.
