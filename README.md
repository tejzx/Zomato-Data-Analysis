# 📌 Zomato Data Analysis Project

## 🚀 Overview
This project involves analyzing the **Zomato dataset** to gain insights into restaurant trends, customer preferences, and food pricing patterns. The analysis includes **data preprocessing, visualization, and machine learning models** to predict restaurant ratings and explore various factors affecting them.

## 📂 Project Structure
```
├── data/                 # Dataset and cleaned data files
├── notebooks/            # Jupyter notebooks for analysis
├── src/                  # Python scripts for preprocessing & modeling
├── models/               # Saved trained models
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
```

## 📊 Dataset Description
The dataset contains information about:
- **Restaurant details**: Name, location, cuisine types, price range, and online delivery options.
- **Customer interactions**: Ratings, votes, and reviews.
- **Geographical information**: City-wise restaurant distribution.

## 🛠️ Installation
To run this project locally, follow these steps:
```bash
# Clone the repository
git clone https://github.com/yourusername/Zomato-Analysis.git
cd Zomato-Analysis

# Install dependencies
pip install -r requirements.txt
```

## 🔍 Exploratory Data Analysis (EDA)
- Handling missing values & duplicates
- Visualizing restaurant distribution across locations
- Analyzing pricing patterns & online delivery impact

## 🤖 Machine Learning Models
- **Regression Model**: Predicting restaurant ratings.
- **Classification Model**: Identifying high-rated restaurants.

## 📈 Key Findings
- The **average price range** varies significantly across different cuisines.
- **Online delivery services** impact customer engagement & ratings.
- **Restaurant location** is a key factor influencing popularity.

## 📌 How to Use
Run the Jupyter Notebook:
```bash
jupyter notebook zomato_project.ipynb
```
Modify hyperparameters in `src/model_training.py` to experiment with different models.

## 🔗 References
- [Zomato API](https://developers.zomato.com/documentation)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

## 🤝 Contributing
Want to contribute? Feel free to fork the repo and submit pull requests!

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
