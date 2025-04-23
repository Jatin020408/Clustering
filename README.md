

## 📌 Part 1: Clustering Analysis

### 🔗 Dataset Used
- **Dataset:** Wine Quality Dataset (UCI ID: 186)
- **Goal:** Apply different clustering algorithms under various preprocessing conditions to assess their quality.

### 🛠️ Techniques Applied

- **Preprocessing Techniques:**
  - No preprocessing
  - Min-Max Normalization
  - Log Transform
  - PCA (Principal Component Analysis)
  - Log Transform + Normalization
  - Log Transform + Normalization + PCA

- **Clustering Algorithms:**
  - KMeans
  - Agglomerative (Hierarchical) Clustering
  - Mean Shift Clustering

- **Evaluation Metrics:**
  - Silhouette Score
  - Calinski-Harabasz Index
  - Davies-Bouldin Score

### ✅ How to Run

```bash
python clustering_analysis.py

```
pip install numpy pandas matplotlib seaborn datasets torch transformers
```
## 6. Output

The script will print the TOPSIS scores and display the best-ranked model:




```bash
  TOPSIS Results for Conversational Models:
                                  TOPSIS Score
microsoft/DialoGPT-small                0.7317
gpt2                                    0.6431
EleutherAI/gpt-neo-125M                 0.6014
microsoft/DialoGPT-medium               0.5272
facebook/blenderbot-400M-distill        0.1813
```
Best model based on TOPSIS analysis: microsoft/DialoGPT-small

## Author

This project was developed for an AI/ML research project on conversational models. If you have any questions, feel free to reach out!

## License

MIT License
    


