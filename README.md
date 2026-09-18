# Rodrigo França

Applied economist and data scientist, and a graduate student in Computational Analysis and Public Policy at the University of Chicago. I combine econometrics and machine learning to study how cities tax property, house people, and move them around, usually on questions where the policy conclusion depends on whether an effect is real.

Most of my work runs on large administrative datasets, and a good share of the difficulty is getting them into a usable state: records that were never machine-readable, geographies that do not align, identifiers that disagree between sources. I try to be equally clear about what a result shows and about how much it depends on choices I made along the way.

Research intern at the World Bank's DECDI division, formerly DIME (Jun to Aug 2026), working on satellite imagery analysis of transit-driven construction in Dakar and on Mumbai property tax records. Research assistant at the Mansueto Institute for Urban Innovation through June 2026, returning in September 2026 to write up the archival digitisation method. Before that, two years at the Insper Cities Lab in São Paulo on empirical urban and crime economics, mentoring students and teaching econometrics and GIS.

## What I work on

- **Causal inference.** Difference-in-differences, regression discontinuity, IV, staggered designs. First-author publication in *Utilities Policy*, second-author paper on police body cameras under review.
- **Machine learning at scale.** End-to-end pipelines, feature engineering, gradient boosting. Built a horizontal-equity audit across 1.1M NYC properties.
- **Remote sensing.** Difference-in-differences on 100 m satellite grids (Google Open Buildings, GHSL) to measure how transit reshapes the built environment.
- **Archival data.** OCR and NLP pipelines that turn century-old registers into analysis-ready panels.
- **Policy and regulation.** Zoning, land use, property tax assessment, infrastructure policy. I read the rules alongside the data, because the rules usually explain what the data is doing.

## Selected Projects

| Project | Stack | What it does |
|---|---|---|
| [NYC Property Tax](https://github.com/Rodrigofch7/nyc_property_taxes_local) · [live](https://nycpropertytaxes.streamlit.app/) | Python · LightGBM · ETL | Tests whether New York's assessment roll satisfies horizontal equity, measuring each of 1.1M properties against a peer group rather than a citywide benchmark. Roughly 43% sit more than 15% from their peer-group median, on a peer definition and threshold we set ourselves. I designed the peer-group methodology, built the pipeline, and trained the models. |
| [Data Centers Next Door](https://github.com/Rodrigofch7/data-centers-urban-effects) · [live](https://rodrigofrancac.shinyapps.io/project-datacenter-urban-effects/) | R · Shiny · Spatial | Matches 45 confirmed Chicago-area data centres against ZIP-level Zillow home values and Census household costs across 660 metropolitan ZIPs, examining what moved around each opening. Descriptive rather than causal. I did the scraping, geocoding, and dashboard. |
| [Water Privatisation and Health](https://www.sciencedirect.com/science/article/abs/pii/S0957178725000189?via%3Dihub) | Panel Data · DiD | Asks whether Brazil's earlier water privatisations justified the 2020 sanitation law, comparing matched municipalities from 1998 to 2021. Significant reductions in under-five diarrhoeal morbidity, no effect on unrelated diseases, results varying across municipalities. Published in *Utilities Policy*, first author. |

## background

🇧🇷 Brazilian &nbsp;·&nbsp; 📍 Chicago, IL &nbsp;·&nbsp; 🎓 UChicago MSCAPP

**Languages:** Portuguese (native) · English (fluent) · Spanish (professional working) · German (conversational)

[![Website](https://img.shields.io/badge/Website-rodrigofch7.github.io-B23A48?style=flat&logo=githubpages&logoColor=white)](https://rodrigofch7.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/rodrigofrancac/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-publications-lightgrey?style=flat&logo=google-scholar)](https://scholar.google.com/citations?user=6D65dqUAAAAJ&hl=pt-BR)
