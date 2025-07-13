# 🎧 Spotify Song Clustering using K-Means

This project explores unsupervised learning on a large-scale music dataset from `Spotify`, containing over **1.2 million tracks**. By leveraging audio features such as danceability, energy, and tempo, the goal is to group songs into meaningful clusters and uncover hidden patterns in musical characteristics.

> Spotify Tracks Dataset (1.2M+ songs with audio features)<br>
> Original Source: <a href="https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs">Kaggle (Rodolfo Figueroa)</a><br>
> Note: I have manually deleted few columns from original dataset which were not useful & increased the dataset size significantly according to me.

---

## 📌 Objective

To cluster Spotify songs based on their audio features using `K-Means`, identify the optimal number of clusters using the `Elbow Method`, and assign intuitive names to each cluster by analyzing representative songs.

---

## 📊 Clustering Approach

- Trained **K-Means clustering** for a range of cluster values
- Applied the **Elbow Method** to determine the ideal number of clusters
- Selected representative tracks from each cluster
- Assigned **custom names** to clusters based on retrieved audio traits

---

## 📈 Results

- Successfully grouped tracks into distinct musical categories
- Provided clear visualizations of the Elbow curve and cluster distributions
- Analyzed the number of songs in each custom-named cluster to interpret the overall structure of the Spotify dataset

| Metrics | Values |
|---------|--------|
|Calinski-Harabasz Score|`~ 236753.94`|
|Davies-Bouldin Score|`~ 1.21`|
|Silhouette Score|`~ 0.30`|

---

## 📁 File Structure

```
Spotify/
│
├── Spotify-Clusters.ipynb    🔹 Jupyter notebook containing entire ML Workflow
├── Spotify-Clusters.py       🔹 Python File
└── README.md                 🔹 This file !!
```

---

## 👤 Author
Anuj Kulkarni - aka - steam-bell-92

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
