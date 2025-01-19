# Statistical Models Final Project
<img src="https://img.shields.io/badge/-Python-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/-Jupyter Notebook-orange?style=for-the-badge"> <img src="https://img.shields.io/badge/-Pandas-purple?style=for-the-badge"> <img src="https://img.shields.io/badge/-Numpy-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/-Scipy-yellow?style=for-the-badge"> 

## About
This project explores statistical methods to analyze the fecundity of fruit flies (*Drosophila melanogaster*) using data collected by R.R. Sokal (Sokal & Rohlf, 1981). The dataset includes the per diem fecundity (eggs laid per female per day for the first 14 days) for 25 females from three genetic lines:

- **RS (Resistant):** Selected for resistance to DDT.
- **SS (Susceptible):** Selected for susceptibility to DDT.
- **NS (Nonselected):** Control strain with no selective breeding.

The primary research questions addressed are:
1. Do the two selected lines (RS and SS) differ in fecundity from the nonselected line (NS)?
2. Does the line selected for resistance (RS) differ in fecundity from the line selected for susceptibility (SS)?

## Data Source
Sokal, R.R., & Rohlf, F.J. (1981). *Biometry* (2nd ed.). San Francisco: W.H. Freeman, 239.

## Methods
The project applies the following statistical techniques:
- **One-way ANOVA:** To compare the means across the three groups.
- **Tukey’s HSD Post-Hoc Test:** To identify pairwise differences after ANOVA.
- **T-Test:** To test differences between RS and SS groups directly.

## Results
The analysis confirmed that:
1. Significant differences exist between the NS line and the two selected lines (RS and SS).
2. No significant difference was found between RS and SS lines.

## Group Members
This project was completed as a group effort by:
- Vladyslav Horbatenko (vladyslav@ruc.dk)
- Layba Naeem (layba@ruc.dk)
- Maria Paz Buonomo Quiroga (paz@ruc.dk)
- Rishni Mahendran (rishni@ruc.dk)
- Maxim Gutu (stud-gutu@ruc.dk)
- Cojocaru Vlad (stud-cojocaru@ruc.dk)

## Course and Grade
This was the final project for the *Statistical Models* course during Autumn Semester 2024. Final grade: **12**.