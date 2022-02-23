## Tactile Sensor Calibration using ML  
**Description**: <br /> 
Calibrating sensors physically is a time consuming process, especially for a distributed sensor with many measurements. In this project, I attempt to use ML to calibrate the sensors.<br /> 

Since it's a regression problem, I implemented a number of ML regression algorithms and compare their performance. Namely, Linear Regression, SGD Regression, Quadratic Huber Regression, and Neural Network were implemented. 

**Data**: <br /> 
There is two catagories of data used in this project:<br />
1- The refrence data; obtained from Nano 1.5/1.5, a 6-axis force/torque (F/T) sensor from BL Autotech.<br />
2- The real-life data; measured from the companys'sensors that needs to be calibrated.<br />
Some preprocessing and normalization has been done on the data. The datasets are not included due to confidentiality. 


**Requarments**: <br />
Python <br />
TensorFlow <br />
Numpy <br />
Matplotlib <br />
Scipy <br />
Scikit-learn <br />
