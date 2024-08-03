
![Logo](https://camo.githubusercontent.com/555263d5ba51af334cc6de27b11facd2f1f978729fbee6f1f67ad0078a2f675b/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f642f64392f4e6575726f6e642e706e67)
# Key Information Extraction Research

Welcome to the documentation for Key Information Extraction (KIE) problem. In this document, I will introduce my research about recent useful methods on extracting key information from documents. This is an important area in natural language processing (NLP) and computer vision.
## 1. Introduction
In an age dominated by digital information, document analysis and understanding are fundamental pillars of information retrieval and knowledge extraction. The ability to automatically process, interpret, and extract insights from documents has farreaching applications across various domains, including finance, healthcare, legal, and
administrative sectors.

Extracting key information from unstructured document images, such as historical documents, receipts, orders, and credit notes, plays a crucial role in office automation. This includes tasks like efficient archiving and compliance checking. Traditional approaches often rely on a set of templates that specify keywords and their layouts. While these methods can accurately extract key information, they are not robust against partial text recognition errors, which frequently occur. Furthermore, these methods fail to generalize to documents with unseen templates, limiting their applicability in many real-world scenarios.

To address these limitations, I am researching solutions for the Key Information Extraction (KIE) problem. As part of my research, I have investigated two datasets: a [Mobile-Captured Image Document Recognition for Vietnamese Receipts](https://www.rivf2021-mc-ocr.vietnlp.com/) and an English Invoice dataset ([FATURA](https://zenodo.org/records/8261508)). These datasets will be used to experiment with and evaluate my research methods.
## 2. Problem Formulation
### 2.1. Mobile-Captured Image Document Recognition for Vietnamese Receipts

At maximum, a receipt image is associated with 4 fields (SELLER, ADDRESS, TIMESTAMP, TOTAL_COST) annotated by human annotators.

Input and output of this task is describled as image below:


![Logo](https://lh5.googleusercontent.com/2kHHF_OEgqzXSgfPniPzJ7JGaxPWP7RKLDYNq-R07UyQ8VKZryxpFMVzYmqo0bE0AUAmm-RaYImp22P4dKxGNOekCzNjJH9GyuUnZMFR-h583inagvHHAxyAOHwQV7D16w=w1280)

Note that detected fields (text lines) are ordered by SELLER, SELLER_ADDRESS, TIMESTAMP, TOTAL_COST. If a field is missing, it is set empty in the output text.

### 2.2. English Invoice Key Information Extraction

Real-world English invoice datasets, while valuable for model training and evaluation, often suffer from significant limitations. These issues primarily revolve around limited diversity, with datasets frequently skewed towards specific domains or regions. To tackle these challenges, some authors introduce FATURA, a multi-template invoice document images dataset. This dataset exhibits a remarkable diversity in invoice layouts, aiming to significantly enhance the capabilities of models for analyzing and understanding unstructured documents.

FATURA is a synthesized dataset, which has 10000 images covering 50 templates. This dataset is public for research. However, this label of this data is not correct when I manually check. Due to resource limitations for labelling. I have pickup 500 images covering 50 templates to create data for research.





## 3. Researched Solutions
### 3.1. Vietnamese Receipts Method
### 3.2. English Invoice Solutions Method
#### 3.2.1. OCR-based Methods
##### 3.2.1.1. Graph-based pipeline
##### 3.2.1.2. LayoutLM series
#### 3.2.2. OCR-free Methods
## 4. Data Preparation
### 4.1. Data Collection
### 4.2. Data Labelling
### 4.3. Data Analysis
### 4.4. Data Splitation
## 5. Environment Setup
### 5.1 Vietnamese Receipt
### 5.2 English Invoice dataset
## 6. Experiment and Evaluations
## 7. Conclusions
## 8. Demo



## 9. References

