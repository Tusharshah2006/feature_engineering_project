# Skewness

The third most important step in Pre-processing is performing skewness removal from the dataset.
These steps transforms the dataset statistically close to Gaussian dataset, so that the largest set of tools are available to  use on the dataset.

For this task we will be using the raw(original data) data. Can you guess why?

Reason behind this is when do we remove outlier from the data then skewness also shifts. So if distribution is left skewed, then after outlier removal it will shift to right side.** 


## Write a function `skewness_log` that:
- Remove the skewness from the variable on which log transformation is applied and give transformed value in new column of dataset.
- Should remove the skewness from variables `SalePrice` and `GrLivArea`

    
### Parameters:

| Parameter | dtype | argument type | default value | description |
| --- | --- | --- | --- | --- | 
| data| dataframe | compulsory |  | making changes into dataset |


### Returns:

| Return | dtype | description |
| --- | --- | --- | 
| Skewness value | Float | Skewness measure of variable 1 |
| Skewness value | Float | Skewness measure of variable 2 |


