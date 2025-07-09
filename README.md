# 📸 Instagram Data EDA Analysis

A comprehensive exploratory data analysis (EDA) project focused on understanding user engagement, content patterns, and performance trends on Instagram. This project aims to reveal actionable insights that can inform content strategies and user behavior trends.

---

## 📂 Project Overview

This notebook dives deep into Instagram performance data to:

- Examine content engagement trends.
- Identify the best-performing post types.
- Explore factors driving likes, reach, impressions, and saves.
- Visualize patterns using insightful graphs and statistics.

---

## 🔍 Goals of the Analysis

- Understand how **content types** affect reach and engagement.
- Discover which **hashtags, captions, or days** generate the most impact.
- Correlate **impressions, follows, shares**, and other metrics.
- Provide actionable insights for better content performance on Instagram.

---

## 📊 Key Insights from EDA

- **Correlation heatmaps** between metrics like likes, saves, shares, impressions, reach, etc.
- **Bar charts** to show most engaging content types.
- **Box plots and line graphs** revealing engagement variability and trends over time.
- **Feature importance** derived from engagement metrics.

📈 **Tools Used:**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `plotly`

---

## 🧾 Dataset Columns

| Feature           | Description                                             |
|-------------------|---------------------------------------------------------|
| Hashtags Used     | List of hashtags used in a post                         |
| Caption           | Caption text of the post                                |
| Likes             | Number of likes received                                |
| Impressions       | Total times the post was seen                           |
| Reach             | Unique users who saw the post                           |
| Saved             | Number of users who saved the post                      |
| Shares            | Number of times the post was shared                     |
| Profile Visits    | Profile visits from the post                            |
| Follows           | New follows from the post                               |
| Content Type      | Type of post (Reel, Image, Carousel, etc.)              |
| Date              | Posting date                                            |

📌 *This is a sample or synthetic dataset used for educational purposes.*

---

## 📌 Results Summary

- **Carousel posts** often generate more saves and shares.
- **High impression posts** don’t always translate to high engagement—**captions matter**.
- Engagement is **strongly correlated** with saves and shares, not just likes.
- **Post timing** and **content type** significantly impact profile visits and follows.

---

## 🚀 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/sahil007707/instagram-eda-analysis.git
   cd instagram-eda-analysis
