# YouTube Trending Videos Analysis

## Project Overview

This project analyzes YouTube Trending Videos data using Python and popular data analysis libraries such as NumPy, Pandas, Matplotlib, Seaborn, and WordCloud.

The goal is to discover patterns in trending videos, understand audience engagement, identify popular categories, and visualize key insights.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- WordCloud

---

## Dataset Information
   
### Dataset Name
YouTube Trending Videos Dataset

### Source
Kaggle

### Dataset Description

The dataset contains information about trending YouTube videos including:

- Video Title
- Channel Name
- Category
- Publish Date
- Trending Date
- Views
- Likes
- Dislikes
- Comment Count
- Tags
- Video Duration

This dataset helps analyze viewer engagement and trending behavior on YouTube.

### Dataset

The dataset used in this project is publicly available on Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/kunxue/cavideos

Due to GitHub file size limitations, the dataset is not included in this repository.

Steps to use:

1. Visit the Kaggle dataset page.
2. Download the dataset.
3. Extract the files.
4. Place the CSV file inside the `dataset/` folder.

---

## Project Objectives

The following analyses were performed:

1. Distribution of Views, Likes, Dislikes and Comments.
2. Categories with the Highest Number of Trending Videos.
3. Category with Highest Average Views.
4. Correlation Analysis of Engagement Metrics.
5. Monthly Trending Video Analysis.
6. Trending Videos by Day of Week.
7. Top 10 Channels Appearing in Trending List.
8. Videos with Highest Like-to-View Ratio.
9. Impact of Video Duration on Views.
10. Relationship Between Title Length and Views.
11. Most Frequently Used Tags in Trending Videos.
12. Effect of Title Length Categories on Engagement.
13. Engagement Metrics Across Different Video Durations.

---

## Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from wordcloud import WordCloud
