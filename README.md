# Persistent quaternary ammonium compounds in Chinese estuaries as key drivers of environmental resistome beyond antibiotics
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8305808.svg)](https://doi.org/10.5281/zenodo.8305808)
<p align="left">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Python-3776AB.svg?style&logo=Python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/github/license/WestonSu/Antimicrobials?style&color=5D6D7E" alt="GitHub license" />
</p>


---
## 📂 Repository Structure

<details closed><summary>Graph Attention Network (GAT)</summary>

| File                                                                            | Summary                                |
| ---                                                                             | ---                                    |                         
| [Antibacterials.ipynb](https://github.com/WestonSu/Antimicrobials/blob/main/GAT/code/Antibacterials.ipynb)                                 | The results for model training, evaluation, and prediction using GAT can be step-by-step reproduced by running 'Antibacterials.ipynb'.|                                             
| [AttentiveLayers.py](https://github.com/WestonSu/Antimicrobials/blob/main/GAT/code/AttentiveFP/AttentiveLayers.py)                         | Defines the deep learning model for recognizing chemical fingerprints.|
| [Featurizer.py](https://github.com/WestonSu/Antimicrobials/blob/main/GAT/code/AttentiveFP/Featurizer.py)                                   | Extracts features of chemical molecules to serve as inputs for the deep learning model.|
| [getFeatures.py](https://github.com/WestonSu/Antimicrobials/blob/main/GAT/code/AttentiveFP/getFeatures.py)                                 | Extracts features from SMILES strings of chemical molecules, transforming them into model inputs.|
| [hyper_parameter_search.py](https://github.com/WestonSu/Antimicrobials/blob/main/GAT/code/hyper_parameter_search.py)                       | Search for the optimal model hyperparameters.|

</details>

<details closed><summary>Directed Message Passing Neural Networks (D-MPNN)</summary>

| File                                                                            | Summary                                |
| ---                                                                             | ---                                    |
| [DMPNN.ipynb](https://github.com/WestonSu/Antimicrobials/blob/main/DMPNN.ipynb) |The results for model training, evaluation, and prediction using DMPNN can be step-by-step reproduced by running 'DMPNN.ipynb'.|

</details>

<details closed><summary>eXtreme Gradient Boosting (XGBoost)</summary>

| File                                                                                        | Summary                                  |
| ---                                                                                         | ---                                      |
| [XGBoost.ipynb](https://github.com/WestonSu/Antimicrobials/blob/main/XGBoost/XGBoost.ipynb) | The results for model training, evaluation, and prediction using XGBoost can be step-by-step reproduced by running 'XGBoost.ipynb'.|
| [Anti.txt](https://github.com/WestonSu/Antimicrobials/blob/main/XGBoost/Anti.txt)           | Prompt exceeds max token limit: 5897.    |
| [Anti_MD.txt](https://github.com/WestonSu/Antimicrobials/blob/main/XGBoost/Anti_MD.txt)     | Prompt exceeds max token limit: 1798445. |

</details>

<details closed><summary>K-Nearest Neighbors (KNN): Model’s applicability domain</summary>

| File                                                                                                                               | Summary                                 |
| ---                                                                                                                                | ---                                     |
| [Applicability_Domain.ipynb](https://github.com/WestonSu/Antimicrobials/blob/main/Applicability_Domain/Applicability_Domain.ipynb) | Prompt exceeds max token limit: 5171.   |
| [training_set.sdf](https://github.com/WestonSu/Antimicrobials/blob/main/Applicability_Domain/training_set.sdf)                     | Prompt exceeds max token limit: 307209. |
| [test_set.sdf](https://github.com/WestonSu/Antimicrobials/blob/main/Applicability_Domain/test_set.sdf)                             | Prompt exceeds max token limit: 212299. |

</details>

---
## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the Antimicrobials repository:
```sh
git clone https://github.com/WestonSu/Antimicrobials
```

2. Change to the project directory:
```sh
cd Antimicrobials
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```
---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Antimicrobials](#-running-Antimicrobials)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

HTTPStatus Exception: 429

---

## 📦 Features

HTTPStatus Exception: 429

---





### 🤖 Running Antimicrobials

```sh
python main.py
```

### 🧪 Tests
```sh
pytest
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

---

## Citations <a name="citations"></a>  

We ask users to cite ****** directly by referencing the following paper:

Su, W. et al. Persistent quaternary ammonium compounds in Chinese estuaries as key drivers of environmental resistome beyond antibiotics.

*** also builds on a number of other projects, ideas, and software including ******. Please consider citing the following full list of papers when relevant:  

1. Stokes, J. M. et al. A deep learning approach to antibiotic discovery. Cell 180, 688–702.e613 (2020).
2. Yang, K. et al. Analyzing learned molecular representations for property prediction. J. Chem. Inf. Model. 59, 3370–3388 (2019).
3. Veličković, P. et al. Graph attention networks. Preprint at https://arxiv.org/abs/1710.10903 (2017).
4. Xiong, Z. et al. Pushing the boundaries of molecular representation for drug discovery with the graph attention mechanism. J. Med. Chem. 63, 8749–8760 (2020).
5. Chen, T. & Guestrin, C. XGBoost: a scalable tree boosting system. In Proc. 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 785–794 (Association for Computing Machinery, 2016)
6. Lundberg, S. M. et al. From local explanations to global understanding with explainable AI for trees. Nat. Mach. Intell. 2, 56–67 (2020).



