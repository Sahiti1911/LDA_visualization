# 📊 LDA Topic Modeling & Visualization

![LDA Visualization](https://miro.medium.com/max/1200/1*q-7AbUncfYb5bbHe4T3P3g.png)

## 🔍 Overview
This project applies **Latent Dirichlet Allocation (LDA)** to analyze topics in the **NIPS Papers Dataset** and visualizes the extracted topics in an interactive manner. The dataset contains research papers from the prestigious Neural Information Processing Systems (NIPS) conference, making it a valuable resource for analyzing trends in machine learning research.

## 📌 Dataset
- **Source:** [Kaggle - NIPS Papers Dataset](https://www.kaggle.com/datasets/benhamner/nips-papers?resource=download)
- **Contents:** Research papers from 1987 to 2016, containing abstracts, titles, authors, and full-text data.

## 🚀 Features
- **Preprocesses text data**: Tokenization, stopword removal, and lemmatization.
- **Performs LDA topic modeling** to extract latent topics from research papers.
- **Visualizes topics interactively** using `pyLDAvis`.
- **Generates word clouds** to illustrate top words per topic.
- **Explores trends over time** using topic distribution analysis.

## 🛠 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/lda-visualization.git
cd lda-visualization
pip install -r requirements.txt
```

## 📜 Usage
### Running the Project
Run the Jupyter Notebook:

```bash
jupyter notebook "topic Modelling (Nips Dataset).ipynb"
```

Or execute the script to generate visualizations:

```bash
python lda_visualization.py
```

### Using the Visualizations
- Open the `pyLDAvis` interactive plot to explore topic distributions.
- Check the generated word clouds for a summary of each topic.
- Analyze the trends of machine learning research over the years.

## 📊 Example Output
**LDA Interactive Visualization:**
![pyLDAvis Example](https://github.com/user-attachments/assets/9aad95fd-1193-4099-a6d9-8b82eeab3be1)

**Word Cloud of Topics:**
![Word Cloud Example](https://github.com/user-attachments/assets/9c8b370f-8a22-4767-9fb8-82238b69ace3)


## 📖 References
- Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). *Latent Dirichlet Allocation*.
- Kaggle NIPS Dataset: https://www.kaggle.com/datasets/benhamner/nips-papers
- `gensim`, `pyLDAvis`, `matplotlib`, `seaborn`

## 🤝 Contributing
Pull requests are welcome! If you encounter any issues, feel free to open an issue.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
⭐ If you find this project useful, give it a star on GitHub! ⭐
