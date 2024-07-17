# Replication materials for "A global perspective on social stratification in science"

This data comprises the number of Scopus authors by OECD macro field of science, country, authors' inferred gender, author's academic age, and bibliometric class. The sum of the column counts is: 8,225,368. 

**Please note**: there are 554 rows in the table indicated with "NA" where some of these variables are missing.

## Paper metadata
**Title**: A global perspective on social stratification in science

**Authors**: Aliakbar Akbaritabara (Max Planck Institute for Demographic Research, Rostock, Germany), Andres F. Castro Torres (Max Planck Institute for Demographic Research, Rostock, Germany; Center for Demographic Studies, Barcelona, Spain), Vincent Larivière (Université de Montréal, Montréal, Canada)

**Corresponding author and email**: Aliakbar Akbaritabar, akbaritabar@demogr.mpg.de

**Abstract**: 
To study stratification among scientists, we reconstruct the career-long trajectories of 8.2 million scientists worldwide using 12 bibliometric measures of productivity, geographical mobility, collaboration, and research impact. While most previous studies examined these variables in isolation, we study their relationships using Multiple Correspondence and Cluster Analysis. We group authors according to their bibliometric performance and academic age across six macro fields of science, and analyze co-authorship networks and detect collaboration communities of different sizes. We found a stratified structure in terms of academic age and bibliometric classes, with a small top class and large middle and bottom classes in all collaboration communities. Results are robust to community detection algorithms used and do not depend on authors’ gender. These results imply that increased productivity, impact, and collaboration are driven by a relatively small group that accounts for a large share of academic outputs, i.e., the top class. Mobility indicators are the only exception with bottom classes contributing similar or larger shares. We also show that those at the top succeed by collaborating with various authors from other classes and age groups. Nevertheless, they are benefiting disproportionately from these collaborations which may have implications for persisting stratification in academia.

**Keywords**:
bibliometric data; research productivity; scientific collaboration; scientific mobility; scholarly impact and citations

**Paper's DOI**: [https://doi.org/10.1057/s41599-024-03402-w](https://doi.org/10.1057/s41599-024-03402-w)

**Dataset's DOI**:
[![DOI](https://zenodo.org/badge/819806358.svg)](https://zenodo.org/doi/10.5281/zenodo.12527943)


**Journal**: Nature Humanities and Social Sciences Communications

**How to cite**:

```
Akbaritabar, A., Castro Torres, A.F. & Larivière, V. A global perspective on social stratification in science. Humanit Soc Sci Commun 11, 914 (2024). https://doi.org/10.1057/s41599-024-03402-w

```

```bibtex

@article{akbaritabar2024GlobalPerspectiveSocial,
  title = {A Global Perspective on Social Stratification in Science},
  author = {Akbaritabar, Aliakbar and Castro Torres, Andr{\'e}s Felipe and Larivi{\`e}re, Vincent},
  year = {2024},
  month = jul,
  journal = {Humanities and Social Sciences Communications},
  volume = {11},
  number = {1},
  pages = {1--10},
  publisher = {Palgrave},
  issn = {2662-9992},
  doi = {10.1057/s41599-024-03402-w},
  abstract = {To study stratification among scientists, we reconstruct the career-long trajectories of 8.2 million scientists worldwide using 12 bibliometric measures of productivity, geographical mobility, collaboration, and research impact. While most previous studies examined these variables in isolation, we study their relationships using Multiple Correspondence and Cluster Analysis. We group authors according to their bibliometric performance and academic age across six macro fields of science, and analyze co-authorship networks and detect collaboration communities of different sizes. We found a stratified structure in terms of academic age and bibliometric classes, with a small top class and large middle and bottom classes in all collaboration communities. Results are robust to community detection algorithms used and do not depend on authors' gender. These results imply that increased productivity, impact, and collaboration are driven by a relatively small group that accounts for a large share of academic outputs, i.e., the top class. Mobility indicators are the only exception with bottom classes contributing similar or larger shares. We also show that those at the top succeed by collaborating with various authors from other classes and age groups. Nevertheless, they are benefiting disproportionately from these collaborations which may have implications for persisting stratification in academia.},
  copyright = {2024 The Author(s)},
  langid = {english},
  keywords = {Science,Sociology,technology and society}
}


```

## Description of the data
The dataset contains SIX columns as follows:

**base_oecd**: Six OECD macro fields of science such as "Agricultural_Sciences", "Engineering_and_Technology", "Humanities", "Medical_and_Health_Sciences", "Natural_Sciences", "Social_Sciences", and "NA" (for missing)  

**base_countr**: Country name (see details in the paper)

**gender**: Inferred gender based on the name of the author; it includes "fem" for "female", "mal" for "male", and "unkn" for "uknown" gender who are the authors whose gender could not be determined. Please see methods section for the details.

**basc_acadag**: Academic age grouped into age groups such as "10-14", "15-20", "2-5", "21-25", "6-9", "One", and "NA" (for missing age group)

**cluster6**: Bibliometric class assigned to authors aggregated at the country level as reported in the paper such as "BT", "ML", "LW", "MH", "TP", "HG", and "NA" (for missing). Please see methods section in the paper for the details.

**count**: Number of unique authors

For queries, contact: akbaritabar@demogr.mpg.de
