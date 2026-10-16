# String Datasets for "Joining Large String Collections with Jaro-Winkler Similarity"

This repository contains the benchmark datasets used in the paper:

> **[Joining Large String Collections with Jaro-Winkler Similarity](https://doi.org/10.1145/3856354)**  
> Manuel Lankes, Daniel Kocher, Daniel Schmitt, Willi Mann, Thomas Samy Dafir, Bin Shen, Yujian Xu, and Nikolaus Augsten  
> _ACM Proc. ACM Manag. Data (SIGMOD), 2027_

> [!NOTE]  
> These datasets are managed using [Git LFS](https://git-lfs.com/). Make sure you have Git LFS installed and initialized before cloning the repository to download the files properly.

## Overview

All datasets have been preprocessed:

- Exact duplicates were removed.
- Non-alphanumeric characters were stripped and all strings were converted to lowercase.
- Records were shuffled to ensure no inherent ordering.
- Formatted as plain text (`.txt`) with **one string per line**.

---

## Datasets

### 1. UK Company Names

- **Description:** A collection of UK company names.
- **Snapshot Date:** 2024-03
- **Source:** [UK Companies House](https://download.companieshouse.gov.uk/en_output.html)
- **License:** [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
- **File:** `company_names_shuffled.txt`

### 2. Job Titles

- **Description:** A collection of job titles from a wide range of job portals and recruitment platforms.
- **Snapshot Date:** 2024-08
- **Source:** [Kaggle Job Titles Dataset](https://www.kaggle.com/datasets/remcostrijdonk/7-million-job-titles-companies-locations)
- **License:** [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- **File:** `shuffled_job_titles.txt`

### 3. DBLP Datasets

- **Description:** Two datasets derived from the DBLP computer science bibliography (Monthly Snapshot, January 2023).
- **Source:** [Dagstuhl Publishing - DBLP Computer Science Bibliography](https://doi.org/10.4230/dblp.xml.2023-01-03)
- **License:** [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)

#### DBLP Authors

- **Description:** A collection of author name sequences from papers in the DBLP bibliography. Each line contains all author names for a single paper, concatenated.
- **File:** `dblp_authors.txt`

#### DBLP Titles

- **Description:** A collection of research paper titles from the DBLP bibliography.
- **File:** `dblp_titles-string.txt`

---

## Citation

If you use the dblp datasets in your research, please cite the following reference:

```bibtex
@misc{dblp.xml.2023-01-03,
    title     = {{dblp computer science bibliography -- Monthly Snapshot XML Release of January 2023}},
    author    = {dblp Team},
    doi       = {10.4230/dblp.xml.2023-01-03},
    url       = {https://doi.org/10.4230/dblp.xml.2023-01-03},
    month     = {January},
    year      = {2023},
    publisher = {Schloss Dagstuhl -- Leibniz-Zentrum f{\"u}r Informatik}
}
```
