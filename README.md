# Python_ABC-XYZ_Inventory_Optimisation
### Overview:
This project is an end-to-end Inventory Optimisation model built in Python. As a Supply Chain professional transitioning into data analytics, my goal with this project was to move beyond static spreadsheet calculations and build a dynamic, automated approach to managing warehouse stock, mitigating stockout risks, and releasing trapped working capital.

### The Business Problem:
Many warehouses rely on historical guesswork or blanket rules for inventory replenishment, resulting in two extremes:

1.Trapped Capital: Holding too much "just-in-case" inventory for highly predictable items.

2.Stockouts: Failing to buffer correctly against highly volatile items during supplier lead times.

### Methodology:
To solve this, I applied statistical supply chain principles to a simulated warehouse dataset (150 SKUs):

* ABC Classification (Financial): Segmented SKUs by annual financial value using the Pareto principle (80/15/5).

* XYZ Classification (Volatility): Measured demand unpredictability using the Coefficient of Variation (CV).

* Dynamic Safety Stock: Calculated optimal buffer levels using the standard statistical formula ($SS = Z \times \sigma_{d} \times \sqrt{L}$), assigning varying service levels (Z-Scores) based on the ABC-XYZ matrix.

* Financial Impact: Compared the newly calculated Reorder Points (ROP) and Maximum Healthy Stock limits against current on-hand stock to identify the exact dollar amount of wasted working capital.

🛠️ Note on My Workflow & AI Integration
My core expertise lies in physical inventory control, operational master data, and supply chain logic. I am actively upskilling in Python and SQL (via DataCamp) to augment these skills.

For this project, I defined the operational parameters, mathematical formulas, and the final executive business recommendation. I then utilized AI as a coding assistant to accelerate the Python generation (Pandas/NumPy). This reflects my approach to modern data work: leveraging AI to handle syntax so I can remain relentlessly focused on data interpretation, problem-solving, and driving actual business value.

### Files in this Repository:

* inventory_data.csv: The raw dataset of 150 SKUs, unit costs, and current stock levels.

* [The Google Colab Notebook](https://colab.research.google.com/drive/10VJxG4uXo8oh79nXkG-Uf310lHanyCP0?usp=sharing) containing the Python code and logic.

* Executive_Summary.pdf: A one-page executive summary translating the code output into actionable procurement steps.
