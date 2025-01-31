# AxoWise User Guide

## Overview
The **User Guide** provides a step-by-step walkthrough of how to use AxoWise to analyze biological networks, detect communities, and extract functional insights using AI-supported techniques.

## Table of Contents
1. [Input Table: Listing Proteins](#input-table-listing-proteins)
2. [Detecting Protein Communities with Protein Network](#detecting-protein-communities-with-protein-network)
3. [Functional Exploration with Function Network](#functional-exploration-with-function-network)
4. [Extracting Relevant Knowledge from Publications](#extracting-relevant-knowledge-from-publications)
5. [AI-Supported Knowledge Extraction](#ai-supported-knowledge-extraction)

## 1. Input Table: Listing Proteins
To begin an analysis, users need to provide an **input table** that lists proteins of interest.
- Format: The table should be in CSV or TSV format.
- Required columns:
  - `Protein_ID`: Unique identifier for the protein.
  - `Protein_Name`: Common or scientific name.
  - `Source`: Data source (e.g., UniProt, KEGG).
- Example Input Table:
  
  | Protein_ID | Protein_Name  | Source  |
  |------------|--------------|---------|
  | P12345     | ExampleProt1 | UniProt |
  | Q67890     | ExampleProt2 | KEGG    |
  
## 2. Detecting Protein Communities with Protein Network
AxoWise enables users to identify **protein communities** based on network connections.
- The **protein network** is constructed using interaction data.
- Algorithms used for community detection include:
  - Louvain clustering
  - Label Propagation
  - Modularity-based approaches
- The result shows clusters of related proteins that may be functionally associated.

## 3. Functional Exploration with Function Network
After detecting protein communities, AxoWise allows for **functional exploration** through a function network:
- Functional terms (e.g., Gene Ontology terms) are linked to proteins.
- The function network visualizes relationships between biological functions.
- Helps in understanding functional modules within detected protein communities.

## 4. Extracting Relevant Knowledge from Publications
AxoWise integrates literature mining to extract relevant knowledge.
- Uses **matching abstracts** from biological publications.
- Retrieves abstracts linked to proteins or functional terms.
- Helps users explore relevant scientific literature automatically.

## 5. AI-Supported Knowledge Extraction
AxoWise leverages **AI models** to enhance knowledge extraction:
- **Named Entity Recognition (NER)** for identifying key biological terms.
- **Semantic Similarity Analysis** to find related studies.
- **Topic Modeling** to categorize literature into functional themes.
- AI-powered summarization to highlight key insights from scientific texts.

## Summary
This guide provides a structured approach to leveraging AxoWise for:
✔ Protein community detection
✔ Functional network exploration
✔ Literature mining
✔ AI-supported insights

For further details, refer to individual sections or visit the [AxoWise GitHub Repository](https://github.com/BackofenLab/AxoWise).

