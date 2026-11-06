# Technical Challenge | Founding Computational Biologist

This repository includes:
- PubMed_Research
  - `retrieve-pdfs.ipynb`*: jupyter notebook that downloads PDFs from PubMed and extracts their text. Uses a list of PMIDs as input and outputs a .csv report with all publication fields, and folders for PDFs, logs, and extracted text as .txt
  - `pubmed_ids.txt`: list of PMIDs to fetch PDFs
  - `PubMed_Complete_Report.csv`: report with all retrievable fields from publications. Used as input to create Publication instances in KG.
- create-kg
  - `json_to_rdflib_graph.ipynb`*: converts a file of a glycan motif from GlyGen into KG (https://www.glygen.org/motif/GGM.000001)
  - `pubs-kg.ipynb`: converts PubMed_Complete_Report.csv into KG
- test-kgs
  - `pubs-graph.owl`: graph for publications in PubMed_Complete_Report.csv
  - `motif_detail_GGM.000001.ttl`: graph for GGM.000001 motif
- Figures
  - `graphdb_glycan-motif`: shows an example of a KG for a specific glycan motif in GraphDB
  - `graphdb_publications`: shows an example of a KG for a set of publications in GraphDB
  - `kg`: shows an example of a KG for a specific publication through a diagram
  - `workflow`: basic workflow of data ingestion with sources and resources


* with chatGPT
