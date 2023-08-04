# Orsted Power Generation Forecasting
This project was part of the second round interview process for a position at Orsted, a global leader in offshore wind energy. The challenge was to forecast power generation for different types of primary fuels (Gas, Oil, Hydro, etc.), for each year and for different countries, using publicly available data from Orsted's power plants.

The complexity of this task comes from the fact that the forecasting model must take into account different growth rates for each type of fuel. Furthermore, these growth rates are dynamic and can be changed by the user in a Power BI dashboard, which implies that the results are recalculated in real time.

To achieve this, the project makes extensive use of DAX (Data Analysis Expressions) to create calculated columns and measures that perform the necessary calculations. This allows for a high degree of interactivity, as the user can modify the parameters and immediately see the impact on the forecasted power generation.

In addition, Python and linear regression were used to handle missing data in the dataset. Specifically, a model was trained to predict missing power generation values based on the available data, and these predicted values were used to fill in the gaps in the data.

The dataset used for this project is publicly available and is included in this repository.
