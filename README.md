# anomaly-detection-in-retail
Identify anomalies in the prices recorded by auditors at various retail stores and locations by using a linear regression model

### Problem
   - A company collects data from different retailers by sending auditors into physical stores to record pricing and assortment information. 
   - This data is then aggregated and validated using outlier identification techniques. 
   
### Solution
   - In this project, a simple pricing model is used. We assumes a store price is equal to a base price for the product/UPC multiplied by a store-specific scaling factor and a region-specific scaling factor.
   - Then the residuals calculated from the difference between the predicted price and the observed price are calculated
   - The records that have large residual are idetified as anomalies.
     
### Notebook
   - `anomaly_detection_in_retail.ipynb`
