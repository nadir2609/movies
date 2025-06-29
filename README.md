

# 🎬 Movie Dataset Analysis & Visualization

This project explores a dataset of movies. It focuses on analyzing various features such as ratings, budgets, box office gross, and personnel involved (e.g., directors, stars). The goal is to extract insights and present them using **data visualization techniques** with Python libraries like `pandas`, `matplotlib`, and `seaborn`.

---

## 📁 Dataset Overview

The dataset contains metadata for multiple movies. Each row represents one movie and includes various numerical and categorical fields for analysis.

### 🔍 Column Descriptions

| Column Name  | Description                                                                                     |
| ------------ | ----------------------------------------------------------------------------------------------- |
| **name**     | The title of the movie.                                                                         |
| **rating**   | The movie's MPAA rating (e.g., G, PG, PG-13, R), indicating the age-appropriateness of content. |
| **genre**    | The primary genre of the movie (e.g., Drama, Comedy, Action).                                   |
| **year**     | The year the movie was released (in this dataset, all values are 1980).                         |
| **released** | The full release date along with the country where it was released.                             |
| **score**    | The average IMDb score (rating) given by users, typically on a scale of 1 to 10.                |
| **votes**    | The number of user votes received on IMDb.                                                      |
| **director** | The name of the movie's director.                                                               |
| **writer**   | The writer(s) or screenwriter(s) credited for the movie.                                        |
| **star**     | The lead actor or actress in the movie.                                                         |
| **country**  | The country where the movie was produced.                                                       |
| **budget**   | The production budget of the movie (in USD).                                                    |
| **gross**    | The total gross earnings at the box office (in USD).                                            |
| **company**  | The production or distribution company responsible for the movie.                               |
| **runtime**  | The duration of the movie in minutes.                                                           |

---

## 📊 Project Features

* **Data Cleaning & Preprocessing**

  * Handled missing values
  * Converted string dates into proper datetime objects
  * Ensured numeric columns had appropriate data types

* **Data Analysis**

  * Distribution of IMDb scores
  * Most popular genres by vote count and rating
  * Correlation between budget and gross earnings
  * Top-grossing and top-rated movies
  * Director and actor analysis
  * Runtime vs score analysis

* **Data Visualization**

  * Histograms of scores and votes
  * Bar charts of gross revenue by genre, director, and company
  * Scatter plots 
  * Heatmaps showing correlation between numerical features
  * Pie charts showing genre or country distribution

---

## 🛠 Tools & Libraries Used

* **Python**
* **pandas** – for data manipulation
* **matplotlib** & **seaborn** – for plotting and visualization
* **numpy** – for numerical operations


---

## 📈 Key Insights

* Higher budgets generally lead to higher gross earnings, but exceptions exist.
* Certain directors and companies consistently produce high-grossing films.
* The genre of **Comedy** was popular in 1980, both in number and in performance.
* Movies with longer runtimes tended to have slightly better scores.
* The **United States** dominated the movie production market in 1980.

---
