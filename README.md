# Anticipate building consumption needs

My mission here for the city of Seattle is to attempt to predict the CO2 emissions and total energy consumption of non-residential buildings for which they have not been measured.

The structural data of the buildings used to fulfill this mission were recorded in 2016 by the city (here their [source](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy)).

In the first part we will clean our data set, carry out a short exploratory analysis and standardize our data so that they can be used to train different prediction models we will choose in the second and third parts to best respond to the problem.<br><br>

<u><strong>Summary</strong></u> :<br>
<br>
<strong>Tools</strong><br>
 
<strong>I. Feature engineering and exploratory analysis</strong><br>
     -- A. 2016_Building_Energy_Benchmarking.xlsx: dataset description and cleaning<br>
     ---- <i>☛ Data set loading and description<br>
     ---- ☛ Check null and duplicates values on primarey key<br>
     ---- ☛ Filter our dataframe on non residential buildings<br>
     ---- ☛ Variables description and selection<br>
     ---- ☛ Encoding qualitative data<br></i>
     -- B. 2016_Building_Energy_Benchmarking.xlsx: exploratory analysis<br>
     ---- <i>☛ Correlation between the total surface of a building and its CO2 emissions (intensity)<br>
     ---- ☛ Correlation between the total surface of a building and its energy consumption (intensity)<br>
     ---- ☛ Correlation between the year of construction of a building and its CO2 emissions<br>
     ---- ☛ Correlation between the year of construction of a building and its energy consumption<br></i>
     -- C. 2016_Building_Energy_Benchmarking.xlsx: data standardization<br>
     ---- <i>☛ Quantitative data standardisation<br>
     ---- ☛ Scaling the YearBuild variable<br></i>

<strong>Conclusion (part 1)</strong>

<strong>II. Seattle buildings CO2 emissions prediction</strong><br>
     -- A. Testing Ridge model<br>
     -- B. Testing Lasso model<br>
     -- C. Testing Random Forest model<br>
     -- D. Testing XGBoost regression model<br>
     -- E. Train previous models with log transformation of the target variable beforehand<br>
     -- F. ENERGYSTARScore feature importance in the chosen model<br>
     -- G. Adding variables and combining variables to improve the performance of the chosen model<br>
     -- H. Hyperparameter optimization of the selected model<br>
     -- I. Explain Predictions using SHAP Values<br>


<strong>Conclusion (part 2)</strong>

<strong>III. Seattle buildings energy consumption prediction</strong><br>
     -- A. Testing Ridge model<br>
     -- B. Testing Lasso model<br>
     -- C. Testing Random Forest model<br>
     -- D. Testing XGBoost regression model<br>
     -- E. ENERGYSTARScore feature importance in the chosen model<br>
     -- F. Adding variables and combining variables to improve the performance of the chosen model<br>
     -- G. Hyperparameter optimization of the selected model<br>
     -- H. Explain Predictions using SHAP Values<br>


<strong>Conclusion (part 3)</strong>
