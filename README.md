----------------------
# Spotify EDA Project

This repository contains an exploratory data analysis (EDA) of a Spotify listening sessions dataset. The aim is to understand user behavior, with a particular focus on the factors influencing track skipping.

## Dataset

- The dataset contains 167,880 entries and 23 features, including session details, user actions, and track metadata.
- Features include skip flags, contextual information (playlists, shuffle), and user types (premium/free).

## Project Structure

- `spotify_eda.ipynb`: Main Jupyter notebook containing data loading, EDA, visualizations, and insight summaries.
- `README.md`: Project overview, setup guide, and documentation.

## Key Analysis Steps

1. **Data Cleaning:**
   - Checked for and confirmed no missing values or duplicates.
2. **Target Analysis:**
   - Explored target variable (`skip2`).
3. **Categorical & Numerical Analysis:**
   - Visualized and interpreted categorical and numeric features.
4. **Correlation & Insights:**
   - Used heatmaps and described feature-relationships.
   - Key findings: Premium users skip less, shuffle increases skips, session length influences skipping.

## How to Run

1. Download or clone this repository.
2. Open the notebook `spotify_eda.ipynb` in Jupyter Notebook or JupyterLab.
3. Ensure `pandas`, `matplotlib`, `seaborn`, and `numpy` are installed.
4. Execute each cell sequentially.

## Results

Bar plots, histograms, boxplots, and heatmaps reveal patterns in user behavior. See the notebook for discussion and images.

## License

This project is provided under the MIT License. Check the dataset’s terms of use before sharing or modifying the data.

---

**Contact & Contributions**:
Feel free to open issues or submit pull requests if you have ideas or spot improvements!
