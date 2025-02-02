# -Lipinski_rule_analysis.py
This project focuses on predicting the aqueous solubility of compounds based on their molecular structure. The dataset includes 2000 compounds with experimental solubility values standardized to LogS units and 21 computed descriptors for analysis. The goal is to evaluate compliance with Lipinski's Rule of Five, a widely used guideline for drug-likeness.

Key Features of the Dataset
Molecular Weight (MolWt):
Range: 20.006 to 872.496 Daltons
Average: 214.267 Daltons
Mode: 130.187 Daltons

Solubility (LogS):
Range: -13.1719 to 1.6988 LogS units
Average: -2.28475 LogS units
Mode: 1.065 LogS units

Number of Hydrogen Donors (NumHDonors):
Range: 0 to 13
Average: 1.094
Mode: 0 (many compounds have no hydrogen donors)

Number of Hydrogen Acceptors (NumHAcceptors):
Range: 0 to 19
Average: 2.8975
Mode: 2

Lipinski's Rule of Five Compliance
Using a Python script in Orange software, the number of compounds complying with Lipinski's rules was calculated. The rules include:
Molecular Weight (MolWt) < 500 Daltons
LogP < 5
Hydrogen Donors (NumHDonors) < 5
Hydrogen Acceptors (NumHAcceptors) < 10

Results:
Total Compounds Compliant: 1820
Group 1:
Compounds: 1648
Compliance within Group: 91%
Overall Compliance: 82.40%
Group 3:
Compounds: 120
Compliance within Group: 0.88%
Overall Compliance: 0.80%


