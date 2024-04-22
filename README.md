

**Project Title:** Bar Crawl Analysis

**Overview:**
This project involves a comprehensive analysis of accelerometer and transdermal alcohol content (TAC) data to explore the correlation between participants' physical movements and their alcohol consumption levels. The aim is to understand how alcohol consumption affects motor activities during a bar crawl.

**Data Collection and Preparation:**
Data was sourced from accelerometer sensors capturing x, y, and z-axis movements, along with timestamps and participant IDs (PIDs). We also utilized TAC data representing alcohol levels. The initial phase involved cleaning and standardizing the data, followed by a detailed merging process where accelerometer data was combined with corresponding TAC readings based on matching timestamps.

**Analysis Techniques:**
The analysis was performed using several advanced techniques:
- **Data Merging:** Individual datasets for each participant were merged with their accelerometer data.
- **Graphical Representations:** Visual plots were generated to depict the x, y, z acceleration and TAC readings over time, highlighting the patterns and intensity of physical movements in correlation with alcohol levels.
- **Entropy and Complexity Calculations:** We applied permutation entropy and complexity measures to segments of the data to assess the unpredictability and complexity of movement patterns under the influence of alcohol.

**Results and Findings:**
The project successfully demonstrated a methodical approach to merging and analyzing complex sensor data. The graphical outputs and entropy metrics provided deep insights into the behavioral changes induced by alcohol consumption during social events such as bar crawls.

**Technologies Used:**
- Python programming language
- Libraries: NumPy, Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

This project highlights the potential of wearable technology in monitoring and understanding human behavior in real-world scenarios, particularly in relation to alcohol consumption and its effects.
