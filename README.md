# football ML project
 
#  Linear Regression from Scratch in NumPy

This project demonstrates how to build and train a simple **Linear Regression model from scratch** using only NumPy, without relying on machine learning libraries like scikit-learn.

---

##  Project Overview

Linear Regression is one of the most fundamental and widely-used algorithms in supervised learning. This project covers:

- Intuitive understanding of Linear Regression
- Mathematical formulation of the model
- Cost function (Mean Squared Error)
- Gradient Descent optimization
- Training loop from scratch
- Visualization of predictions vs actual data

---

##  File Structure

```
📁 Linear-Regression-From-Scratch
│
├── prediction.ipynb   # Main Jupyter notebook with implementation
├── README.md          # Project overview and instructions
```

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

---

##  Model Formula

The linear regression model makes predictions using the formula:

```
ŷ = w₀ + w₁x
```

Where:
- `w₀` is the **bias (intercept)**,
- `w₁` is the **weight (slope)**,
- `x` is the input feature.

The cost function used is **Mean Squared Error (MSE)**:

```
J(w) = (1 / 2m) * Σ(ŷᵢ - yᵢ)²
```

---

##  How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/linear-regression-numpy.git
cd linear-regression-numpy
```

2. Open the notebook:
```bash
jupyter notebook prediction.ipynb
```

3. Run all cells to:
   - Visualize the dataset
   - Train the model using gradient descent
   - Plot predictions vs actual data

---

##  Sample Output

- Cost decreases over time.
- Predicted line fits data well.
- Final weights give a best-fit linear model.

*(Optional: Add prediction plot screenshot here)*

---

##  Learning Objectives

By the end of this project, you’ll understand:
- How Linear Regression works mathematically
- How gradient descent updates weights
- How to implement ML models without libraries
- The difference between analytical solution and iterative optimization

---

## Future Enhancements

- Add multivariable regression
- Implement mini-batch gradient descent
- Compare with scikit-learn’s implementation
- Evaluate model with R² Score

---

## Contributing

Contributions are welcome! Feel free to fork the repo, create issues, or submit pull requests.

---
## License

This project is licensed under the MIT License.
