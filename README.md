# Explaining Machine Learning Predictions with LIME

This project demonstrates how to use the LIME (Local Interpretable Model-agnostic Explanations) library to explain predictions made by a machine learning model. In this example, a toy dataset is generated, and a Decision Tree classifier is trained to predict whether a person will buy a game based on their age and income. LIME is used to provide insights into why the model made a specific prediction.

## Project Overview

1. **Dependencies:** This project requires `numpy`, `scikit-learn`, and `lime` libraries.

2. **Dataset Generation:** A toy dataset of 100 samples is generated, where each sample consists of age and income. Labels are assigned based on whether the sum of age and income is greater than 100.

3. **Data Splitting:** The dataset is split into training and testing sets using the `train_test_split` function from `sklearn.model_selection`.

4. **Model Training:** A Decision Tree classifier is trained using the training data.

5. **Prediction Explanation:** LIME's `LimeTabularExplainer` is used to explain a prediction instance chosen from the test set. The explanation shows which features contributed to the model's prediction.

## How to Use

1. Clone the repository.

2. Install required packages:

3. Open the `explanation.py` file and run the code.

4. Observe the explanation provided by LIME for the chosen prediction instance.

## Additional Notes

- LIME provides local explanations for individual predictions, helping you understand why a specific prediction was made by your machine learning model.

- The example provided uses a toy dataset and a simple Decision Tree classifier, but LIME can be applied to various machine learning models and real-world datasets.

- Feel free to modify the code and experiment with different datasets and models to gain a deeper understanding of prediction explanations.

## License

This project is open-source and available under the [MIT License](LICENSE).
