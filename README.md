# ISS-Tracking-System

🛰️ ISS Tracking System

A real-time web application to track the International Space Station (ISS) on a world map using Python, Dash, Plotly, and API integration.

🚀 Features

Fetches live ISS coordinates from the Open Notify API

Updates the ISS position every few seconds

Displays the ISS path (trail) on an interactive world map

Built using Dash + Plotly for real-time visualization

🛠️ Tech Stack

Python 3

Dash (Plotly)

Requests (API fetching)

Pandas (data handling)

📦 Installation

Clone the repository:

git clone https://github.com/your-username/iss-tracking-system.git
cd iss-tracking-system


Create a virtual environment and install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the Dash app:

python app.py


Then open your browser and go to:

http://127.0.0.1:8050/


You’ll see the live ISS position updating on the map 🌍.

📂 Project Structure
📁 ISS-Tracking-System
 ┣ 📜 app.py           # Main application file
 ┣ 📜 requirements.txt # Dependencies
 ┣ 📜 README.md        # Project documentation
 ┗ 📂 assets/          # (Optional) CSS/JS for Dash

📊 Demo

🔗 YouTube Demo: [Your YouTube Link]
💻 GitHub Repository: [Your GitHub Link]

📌 API Reference

Data is fetched from Open Notify ISS API
.

✨ Future Improvements

Add ISS visibility prediction (when visible from user’s location)

Show crew members onboard

Add 3D globe visualization
