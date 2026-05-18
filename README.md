# YouTube Recommendation Diversity Analysis

This repository contains the final experimental implementation developed for my undergraduate thesis focused on algorithmic personalization and recommendation diversity in digital platforms.

The project investigates how different recommendation strategies affect content diversity and recommendation coverage within YouTube recommendation scenarios.

---

## 📚 Research Objective

The study evaluates how different recommendation approaches influence the diversity of recommended content using real-world YouTube trending data.

The following recommendation strategies were analyzed:

- Popularity-based recommendation
- Content similarity recommendation
- Diversity-oriented recommendation (MMR)

---

## 🛠️ Project Structure

```bash
youtube-recommendation-diversity-analysis/
├── src/
├── data/
├── results/
├── docs/
└── requirements.txt
```

---

## 🧠 Methodology

The experiment was implemented using Python 3.12 and the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tqdm

The main experiment executes three recommendation models:

### 1. Popularity Model
Recommendations based on global engagement metrics.

### 2. Similarity Model
Recommendations generated through content similarity profiles.

### 3. Diversity Model (MMR)
Recommendations reordered using Maximal Marginal Relevance (MMR) to maximize internal diversity.

---

## 📊 Main Results

| Model | ILD | Coverage |
|------|------|------|
| Diversity (MMR) | 0.0749 | 0.0455 |
| Popularity | 0.0565 | 0.0007 |
| Similarity | 0.0051 | 0.0119 |

The MMR-based model achieved the best balance between recommendation relevance and content diversity.

---

## 📈 Metrics Used

- Intra-List Diversity (ILD)
- Catalog Coverage
- Recommendation Diversity

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- scikit-learn
- Recommendation Systems
- Data Analysis

---

## 📂 Dataset

Public dataset used:
[YouTube Trending Dataset - Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

---

## 🎓 Academic Context

This project was developed as part of an undergraduate thesis in Computer Science focused on algorithmic personalization and recommendation system diversity.

---

## 📄 License

Distributed under the MIT License.
