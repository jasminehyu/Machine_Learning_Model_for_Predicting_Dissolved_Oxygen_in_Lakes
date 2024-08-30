# Predicting Dissolved Oxygen Dynamics in Lake Mendota using Transfer Learning
### The project explores transfer learning models for predicting dissolved oxygen levels in Lake Mendota. 

- The approach addresses the challenge of limited data in environmental science by transferring underlying trends from related environments, enhancing prediction accuracy and reliability even with sparse target environment data. 

- The method involves pre-training the model with data from various lakes and fine-tuning it with Lake Mendota-specific data. Integrating scientific knowledge, such as understanding environmental factors affecting DO levels, into the machine learning process, offering improved predictions. 

- The findings demonstrate that transfer learning not only enhances prediction accuracy but also promotes scientific research and technological innovation with more precise and interpretable models.

### Data Sources
-  Data were collected from two primary sources: high-frequency datasets and [low-frequency datasets](./lakes21_parquet/LowFrequency)

### Data Preprocessing
- [Data preprocessing](./20_lakes_data.Rmd) involved the following key steps to ensure consistency and usability:
  1. Data Filtering
  2. Downsampling
  3. Data Merging
  4. Interpolation
 
This preprocessing resulted in two datasets: one specific to Lake Mendota with hourly measurements of surface DO, temperature, TP, TN, and Secchi depth, and another encompassing the same variables for the other 13 lakes.

