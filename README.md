# 🎶 **Spotify Data Clustering and Analysis - Sigmoid ONG**

This project focuses on analyzing Spotify data from all members of the **Sigmoid ONG**. The main objective is to uncover insights into music preferences, track skipping behavior, and overall listening patterns using clustering techniques and other data analysis methods.

## 📁 **Project Structure**

### 1. **Clustering Analysis**
   - **Objective:** Group users based on their music preferences using unsupervised learning techniques.
   - **Dataset:** `clustering_means.csv`
   - This component involves using **KMeans clustering** and evaluating cluster quality using **silhouette scores** to identify distinct music preference groups within the Sigmoid ONG members.

### 2. **Skipping Tracks Analysis**
   - **Objective:** Analyze the skipping behavior of tracks to understand what music listeners tend to skip.
   - **Datasets:** `Sigmoid_Spotify_Data_2.csv`, `duration.csv`
   - In this section, a new dataframe is created to analyze the duration of tracks and correlate it with track skipping behavior.

### 3. **Mood Plots**
   - **Objective:** Analyze mood trends across different tracks listened to by users in Sigmoid.
   - This component uses the Spotify API to gather mood-related data (such as danceability, energy, and valence) for the tracks and visualize these trends.

### 4. **Top Artists and Tracks**
   - **Objective:** Identify the top 5 most listened-to artists and tracks.
   - Using the data from Spotify, the analysis extracts the top 5 most popular artists and songs among Sigmoid members.

## 📊 **Results and Insights**
- The clustering revealed distinct user groups with varying preferences for music genres and styles.
- Track skipping behavior provided insight into what types of music or features users tend to avoid.
- Mood trends showed clear patterns in energy and valence that corresponded with users' listening habits.
- The top 5 artists and tracks helped highlight popular trends within the group.

