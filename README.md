# Movie Data Cleaning and Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on cleaning and exploring a movie dataset using Python. The objective is to transform raw movie data into a structured format and perform Exploratory Data Analysis (EDA) to identify patterns, distributions, and insights.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains 9,827 movie records and 9 columns, including movie titles, genres, release dates, vote averages, popularity, and other movie-related attributes.

## Project Workflow

### 1. Data Exploration
- Examined dataset structure and data types.
- Checked for missing values and duplicate records.
- Generated descriptive statistics.

### 2. Data Cleaning
- Converted release dates into datetime format.
- Extracted release years.
- Removed unnecessary columns such as Overview, Original_Language, and Poster_Url.
- Categorized movie ratings using quantile-based binning.
- Handled missing values.

### 3. Data Transformation
- Split multiple genres into individual categories.
- Used Pandas `explode()` to separate genres into individual rows.
- Converted genre data into categorical format.

### 4. Exploratory Data Analysis
- Analyzed movie genre distribution.
- Visualized movie rating categories.
- Identified movies with maximum and minimum popularity.
- Examined movie release-year distribution using histograms.

## Key Skills Demonstrated
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation using Pandas
- Data Visualization
- Descriptive Statistics
- Working with Categorical Data

## How to Run
1. Clone this repository.
2. Install the required libraries:
   `pip install -r requirements.txt`
3. Open the Jupyter Notebook.
4. Run the cells sequentially.

## Project Status
Completed – Beginner-level Data Analytics Project.

## Author
Aspiring Data Analyst | Python | SQL | Excel | Power BI
