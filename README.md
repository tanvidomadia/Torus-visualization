# Torus-visualization

This script visualizes the student performance in MCQs and Single Responses from an OLI Torus course. It takes the raw Torus data download as input and generates item analysis for MCQs and list of single responses within the course.

Using the script in Windows command line (ensure python3 with relevant packages is installed on your system)

1. Download the raw data file from your Torus course by selecting Improve --> Insights --> Download Raw Data
2. Unzip the file, extract the raw_analytics file and save as CSV in the same directory as the script (Replace the exisiting raw_analytics.csv with this new file). 
3. Run the python script: python torus_visualize.py 
4. The output pdf will be in the above directory along with the other image files and data files. 


