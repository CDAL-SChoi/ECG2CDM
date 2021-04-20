# ECG2CDM
A Standardization Tool for Automated 12-lead Electrocardiogram Interpretation Data through Common Data Model (For ECG interpretation data)

This is a code of making PyQT Program for mapping EKG Diagnostic data to CDM concept code.   
The currently acquired interpretation ontology data was extracted from GE Healthcare, Philips, and Nihon Kohden.


### The software can be found in http://cdal.korea.ac.kr/ECG2CDM/   
**ECG2CDM** is the name of the executable program.


You may execute program with 'executable_ECG2CDM.py'.   
The main progress of the code is as followed:
  1. Read the patient diagnostic data in form of csv file or xlsx file
  2. Map to CDM code by comparing ontology data and diagnostic interpretation data
  3. Output the mapped data according to each patient


The details of Step 2 are shown in the following image:   
![Flowchart_combined](https://user-images.githubusercontent.com/50295574/112262049-54d04480-8cb0-11eb-9514-6f965482b549.png)

Here, the threshold was huristically set to 90%.   


Note that this code is based on bata version.
