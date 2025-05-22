# CSC700 – Sales and Profit Analysis

## Team Members & Roles

- **Abdulaziz Alshehhi** – *Team Leader*  
- **Mohammed Ahmed** – *Research*  
- **Khalid Mansoor** – *Problem Solver*  
- **Hamad Alattar** – *Writer*

---

## Project Overview

This project focuses on analyzing sales and profit data using a rich dataset sourced from Kaggle. The dataset contains essential business metrics across various dimensions including time, customer demographics, product information, and financial figures. Our goal is to draw meaningful insights that can help businesses make informed decisions regarding product performance, customer trends, and regional profitability.

---

## Dataset Description

We used a CSV file named **`StoreSaleData.csv`**, which includes a variety of fields required for effective sales and profit analysis. The file is read using the `pandas` library in Python with the following command:

```python
import pandas as pd

data = pd.read_csv("StoreSaleData.csv", encoding='latin-1')
