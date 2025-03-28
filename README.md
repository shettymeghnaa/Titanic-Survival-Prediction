# Titanic Survival Prediction  
## Overview  
This project predicts whether a passenger survived the Titanic disaster using machine learning techniques. It leverages passenger data such as age, gender, ticket class, and more to make predictions.  
## Dataset  
The dataset used for this project contains information about Titanic passengers, including:  
- **PassengerId**: Unique identifier for each passenger  
- **Pclass**: Ticket class (1st, 2nd, 3rd)  
- **Name**: Name of the passenger  
- **Sex**: Gender  
- **Age**: Age in years  
- **SibSp**: Number of siblings/spouses aboard  
- **Parch**: Number of parents/children aboard  
- **Ticket**: Ticket number  
- **Fare**: Fare paid for the ticket  
- **Cabin**: Cabin number  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  
## Task Objectives  
1. **Preprocess the dataset**: Handle missing values, encode categorical variables, and normalize features.  
2. **Train a Machine Learning Model**: Implement models such as Logistic Regression, Random Forest, or XGBoost.  
3. **Evaluate Performance**: Use accuracy, precision, recall, and F1-score to assess the model.  
4. **Make Predictions**: Generate survival predictions for new passenger data.  
## Project Structure  
📂 Titanic-Survival-Prediction  
│── 📄 Titanic Survival Prediction.ipynb  # Jupyter Notebook with code  
│── 📄 resultfile.csv                     # Output predictions  
│── 📄 README.md                           # Project documentation  
│── 📄 requirements.txt                    # Dependencies  
## How to Run

1.  **Clone the Repository**

    ```bash
    git clone https://github.com/shettymeghnaa/Titanic-Survival-Prediction
    cd Titanic-Survival-Prediction
    ```

2.  **Install Dependencies**

    Make sure you have Python installed. Then, install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3.  **Open the Jupyter Notebook**

    Launch Jupyter Notebook and open the `.ipynb` file:

    ```bash
    jupyter notebook
    ```

    Run the notebook cells step by step.

4.  **Generate Predictions**

    Once the model is trained, use it to predict survival outcomes for new data. The output predictions are saved in `resultfile.csv`, which contains two columns: `PassengerId` and `Survived` (where 1 indicates survival and 0 indicates non-survival).

## Dependencies

This project requires the following libraries:

* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## Results

The model achieved an accuracy of 85% on the test dataset.

Key insights from the dataset:

* Women had a higher survival rate than men.
* Passengers in 1st class were more likely to survive.
* Younger passengers had a better chance of survival.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License

This project is open-source and available under the MIT License.

## 🔗 GitHub Repository

[https://github.com/shettymeghnaa/Titanic-Survival-Prediction](https://github.com/shettymeghnaa/Titanic-Survival-Prediction)
