# Exposure to Multiple Air Pollutants Contributed to 12% of Deaths in Sydney Between 2000 and 2025

## Authors

* **Simon William Mkasimongwa***
* **Robert G. Ryan**
* **Stephen J. Livesley**
* **Robyn Schofield**

## Affiliations

**a** School of Geography, Earth and Atmospheric Sciences, The University of Melbourne, Parkville, VIC 3010, Australia
**b** School of Agriculture, Food and Ecosystem Sciences, Burnley Campus, The University of Melbourne, 500 Yarra Boulevard, Richmond, VIC 3121, Australia

* Corresponding author
Email: [smkasimongwa@student.unimelb.edu.au](mailto:smkasimongwa@student.unimelb.edu.au)
Email: [simonwilliam140293@gmail.com]

---

## Overview

This repository contains the Python code, data, and full analytical workflow supporting the research study:

**“Exposure to multiple air pollutants contributed to 12% of deaths in Sydney between 2000 and 2025.”**

The study evaluates the mortality burden associated with simultaneous exposure to multiple urban air pollutants in Sydney, Australia, using long-term monitoring data between 2000 and 2025.

The project also develops a **Multi-Pollutant Air Quality Health Index (AQHI)** designed to communicate short-term health risks to the public.

---

## Study Objectives

1. Develop a Multi-Pollutant Air Quality Health Index (AQHI) for Sydney.
2. Estimate short-term mortality attributable to combined air pollution exposure.
3. Estimate long-term mortality burden attributable to sustained exposure.
4. Quantify the contribution of individual pollutants to total mortality burden.
5. Evaluate changes in air pollution health risk trends between 2000 and 2025.

---

## Pollutants Included

* Nitrogen Dioxide (**NO₂**)
* Ozone (**O₃**)
* Fine Particulate Matter (**PM₂.₅**)
* Coarse Particulate Matter (**PM₁₀**)

---

## Data Sources

* New South Wales Environment Protection Authority (NSW EPA) air quality monitoring network
* HealthStats NSW mortality statistics
* Australian Bureau of Statistics (ABS) population data

---

## Methods Summary

The analytical workflow includes:

* Spatial aggregation of hourly air quality observations across Greater Sydney
* 3-hour rolling mean and daily maximum exposure metrics
* Multi-pollutant excess risk estimation using published relative risks
* Development of a health-risk-based AQHI framework
* Short-term attributable mortality modelling
* Long-term attributable mortality modelling
* Monte Carlo uncertainty simulation
* Pollutant contribution analysis
* Temporal trend analysis (2000–2025)

---

## Repository Structure

```text
data/         Input datasets
notebooks/    Main Jupyter notebook analysis
figures/      Output visualisations
```

---

## Main Notebook

```text
notebooks/MAQHI_Sydney_Analysis.ipynb
```

---

## Reproducibility

Install required Python packages:

```bash
pip install -r requirements.txt
```

Then open the notebook and run all cells.

---

## Citation

A Zenodo DOI will be linked to this repository upon official release.

---

## License

MIT License

---

## Contact

**Simon William Mkasimongwa**
Graduate Researcher
The University of Melbourne
Email: [smkasimongwa@student.unimelb.edu.au](mailto:smkasimongwa@student.unimelb.edu.au)
Email: [simonwilliam140293@gmail.com](mailto:simonwilliam140293@gmail.com)
