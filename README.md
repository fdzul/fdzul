<h2 align="center">Hi, I'm Felipe Antonio Dzul Manzanilla 👋</h2>
<p align="center">
  <b>Medical entomologist & spatial epidemiologist</b> · Instituto Nacional de Salud Pública (INSP), México<br>
  Turning surveillance, entomological and satellite data into decisions for dengue and arbovirus control 🦟🗺️
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?hl=en&user=3e3-4VkAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0000-0002-2085-9141"><img src="https://img.shields.io/badge/ORCID-0000--0002--2085--9141-A6CE39?style=flat&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://twitter.com/FdzulM"><img src="https://img.shields.io/badge/@FdzulM-000000?style=flat&logo=x&logoColor=white" alt="X"></a>
  <a href="https://github.com/fdzul?tab=followers"><img src="https://img.shields.io/github/followers/fdzul?style=flat&logo=github&label=Followers&color=181717" alt="GitHub followers"></a>
</p>

---

### 🔬 About me

- 🦟 **20+ years** working on prevention and control of vector-borne diseases (dengue, Zika, chikungunya) in Mexico
- 🗺️ **Spatial epidemiology:** hotspot detection, risk mapping and Bayesian spatial models (INLA, BYM2)
- 🤖 **Machine learning** for early warning and active transmission foci (XGBoost, LightGBM, `tidymodels`)
- 🛰️ **Remote sensing** with Google Earth Engine: urban heat islands, LST, vegetation and drought indices
- 📦 **Open-source tools** in R and Python so health programs can reuse the analyses
- 🤝 Collaborations with Emory University, CDC, LSHTM and the University of Oxford

### 🌐 The dengueverse

<p>
  <a href="https://fdzul.r-universe.dev"><img src="https://fdzul.r-universe.dev/badges/:name" alt="r-universe"></a>
  <a href="https://fdzul.r-universe.dev/packages"><img src="https://fdzul.r-universe.dev/badges/:total" alt="packages"></a>
</p>

[**dengueverse**](https://fdzul.github.io/dengueverse/) is a family of R packages for the surveillance, spatial analysis and control of dengue and *Aedes*-borne diseases in Mexico, distributed through [R-universe](https://fdzul.r-universe.dev).

| Area | Package | Description |
|---|---|---|
| Data | [**sinave**](https://github.com/fdzul/sinave) | Imports the eleven vector-borne disease datasets from SINAVE |
| Data | [**rgeomex**](https://fdzul.github.io/rgeomex/) | Geographic boundaries of Mexico, from states to electoral sections (INEGI 2019, INE 2020) |
| Data | [**popmex**](https://fdzul.github.io/popmex/) | Population of Mexico by municipality, sex and age group, also on H3 hexagons, for rates |
| Data | [**denguedatasets**](https://fdzul.github.io/denguedatasets/) | Open-access dengue surveillance and climate datasets from eleven countries |
| Data | [**ewarsmx**](https://github.com/fdzul/ewarsmx) | Climate and epidemiological data for the dengue early warning system in Mexico (EWARS-CSD) |
| Data | [**climex**](https://fdzul.github.io/climex/) | Climate variables from the NASA POWER API for 2,465 municipalities or any set of points |
| Surveillance | [**densnv**](https://fdzul.github.io/densnv/) | Analysis of SINAVE data: transmission foci, Knox test, Rt and epidemiological scenarios |
| Surveillance | [**vectoRcontrol**](https://github.com/fdzul/vectoRcontrol) | Exploration of vector control datasets from Mexico's Ministry of Health |
| Surveillance | [**epifeatures**](https://github.com/fdzul/epifeatures) | Epidemiological features from dengue time series |
| Surveillance | [**boldenr**](https://github.com/fdzul/boldenr) | Dengue bulletin for Veracruz (legacy, being replaced by densnv) |
| Hotspots | [**denhotspots**](https://fdzul.github.io/denhotspots/) | Persistent transmission hotspots, space-time analysis and log-Gaussian Cox processes |
| Hotspots | [**knox**](https://github.com/fdzul/knox) | Knox test for space-time interaction |
| Entomology | [**deneggs**](https://fdzul.github.io/deneggs/) | Predictive maps of *Aedes aegypti* eggs or adults where no collection was made (INLA-SPDE) |
| Risk | [**denrisk**](https://fdzul.github.io/denrisk/) | Spatial datasets on potential dengue transmission in Mexico |
| Risk | [**dengueriskcdmx**](https://github.com/fdzul/dengueriskcdmx) | Data, rasters and code for the dengue risk map of the Mexico City Metropolitan Area |

Install any package from the dengueverse:

```r
install.packages("denhotspots",
                 repos = c("https://fdzul.r-universe.dev",
                           "https://cloud.r-project.org"))
```

#### 🐍 Python versions

| Package | Description |
|---|---|
| [**rgeomex-py**](https://fdzul.github.io/rgeomex-py/) | Geographic boundaries of Mexico (INEGI 2019, INE 2020) |
| [**popmex-py**](https://fdzul.github.io/popmex-py/) | Population of Mexico by municipality, sex and age group, H3 hexagons and LandScan (1 km) |
| [**denguedatasets-py**](https://fdzul.github.io/denguedatasets-py/) | Open-access dengue surveillance and climate datasets |
| [**dengueriskcdmx-py**](https://fdzul.github.io/dengueriskcdmx-py/) | Dengue risk map of the Mexico City Metropolitan Area |
| [**climex-py**](https://fdzul.github.io/climex-py/) | Climate data from the NASA POWER API (experimental) |
| [**densnv-py**](https://fdzul.github.io/densnv-py/) | SINAVE reading, cases by municipality and locality, and Rt (experimental) |

### 📦 Other projects

| Project | Language | Description |
|---|---|---|
| [**spatial_analysis_dengue_R**](https://github.com/fdzul/spatial_analysis_dengue_R) | R | Course/material on spatial analysis of dengue in R |
| [**fdzul.github.io**](https://fdzul.github.io) | Quarto | Personal website: publications, courses, bookdowns and dashboards |

### 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Quarto-75AADB?style=flat&logo=quarto&logoColor=white" alt="Quarto">
  <img src="https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=flat&logo=google&logoColor=white" alt="Google Earth Engine">
  <img src="https://img.shields.io/badge/INLA-Bayesian-6A5ACD?style=flat" alt="INLA">
  <img src="https://img.shields.io/badge/tidymodels-ML-1A162D?style=flat" alt="tidymodels">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
</p>

### 📊 GitHub stats

<p align="center">
  <img src="metrics.svg" alt="GitHub metrics">
</p>

---

<p align="center">
  <i>Ciencia abierta para la salud pública · Open science for public health</i><br>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=fdzul.fdzul" alt="visitors">
</p>
