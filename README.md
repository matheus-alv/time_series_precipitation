   # Time Series of Precipitation in São Paulo

This project is the python code for my undergradutate thesis for my bachelor in Computer Engineer. 

The goal was to create a time series model to best predict the monthly amount of rainfall precipitation for São Paulo city in the upcoming months. 

The dataset used for training and creating the model was obtained through BDMEP, which is the offical data base for INMET (National Institute of Meteorology). The data was subsequently treated for missing values using sources from conventional and automatic stations, which are different methods of measuring precipitation in any given day. 

The presumption was that a seasonal models would best fit the dataset, since besides correlations with the previous months,rainfall does have a seasonal component to it, as the amount of precipitation of a certain month has correlation to the same month from the previous year, as we can observe due to the planet seasons. Therefore this work contemplates the Facebook Prophet (it has a sarima model for comparisson purposes) considering .

The notebook contains the analysis and discussions of the time series components, as well as the model creation and performance evaluation. More detail can be found on the notebook itself.
