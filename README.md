# AI/ML Talks & Literature Reviews

This repository is a growing collection of slide decks on advanced AI/ML topics. Each deck is a structured technical briefing that explains core ideas and architectures, clarifies assumptions and design trade-offs, and summarises how approaches are typically evaluated and compared. The collection reflects my workflow for engaging with technical material—reading and synthesising research and presenting it clearly for an ML audience.

- `Vision Transformers in Medical Imaging.pdf` *(Slides)*: Covers the traditional CNN pipeline, the attention mechanism, and the ViT architecture; includes a structured ViT vs. CNN comparison and an overview of ViT usage in medical image analysis. Highlights the two most common adoption patterns — segmentation and classification — illustrated with a ViT-based hybrid example (TransUNet). Concludes with advantages/challenges of ViTs in medicine and future research directions.
  
- `Graph Neural Networks in Medical Imaging.pdf` *(Slides)*: Introduces GNNs as models for graph-structured data and motivates their relevance for modelling anatomical and functional networks with irregular, relational structure (e.g., connectivity patterns, lesions, vessels). Covers the core GNN architecture via message passing and summarises common GNN variants (GCN, GAT, GraphSAGE). Includes a case study of U-GNN (architecture + reported results) and closes with an overview of applications of GNNs in medical imaging.
  
- `Deep Learning for HCC Histology Prognosis (Paper Review).pdf`: Reviews a paper that uses deep learning to quantify histologic tumour differentiation in hepatocellular carcinoma and evaluate its prognostic value. Covers the study setup (retrospective cohort; digitised slides including H&E, reticulin and IHC), the modelling pipeline (tumour segmentation and automated extraction of differentiation-related features), and the survival-analysis framework used for evaluation (Cox models with LASSO feature selection, bootstrap validation, and C-index reporting across clinical endpoints).

  
## Repository Structure
```text
ML_literature_review_slides/
├── Vision Transformers in Medical Imaging.pdf
├── Graph Neural Networks in Medical Imaging.pdf
├── Deep Learning for HCC Histology Prognosis (Paper Review).pdf
└── README.md
```
