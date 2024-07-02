# Social-Media-Analysis-Dashboard
Overview
This project involves building a social media analytics dashboard to identify and visualize networks of accounts that promote specific links, hashtags, keywords, or topics on various social media platforms. The dashboard helps in examining, visualizing, and identifying patterns in media reliability scores from a list of unreliable news providers.

Project Structure
The project is organized as follows:

bash
.
├── data
│   ├── collected_data.csv          # Collected social media data
│   ├── analyzed_data.csv           # Analyzed social media data
│   ├── top_accounts.csv            # Top accounts by total interactions
├── plots
│   └── top_accounts.png            # Visualization of top accounts
├── src
│   ├── data_collection.py          # Script to collect social media data
│   ├── data_analysis.py            # Script to analyze collected data
│   └── visualization.py            # Script to visualize the analysis results
├── README.md                       # Project overview and instructions
└── requirements.txt                # List of required Python packages
Requirements
Ensure you have the following Python packages installed:

requests
beautifulsoup4
pandas
matplotlib
seaborn
You can install these packages using pip:


pip install -r requirements.txt
Data Collection
The data_collection.py script fetches trending posts from ShareChat. Run the following command to collect data:


python src/data_collection.py
This will save the collected data to data/collected_data.csv.

Data Analysis
The data_analysis.py script analyzes the collected data. Run the following command to analyze the data:


python src/data_analysis.py
This will save the analyzed data to data/analyzed_data.csv and the top accounts to data/top_accounts.csv.

Data Visualization
The visualization.py script visualizes the top accounts by total interactions. Run the following command to create the visualization:

python src/visualization.py
This will save the visualization to plots/top_accounts.png.

Usage
Collect data from ShareChat:

python src/data_collection.py
Analyze the collected data:

python src/data_analysis.py
Visualize the analysis results:

python src/visualization.py
Repository
The project repository contains:

Source code for data collection, analysis, and visualization.
A directory for storing collected and analyzed data.
A directory for storing generated plots.
# Video Demonstration
https://youtu.be/O7_jguIlJKs

Author
Aryen Garg

