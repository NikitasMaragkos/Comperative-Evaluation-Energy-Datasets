# 📊 Comparative Evaluation of Deep Learning Models on Weather-Informed Energy Forecasting

This repository contains the code, datasets, and graphical abstract accompanying our paper:  
**"A comparative evaluation of time-series forecasting models for Energy Datasets"**

![Graphical Abstract](grph_abst_final.PNG)

In this work, we conduct a systematic comparative analysis of state-of-the-art deep learning models—such as **DLinear**, **NBEATS**, **NHITS**, **Autoformer**, **FEDformer**, and **Informer**—across a diverse collection of **24 energy-related time series**. These datasets are enriched with aligned **weather information** (e.g., temperature, wind speed, solar radiation) to reflect more realistic forecasting scenarios.

Our experiments evaluate model performance over **hourly**, **daily**, and **monthly** forecast horizons, considering both **short-** and **long-term** prediction tasks. We benchmark forecasting accuracy, training efficiency, and resource usage to provide a comprehensive understanding of each model's strengths and limitations.

---

## 📁 What's Included

- 🧠 Implementation built using [NeuralForecast](https://github.com/Nixtla/neuralforecast) library  
- ⚡ A variety of energy datasets (consumption, generation) from [ENTSO-E](https://www.entsoe.eu/)
- 🌦️ Matched weather datasets used as exogenous variables from [Open-Meteo](https://open-meteo.com/)
- 📊 Model training, evaluation scripts, and metrics  
- 🖼️ A graphical abstract summarizing the methodology and results  

---

## 🔁 Reproducibility

To support transparency and future work, the **necessary code and datasets** are publicly available in this repository.

---

## 📄 Reference
We kindly request that you cite our paper along with the original websites from which the datasets were sourced.

> *A comparative evaluation of time-series forecasting models for Energy Datasets*  
> *Nikitas Maragkos, Ioannis Refanidis*  
> *Computers / SI: Artificial Intelligence-Driven Innovations in Resilient Energy Systems, 2025 
> [DOI or link – coming soon]


> Zippenfenig, P. (2023). *Open-Meteo.com Weather API*. Zenodo. https://doi.org/10.5281/zenodo.7970649  
> License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

<details> <summary>BibTeX</summary>
bibtex
Αντιγραφή
Επεξεργασία
@software{Zippenfenig_Open-Meteo,
  author = {Zippenfenig, Patrick},
  doi = {10.5281/zenodo.7970649},
  license = {CC-BY-4.0},
  title = {Open-Meteo.com Weather API},
  year = {2023},
  copyright = {Creative Commons Attribution 4.0 International},
  url = {https://open-meteo.com/}
}
</details>

Website: [https://open-meteo.com/](https://open-meteo.com/)
