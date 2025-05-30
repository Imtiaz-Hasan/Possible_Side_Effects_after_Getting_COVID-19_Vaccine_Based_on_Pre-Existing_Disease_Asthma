# Possible Side Effects after Getting COVID-19 Vaccine Based on Pre-Existing Disease: Asthma

This repository contains the code and analysis for the research paper investigating possible side effects of COVID-19 vaccines (Moderna, Pfizer, and Janssen) in individuals with pre-existing asthma conditions.

## Abstract

Vaccination could be a critical preventative strategy against coronavirus disease 2019 (COVID-19), and it is essential to understand the vaccine's usability in the general population. A safe and effective vaccination is the most effective way to terminate this epidemic. Many communities throughout the globe have expressed concerns regarding the efficacy and side effects of coronavirus SARS CoV2 vaccinations. Vaccines are now being rushed to market. Many papers have been published on COVID-19 vaccine, hesitancy, acceptance rate, local survey, vaccine distribution, vaccine information, etc. However, none of them mentioned any potential side effects from the COVID-19 vaccination for those with pre-existing disease like Asthma. The study aimed to describe the possible side effects after getting COVID-19 vaccines (Moderna, Pfizer and Janssen) for those who have a pre-existing disease like Asthma.

## Dataset

The datasets used in this research are available at: [Dataset Link](https://drive.google.com/drive/folders/1t7jBAXcHuXYOg3Pqhkd_XNfPBzOFBBJt?usp=sharing)

The repository contains the following datasets:
- accuracy-dataset.xlsx
- accuracynew-dataset.xlsx
- binary_dataset.xlsx
- new-dataset.xlsx
- newdataset.xlsx

## Installation

### Option 1: Local Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/Possible_Side_Effects_after_Getting_COVID-19_Vaccine_Based_on_Pre-Existing_Disease_Asthma.git
cd Possible_Side_Effects_after_Getting_COVID-19_Vaccine_Based_on_Pre-Existing_Disease_Asthma
```

2. Install the required Python packages:
```bash
pip install -r requirements.txt
```

### Option 2: Google Colab
1. Open [Google Colab](https://colab.research.google.com)
2. Upload the Jupyter notebooks from this repository to your Google Drive
3. Mount your Google Drive in Colab:
```python
from google.colab import drive
drive.mount('/content/drive')
```
4. Navigate to your notebook location in Google Drive
5. The required packages will be installed automatically when you run the notebooks

## Project Structure

The repository contains the following Jupyter notebooks:

### Main Analysis
1. `Covid-19_vaccine_side_effect.ipynb` - Main analysis of COVID-19 vaccine side effects
2. `Data preparation.ipynb` - Data preprocessing and preparation
3. `vaccine history count.ipynb` - Analysis of vaccine history and counts

### Model Implementation
1. `Decision_&_Random_forest_tree.ipynb` - Implementation of Decision Tree and Random Forest models
2. `Accuracy_test.ipynb` - Testing accuracy of the models
3. `Accuracy_percentage.ipynb` - Analysis of accuracy percentages

### Additional Analysis
1. `Highest history Asthma.ipynb` - Analysis of asthma-related vaccine history
2. `Highest history JANSSEN MALE.ipynb` - Analysis of Janssen vaccine effects in males
3. `Highest history JANSSEN FEMALE.ipynb` - Analysis of Janssen vaccine effects in females

## Usage

1. Download the datasets from the provided Google Drive link
2. Place the datasets in the project directory
3. Open and run the Jupyter notebooks in the following order:
   - First run `Data preparation.ipynb` for data preprocessing
   - Then run `Covid-19_vaccine_side_effect.ipynb` for the main analysis
   - Use `vaccine history count.ipynb` for vaccine history analysis
   - Run `Decision_&_Random_forest_tree.ipynb` for model implementation
   - Finally, run the accuracy analysis notebooks (`Accuracy_test.ipynb` and `Accuracy_percentage.ipynb`)
   - For specific analyses, refer to the additional analysis notebooks

## Citation

If you use this code or dataset in your research, please cite our paper:

```
https://doi.org/10.1145/3542954.3543001
```

## Contact

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:imtiaz.hasan121@gmail.com)
