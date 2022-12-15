
PATCRdb: Database of TCRs from data mining patent documents.

Version 1. 2022.12.15

University of Southern Denmark
*contact: bootyoona@gmail.com / konrad@sciride.org



[Introduction]

PATCRdb comprises t-cell receptor (TCR) sequences found in patent documents from three patent sources: United States Patent and Trademark Office(USPTO FT, USPTO PSIPS), World Intellectual Property Organization (WIPO), DNA Data Bank of Japan (DDBJ).

Current release of the database is December 2022.

The database currently covers 23,593 TCR sequences from 496 patent families.



[Database Contents]

Both .csv files contain unique combination of the entries.


1. PATCRdb_sequence.csv

# Sequence: TCR variable region sequence found in the patent document
# Patent family: The patent family the sequence was found in (*Not identified families are left blank)
# Patent number: The patent documents the sequence was found in


2. PATCRdb_metadata.csv

(*Entries without their mention of title or applicant were removed)

# Patent family: The patent family corresponding to the patent document
# Title: Title of the patent document
# Applicant: Applicants of the patent document (*Only the primary applicant was extracted from each patent document)