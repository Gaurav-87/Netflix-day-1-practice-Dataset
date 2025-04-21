# Netflix-day-1-practice-Dataset
# Netflix Titles Data Cleaning Project

This project focuses on cleaning and preprocessing a dataset of Netflix titles using Python and pandas in Google Colab.

## 📄 Dataset

The dataset used is `netflix_titles.csv`, which contains information about movies and TV shows available on Netflix.

## 🧹 Cleaning Tasks Performed

1. **Loaded the dataset** in Google Colab using pandas.
2. **Handled missing values**:
   - Filled missing values in the `director` column with `"Unknown"`.
   - Removed rows with missing `title`.
3. **Removed duplicate rows** to ensure data integrity.
4. **Standardized text fields** like `country` by trimming whitespace and applying proper casing.
5. **Converted date formats**:
   - Transformed the `date_added` column to `datetime` format.
6. **Cleaned column names**:
   - Converted all headers to lowercase and replaced spaces with underscores.
7. **Ensured correct data types**:
   - Confirmed `release_year` is an integer.
   - Confirmed `date_added` is in datetime format.
8. **Exported the cleaned dataset** as `cleaned_netflix_titles.csv`.

## 📁 Output

- `cleaned_netflix_titles.csv` — the cleaned and ready-to-use dataset.

## 🚀 Tools Used

- Python
- pandas
- Google Colab

## 📌 Getting Started

To run this project:
1. Open the `.ipynb` file in Google Colab.
2. Upload the original `netflix_titles.csv`.
3. Run all cells to clean the data.
4. Download the final cleaned file.

---

Feel free to fork or modify this repo to build further insights or visualizations!
