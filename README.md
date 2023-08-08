# Age-Related Conditions Prediction

## Description
The competition dataset contains anonymized health metrics linked to three age-related conditions, aiming to predict a binary outcome of the diagnosis. The dataset, sourced from the Behavioral Risk Factor Surveillance System (BRFSS), has been refined to focus on fifty-six health characteristics linked to these conditions. The primary goal is to predict a binary outcome of diagnosis:

- class 1: diagnosed with one of the three conditions
- class 0: no diagnosis
  
## Code

The code starts by importing essential libraries for data analysis, modeling, and plotting. It then reads the dataset, cleans the data, and displays it for a preliminary view. 

The top 25 important variables are identified using ANOVA. The data imbalance is corrected to avoid bias, and the data is normalized. The code then proceeds to build various models, followed by hyperparameter tuning to optimize the models' performance.

This code emphasizes the importance of understanding the underlying patterns within the data, which could potentially lead to better diagnostic tools or interventions for age-related conditions in the future.

[Code](Age_Related_Conditions.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
