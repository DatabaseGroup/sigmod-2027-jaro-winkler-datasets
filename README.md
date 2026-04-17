# Datasets for the Paper "Joining Large String Collections with Jaro-Winkler Similarity"

This repository contains the datasets used in the paper "Joining Large String Collections with Jaro-Winkler Similarity".
Git LFS is used to manage the large datasets, so you will need to have Git LFS installed to access the files.

All datasets were preprocessed to remove exact duplicates and shuffled to ensure randomness.
The datasets are provided in plain text format, with one string per line.

## Datasets

### UK Company Names

- **Description**: A collection of UK company names.
- **Snapshot Date**: 2024-03
- **Source**: [UK Companies House](https://download.companieshouse.gov.uk/en_output.html)
- **License**: [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
- **File**: `company_names_shuffled.txt`

---

### Job Titles

- **Description**: A collection of job titles from a wide range of job portals and recruitment platforms.
- **Snapshot Date**: 2024-08
- **Source**: [Kaggle Job Titles Dataset](https://www.kaggle.com/datasets/remcostrijdonk/7-million-job-titles-companies-locations)
- **License**: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- **File**: `shuffled_job_titles.txt`

---

### DBLP Datasets

- **Description**: Two datasets derived from the DBLP computer science bibliography (Snapshot of January 2023)
- **Source**: [Dagstuhl Publishing - DBLP Computer Science Bibliography](https://doi.org/10.4230/dblp.xml.2023-01-03)
- **License**: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)

#### DBLP Authors

- **Description**: A collection of author names and paper titles from the DBLP computer science bibliography. Each line contains all author names off a paper, concatenated.

#### DBLP Titles

- **Description**: A collection of paper titles from the DBLP computer science bibliography.

### Citation

```bibliography
@misc{dblp.xml.2023-01-03,
    title     = {{dblp computer science bibliography – Monthly Snapshot XML Release of January 2023}},
    author    = {dblp Team},
    doi       = {10.4230/dblp.xml.2023-01-03},
    url       = {https://doi.org/10.4230/dblp.xml.2023-01-03},
    month     = {January},
    year      = {2023},
    publisher = {Schloss Dagstuhl -- Leibniz-Zentrum f{\"u}r Informatik}
}
```
