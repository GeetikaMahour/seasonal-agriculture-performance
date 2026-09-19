Seasonal Agriculture Performance Analysis

📌 Project Overview

This project analyzes agricultural performance across different seasons, crops, and states using a seasonal agriculture dataset.

The analysis focuses on understanding how agricultural profitability changes between the Kharif, Rabi, and Zaid seasons and identifying factors that influence farm profitability and water usage.


🎯 Objectives

Compare agricultural profitability across seasons.

Analyze profit and loss at the farm level.

Compare performance across different crops and states.

Study the relationship between agricultural inputs, prices, yield, and profit.

Compare irrigation methods and their water usage.

Identify crops that remain profitable during the Zaid season.


🛠️ Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Data Analysis & Visualization


📊 Key Findings


The analysis shows a clear difference in agricultural performance across seasons.


Kharif has the highest median profit per hectare at approximately ₹8,340.

Rabi has a median profit per hectare of approximately −₹894.

Zaid has the lowest median profit per hectare at approximately −₹13,760.

Approximately 42% of farms lose money in Kharif.

Approximately 51% of farms lose money in Rabi.

Approximately 64% of farms lose money in Zaid.

The seasonal ranking remains consistent across the analyzed crops and states.

Input costs and prices do not differ by season in the dataset, indicating that the observed seasonal profitability difference is primarily associated with yield.

Drip irrigation performs best across seasons while using approximately 30% less water than flood irrigation.

Chilli and sugarcane are the only crops that remain above break-even during Zaid.

📈 Results


The project generates 11 visualization charts showing seasonal profitability, crop performance, state-level performance, irrigation methods, water usage, and other agricultural indicators.

The charts are available in the figures folder.


📁 Project Structure

seasonal-agriculture-performance/
│
├── seasonal_agriculture_performance.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
│
└── figures/
    ├── figure1.png
    ├── figure2.png
    ├── ...
    └── figure11.png

	
⚠️ Limitations

The analysis is limited to state and crop-level comparisons because the district information in the dataset does not consistently correspond to the stated states.

Therefore, district-level conclusions were not included in the main analysis.

The findings also describe patterns in the provided dataset and should not automatically be interpreted as representing all agricultural farms in India.

👤 Author

Name: GEETIKA MAHOUR

📄 Dataset

The analysis uses the provided:

seasonal_agriculture_performance_dataset.csv

📓 Notebook

The complete analysis, calculations, visualizations, and findings are available in:

seasonal_agriculture_performance.ipynb
