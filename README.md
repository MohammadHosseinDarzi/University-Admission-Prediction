# 🚀 University Admission Prediction Model

A machine learning model that predicts a student's chance of admission to a graduate program based on their academic profile. This project uses a Linear Regression model to analyze the relationship between various factors and the probability of acceptance.

## 📊 Dataset

The project utilizes the `adm_data.csv` dataset, which contains the following features for 400 applicants:

| Feature           | Description                                     | Range         |
| ----------------- | ----------------------------------------------- | ------------- |
| `GRE Score`       | Graduate Record Examinations score              | 0 - 340       |
| `TOEFL Score`     | Test of English as a Foreign Language score     | 0 - 120       |
| `University Rating` | The rating of the university they applied to    | 1 - 5         |
| `SOP`             | Statement of Purpose strength                   | 1 - 5         |
| `LOR`             | Letter of Recommendation strength               | 1 - 5         |
| `CGPA`            | Cumulative Grade Point Average                  | 0 - 10        |
| `Research`        | Whether the applicant has research experience | 0 (No) or 1 (Yes) |
| `Chance of Admit` | **Target Variable:** The probability of admission | 0.0 - 1.0     |


## 🛠️ Technologies & Libraries Used

*   **Python 3**
*   **Jupyter Notebook**
*   **Pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical operations.
*   **Scikit-learn:** For building and evaluating the machine learning model.
*   **Matplotlib & Seaborn:** For data visualization.

## ⚙️ How to Run This Project

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
```sh
git clone https://github.com/mohammadhosseindarzi/University-Admission-Prediction.git
cd University-Admission-Prediction

