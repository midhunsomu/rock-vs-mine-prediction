

# Rock vs Mine Prediction using Convolutional Neural Network (CNN)

## Description
This project involves classifying sonar signals as either "Rock" or "Mine" using a **Convolutional Neural Network (CNN)**. The dataset used in this project is the **Sonar Dataset**, containing sonar signals with 60 features. The model is built using **TensorFlow** and **Keras**, which classifies the signals into two categories: "R" for Rock and "M" for Mine.

## Dataset
The dataset used in this project is the **Sonar Dataset**, which consists of 60 attributes derived from sonar signals. The attributes represent the intensity of the echo received from a sonar system, used to classify objects into two categories: **Rock (R)** and **Mine (M)**.

- **Input features**: 60 numerical values representing sonar signal intensities.
- **Output labels**: Binary classification – either "Rock" (R) or "Mine" (M).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/midhunsomu/rock-vs-mine-prediction.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load the **Sonar Dataset** using `pandas`.
2. Preprocess the data by splitting it into training and testing sets using **train_test_split**.
3. **Standardize** the features to ensure they are in the range [0, 1].
4. Convert the categorical labels ("R" and "M") to numeric values using **LabelEncoder**.
5. Build and compile the **CNN model** using **Keras** with layers such as **Dense** and **Flatten**.
6. Train the model for 10 epochs and evaluate its performance on the test data.
7. Visualize the loss and accuracy during the training process.

### Example Command:
```bash
python rock_vs_mine_prediction.py
```

## Model Evaluation
- **Loss**: 0.5609  
- **Accuracy**: 76.19%  

## Technologies Used
- **Python**: Main programming language.
- **TensorFlow/Keras**: For building and training the CNN model.
- **Scikit-learn**: For data preprocessing and splitting.
- **Matplotlib**: For data visualization.

---

