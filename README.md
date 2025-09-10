# Tel Aviv Apartments Rent Prediction Project
This project aims to predict apartment rental prices in Tel Aviv using machine learning models. The notebook covers data wrangling, feature engineering, and building predictive models using Elastic Net and Decision Trees. We evaluate the performance of both models and compare their results.

## 📓 Notebook

👉 [Open on nbviewer](https://nbviewer.org/url/https://github.com/adirbella37/RentalPrice-ML-Modeling/blob/main/apartment_rent_prediction.ipynb)

## ⚙️ Technologies
- Python — main programming language
- Pandas — for data wrangling and preprocessing
- Scikit-learn — for building and training models (Elastic Net, Decision Trees)
- Matplotlib & Seaborn — for visualizations
- Pickle — to save the trained models

## 📂 Project Structure

| File/Folder                       | Description                                |
|----------------------------------|--------------------------------------------|
| `apartment_rent_prediction.ipynb` | Main Jupyter Notebook (data wrangling, feature engineering, modeling) |
| `train.csv`                       | Training dataset                           |
| `en_model.pkl`                    | Saved Elastic Net trained model            |
| `README.md`                       | Project documentation                      |

## ▶️ How to run

You can get this project in two ways:

**Option 1 – Using Git**

```bash
git clone https://github.com/adirbella37/RentalPrice-ML-Modeling.git
cd RentalPrice-ML-Modeling
```

**Option 2 – Download as ZIP**

1. Click the green Code button at the top of this repository
2. Select Download ZIP
3. Extract the ZIP file on your computer

## 📈 Key Insights
- Elastic Net provided more stable predictions but with slightly lower accuracy.  
- Decision Trees captured non-linear relationships but risked overfitting.  
- Feature engineering (size, rooms, neighborhood distances) had the strongest impact on prediction accuracy.  

## 📜 License
This project is licensed under the MIT License.
