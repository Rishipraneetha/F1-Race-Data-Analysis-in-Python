🏎️ Formula 1 Telemetry Analysis & Visualization using FastF1
📌 Overview
This project analyzes real-world Formula 1 race data using the FastF1 Python library. It focuses on extracting, processing, and visualizing telemetry data such as speed, throttle, braking, and lap times to gain insights into driver performance.
🚀 Features
📊 Driver performance comparison
⚡ Speed vs Distance visualization
🧠 Telemetry analysis (Throttle, Brake, Speed)
⏱️ Fastest lap extraction
📉 Lap time distribution analysis
🔍 Delta time comparison between drivers
🛠️ Tech Stack
Python
FastF1
Pandas
Matplotlib
Google Colab
⚙️ Installation & Setup
1. Install dependencies
pip install fastf1
2. Enable cache and load session
import os
import fastf1 as ff1

os.makedirs('cache', exist_ok=True)
ff1.Cache.enable_cache('cache')

session = ff1.get_session(2023, 'Monaco', 'R')
session.load()
📊 Example Visualizations
Speed vs Distance
Compares speed of drivers across the track
Helps identify performance in straights vs corners
Throttle & Brake Analysis
Shows driving style
Identifies aggressive vs smooth driving
Delta Time Plot
Shows time difference between drivers at each track point
📂 Project Structure
├── notebooks/
│   └── analysis.ipynb
├── cache/              # FastF1 cached data
├── images/             # Saved plots
└── README.md
🧠 Key Learnings
Working with real-world sports data
Data cleaning and filtering using Pandas
Visualizing telemetry data effectively
Understanding performance insights from raw data
📈 Future Improvements
Add interactive dashboards (Plotly/Streamlit)
Analyze tire strategies and pit stops
Automate multi-race comparisons
Build a web-based visualization tool
🎯 Use Cases
Data analysis portfolio project
Sports analytics exploration
Interview demonstration project
🤝 Contributing
Feel free to fork this repo and experiment with different races, drivers, and visualizations!
⭐ Acknowledgements
FastF1 library for providing access to F1 data
Official Formula 1 data sources
📬 Contact
If you found this project useful, feel free to connect or give a ⭐ to the repo!
