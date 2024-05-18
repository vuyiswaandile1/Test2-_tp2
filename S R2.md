#### Categorical Data
Column: `settlement_name`
Description: Categorical data represent discrete categories or labels. In this dataset, `settlement_name` categorizes different informal settlements. This type of data is typically encoded into numerical values using techniques like one-hot encoding or label encoding before being used in machine learning models.

#### Numerical Data
Column: `population_density`
Description: Numerical data represent quantitative values. In this dataset, `population_density` provides the number of people per unit area, which is a continuous variable. Numerical data can be directly used in machine learning models and often require normalization or standardization to ensure that all features contribute equally to the model.

#### Normalized Data (Feature Scaling)
Column: `population_density_normalized` (after normalization)
Description: Normalized data scales numerical values to a specific range, usually [0, 1] or [-1, 1]. In this dataset, `population_density_normalized` is obtained by scaling the `population_density` column using Min-Max scaling. Normalization ensures that all features contribute equally to the model and helps in faster convergence during training.

