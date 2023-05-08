# Wind Turbine Anomaly Detection using Machine Learning

This repository contains a part of my final project that focuses on the use of machine learning for wind turbine anomaly detection. I used two datasets: the Engie dataset and the Kelmarsh dataset.

## Datasets
I used two datasets in this project: the Engie dataset and the Kelmarsh dataset.
### Engie Dataset
The Engie La Haute Borne dataset contains data from a 21 MW wind farm located in Vaudeville-le-Haut commune, Meuse department, France. The wind farm contains 4 identical MM82 wind turbines from Senvion, each generating up to 2 MW of energy. The dataset includes measurements such as wind turbine name, date and time, average blade angle (Ba_avg), minimum blade angle (Ba_min), maximum blade angle (Ba_max), standard deviation of blade angle (Ba_std), average rotor temperature (Rt_avg), minimum rotor temperature (Rt_min), maximum rotor temperature (Rt_max), standard deviation of rotor temperature (Rt_std), and many more.
### Kelmarsh Dataset [1]
The Kelmarsh dataset contains data from the Kelmarsh wind farm in the UK. The dataset contains 10-minute SCADA and events data from the 6 Senvion MM92 wind turbines at Kelmarsh wind farm, grouped by year from 2016 to mid-2021. It includes measurements such as power output, wind speed, rotor speed, and other operational parameters of the wind turbines.

## Models
For the Engie Dataset, I used some clustering techniques for outliers detection and compaired the results just by visulsing the results because this dataset is not labled.

For the kelmarsh dataset, I implemented and trained several machine learning models, including:
- Long Short-Term Memory Autoencoder (LSTM-AE)
- Convolutional Neural Network (CNN)
- Artificial Neural Network (ANN)

## Results

(Brief summary of the results here)

## Conclusion

(conclusion here)

## Bibliography
[1]Plumley, Charlie, “Kelmarsh wind farm data”. Zenodo, Feb. 01, 2022. doi: 10.5281/zenodo.5841834.
