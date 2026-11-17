# 📱 Google Play Store Data Analysis

## 📌 Project Overview

This project focuses on analyzing Google Play Store applications to understand app distribution, user ratings, installation patterns, pricing strategies, and monetization methods.

Using Python and exploratory data analysis (EDA), the project explores different app genres, ratings, reviews, pricing models, advertisements, and in-app purchases to identify meaningful patterns and insights.

## 🎯 Project Objectives

- Analyze the distribution of applications across different genres.
- Understand app ratings and user review patterns.
- Compare free and paid applications.
- Explore installation trends across applications.
- Analyze the relationship between app ratings and other features.
- Examine monetization strategies through advertisements and in-app purchases.
- Identify patterns in application pricing and content ratings.

## 📂 Dataset Information

**Dataset:** Google Play Apps 2026 Sample

- Total Records: 100,013
- Total Features: 19
- Data Type: Structured Tabular Data

### Key Features

| Column | Description |
|---|---|
| app_id | Unique application identifier |
| title | Application name |
| developer | Application developer |
| genre | Application category |
| is_game | Indicates whether the app is a game |
| installs | Number of application installations |
| score | Average user rating |
| ratings | Total number of ratings |
| reviews | Total number of reviews |
| free | Indicates whether the app is free |
| price | Application price |
| contains_ads | Indicates whether the app contains advertisements |
| offers_iap | Indicates whether the app offers in-app purchases |
| content_rating | Application age rating |
| released | Application release date |
| last_updated | Last update date |

## 🛠️ Technologies & Libraries Used

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis

## 🔍 Analysis Workflow

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined dataset dimensions, columns, and data types.
- Used descriptive statistics to understand numerical features.
- Identified unique values and categorical distributions.

### 2. Data Cleaning
- Checked for missing values and duplicate records.
- Examined missing values in ratings, reviews, release dates, and developer information.
- Handled missing values using suitable techniques.
- Converted columns into appropriate data types.
- Prepared the dataset for exploratory analysis.

### 3. Exploratory Data Analysis (EDA)

**Univariate Analysis**
- Distribution of application genres.
- Distribution of app ratings.
- Free vs. paid application distribution.
- Advertisement availability.
- In-app purchase distribution.
- Application content ratings.
- Installation distribution.

**Bivariate Analysis**
- App ratings across different genres.
- Free vs. paid application ratings.
- Genre-wise application distribution.
- Price vs. app ratings.
- Advertisement availability across genres.
- In-app purchases across application categories.
- Ratings vs. number of reviews.

**Multivariate Analysis**
- Correlation analysis of numerical features.
- Genre-wise comparison of application ratings and pricing.
- Relationships between application characteristics and user engagement.

## 📊 Key Dataset Observations

- Education is the most represented genre, with 10,438 applications.
- Approximately 98,537 applications are free, making free apps the dominant pricing model.
- Around 43,449 applications contain advertisements.
- Approximately 18,500 applications offer in-app purchases.
- The Everyone content-rating category contains the largest number of applications.
- The average available application rating is approximately 4.03.
- Ratings are available for 31,755 records, indicating substantial missing data in the rating-related columns.

## 📈 Data Visualizations

The project uses different statistical visualizations to identify patterns and relationships within the dataset.

Add your exported charts inside the `images` folder.

Example:

```markdown
![Genre Distribution](images/genre_distribution.png)

![Rating Distribution](images/rating_distribution.png)

![Correlation Heatmap](images/correlation_heatmap.png)
```

## 📁 Project Structure

```text
Google-Play-Store-Analysis/
│
├── images/
│   ├── genre_distribution.png
│   ├── rating_distribution.png
│   └── correlation_heatmap.png
│
├── Playstore_Dataset_Analysis.ipynb
├── google_play_apps_2026_sample.csv
└── README.md
```

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Google-Play-Store-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the analysis notebook and execute the cells.

## 📝 Conclusion

This project explores the Google Play Store ecosystem through exploratory data analysis. It provides insights into application categories, ratings, pricing models, installation patterns, and monetization strategies. The analysis demonstrates how Python-based data analytics and visualization can help understand application market trends and user engagement.

---

**Project Category:** Data Analytics | Exploratory Data Analysis

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn
