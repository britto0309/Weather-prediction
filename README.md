# Weather-prediction

# 🌦️ Weather Prediction using Decision Tree

## 📌 Project Overview

This project predicts whether the weather conditions are suitable for playing outdoor games using the **Decision Tree Classification** algorithm from **Scikit-learn**.

The model is trained on a weather dataset containing different weather conditions such as **Outlook, Temperature, Humidity, and Wind**. Based on these inputs, it predicts whether the output is **Play = Yes** or **Play = No**.

The project also visualizes the trained Decision Tree and displays the importance of each feature.

---

# 🎯 Objectives

* Build a weather prediction model using the Decision Tree algorithm.
* Train the model using a weather dataset.
* Predict whether weather conditions are suitable for playing.
* Visualize the Decision Tree.
* Display the importance of each weather feature.

---

# 🧠 Machine Learning Algorithm

**Algorithm Used:** Decision Tree Classifier

A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It makes predictions by splitting the dataset into branches based on feature values until a final decision is reached.

In this project, the model predicts:

* **Yes** → Suitable weather for playing.
* **No** → Not suitable weather for playing.

---

# 📂 Dataset

The project uses a manually created dataset containing **20 weather records**.

### Input Features

* Outlook (Sunny, Overcast, Rain)
* Temperature (Hot, Mild, Cool)
* Humidity (High, Normal)
* Wind (Weak, Strong)

### Target Variable

* Play (Yes / No)

---

# ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

# 📚 Libraries Used

```python
pandas
matplotlib
scikit-learn
```

---

# 🔄 Project Workflow

1. Create the weather dataset.
2. Convert categorical values into numerical values using **Label Encoding**.
3. Train the Decision Tree Classifier.
4. Accept weather details from the user.
5. Predict whether the weather is suitable for playing.
6. Display the Decision Tree visualization.
7. Display the Feature Importance graph.

---

# 🔢 Data Preprocessing

Since machine learning models work with numerical data, categorical values such as:

* Sunny
* Rain
* Overcast

are converted into numerical values using **LabelEncoder**.

Example:

| Original Value | Encoded Value |
| -------------- | ------------: |
| Overcast       |             0 |
| Rain           |             1 |
| Sunny          |             2 |

---

# 🌳 Decision Tree Visualization

The project displays the complete Decision Tree after training.

The tree shows:

* Decision nodes
* Splitting conditions
* Leaf nodes
* Final predictions

This helps understand how the model makes decisions.

---

# 📊 Feature Importance

The project also generates a **Feature Importance** graph.

This graph shows which weather feature contributes the most to the prediction.

For example:

* Outlook
* Humidity
* Wind
* Temperature

Higher importance indicates a greater influence on the prediction.

---

# 🚀 Features

* Weather Prediction
* Decision Tree Classification
* Label Encoding
* Interactive User Input
* Decision Tree Visualization
* Feature Importance Graph

---

# ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Weather-Prediction-Decision-Tree.git
```

### Navigate to the project folder

```bash
cd Weather-Prediction-Decision-Tree
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python weather_prediction.py
```

---

# 💻 Sample Input

```
Outlook: Sunny
Temperature: Hot
Humidity: High
Wind: Weak
```

---

# 📤 Sample Output

```
Prediction Result:

Play = No
```

---

### Another Example

#### Input

```
Outlook: Overcast
Temperature: Mild
Humidity: Normal
Wind: Weak
```

#### Output

```
Prediction Result:

Play = Yes
```

---

# 📈 Output Visualizations

The project generates two graphical outputs:

### 1. Decision Tree Diagram

Displays the complete Decision Tree used for prediction.

```markdown
![Decision Tree](decision_tree.png)
```

---

### 2. Feature Importance Graph

Displays the contribution of each feature to the prediction.

```markdown
![Feature Importance](feature_importance.png)
```

---

# 📁 Project Structure

```
Weather-Prediction-Decision-Tree
│
├── weather_prediction.py
├── README.md
├── requirements.txt
├── decision_tree.png
├── feature_importance.png
└── .gitignore
```

---

# 📖 Learning Outcomes

Through this project, you will learn:

* Decision Tree Classification
* Label Encoding
* Data preprocessing
* Model training and prediction
* Decision Tree visualization
* Feature Importance analysis
* Interactive machine learning applications

---

# 🔮 Future Improvements

* Train the model on a larger real-world weather dataset.
* Include additional weather features such as rainfall, pressure, and visibility.
* Add model evaluation using a train-test split and accuracy score.
* Build a web application using Streamlit or Flask.
* Save and load the trained model using Joblib or Pickle.

---

# 👨‍💻 Author

**Britto Domnic Aro J**

Machine Learning Enthusiast | Python Developer | AI Learner

---

# ⭐ If you found this project useful, consider giving this repository a Star on GitHub!

