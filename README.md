
# PATCRdb: Database of TCRs from data mining patent documents.

2022.12.21 (Version 1)

University of Southern Denmark

Contact: Yoona Lee (bootyoona@gmail.com); Konrad Krawczyk (konrad@sciride.org)



## [Introduction]

PATCRdb comprises t-cell receptor (TCR) sequences found in patent documents from three patent sources: United States Patent and Trademark Office(USPTO FT, USPTO PSIPS), World Intellectual Property Organization (WIPO), DNA Data Bank of Japan (DDBJ).

Current release of the database is December 2022.

The database currently covers 26,391 TCR sequences from 495 patent families.

It is created inspired by the protocol of data mining patented antibody sequences described [here](https://pubmed.ncbi.nlm.nih.gov/33722161/)



## [Database Contents]

### 1. TCR Sequence DB 
PATCRdb_sequence.csv

- **Original sequence**: The sequence in the form ANARCI received it.
- **Variable region sequence**: After processing the original sequence via ANARCI/IgBLAST, only the variable portion.
- **Sequence name**: name of the patent and the sequence number where the sequence was identified.
- **Families**: European Patent Office (EPO)-defined families, that provide an equivalence class for patent documents with different numbers across different jurisdictions (to be taken as a unique identifier of a patent document).



### 2. TCR Patent Metadata DB 
PATCRdb_metadata.csv

- **Title**: The title of the patent document.
- **Abstract**: The abstract of the patent document.
- **Family**: The EPO family assigned to the document.
- **Applicants**: The applicants on the patent document, e.g. company names.
- **Inventors**: The people cited as inventors of the given work.
- **Dates**: List of dates associated with the document, as there can be several in a lifetime of a patent document.
- **Classes**: The Cooperative Patent Classification (CPC) schemes.

