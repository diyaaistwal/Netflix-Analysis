# Netflix-Analysis


# Netflix Data Analysis Project

This project involves analyzing Netflix data to uncover meaningful insights and answer specific business questions. The dataset contains information about Netflix's movies and TV shows, such as titles, release dates, durations, and countries of origin.

---

## Dataset
The dataset used for this analysis is **`dataset_netflix.csv`**, which contains the following columns:
- `show_id`: Unique identifier for each show or movie.
- `type`: Indicates whether the entry is a "Movie" or a "TV Show".
- `title`: Title of the show or movie.
- `director`: Name of the director.
- `country`: Country of production.
- `date_added`: Date when the show or movie was added to Netflix.
- `release_year`: Year when the show or movie was released.
- `rating`: Age rating for the content.
- `duration`: Duration of movies (in minutes) or TV shows (in seasons).
- `listed_in`: Genres/categories of the show or movie.

---

## Tasks
The following tasks are part of this project:

### **Task 1: Breaking Down a Timestamp**
- **Objective**: Break the `date_added` column into three new columns:
  - `month_added`: Full month name (e.g., "September").
  - `year_added`: Year (e.g., 2020).
  - `day_added`: Full day name (e.g., "Monday").
  
### **Task 2: Count of TV Shows**
- **Objective**: Find the total count of TV shows available on Netflix.
- **Hint**: Use the `type` column to filter rows where the value is "TV Show".

### **Task 3: Movies Released in December**
- **Objective**: Identify how many movies were added to Netflix during the high-demand month of December.
- **Hint**: Filter rows where `type` is "Movie" and `month_added` is "December".

### **Task 4: Median Movie Duration**
- **Objective**: Calculate the median duration of movies available on Netflix.
- **Hint**: Filter the dataset to only include rows where `type` is "Movie", and then compute the median of the `duration` column.

### **Task 5: Country with Maximum Titles**
- **Objective**: Find the country with the highest number of titles (both TV shows and movies).
- **Hint**: Group the data by `country` and count the number of titles for each country.

### **Task 6: Country with Maximum TV Shows and Movies**
- **Objective**: Identify the country with the maximum number of both TV shows and movies.
- **Hint**: Similar to Task 5, but considering both `type` values ("Movie" and "TV Show") in the analysis.

### **Task 7: Median Duration of Movies**
- **Objective**: Calculate the median duration of movies in Netflix’s catalog.
- **Hint**: Filter for `type` as "Movie", then calculate the median of the `duration` column.

---
