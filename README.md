# 💊 AI-Driven Drug Repositioning Using Graph Neural Networks

> Research-oriented healthcare AI system that leverages Graph Neural Networks (GNNs) and biomedical knowledge graphs to identify potential drug-disease associations for drug repositioning.

## 📌 Overview

Drug repositioning (drug repurposing) is the process of identifying new therapeutic uses for existing drugs. Traditional drug discovery is expensive, time-consuming, and often requires more than a decade of research and clinical validation.

This project proposes an AI-driven framework that integrates large-scale biomedical datasets into a heterogeneous knowledge graph and applies Graph Neural Networks (GraphSAGE) to predict novel drug-disease relationships. By learning complex interactions among drugs, proteins, and diseases, the system assists researchers in identifying promising candidates for drug repurposing.

This work was developed as a research project and resulted in a published academic paper titled:

**"AI-Driven Drug Repositioning Using Graph Neural Networks"**

---

## 🎯 Research Objectives

* Build a large-scale biomedical knowledge graph.
* Integrate heterogeneous biomedical datasets.
* Learn meaningful graph embeddings using Graph Neural Networks.
* Predict novel drug-disease associations.
* Support data-driven drug repositioning and healthcare research.

---

## 🧬 Datasets Used

### DrugBank

* 9,875 drugs
* 5,096 proteins
* 26,766 drug-protein interactions

### STRING Database

* 472,588 high-confidence protein-protein interactions

### DisGeNET

* 38,959 protein-disease associations

The integrated graph contains more than **500,000 biological relationships** connecting drugs, proteins, and diseases.

---

## 🏗 System Architecture

### Data Collection

* DrugBank XML parsing
* STRING interaction network extraction
* DisGeNET API integration

### Data Preprocessing

* Data cleaning
* Duplicate removal
* Identifier mapping
* Feature initialization

### Knowledge Graph Construction

* Drug Nodes
* Protein Nodes
* Disease Nodes
* Multi-relational edges

### Graph Neural Network Pipeline

* 3-Layer Heterogeneous GraphSAGE Encoder
* Relation-specific message passing
* 2-Layer MLP Decoder
* Drug-Disease Link Prediction

---

## 🚀 Technologies Used

* Python
* PyTorch
* PyTorch Geometric
* Graph Neural Networks (GNN)
* GraphSAGE
* DrugBank
* STRING Database
* DisGeNET API
* NumPy
* Pandas
* Jupyter Notebook

---

## 📊 Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 86.8% |
| Precision | 82.6% |
| Recall    | 93.4% |
| F1-Score  | 87.7% |
| ROC-AUC   | 0.942 |

The model demonstrated strong predictive capability for identifying potential drug-disease associations and achieved excellent discrimination performance with a ROC-AUC of 0.942.

---

## 🔬 Key Contributions

* Developed a heterogeneous biomedical knowledge graph containing over 500,000 biological relationships.
* Implemented a GraphSAGE-based Graph Neural Network for drug-disease link prediction.
* Integrated multiple biomedical datasets into a unified learning framework.
* Designed an interpretable drug recommendation pipeline based on biological pathways.
* Evaluated the model using standard classification and ranking metrics.

---

## 🌍 Applications

* Drug Repositioning
* Drug Discovery
* Precision Medicine
* Biomedical Research
* Clinical Decision Support Systems
* Healthcare Analytics

---

## 📄 Publication

**Rushikesh Vinayak Jagtap, Srija Paul Chowdhury, Mathan Kumar Mounagurusamy**

*"AI-Driven Drug Repositioning Using Graph Neural Networks"*

Department of Computing Technologies, SRM Institute of Science and Technology.

---

## 👩‍💻 Author

**Srija Paul Chowdhury**

B.Tech Computer Science and Engineering
SRM Institute of Science and Technology

GitHub: https://github.com/srijaaa05

LinkedIn: https://www.linkedin.com/in/srija-paul-chowdhury-94807728a/

---

## ⭐ Future Work

* Incorporate molecular structure information.
* Explore Heterogeneous Graph Transformers (HGT).
* Integrate additional biomedical datasets.
* Develop explainable AI-based recommendation mechanisms.
* Deploy the model as an interactive healthcare research platform.
