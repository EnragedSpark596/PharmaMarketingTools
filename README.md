# Pharma Marketing Tools

A collection of Python data-analysis prototypes exploring how public and synthetic healthcare data can be used to investigate pharmaceutical marketing, healthcare-provider segmentation, patient characteristics and unstructured healthcare text.

## Project Overview

This repository grew out of an interest in how data science could be applied to pharmaceutical marketing and healthcare business questions.

The individual notebooks explore different parts of that problem. Some use publicly available healthcare data, while others generate synthetic data intended to resemble the kinds of datasets a pharmaceutical organization might work with.

The goal was not to create a finished commercial application, but to experiment with how Python could be used to generate, combine, analyze and visualize healthcare-related data and turn it into potentially useful business insights.

## What the Repository Explores

The notebooks cover several related areas:

* Generation of synthetic physician and patient data
* Use of public healthcare and insurance data
* Cancer incidence/risk data
* Healthcare-provider characteristics and segmentation
* Visualization of physician and healthcare-market data
* Simulation of pharmaceutical marketing interactions
* Principal Component Analysis (PCA)
* K-means clustering
* Decision-tree analysis
* Natural-language processing of healthcare-professional text
* Text cleaning, tokenization, stemming, lemmatization and part-of-speech analysis

Together, the projects represent experiments in moving from raw or simulated healthcare information toward data that could support segmentation, targeting, visualization and exploratory business analysis.

## Repository Contents

### `DoctorDataGenerator2.2.ipynb`

Generates synthetic physician/practice data using assumptions and publicly available state-level information.

The notebook combines generated characteristics with external data such as physician populations and insurance coverage. It also explores decision-tree analysis of the resulting data.

`DoctorDataGenerator2.ipynb` is an earlier version of this work and is retained as part of the project's development history.

### `PatientPersonaGenerator2.ipynb`

Explores the generation of synthetic patient personas using demographic and health-related characteristics.

The notebook uses Python probability and random-selection techniques to create artificial patient records for experimentation without relying on identifiable patient-level data.

### `MarketingTouches_TypesFrequencies2.1.ipynb`

Explores simulated interactions between pharmaceutical marketing activities and healthcare providers.

The notebook uses data-analysis and machine-learning techniques including:

* Data manipulation with pandas
* Feature scaling
* Principal Component Analysis (PCA)
* K-means clustering
* Visualization of resulting patterns

The purpose was to investigate whether simulated marketing and provider characteristics could be used to identify meaningful groups or patterns.

### `DrDataVisualizations.ipynb`

Explores healthcare-provider and state-level data through statistical analysis and visualization.

Technologies used include pandas, NumPy, Matplotlib, seaborn, SciPy and scikit-learn preprocessing tools.

### `CancerRates.ipynb`

Explores cancer-rate information by characteristics including cancer type, age range and gender, and experiments with representing this information in pandas data structures for use in other healthcare-data models.

### `NLTK_HCPsentiment6_taggingPOS.ipynb`

An exploratory natural-language-processing notebook working with healthcare-professional text.

The notebook experiments with techniques including:

* Text cleaning
* Tokenization
* Stemming
* Lemmatization
* Part-of-speech processing

It uses NLTK to explore how unstructured healthcare text might be transformed into information suitable for further analysis.

## Supporting Data

The repository also contains CSV files used by the notebooks, including state-level physician and insurance-coverage data.

Some of the notebooks combine these source datasets with synthetically generated records. Synthetic records are intended for experimentation and demonstration and should not be interpreted as information about actual individual physicians or patients.

## Technologies Used

* **Python**
* **pandas** — data manipulation and analysis
* **NumPy** — numerical operations and data generation
* **Matplotlib** — visualization
* **seaborn** — statistical visualization
* **SciPy** — statistical analysis
* **scikit-learn** — preprocessing, PCA, clustering and decision-tree analysis
* **NLTK** — natural-language processing
* **pydotplus** — decision-tree visualization
* **Jupyter Notebook** — exploratory development and documentation

## Running the Project

Clone the repository:

```bash
git clone https://github.com/EnragedSpark596/PharmaMarketingTools.git
cd PharmaMarketingTools
```

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```

and select the notebook you want to explore.

### Additional dependencies

Some NLTK functionality may require NLTK language resources to be downloaded separately.

The decision-tree visualization in `DoctorDataGenerator2.2.ipynb` may also require Graphviz to be installed on the local system in addition to the Python `pydotplus` package.

## Project Context

This is a collection of earlier exploratory Python and data-science work and has been preserved substantially in its original form as part of my development portfolio.

The repository was created while I was exploring how data science could be applied to real business problems in healthcare and pharmaceutical marketing. Rather than following a single course exercise, the notebooks reflect a broader effort to think through the kinds of information a pharmaceutical organization might possess or obtain and experiment with ways that Python could help extract useful insights from it.

The work includes both public data and synthetic data generated specifically for experimentation.

These notebooks are exploratory rather than production software. Some contain intermediate experiments, older Python-library APIs and assumptions made for demonstration purposes. They are included to show the development process as well as the resulting analyses.

## Data and Ethical Considerations

The synthetic physician and patient information generated by these notebooks is intended for demonstration and experimentation.

Synthetic records should not be interpreted as representing real individuals, and analyses based on simulated assumptions should not be treated as evidence about actual patients, healthcare professionals or markets.

Any application of similar techniques to real healthcare or pharmaceutical data would require appropriate attention to data provenance, privacy, regulatory requirements, bias, validation and the limitations of the underlying data.

## Author

**Ian Jones**

Former chemical and process safety engineer developing Python skills in data analysis, automation, machine learning, visualization and practical problem-solving.
