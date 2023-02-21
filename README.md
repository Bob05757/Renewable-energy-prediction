# Rewable-energy-prediction
1. The innovation of this competition is to propose a labeling technology (clustering), which can refer to our published paper (A novel short-term load forecasting framework based on time-series
clustering and early classification algorithm, https://doi.org/10.1016/j.enbuild.2021.111375)

2. According to the existing characteristic variables (temperature, wind speed, etc.), first predict the label (0, 1) of the daily solar power generation load, 0 represents low power generation, and 1 represents high power generation. This label is used as the input feature variable when predicting.

3. At the same time, feature engineering was done, including the shift of feature variables, adding more dimensional feature variables

4. Afterwards, we also did research on the integrated model, and found that the integrated model did not achieve better results, but lightgbm scored the highest, so we did not integrate

PS: Although in the integrated model, higher scores can be obtained by setting the weights of different models, we think that this result only performs better on the existing data set, and the effect of changing the data set may be worse, that is,
Poor generalization ability. Therefore, we did not adopt this method, but started more from feature engineering, mining useful information as much as possible to improve the accuracy of the model. Although we used a separate linghgbm model, we
We have achieved good results in both the preliminary and semi-finals, so we have reason to believe that our proposed model has good generalization performance. The proposed labeling technology works well and is one of our major innovations.
