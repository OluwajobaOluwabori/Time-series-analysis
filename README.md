## Kaggle Project Statement
Often times, we always ask how do these National Electricity Distribution agencies measure and generate the bills the serve to their customers. Out of our inquisitive nature as man, we would realy like to know. It is not rocket science - because our bills are generated based on energy consumption in our household over a given period of time. So, how can i know what contribute to most energy consumption in my household? This is an important question that requires a holistic answer.

Context: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

# Time-series-analysis
I explored and built a time series forecasting model for measurements of electric power consumption in one household with a one-minute sampling 
rate over a period of almost 4 years.
This data represents a multivariate time series of power-related variables which could in turn be used to model, and even forecast future electricity consumption.

## Data Set Information

Data Link: https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

This archive contains 2075259 measurements gathered between December 2006 and November 2010 (47 months).

Notes:

1. (globalactivepower*1000/60 - submetering1 - submetering2 - submetering3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.

2. The dataset contains some missing values in the measurements (nearly 1.25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

Attribute Information:

date: Date in format dd/mm/yyyy  
time: time in format hh:mm:ss  
globalactivepower: household global minute-averaged active power (in kilowatt)  
globalreactivepower: household global minute-averaged reactive power (in kilowatt)  
voltage: minute-averaged voltage (in volt)  
global_intensity: household global minute-averaged current intensity (in ampere)  
submetering1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).  
submetering2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.  
submetering3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.<br>
