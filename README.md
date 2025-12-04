# weather-data-visualizer-
A simple Python project that analyzes weather data using pandas, numpy, and matplotlib. It loads a CSV file, cleans the data, calculates basic statistics, and visualizes trends like temperature, rainfall, and humidity.

📂 Project Structure
weather_project/
│
├── weather_analyzer.py     # Main Python script
├── weather.csv             # Weather dataset
└── README.md               # Project documentation

📌 Features
Load weather data from CSV
Clean missing or invalid values
Convert date column to datetime format

Calculate:
Mean Temperature
Maximum Temperature
Minimum Humidity
Standard Deviation of Rainfall
Generate visualizations:
Daily Temperature Trend
Monthly Rainfall Bar Chart

🛠 Technologies Used
-Python
-pandas
-numpy
-matplotlib
▶ How to Run the Project
1. Install required libraries:
pip install pandas numpy matplotlib
2. Make sure weather.csv is in the same folder as your script.
3. Run the program:
python weather_analyzer.py

📊 Output Files Generated
The script automatically saves the following files:
temp_trend.png
monthly_rainfall.png
humidity_temp_scatter.png
Cleaned dataset: cleaned_weather.csv

✨ Sample Dataset Format
Date,Temp,Humidity,Rainfall
2024-01-01,22,55,0
2024-01-02,24,58,2
2024-01-03,23,52,0
<img width="1918" height="1079" alt="Screenshot 2025-12-04 092219" src="https://github.com/user-attachments/assets/1c1373a7-4376-4a3f-89f3-b406025d560d" />


Humidity vs Temperature Scatter Plot
