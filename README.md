# PAQS-Calculation-Tools
Tools and documentation for the **Pedestrian Access Quality Score (PAQS)**, a metric developed at UC Berkeley to measure the quality of pedestrian access routes to rapid transit stations.

## 🔍 About the Metric
PAQS is designed to assess the quality of pedestrian access to transit through the lenses of route directness and perceived safety. The score is intended to support urban planning, transportation research, and accessibility studies.

## 📁 Repository Contents
- `PAQS_calc_route.xlsx`  
  Excel-based tool for calculating PAQS for individual pedestrian access routes. Includes embedded formulas and guidance.
  
- `PAQS_calc_station.xlsx`  
  Excel-based tool for calculating PAQS for entire transit stations by aggregating individual route scores. 
  
- `var_descriptions.xlsx`  
  Equations and variables used to calculate PAQS. The embedded equations in the above spreadsheets automatically perform the calculations shown in this spreadsheet.
  
- `README.md`  
  This file — basic overview and usage instructions.

## 🛠️ How to Use These Tools
1. Please read the **Introduction** and **Methodology** sections of the associated thesis for an overview of how the metric works and how it is calculated. There are figures to help you understand the structure of the metric.
2. For **each** access route you choose to analyze, open **ONE** `PAQS_calc_route.xlsx` file.
3. Use Google Earth imagery or physical field visits to fill in the required data in the spreadsheet. Follow the instructions in the file. Embedded formulas will automatically calculate PAQS.
4. Repeat steps 2-3 for every route you wish to analyze. Note: **You must use a new spreadsheet for every route.** (Make a copy of `PAQS_calc_route.xlsx`)
5. For the entire station to which those routes belong, open `PAQS_calc_station.xlsx` and fill it in according to the instructions in the file. This will calculate PAQS for the entire station.
7. Refer to `var_descriptions.xlsx` for an explanation of the variables and scoring logic.

## 📖 Citation
If you use or adapt this tool, please cite:
> Matthew Cheng. (2025). *Holistically Evaluating Pedestrian Access Quality in the Transit Station Polygon Vicinity* (Master’s Thesis, University of California, Berkeley). https://github.com/Trainzguy2472/PAQS-Calculation-Tools

## 🧾 License
This project is made available under the [MIT License](LICENSE), allowing free use with attribution.

## 📬 Contact
For questions or collaboration, contact:
- **Name**: Matthew Cheng  
- **Email**: mcheng213@berkeley.edu 
