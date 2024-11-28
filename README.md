# Replication kit

This repository accompanies the paper "Perspective of Software Engineering Researchers on Machine Learning Practices Regarding Research, Review, and Education" currently under review. The repository contains the data and the code to reproduce the results from the paper.

# Content

The repository contains the following files:
- The `Generation` contains the questionnaires and queries to obtain the information.
- The `Data` directory contains the data used in the paper.
    - Demographics of the interview participants
    - Initial codes for interviews, surveys, and papers
    - Harmonized codes for interviews, surveys, and papers
    - Axial codes for interviews, survey, and papers
- The `Code` contains the code used for the analysis and the plots from the paper.

# Reproducing the results

To reproduce the results from the paper, you can use the Data and code provided. 

```bash
git clone git@github.com:aieng-lab/Replication-kit-Perspective-of-SE-Researchers-on-ML-Practices.git
cd Replication-kit-Perspective-of-SE-Researchers-on-ML-Practices
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```