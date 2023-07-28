#  z-scoring Transformation
     The Z-scoring transformation (also known as z-score normalization or standardization) is a process that transforms a dataset by centering its mean at zero and scaling its standard deviation to one. This transformation brings the values of the dataset into a standardized format, making it more suitable for analysis and comparisons.

Z-scoring is calculated using the following formula:

z= (x−μ) / σ 
​ 

Where:
x : Data point to be transformed
μ : Mean of the dataset
σ : Standard deviation of the dataset
z : Z-score (the transformed value)

The Z-score indicates how many standard deviations a data point is away from the mean. A positive Z-score means the data point is above the mean, 
while a negative Z-score means it is below the mean. A Z-score of 0 indicates that the data point is equal to the mean.

The Z-scoring transformation makes the distribution of the dataset closer to a standard normal distribution, ensuring that data used for statistical analysis 
and modeling are on similar scales. This allows for more accurate analysis and comparison of data with different magnitudes.

Z-scoring transformation is commonly used in machine learning and statistical analysis. It is often applied during data preprocessing to standardize 
and normalize the dataset. Additionally, it is employed to improve the performance of certain algorithms and reduce the impact of data dependence.




