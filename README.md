# Noise-Removing-and-Deblurring
The submitted code is written in Python language, and is expected to work on any Python IDE
(like, Pycharm, Spyder, etc.)
- To run the code, one needs to install the following libraries:
(i) Matplotlib - Used to plot graphs
(ii) Pandas - Used to import the data file from the device
(iii) Math - Used to perform certain mathematical operations
Additionally, you may also need a library named, xlrd, since we are working with excel sheets.
- The data file should preferably be in excel format (with .xlsx extension).
The data file can be found and downloaded in xlsx format from the following link:
https://drive.google.com/file/d/1ejJT4sfR1OV08U_LnjOSomw_qR4jq0bA/view?authuser=0
- To import the file from your device, you have to replace line 18 with the following:
data=pd.read_excel(r'Location of the data file\File name.xlsx') #import data sheet
- Now, the program is ready to run
