# Weather Dashboard

Welcome to the Weather Dashboard Repository!

This tool is designed to streamline the process of extracting detailed weather forecasts for 200 cities worldwide over the next 15 days, analyzing 25 key weather features. Whether you're a researcher, data analyst, or enthusiast looking to gather insights, this dashboard has you covered.

## 🌍 Overview

This project displays a real time 15-day weather forecast for 200 cities worldwide, analyzing 25 key weather features. The data is extracted using the Visual Crossing Weather API, processed in Python, and visualized in Power BI with automated alerts for extreme weather conditions.

## 🚀 Features

### User Input

The script first pulls real-time weather data using a Python API script. This includes 25 features.

### Data Retrieval

The Python script fetches the latest weather data, processes it, and sends it to Power BI using Power Query for transformation.

### Multithreading

To expedite the data extraction process, the scraper utilizes multithreading, enabling concurrent execution of API calls for multiple cities.

### Comprehensive Data Collection

The script extracts detailed information on weather conditions, wind patterns, precipitation levels, temperature variations and much more for 15 days.

### Data Aggregation

As data is retrieved, it is aggregated and formatted into structured datasets for visualization in Power BI.

### Dashboard Visualization

Power BI presents real-time insights in an interactive dashboard containing 4 key worksheets in report:

- **Rain**: Displays forecasted precipitation for each city.
- **Snow**: Analyzes snowfall predictions.
- **Wind**: Tracks wind speed and direction trends.
- **Temperature**: Shows temperature fluctuations over 15 days.

### Email Alerts via Power Automate

The system triggers email notifications for significant temperature drops in selected cities, enabling proactive weather monitoring.

## 🧭️ Tech Stack

- **Python**
- **Power BI**
- **Power Automate**

## 🛠️ Contribution
We welcome contributions from the community to enhance and improve this tool further. Whether it's adding new features, optimizing performance, or fixing bugs, your contributions are highly appreciated. Please refer to the contribution guidelines in the repository for more information on how to get involved.

## 📝 Feedback
Your feedback is essential in helping us improve the WeatherDashboard. If you encounter any issues, have suggestions for new features, or simply want to share your experience using the tool, don't hesitate to reach out to us through the GitHub repository's issue tracker.
