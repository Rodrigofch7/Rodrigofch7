# Rodrigo França

Applied economist and data scientist, and a graduate student in Computational Analysis and Public Policy at the University of Chicago. I use economics and machine learning to answer questions about cities: who pays too much property tax, what a new bus line does to the neighbourhood around it, whether privatising water made people healthier.

Most of my work is on large public datasets, and most of the difficulty is in getting them into a usable state. Records that were never machine-readable, geographies that do not line up, identifiers that disagree between sources. I care about getting the answer right and about being clear on how much the answer depends on choices I made.

Research intern at the World Bank's DECDI division, formerly DIME (Jun to Aug 2026), working on satellite imagery analysis of transit-driven construction in Dakar and on Mumbai property tax records. Research assistant at the Mansueto Institute for Urban Innovation through June 2026, returning in September 2026 to write up the archival digitisation method. Before that, two years at the Insper Cities Lab in São Paulo doing empirical urban and crime economics, mentoring students, and teaching econometrics and GIS.

## What I work on

- **Causal inference.** DiD, RDD, IV, staggered designs. First-author publication in *Utilities Policy*, second-author working paper on police body cameras in progress.
- **Machine learning on big datasets.** End-to-end pipelines, feature engineering, gradient boosting. Built a fairness audit across 1.1M NYC properties.
- **Satellite data.** Difference-in-differences on 100 m grids (Google Open Buildings, GHSL) to measure how transit changes what gets built.
- **Archival data.** OCR and NLP pipelines that turn century-old registers into tables you can actually run a regression on.
- **Policy and regulation.** Zoning, land use, property tax assessment, infrastructure policy. I read the rules alongside the data, because the rules usually explain what the data is doing.

## Selected Projects

| Project | Stack | What it does |
|---|---|---|
| [NYC Property Tax](https://github.com/Rodrigofch7/nyc_property_taxes_local) · [live](https://nycpropertytaxes.streamlit.app/) | Python · LightGBM · ETL | Two houses that are alike should pay similar tax. This checks whether that holds across 1.1M New York properties, comparing each one only against properties genuinely like it rather than a citywide average. About 43% sit more than 15% from what their closest comparables pay, on a definition of "comparable" we chose ourselves. I designed the comparison method, built the pipeline, and trained the models. |
| [Data Centers Next Door](https://github.com/Rodrigofch7/data-centers-urban-effects) · [live](https://rodrigofrancac.shinyapps.io/project-datacenter-urban-effects/) | R · Shiny · Spatial | Data centres are going up fast around Chicago. This maps 45 confirmed facilities against Zillow home values and Census household costs across 660 ZIP codes, showing what moved around each opening. Patterns, not causes. I did the scraping, geocoding, and dashboard. |
| [Water Privatisation and Health](https://www.sciencedirect.com/science/article/abs/pii/S0957178725000189?via%3Dihub) | Panel Data · DiD | In 2020 Brazil made it easier for private companies to run water systems. This paper asks whether that was a good idea, comparing matched municipalities from 1998 to 2021. Fewer hospital admissions for diarrhoeal disease among under-fives, no change in unrelated diseases, mixed across municipalities. Published in *Utilities Policy*, first author. |

## background

🇧🇷 Brazilian &nbsp;·&nbsp; 📍 Chicago, IL &nbsp;·&nbsp; 🎓 UChicago MSCAPP

**Languages:** Portuguese (native) · English (fluent) · Spanish (conversational)

[![Website](https://img.shields.io/badge/Website-rodrigofch7.github.io-B23A48?style=flat&logo=githubpages&logoColor=white)](https://rodrigofch7.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/rodrigofrancac/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-publications-lightgrey?style=flat&logo=google-scholar)](https://scholar.google.com/citations?user=6D65dqUAAAAJ&hl=pt-BR)
