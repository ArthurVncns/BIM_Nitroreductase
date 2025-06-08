# Exploration of Nitroreductase Protein Sequence Datasets for Generative Modeling

## Description

Nitroreductases are a class of enzymes that play a crucial role in the reduction of nitro compounds, which are commonly found in various environmental pollutants and pharmaceutical agents. These enzymes are of significant interest due to their potential applications in bioremediation, drug metabolism, and synthetic biology. Understanding the structural and functional diversity of nitroreductases is essential for harnessing their potential in various biotechnological applications.

The primary objective of this project is to explore the sequence space of nitroreductases using advanced bioinformatics techniques. By leveraging machine learning and generative models, we aim to generate novel nitroreductase sequences that retain the functional characteristics of natural sequences. This approach not only enhances our understanding of these enzymes but also opens up new avenues for designing custom nitroreductases with tailored properties.

## Project Structure

- `.idea/` - Configuration files for JetBrains IDE projects.
- `.ipynb_checkpoints/` - Checkpoints for Jupyter notebooks.
- `data/` - Directory containing data used in the project.
- `figures/` - Directory for storing generated figures and plots.
- `notebooks/` - Directory containing Jupyter notebooks.
  - `BIM_project.ipynb` - The main notebook with all the project code.
- `scripts/` - Additional scripts used in the project.
- `.DS_Store` - macOS configuration file.
- `Project_NETTI_PEINETTI_Nitroreductase_.pdf` - Additional project documentation.
- `Projet_BIM.pdf` - Final report.

## Project Content

1. **Data Collection and Pre-processing**: We gather and align nitroreductase sequences using HMMER, a powerful tool for sequence alignment.
2. **Data Exploration**: We use dimensionality reduction techniques such as Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE), as well as clustering methods like K-means to identify patterns and groupings within the data.
3. **Development and Training of a Variational Autoencoder (VAE)**: A type of generative model capable of learning the underlying distribution of the input data. The VAE is trained to reconstruct and generate new nitroreductase sequences.
4. **Analysis of Generated Sequences**: The generated sequences are subjected to rigorous analysis to ensure their quality and similarity to natural sequences.
5. **Classification Techniques**: We employ classification techniques such as Logistic Regression and Random Forest to classify the generated sequences and assess their functional properties.

## Dependencies

List of libraries and tools required to run the project:

- Python 3.12
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- PyTorch
- Matplotlib
- Seaborn
- HMMER

## Authors

- Arthur Vincens
- Sofia Terki