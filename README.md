<div align="center">

<img src="Banner.png" width="100%" alt="SD-Learner Banner">

# SD-Learner

### A Meta-Learning Framework with Graph Neural Networks for Few-Shot Biomedical Graph Classification

![Research](https://img.shields.io/badge/Research-Graph%20Neural%20Networks-0A66C2)
![Meta Learning](https://img.shields.io/badge/Meta-Learning-success)
![Few-Shot Learning](https://img.shields.io/badge/Few--Shot%20Learning-blue)
![Biomedical Graphs](https://img.shields.io/badge/Domain-Biomedical%20Graphs-red)
![Repository](https://img.shields.io/badge/Repository-Research%20Showcase-black)

---

**Research Repository**

Architecture • Methodology • Experimental Results

</div>

---

# 📌 Research Status

This repository presents the **architecture, research methodology, and selected experimental visualizations** of **SD-Learner (Single Domain Learner)**, a Meta-Learning framework developed for **Few-Shot Biomedical Graph Classification**.

> **Note**
>
> The accompanying manuscript has **not yet been formally published**. Therefore, the complete implementation, trained models, and manuscript are intentionally withheld until completion of the publication process.

---

# 📖 Overview

SD-Learner (Single Domain Learner) is a research framework developed to investigate **Few-Shot Biomedical Graph Classification** using **Meta-Learning** and **Graph Neural Networks**.

The project explores learning strategies capable of improving graph classification performance in scenarios where only a limited number of labeled graph samples are available. The research focuses on developing a robust framework for graph representation learning while addressing the challenges associated with low-data biomedical environments.

This repository serves as the official research repository for SD-Learner, presenting selected research assets and experimental outcomes while protecting unpublished scientific contributions during the peer-review process.

---

# 🎯 Motivation

Graph Neural Networks have demonstrated significant success across numerous biomedical applications, including molecular property prediction, drug discovery, biological network analysis, and graph-based healthcare research.

Despite these advances, obtaining large, well-annotated biomedical graph datasets remains challenging. Traditional deep learning approaches often require substantial labeled data, making them less effective in few-shot scenarios.

SD-Learner investigates Meta-Learning techniques combined with Graph Neural Networks to improve learning capability under limited-data conditions while maintaining strong graph representation quality and reliable classification performance.

The proposed research aims to contribute toward more effective graph learning solutions for biomedical applications where labeled data is scarce.

---

# ✨ Research Contributions

This repository showcases several research components developed during the SD-Learner project, including:

- Proposed **SD-Learner** research framework for Few-Shot Biomedical Graph Classification.
- High-level research methodology illustrating the complete research workflow.
- Proposed framework architecture.
- Experimental evaluation across benchmark biomedical graph datasets.
- Performance comparison using multiple evaluation metrics.
- Comprehensive ablation study demonstrating the contribution of the proposed framework components.

> **Publication Notice**
>
> Detailed technical contributions, implementation procedures, architectural innovations, mathematical derivations, and source code will be made publicly available following the official publication of the associated research paper.

---

# 📂 Repository Structure

```text
SD-Learner
│
├── assets/
│   ├── Proposed Model/
│   │     └── SD-Learner.png
│   │
│   ├── Research Methodology/
│   │     └── Research Methodology.png
│   │
│   ├── Results/
│   │     ├── Accuracy Comparison.png
│   │     ├── Precision.png
│   │     ├── Recall.png
│   │     ├── F1 Score.png
│   │     ├── AUC ROC.png
│   │     ├── Training Curves.png
│   │     └── Ablation Study.png
│   │
│   └── banner.png
│
└── README.md
```

---

# 🏗 Proposed Architecture

<p align="center">
<img src="assets/Proposed Model/SD-Learner.png" width="900">
</p>

The figure above illustrates the conceptual architecture of **SD-Learner (Single Domain Learner)**.

The proposed framework has been designed to investigate **Few-Shot Biomedical Graph Classification** by integrating modern **Meta-Learning** strategies with **Graph Neural Networks (GNNs)**.

The architecture presents the overall research workflow from graph representation learning through model optimization and evaluation. It provides a high-level visualization of the framework while intentionally omitting implementation-specific details during the peer-review process.

The complete architectural design, implementation details, and technical discussion will be made publicly available following the official publication of the associated manuscript.

---

# 🔬 Methodology

<p align="center">
<img src="assets/Research Methodology/Research Methodology.png" width="900">
</p>

The SD-Learner research follows a systematic methodology that encompasses the complete lifecycle of the proposed framework, from problem formulation to experimental evaluation.

The methodology consists of several interconnected research stages, including:

- Problem Definition
- Dataset Preparation
- Model Development
- Experimental Evaluation
- Performance Analysis
- Result Interpretation

Each stage contributes to the comprehensive evaluation of the proposed framework while ensuring a structured and reproducible research workflow.

> **Note**
>
> To preserve the originality of the proposed research, the detailed methodology, experimental procedures, mathematical formulations, and implementation strategies are intentionally withheld until the associated manuscript has been formally published.

---

# 🧪 Experimental Evaluation

The proposed SD-Learner framework has been evaluated through a comprehensive experimental study using benchmark biomedical graph datasets.

The evaluation investigates the performance of the framework under **Few-Shot Learning** settings and compares its behavior across multiple experimental scenarios.

## Benchmark Datasets

The experimental study utilizes publicly available benchmark datasets commonly adopted for biomedical graph classification research.

The detailed dataset descriptions and preprocessing procedures are available in the accompanying manuscript and will be released following publication.

---

## Evaluation Metrics

The performance of the proposed framework has been assessed using multiple evaluation metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score
- AUC-ROC

These metrics provide a comprehensive assessment of the framework's predictive capability across different experimental settings.

---

## Experimental Analysis

The experimental evaluation investigates several aspects of the proposed framework, including:

- Overall classification performance
- Comparative performance analysis
- Learning behavior
- Model robustness
- Component-wise contribution through ablation studies

The repository presents summarized visualizations of these experiments while reserving detailed analyses for the published manuscript.

---

# 📊 Experimental Results

The following figures present selected visualizations obtained during the experimental evaluation of SD-Learner.

These results are included to showcase the research outcomes while protecting the originality of the unpublished work.

---

## Accuracy Comparison

<p align="center">
<img src="assets/Results/Accuracy Comparison.png" width="850">
</p>

The accuracy comparison summarizes the classification performance observed during the experimental evaluation.

Detailed numerical analyses, statistical significance tests, and comparisons with existing approaches will be included in the published manuscript.

---

## Precision

<p align="center">
<img src="assets/Results/Precision.png" width="700">
</p>

The precision results provide a visual overview of the framework's predictive performance across the conducted experiments.

---

## Recall

<p align="center">
<img src="assets/Results/Recall.png" width="700">
</p>

The recall evaluation illustrates the framework's ability to correctly identify relevant graph instances during classification.

---

## F1-Score

<p align="center">
<img src="assets/Results/F1 Score.png" width="700">
</p>

The F1-Score summarizes the balance between precision and recall achieved during experimental evaluation.

---

## AUC-ROC

<p align="center">
<img src="assets/Results/AUC ROC.png" width="700">
</p>

The AUC-ROC visualization provides an additional perspective on the classification performance of the proposed framework.

---

## Training Behaviour

<p align="center">
<img src="assets/Results/Training Curves.png" width="850">
</p>

The training curves illustrate the learning behavior observed throughout the optimization process.

Training configurations, optimization strategies, and implementation details will be released after publication.

---

## Performance Comparison

The experimental evaluation compares SD-Learner against established Graph Neural Network baselines commonly used for graph classification research.

To preserve the originality of the proposed work, detailed numerical comparisons and implementation-specific analyses are intentionally omitted from this repository until the completion of the publication process.

---

# 📈 Ablation Study

<p align="center">
<img src="assets/Results/Ablation Study.png" width="850">
</p>

The ablation study investigates the contribution of the major components incorporated within the SD-Learner framework.

This analysis provides insights into the overall effectiveness of the proposed approach while highlighting the importance of individual architectural components.

Detailed interpretations and quantitative analyses are intentionally reserved for the officially published manuscript.

---

# 🏆 Key Findings

The experimental investigation demonstrates the effectiveness of the proposed SD-Learner framework for Few-Shot Biomedical Graph Classification.

The summarized findings of this research include:

- SD-Learner demonstrates competitive performance across benchmark biomedical graph classification tasks.
- The proposed framework exhibits strong learning capability under limited labeled data scenarios.
- Comprehensive experimental evaluation validates the effectiveness of the proposed learning strategy.
- Ablation analysis highlights the contribution of the major components incorporated within the framework.
- The experimental results indicate promising generalization capability for few-shot biomedical graph learning applications.

> **Note**
>
> Detailed quantitative analyses, statistical significance testing, and comprehensive discussions are intentionally reserved for the officially published manuscript.

---

# 🚀 Future Work

The SD-Learner project will continue to evolve beyond its current scope.

Future research directions include:

- Evaluation on additional biomedical graph datasets.
- Investigation of more advanced Graph Neural Network architectures.
- Integration of self-supervised graph representation learning techniques.
- Extension toward heterogeneous and dynamic graph learning.
- Large-scale evaluation across real-world biomedical applications.
- Public release of implementation resources following publication.

---

# 👥 Authors

**Raheel Khan [1]**

**Muhammad Wasim [1,2]**

**Adnan Khan [3]**

**Saad Alahmari [4]**

---

# 📄 Citation

The manuscript associated with **SD-Learner** is currently **under peer review**.

Citation information, DOI, and publication details will be added immediately after the manuscript has been officially published.

If you reference this repository before publication, please refer only to the repository itself and refrain from citing unpublished research findings.

---

# 📜 License

© All Rights Reserved.

Unless otherwise stated, all research materials contained in this repository remain the intellectual property of the respective authors.

No permission is granted to reproduce, redistribute, modify, or publish any portion of the unpublished research, including figures, methodology, implementation concepts, or experimental assets, without prior written permission from the authors.

An appropriate open-source license and implementation resources will be released following the official publication of the associated manuscript.

---

# ⚠️ Disclaimer

This repository has been created solely to showcase the progress and outcomes of the SD-Learner research project.

The visual assets included in this repository—including the proposed framework, research methodology, experimental visualizations, and ablation study—are provided for academic portfolio and research showcase purposes only.

To preserve the originality of the ongoing research, the following materials are intentionally withheld until completion of the publication process:

- Source code
- Complete implementation
- Training scripts
- Trained models
- Mathematical formulations
- Experimental protocols
- Hyperparameter configurations
- Supplementary materials
- Complete manuscript

These resources will be made publicly available following the successful publication of the associated research paper.

---

<div align="center">

### ⭐ If you find this research interesting, please consider starring this repository.

Thank you for visiting the official **SD-Learner** research repository.

Research Methodology • Proposed Framework • Experimental Evaluation • Publication Updates

</div>
