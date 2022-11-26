# Data Generators:

All the programs in this repository uses the openpyxl library to store the generated data into a datasheet for use later.

openpyxl is a Python library to read/write .xlsx/xlsm/xltx/xltm files.
More info on openpyxl: https://openpyxl.readthedocs.io/en/stable/

1. **body_weights_random.py**:

    This program generates 100 random samples of body weights between 120 to 250 lbs and stores them in a .xlsx datasheet. The boundries of the body weight can be changed according to need. The data should generate normally distributed data 
which can be used in statistical analysis.

2. **time_interval_random.py**:

    This program generates 100 random time intervals from 9am to 6pm with the difference between consecutive time intervals to be between 200 seconds to 350 seconds. The bounds can be changed to show exponential distribution according to your need. The generated data is stored in a datasheet.


    
