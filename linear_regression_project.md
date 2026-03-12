# Stage 1: Train the Model (train.py)

1. Download and use a dataset from **Kaggle**.
2. Train a **Linear Regression** model using the dataset.
3. Achieve a model accuracy of **more than 90%**.
4. Generate and display a **graph/visualization** related to the model  
   (for example: regression line, prediction vs. actual values, or error plot).

---

# Stage 2: Use the Model for Prediction (predict.py)

1. Save the trained model as **`model.pkl`**.
2. Create a new Python file called **`predict.py`** and load the saved model.
3. Allow the user to **enter input values from the terminal** using `input()`.
4. Use the entered values to **make a prediction with the trained model**.
5. Test incorrect inputs:
   - Enter a **number where a word is expected**.
   - Enter a **word where a number is expected**.
6. Implement **input validation or error handling** to correctly manage these cases.

---

# Stage 3: Simple Web Interface

1. Create a **new file** for a simple web interface.
2. Develop a **one-page website** that demonstrates the model.
3. Display the **graph generated in Stage 1**.
4. Show the **model accuracy and error metrics**.
5. Display **10 samples from the dataset**.
   - If you removed any columns during preprocessing, explain why and show the **final dataset used for training**.
6. Add an **input form** where the user can enter values  
   (for example: number of rooms, floor number, etc.).
7. When the user clicks the **“Predict” button**, display the **prediction result on the webpage**.
