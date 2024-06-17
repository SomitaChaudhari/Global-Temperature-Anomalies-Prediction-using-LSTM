# Global Temperature Anomalies Prediction
**Project Description**: This project aims to predict global temperature changes using historical temperature anomaly data. By utilizing LSTM (Long Short-Term Memory) networks, we can model and predict future temperature anomalies based on past data.

**Libraries used**: Python, TensorFlow (Keras)
, NumPy, Matplotlib, Pandas.
*Tools Used:* Jupyter Notebook


**Methodlogy used**: The methodology involves data preprocessing, exploratory data analysis, data splitting, model building using LSTM networks, and visualization of the results.

- *Importing libraries* 
- *Loading, Preprocessing Data & EDA*: 
    - Loaded the dataset from the specified directory.
    -  Filtered the dataset to include only global temperature anomalies.
    - Selected the 'change temp' column for analysis.
    - Plotted the temperature changes over the years for different hemispheres.
    - Created a line graph to visualize temperature changes from 1880 to 2020.
- *Data preparation for LSTM*:
    - Split the dataset into training and testing sets in a 90:10 ratio.
    - Prepared the training and testing data for the model.- 
    - Created sequences of past 116 years' data to predict the next 10 years.
    - Reshaped the training data to fit the LSTM model.
- *Model Building & Training*: 
    - Built a sequential LSTM model with bidirectional LSTM layers and dropout for regularization.
    - Added multiple LSTM layers with dropout in between.
    - Compiled the model using 'adam' optimizer and 'mean_squared_error' loss function.
    - Trained the model with the training data for 500 epochs and a batch size of 32.
    - Fitted the model to the training data and monitored the training process.

- *Visualization*: 
    - Created bar plots to compare predicted and actual temperature changes.

- *Results* : 
   - The model was able to predict future temperature anomalies based on past data
   - Visualizations showed the effectiveness of the LSTM model in capturing the trend of temperature changes over the years.








