# Student Research Project

Title: Spectral Analysis of Non-linear, Non-stationary Time Series Data Using Hilbert-Huang Transform and Spectrogram.

Work Summary:

- To deeply understand the working, limitations and strengths of the Fourier Spectral analysis (FFT + Spectrogram) and able to write codes for FSA in Matlab and Python.
- To understand the working of the Hilbert Huang Transform and able to write codes for Hilbert Spectral Analysis (HSA) in Matlab and Python
- To apply these methods to artificial as well as natural time series signals to valuable generate insights
- Performance comparisons of both the algorithms / Frameworks. 
- Finding out about the limitations of HHT and recent research in HHT to overcome these shortcomings.
- Apply these methods to sensor data from offshore Wind Turbines (accelerometer, temperature, pressure sensors) and generate insights.

### Data Analysis of Artificially generated signal

FSA and HSA was applied to artificially generated signals. These signals were generated by a combination sinusoids.

### Analysis of sensors data from offshore wind turbines

Data sets of natural signals were obtained from In-Situ-Wind project of SHM department of University of Siegen. 
The datasets were meant to be used for student research project only. They were obtained by the permission of Prof. Dr-Ing Peter Kreamer.

![5 11_Wind_Turbine_Data_Structure](https://github.com/Vishusharma296/Studienarbeit_HHT_Spectrogram_WT/assets/73486657/355fcb03-be26-4c2f-8912-dd32c50c98de)


### Main contents of the repository

- Latex source file of the report
- Research Papers and Books
- Matlab codes for data analysis (live script mlx files)
- Jupyter notebooks for data analysis (python)
- Images of the data analysis results
- Notes - Presentations and scanned
- CSV files from Offshore-Wind Turbine data. These CSVs were extracted from two large Data Structures in Matlab files/tables. These CSVs contains the following sensor data:

- D1--- Data set 1, obtained on 24-01-2022
- D2--- Data set 2, obtained on 29-01-2022

- Acc---Acclerometer data
- DMS---Strain gauge data
- INC--- Inclination data
- Temp--- Temperature data
- EOC--- Environmental operating conditions data

Only relevant parts of the datasturcture were converted and extracted into CSVs. These files were later analysed by applying Hilbert Huang Transform and Spectrogram for a comparitive study.
