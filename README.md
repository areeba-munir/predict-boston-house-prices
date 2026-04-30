# Boston Housing Price Predictor

### 📊 Project Overview
This project uses Multivariable Linear Regression to estimate residential property values in Boston. It explores how socio-economic factors, geography, and building characteristics influenced home prices in the 1970s.

### 🛠 Key Features & Workflow
* **EDA:** Visualized data distributions and correlations using Seaborn and Plotly.
* **Data Preprocessing:** Handled features like the "Charles River" dummy variable and analyzed the $50k price cap.
* **Modeling:** Built a Linear Regression model using `scikit-learn`.
* **Optimization:** Improved model performance (R-Squared jump from 0.75 to 0.79) by applying a **Log Transformation** to the target price.
* **Evaluation:** Analyzed residuals and skewness to ensure model reliability.

### 📈 Key Insights
* **Room Premium:** Each additional room significantly increases the home value.
* **Education Impact:** A higher student-to-teacher ratio (PTRATIO) negatively impacts house prices.
* **Pollution:** Nitric oxide levels (NOX) show a strong negative correlation with distance to employment centers.

### 🚀 Technologies Used
* Python
* Pandas & NumPy
* Seaborn & Plotly
* Scikit-Learn

### 🚀 How to Run
1. Clone the repo.
2. Install dependencies: `pip install pandas numpy seaborn scikit-learn plotly`
3. Open the `.ipynb` file in Google Colab.
