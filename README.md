# xspaces-analysis-code-
 “Code for paper: Analysing Social Network Structures and Thematic Engagement on X Audio Spaces”

# X Spaces Network Analysis

This repository contains the Colab notebooks and Python scripts used in the paper:

**"Analysing Social Network Structures and Thematic Engagement on X Audio Spaces"**

## 📂 Files

| **Path**                        | **Description**                                                     |
| ------------------------------- | ------------------------------------------------------------------- |
| **notebooks/**                  | Contains Jupyter notebooks for analysis                             |
| ├── `1_network_analysis.ipynb`  | Constructs user-user graph, computes measures & small-world metrics |
| ├── `2_bipartite_network.ipynb` | Builds user-space bipartite graph & measures participation dynamics |
| └── `3_topic_alignment.ipynb`   | Aligns X API topics with TweetNLP topics using BERT + spaCy   |
| **data/**                       | Contains sample datasets for testing                                |
| ├── `sample_users.csv`          | Sample dataset for network analysis                                 |
| ├── `sample_relationships.csv`  | Sample user-user relationships                                      |
| ├── `sample_user_nodes.csv`     | Sample users for bipartite network                                  |
| ├── `sample_space_nodes.csv`    | Sample spaces for bipartite network                                 |
| └── `sample_edges.csv`          | Sample user-space participation edges                               |
| **README.md**                   | Project documentation                                               |




## ⚠️ Data Access

The dataset used in this study comes from X (Twitter) Spaces and cannot be publicly shared due to privacy restrictions.
However, you can adapt these notebooks to run on your own dataset using the provided sample files.

## ▶️ Running the Notebooks

Open any notebook in Google Colab.

> Upload the required sample data from the data/ folder.

> Run the cells to reproduce the methodology.

> For 3_topic_alignment.ipynb, install the required libraries before running:

    pip install -U sentence-transformers spacy
    python -m spacy download en_core_web_lg

## 🧾 Citation

If you use this code, please cite the following paper:

Darwish, R., Abdelmoty, A.I. & Turner, L.D.
Analysing social network structures and thematic engagement on X audio spaces.
Social Network Analysis and Mining 15, 90 (2025).
https://doi.org/10.1007/s13278-025-01516-w

## 📄 License

This project is licensed under the MIT License.
