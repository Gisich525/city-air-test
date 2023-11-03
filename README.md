# city-air-test
The main parameters of the electrochemical sensor `SO2` are the voltage values at the working and auxiliary electrodes `SO2op1` and `SO2op2`. In addition to the main parameters, the sensor can be affected by the temperature and concentration of the cross gas `NO2`.
There are two files at your disposal:
- File with the results of laboratory calibration of the sensor - `G2.csv`.
- File with sensor readings in the field - `test.csv`
The examinee is asked to propose a model describing the concentration of `SO2` in the atmosphere taking into account the influence of external factors on the sensor and build a model forecast based on data collected in the field.
Task by points:
1. Read the files `G2.csv` and `test.csv`.
2. Propose a candidate model (with the exception of multiparameter linear regression) describing the dependence of the gas concentration `SO2` on the values of `SO2op1`, `SO2op2`, `T` and cross-gas `NO2`.
4. Compare the forecast of the resulting model with multivariable linear regression. The choice of comparison metrics is at the discretion of the examinee.
5. Construct graphs of model forecasts versus time on training and test samples.
6. Interpret the results obtained.
6. Draw conclusions.
----------
* Additional questions:
     - Evaluate the errors of the proposed model and linear regression.
     - How does the proposed model differ from linear regression?
     - What can be said about the training and test samples?

