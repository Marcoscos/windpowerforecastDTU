# windpowerforecastDTU
The project´s work is based in the theory from the course taught at "02456 Deep Learning", at the Technical Unviersity of Denmark (DTU). The course is graded based on the work contained in this repo, a report presented in scientific literature format and a presentation through a poster, also included in the repo. The overall mark is 12/12, the highest possible mark.

The project's aim is to forecast wind power 48-hours ahead and allow for optimal price selection for selling electricity. The end goal is to obtain the most accurate forecast for the wind farm´s wind power. From an academic point of view, we are interested in defining a benchmark of wind power forecasting with relatively simple CNN and LSTM models, and identify the best approach, Time Series or Regression-focused.

The project is divided into two notebooks, which correcspond to the Exploratory Data Analysis (EDA.ipynb), in which we explore the dataset, define the data formats and begin the preparation of the dataset.
The second notebook, called Forecasting.ipynb, contains the Dataset generator, the creation of the batches, the definition of the model architectures, the predictions (forecasting) and the evaluation of the forecasts. 

The notebooks are slef-explanatory, meaning that each step performed along the ntoebooks contains notes and explanations, either in markdown or as regular # comments next to the code.

PS: For the best experience reviewing the notebooks, it is recommended to make use of the table of contents through nbextensions or using Colab or databricks. 


Authors:
Alvaro Carrera Cardeli, Marcos Ivorra Peleguer and Santiago Ribelles Garcia
