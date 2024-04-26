# System-Performance-Monitoring
This project aims to monitor live system performance using Python, SQL, and Power BI.


This project provides a comprehensive system performance monitoring solution using Python, SQL, and Power BI. It collects real-time data on CPU usage, memory usage, network activity, and disk usage from the local system and visualizes it using Power BI for easy analysis and interpretation.

#Features
Real-time Data Collection: Python script (system_performance.py) continuously collects system performance data.
Data Storage: Data is stored in a MySQL database for historical analysis and long-term trend monitoring.
Visualization: Power BI report (system_performance_report.pbix) offers visual insights into system performance metrics with interactive charts and graphs.
Project Structure
system_performance.py: Python script responsible for collecting system performance data using libraries such as psutil and inserting it into the MySQL database.
system_performance_report.pbix: Power BI report file for visualizing system performance metrics.
README.md: Detailed information about the project, including usage instructions and requirements.

#Usage
Python Script (system_performance.py):
Ensure Python 3.x is installed on your system.
Install the required Python libraries using pip install -r requirements.txt.
Update the MySQL database credentials in the script if necessary.
Run the script using python system_performance.py to start collecting system performance data.
Power BI Report (system_performance_report.pbix):
Download and install Power BI Desktop from here.
Open the system_performance_report.pbix file in Power BI Desktop.
Use the provided data connections to connect to your MySQL database.
Customize the report layout and visuals as needed.
Save and publish the report to share with others or schedule automatic data refreshes.

#Requirements
Python 3.x
MySQL Database
Python libraries: mysql-connector-python, psutil

#Contributing:
Contributions to enhance and extend the functionality of this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.
