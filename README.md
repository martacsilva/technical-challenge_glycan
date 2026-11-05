# Technical Challenge | Founding Computational Biologist

This repository includes:
- PubMed_Research
  - `retrieve-pdfs.ipynb`: jupyter notebook that downloads PDFs from PubMed and extracts their text. Uses a list of PMIDs as input and outputs a .csv report with all publication fields, and folders for PDFs, logs, and extracted text as .txt
  - `pubmed_ids.txt`: list of PMIDs to fetch PDFs
  - `PubMed_Complete_Report.csv`: report with all retrievable fields from publications. Used as input to create Publication instances in KG.
- Figures
  - `graphdb_glycan-motif`: shows an example of a KG for a specific glycan motif in GraphDB
  - `kg`: shows an example of a KG for a specific publication through a diagram
  - `workflow`: basic workflow of data ingestion with sources and resources
