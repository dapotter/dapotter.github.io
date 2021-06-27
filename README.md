# [Golf Score Prediction](https://github.com/dapotter/Golf-score-predictor)

This project is a golf score predictor (GSP) for each hole played by each player in a PGA Tour tournament using weather, player skill, and golf course hole difficulty features in random forest and gradient boosting tree models. By one-hot encoding categorical features and using PCA to reduce the feature load, an accuracy and precision of 58% and a log-loss of 1.05 is achieved for the 2018 US Open at Shinnecock Hills.

# [Fire Weather Prediction](https://github.com/dapotter/Fire-weather)

Fire weather prediction in OR and WA state using synoptic weather variables such as geopotential height at 500 hPa (H500), surface pressure reduced to mean sea level (PMSL), and convective available potential energy (CAPE). Longitude and latitude gradients for both H500 and PMSL are used, not the downloaded point values, as the gradients drive surface level winds leading to high-risk fire conditions. CAPE is added to include the effect of thunderstorm activity which delivers dry electrical storms in the summer time, causing the majority of burned acreage during a fire season. I used an LSTM model on data from 1979 to one month from the present present to predict fire weather for the current month.

![](/Plots/latlon_subset_OR_WA_display_small.png)
