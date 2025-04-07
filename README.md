<b> Netflix Titles Dataset - Data Cleaning & Preprocessing </b>

This project involves cleaning and preprocessing the Netflix Titles Dataset to prepare it for further analysis or visualization.

📌 Dataset Source : 

The original dataset (netflix_titles.csv) contains information about Netflix shows and movies, including attributes like title, type, director, cast, country, release year, rating, and more.

🧹 Data Cleaning Steps Performed :

1. Loaded the Dataset using pandas from a CSV file.

2. Removed Duplicates to ensure each record is unique.

3. Standardized Column Names by converting to lowercase and replacing spaces with underscores.

4. Handled Missing Values:

    - Replaced missing director and cast with "Not Available".

    - Filled missing country with the most frequent country.

    - Filled missing rating with "Not Rated".

    - Parsed date_added column into datetime format and removed rows with invalid dates.

5. Created New Features:

    - Extracted added_year and added_month from date_added.

6. Converted Data Types:

    - Ensured release_year is of integer type.

7. Standardized Text Columns:

    - Cleaned whitespace and formatted type, title, and rating columns.

8. Reordered Columns logically for better readability and analysis.

9. Saved the Cleaned Dataset as Netflix_Titles_Cleaned_Formatted.csv.

✅ Output :

The cleaned dataset is ready for use in data analysis, visualization, or machine learning tasks.

