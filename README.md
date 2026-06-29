# Weather Prediction using Decision Tree

## Project Description

This project uses the **Decision Tree Classification** algorithm to predict whether a game should be played based on weather conditions. The model is trained on a weather dataset containing attributes such as outlook, temperature, humidity, and wind. After training, users can enter weather conditions, and the model predicts whether the outcome will be **"Yes"** or **"No"**.

The project provides a simple demonstration of how decision trees learn patterns from categorical data and use them to make predictions.

---

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## Dataset Information

The dataset includes the following weather attributes:

| Feature     | Description                                         |
| ----------- | --------------------------------------------------- |
| Outlook     | Sunny, Overcast, or Rain                            |
| Temperature | Hot, Mild, or Cool                                  |
| Humidity    | High or Normal                                      |
| Wind        | Weak or Strong                                      |
| Play        | Target variable indicating whether to play (Yes/No) |

---

## Implementation

The workflow of the project includes:

* Creating a weather dataset using Pandas.
* Encoding categorical values with `LabelEncoder`.
* Training a Decision Tree Classifier using the entropy criterion.
* Accepting weather conditions from the user.
* Predicting whether the game should be played.
* Visualizing the trained decision tree.
* Displaying feature importance to identify the most influential weather factors.

---

## Output

The application predicts one of the following outcomes:

* **Play = Yes**
* **Play = No**

It also generates:

* A visualization of the trained Decision Tree.
* A Feature Importance chart showing the contribution of each weather attribute.

---

## Future Scope

* Train the model using a larger real-world weather dataset.
* Compare the Decision Tree model with other classification algorithms.
* Build a graphical user interface for easier interaction.
* Improve prediction performance through hyperparameter tuning and cross-validation.

---

## Author

**Britto Domnic Aro J**

Aspiring Machine Learning Engineer | Python Developer | Data Analytics Enthusiast
