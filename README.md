# Hi, I'm Jorai Thomas 👋

3rd Year Computer Science @ University of Surrey — building toward **medical data science** 
with a focus on **computational genomics**, population-aware ML, and clinically responsible AI evaluation.

---

## 🔬 What I'm building

| Project | Status |
|---|---|
| [ClinVar Variant Classifier](https://github.com/jorai-thomas/clinvar-classifier) | ✅ Complete — [Live Demo](https://clinvar-classifier-cfdyqhgeoh79yhepbrwafn.streamlit.app/) |
| Adversarial Deconfounding for Population-Aware Genomic Variant Classification | 🔄 Year 3 Dissertation |
| ACMG/AMP Clinical Variant Interpretation Tool | 📋 Planned — post-dissertation |

---

## 🧬 Research focus

Most genomic AI tools are trained on European-ancestry data and deployed on everyone.
My work investigates and corrects that bias — building models that generalise equitably
across populations, not just on the populations they were trained on.

Motivated by the NHS retirement of the race-based eGFR correction formula in 2021
and its direct equivalent in genomic variant classification.

**Core finding from ClinVar project:**
Gene-identity encoding tripled the performance gap between well-studied and understudied
genes (AUC gap +0.08 → +0.22). A CNN trained on flanking sequence context eliminated
it entirely (−0.02) — confirming sequence models generalise without inheriting database bias.

---

## 🚀 Flagship Projects

### [ClinVar Pathogenic Variant Classifier](https://github.com/jorai-thomas/clinvar-classifier) · [Live Demo](https://clinvar-classifier-cfdyqhgeoh79yhepbrwafn.streamlit.app/)
End-to-end genomic ML pipeline on 341,825 ClinVar SNVs. Four models trained and evaluated
with a full equity audit — demonstrating that sequence-based encoding eliminates gene-level
ascertainment bias. Deployed as a live Streamlit demo with real-time NCBI sequence retrieval.

### [BreastMNIST Clinical Evaluation](https://github.com/jorai-thomas/clinvar-classifier)
Logistic regression baseline vs CNN on medical imaging data. AUC 0.797 → 0.862.
Clinical-style evaluation: ROC/AUC, confusion matrices, calibration, early stopping.

### AI Coursework (COM2028)
ML methods implemented from first principles — logistic regression gradients, SGD,
k-means, numerical stability. Foundation for everything built since.

---

## 🛠 Tech Stack

**Languages:**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**ML / Data:**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)

**Bioinformatics:**

![Biopython](https://img.shields.io/badge/Biopython-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pyfaidx](https://img.shields.io/badge/pyfaidx-4B8BBE?style=for-the-badge)

**Data Formats:**

![VCF](https://img.shields.io/badge/VCF-6DB33F?style=for-the-badge)
![FASTA](https://img.shields.io/badge/FASTA-6DB33F?style=for-the-badge)

**Tools & Deployment:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📍 Research Roadmap

- ✅ BreastMNIST — clinical ML evaluation foundation
- ✅ ClinVar classifier — real genomic data, confounder audit, sequence encoding, live demo
- 🔄 Adversarial deconfounding dissertation — TCGA + 1000 Genomes, DNABERT, population-invariant features
- 📋 ACMG/AMP clinical variant interpretation tool — benchmarked against InterVar/VarSome, equity layer built in

---

## 📬 Get in Touch

jorai8.thomas@gmail.com
[LinkedIn](https://www.linkedin.com/in/jorai-thomas-cs)
