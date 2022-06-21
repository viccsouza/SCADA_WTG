# SCADA Wind Turbine Generator

This is a basic notebook to:
- compile data from several excel files to a single dataframe
- extract only the needed columns
- transform some columns to the desired format and data type
- join the alarm code table to add the information of the system related to the alarm
- join the windfarm table to increment the name of the power plant related to the complex name
- reset the index after all transformations
- create the output file with the new dataframe

I used a single notebook for each SCADA System, I didn't unified both notebooks because I'd need to have two different outputs for later analysis.
Some easy improvements of the code are pending on the compilation of several files part, because at the time I did not have time to do it.
