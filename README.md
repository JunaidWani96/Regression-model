---

# 🍽️ Restaurant Rating Analysis & Prediction

This project performs an end-to-end analysis of restaurant data, including data exploration, visualization, feature engineering, and predictive modeling to forecast the **Aggregate Rating** of restaurants. It leverages Python and common data science libraries such as `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, and `folium`.

##  Dataset

* Source: `dataset(1).csv`
* Contains information about restaurants including name, location, cuisines, price range, table booking, online delivery, votes, and ratings.

## 📌 Project Structure

### Level 1

* **Data Exploration & Preprocessing**: Inspects dataset structure, handles missing values, and checks for class imbalances.
* **Descriptive Analysis**: Computes basic statistics and explores categorical variable distributions.
* **Geospatial Analysis**: Maps restaurants using latitude/longitude and examines distribution by city/country.

### Level 2

* **Table Booking & Online Delivery**: Assesses availability and influence on ratings.
* **Price Range Analysis**: Studies common price ranges and their impact on ratings.
* **Feature Engineering**: Adds new features like name/address length and encodes categorical variables.

### Level 3

* **Predictive Modeling**: Builds and evaluates models (Linear Regression, Decision Tree, Random Forest) to predict aggregate ratings.
* **Customer Preference Analysis**: Explores cuisines based on popularity and rating trends.
* **Data Visualization**: Visualizes feature distributions and their relationship with the target variable.

## 📊 Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

## 🧪 Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

## 📈 Visual Insights

* Histograms, bar plots, scatter plots, and box plots
* Geospatial heatmaps
* Feature vs. target correlation analysis

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn folium geopandas
   ```
3. Place `dataset.csv` in the project directory
4. Run the script:

   ```bash
   python main.py
   ```

---

Would you like a shorter version, or include badges for things like license, Python version, or dependencies?
