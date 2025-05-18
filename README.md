# Investigating Netflix Movies and Guest Stars in *The Office*

This project explores trends in Netflix movie durations over time using Python, pandas, and matplotlib. It was originally completed as part of a guided project on DataCamp, focusing on practical data manipulation and visualization skills.

![Netflix Banner](https://assets.datacamp.com/production/project_1237/img/netflix.jpg)

## 📌 Overview

This notebook investigates:
- Whether the average duration of Netflix movies is declining over time.
- How different genres (e.g. Children, Documentaries, Stand-Up) might influence this trend.
- How to visually explore such datasets using Python's `pandas` and `matplotlib`.

We also filter and analyze subsets of the Netflix dataset and explore how genres may skew average durations.

---

## 📂 Dataset

- **File**: `netflix_data.csv`
- **Columns of Interest**:
  - `title`
  - `country`
  - `genre`
  - `release_year`
  - `duration`
  - `type` (Movie or TV Show)

You can find the CSV in the `datasets/` directory.

---

## 📊 Key Steps

1. **Create Sample Duration Dataset (2011–2020)**  
   - Created a dictionary with average movie durations over the past decade.
   - Visualized this with a simple line plot.

2. **Load Full Netflix Dataset**  
   - Filtered to include only **Movies**, excluding **TV Shows**.
   - Selected key columns to focus analysis.

3. **Data Visualization**  
   - Created scatter plots of movie durations by release year.
   - Highlighted genres like *Children*, *Documentaries*, and *Stand-Up* with different colors.

4. **Genre Influence Analysis**  
   - Shorter movies were primarily from non-feature film genres.
   - Used conditional coloring to show genre patterns.

---

## 📈 Example Visualizations

- **Line Plot**: Average movie durations from 2011 to 2020.
- **Scatter Plot**: Movie durations over time.
- **Color-Coded Scatter Plot**: Genre-specific duration trends.

---

## 🛠 Tools Used

- Python 3 (Google Colab)
- `pandas` for data handling
- `matplotlib` for data visualization

---

## 🤔 Conclusion

Although Netflix's average movie duration appears to be declining, a deeper dive reveals that this is partly due to the presence of shorter films in genres like children's content and documentaries. These skew the overall average but don't necessarily indicate a broad industry trend.

---

## 📚 Learn More

This notebook was inspired by exercises from the [Intermediate Python](https://learn.datacamp.com/courses/intermediate-python) and [Data Manipulation with pandas](https://www.datacamp.com/courses/data-manipulation-with-pandas) courses on DataCamp.

---

## 👤 Author

**Moustafa Rezk**  
GitHub: [rezk1834](https://github.com/rezk1834)
