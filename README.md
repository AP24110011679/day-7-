This program takes energy readings of buildings, classifies them, and evaluates overall energy efficiency.
Logic (Simple)
Input: User enters energy readings.
Classification:
0–50 → Efficient
51–150 → Moderate
150 → High
<0 → Invalid
Filtering: Negative values are ignored in calculations.
Summary: Calculates total consumption and number of valid readings.
Decision:
Many high values → Overconsumption
Balanced efficient & moderate → Balanced Usage
High total → Energy Waste
No high values → Efficient Campus
Else → Moderate Usage
Output
Category-wise readings
Total consumption & building count
Final efficiency result
