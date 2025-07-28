# PAQS-Calculation-Tools
Tools and documentation for the **Pedestrian Access Quality Score (PAQS)**, a metric developed at UC Berkeley to measure the quality of pedestrian access routes to rapid transit stations.

## 🔍 About the Metric
PAQS is designed to assess the quality of pedestrian access to transit through the lenses of route directness and perceived safety. The score is intended to support urban planning, transportation research, and accessibility studies.

## 📁 Repository Contents
- `PAQS_Calculator.xlsx`  
  Excel-based tool for calculating PAQS based on input variables. Includes embedded formulas and guidance.
  
- `PAQS_ExampleData.xlsx`  
  Sample dataset used in the thesis to demonstrate PAQS application.
  
- `Methodology_Summary.pdf`  
  A brief overview of the metric’s development, scoring system, and validation.

- `README.md`  
  This file — basic overview and usage instructions.

## 🛠️ How to Use These Tools
1. Please read the **Introduction** and **Methodology** sections of the associated thesis for an overview of how the metric works and how it is calculated. There are figures to help you understand the structure of the metric.
2. For **each** access route you choose to analyze, open **ONE** `metric calculator each route new.xlsx` file.
3. Use Google Earth imagery or physical field visits to fill in the required data in the spreadsheet. Embedded formulas will automatically calculate PAQS.
4. For the entire station you choose to analyze, open **ONE** `metric calculator whole station.xlsx` file. This will calculate PAQS for the entire station.
5. The PAQS will be calculated automatically using the embedded formulas.
6. Refer to `Methodology_Summary.pdf` for an explanation of the variables and scoring logic.

## 📖 Citation
If you use or adapt this tool, please cite:

> Matthew Cheng. (2025). *Pedestrian Access Quality Score: A New Metric for Evaluating Urban Pedestrian Conditions* (Master’s Thesis, University of California, Berkeley). [GitHub Repository URL]

## 🧾 License
This project is made available under the [MIT License](LICENSE), allowing free use with attribution.

## 📬 Contact
For questions or collaboration, contact:
- **Name**: Matthew Cheng  
- **Email**: mcheng213@berkeley.edu 
