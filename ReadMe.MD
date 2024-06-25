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

**DOI**: YYYYYYY-YYYYY

**Journal**: Nature Humanities and Social Sciences Communications

**How to cite**:

```
Akbaritabar, A., Castro Torres, A. F., & Larivière, V. (2023). A global perspective on the social structure of science (WP-2023-029; 0 ed., p. WP-2023-029). Max Planck Institute for Demographic Research. https://doi.org/10.4054/MPIDR-WP-2023-029

```

```bibtex

@techreport{akbaritabar2023GlobalPerspectiveSocial,
  title = {A Global Perspective on the Social Structure of Science},
  author = {Akbaritabar, Aliakbar and Castro Torres, Andr{\'e}s F. and Larivi{\`e}re, Vincent},
  year = {2023},
  month = may,
  edition = {0},
  number = {WP-2023-029},
  pages = {WP-2023-029},
  address = {Rostock},
  institution = {Max Planck Institute for Demographic Research},
  doi = {10.4054/MPIDR-WP-2023-029},
  urldate = {2023-06-10},
  copyright = {All rights reserved},
  langid = {english}
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
