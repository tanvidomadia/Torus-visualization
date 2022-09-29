# Torus-visualization

This script visualizes the student performance in MCQs and Single Responses from an OLI Torus course. It takes the raw Torus data download as input and generates item analysis for MCQs and list of single responses within the course.

Running the script in Windows command line: 
1. Download the Github repository in your local system in a new folder and delete the raw_analytics.csv file. 

2. Ensure python3 with pip, pandas, matplotlib and fpdf is installed in your system. If python along with the relevant packages is not installed, follow the below steps: 
a. Install python by following steps mentioned in https://www.digitalocean.com/community/tutorials/install-python-windows-10 
b. Install pip by following steps mentioned in https://www.geeksforgeeks.org/how-to-install-pip-on-windows/ 
c. Install pandas by using the command: pip install pandas
d. Install matplotlib by using the command: pip install matplotlib
e. Install fpdf by using the command: pip install fpdf

2. Download the raw data file from your Torus course by selecting Improve --> Insights --> Download Raw Data

3. Unzip the file, extract the raw_analytics file and save as CSV in the same directory as the script. 

4. Run the python script: python torus_visualize.py 
or py torus_visualize.py

5. The output pdf (torus_visualize_output.pdf) will be in the above directory along with the other image files and data files. 


