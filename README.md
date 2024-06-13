# PPM-HOSPITAL  

![PyPI - Python Version](https://img.shields.io/badge/python-3.12-3776AB?logo=python)

## > Scripts
```01_data_preprocessing.ipynb```: Analyses and filter initial event log (saved in ```DATA_DIR```).  
The script adds the accumulated time in hours and days to the original data for each case-id activity in ```DATA_LOG_DIR/*_filtered.csv```.  
The script also generates the file ```DATA_LOG_DIR/*_total_time.csv``` containing, for each case-id the total number of activities and the total time of the case-id in hours and days.  

```02_data_prefix.ipynb```: Given an event log, it extracts its 'prefix' (the first n events) and save it in ```DATA_LOG_DIR```.  
 
```03_data_encoding.ipynb```: Encodes the event log and save it in DATA_LOG_ENCODED_DIR. Set the variable ```encoding``` to 'B' = binary, 'F' = Frequency, 'I' = simple Index.   

### > Script Dependencies
See ```requirements.txt``` for the required libraries (```pip install -r requirements.txt```).  
