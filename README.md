# YouTube Recommendation Diversity Analysis

This repository contains the final experimental implementation developed for my undergraduate thesis on algorithmic personalization and recommendation diversity in digital platforms.

The project investigates how different recommendation strategies affect content diversity and recommendation coverage in YouTube recommendation scenarios.

---

## 📚 Research Objective

The study evaluates how different recommendation approaches influence the diversity of recommended content using real-world YouTube trending data.

The following recommendation strategies were analyzed:

- Popularity-based recommendation
- Content similarity recommendation
- Diversity-oriented recommendation (MMR)

---

## 🧠 Methodology

The experiment was implemented using Python 3.12.

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
- Matplotlib
- Seaborn
- tqdm

---

## 📁 Project Structure

```bash
youtube-recommendation-diversity-analysis/
├── src/
│   ├── gera_ratings_youtube.py
│   └── main_youtube.py
├── data/
│   ├── USvideos.csv
│   └── metrics.csv
├── results/
├── docs/
├── requirements.txt
└── README.md
```

---

## 📂 Dataset

Public dataset used:

[YouTube Trending Dataset - Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

The experiment uses YouTube trending video data to simulate recommendation scenarios and evaluate diversity outcomes.

---

## 🚀 How to Reproduce

### 1. Clone this repository

```bash
git clone https://github.com/paulagalvao19/youtube-recommendation-diversity-analysis.git
cd youtube-recommendation-diversity-analysis
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the experiment

```bash
python src/main_youtube.py
```

### 6. Check the outputs

After execution, the generated metrics and visualizations will be available in:

```bash
data/
results/
```

---

## 📄 Related Thesis Repository

The full undergraduate thesis, including the Portuguese and English PDF versions, is available here:

[Algorithmic Personalization Analysis](https://github.com/paulagalvao19/algorithmic-personalization-analysis)

---

## 🎓 Academic Context

This project was developed as part of an undergraduate thesis in Computer Science at Universidade FUMEC.

The thesis investigates the effects of algorithmic personalization on content exposure diversity in digital platforms.

---

## 📄 License

Distributed under the MIT License.# YouTube Recommendation Diversity Analysis

This repository contains the final experimental implementation developed for my undergraduate thesis on algorithmic personalization and recommendation diversity in digital platforms.

The project investigates how different recommendation strategies affect content diversity and recommendation coverage in YouTube recommendation scenarios.

---

## 📚 Research Objective

The study evaluates how different recommendation approaches influence the diversity of recommended content using real-world YouTube trending data.

The following recommendation strategies were analyzed:

- Popularity-based recommendation
- Content similarity recommendation
- Diversity-oriented recommendation (MMR)

---

## 🧠 Methodology

The experiment was implemented using Python 3.12.

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
- Matplotlib
- Seaborn
- tqdm

---

## 📁 Project Structure

```bash
youtube-recommendation-diversity-analysis/
├── src/
│   ├── gera_ratings_youtube.py
│   └── main_youtube.py
├── data/
│   ├── USvideos.csv
│   └── metrics.csv
├── results/
├── docs/
├── requirements.txt
└── README.md
```

---

## 📂 Dataset

Public dataset used:

[YouTube Trending Dataset - Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

The experiment uses YouTube trending video data to simulate recommendation scenarios and evaluate diversity outcomes.

---

## 🚀 How to Reproduce

### 1. Clone this repository

```bash
git clone https://github.com/paulagalvao19/youtube-recommendation-diversity-analysis.git
cd youtube-recommendation-diversity-analysis
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the experiment

```bash
python src/main_youtube.py
```

### 6. Check the outputs

After execution, the generated metrics and visualizations will be available in:

```bash
data/
results/
```

---

## 📄 Related Thesis Repository

The full undergraduate thesis, including the Portuguese and English PDF versions, is available here:

[Algorithmic Personalization Analysis](https://github.com/paulagalvao19/algorithmic-personalization-analysis)

---

## 🎓 Academic Context

This project was developed as part of an undergraduate thesis in Computer Science at Universidade FUMEC.

The thesis investigates the effects of algorithmic personalization on content exposure diversity in digital platforms.

---

## 📄 License

Distributed under the MIT License.
