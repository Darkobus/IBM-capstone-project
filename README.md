# IBM Data Science Professional Certificate — capstone

**Question:** will the SpaceX Falcon 9 first stage land successfully? A successful landing
means the stage can be reused, which is the main driver of launch cost.

Coursera / IBM capstone, covering the full workflow from data collection to a predictive model.

## Notebooks

| Step | Notebook | What it does |
|---|---|---|
| 1 | [API](notebooks/API.ipynb) | Launch data from the SpaceX REST API |
| 2 | [Webscrapping](notebooks/Webscrapping.ipynb) | Falcon 9 launch records scraped from Wikipedia |
| 3 | [Data wrangling](notebooks/Data-wrangling.ipynb) | Cleaning, landing-outcome label |
| 4 | [SQL](notebooks/SQL.ipynb) | Exploratory queries |
| 5 | [Data visualisation](notebooks/Data-Visualisation.ipynb) | EDA: payload, orbit, launch site vs. success |
| 6 | [Folium](notebooks/Folium.ipynb) | Interactive maps of launch sites and their surroundings |
| 7 | [Dashboard](notebooks/Dashboard.ipynb) | Plotly Dash dashboard |
| 8 | [Machine learning](notebooks/Machine-Learning.ipynb) | Logistic regression, SVM, decision tree, KNN with GridSearchCV |

## Result

All tuned classifiers reach roughly **0.85 cross-validated accuracy** on the training split
(logistic regression 0.846, SVM 0.848, KNN 0.848). The test set is small (18 launches),
so the models are hard to separate on it.

## Other course assignments

`course-tasks/` — smaller assignments from the same programme (stock data scraping for Tesla /
GameStop, module 2 task).
