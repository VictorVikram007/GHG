# GHG- Greenhouse Gas Emission Prediction
## 📊 Supply Chain Emission Data Analysis (2010–2016)

This project is focused on analyzing **Supply Chain Emission Factors** for U.S. industries and commodities from **2010 to 2016**, using an Excel dataset. The data includes various emission metrics across different sectors, which are loaded, cleaned, and prepared for analysis and modeling using Python.

---

## 📘 What I Learned

Throughout this project, I learned:

- How to load Excel sheets dynamically using `pandas.read_excel()` and f-string formatting.
- How to handle multiple sheets in a loop and merge them into a single DataFrame.
- How to clean and rename columns for consistency across different datasets.
- How to use `try-except` blocks to catch errors while processing multiple files.
- How to combine multiple DataFrames using `pd.concat()` with proper indexing.
- How to identify missing values using `df.isnull().sum()` and understand data quality.
- How to modularize Python code using reusable functions.
- Improved my understanding of real-world data preprocessing in supply chain contexts.

---

## 📂 Project Structure

```text
.
├── week1.ipynb        # Python script or notebook with code
├── SupplyChainEmissionFactors...xlsx # Dataset file (Excel)
└── README.md                        # This documentation file
