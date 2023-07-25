# Chernobyl-Cleaning
The data includes various measurements taken at different locations ("Ville") in different countries ("PAYS"), such as the concentrations of different isotopes in the air, including Iodine-131 ("I_131_(Bq/m3)"), Cesium-134 ("Cs_134_(Bq/m3)"), and Cesium-137 ("Cs_137_(Bq/m3)"). 
The dataset also includes the date of the measurements, the geographic coordinates of the measurement locations, the duration of sampling, and the end time of sampling.

I've done a significant amount of data cleaning and preprocessing. This includes:

1. Handling missing values by replacing them with the mean value of the respective column.
2. Converting the date column to a proper datetime format.
3. Converting the end time of sampling and the duration of sampling from a string in the format "h:min" to the number of minutes past midnight.
4. Visualizing the data with box plots and removing outliers using the Interquartile Range (IQR) method.
5. Checking for duplicates and removing them.
6. Creating new columns indicating the pollution level (low, medium, or high) for each isotope based on its concentration.
