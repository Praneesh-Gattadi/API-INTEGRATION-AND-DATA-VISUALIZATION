# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Gattadi Praneesh

*INTERN ID*: CT04DM1319

*DOMAIN*: Python Programming

*DURATION*: 4 Weeks

*MENTOR*: NEELA SANTOSH

# Weather Dashboard with Streamlit & OpenWeatherMap API

This project is a real-time Weather Dashboard built using Python and Streamlit, integrated with the OpenWeatherMap API. It allows users to view live weather conditions of any city, displays a range of weather parameters, and presents interactive data visualizations of mock historical trends using Seaborn and Matplotlib.

## Features

- Fetch current weather data for any city
- Show temperature, humidity, pressure, wind speed, visibility, sunrise/sunset, description
- Display weather icon dynamically
- Generate and display mock historical trends
- Visualize trends using Seaborn line plots
- Download data as CSV
- Cache API responses for speed
- Responsive and clean UI

## Tech Stack

| Technology   | Description                              |
|--------------|------------------------------------------|
| Python       | Backend logic                            |
| Streamlit    | Frontend web app framework               |
| OpenWeatherMap API | Real-time weather data provider  |
| Pandas       | Data manipulation                        |
| Matplotlib   | Visualization toolkit                    |
| Seaborn      | Enhanced statistical visualizations      |
| Requests     | HTTP API requests                        |

## Installation & Setup

**Step 1: Download the Project Code**
Go to the folder where you want to keep the project, then open a terminal or command prompt and type:
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
If you don’t use Git, you can also manually download the ZIP file from GitHub and unzip it.

**Step 2 (Optional): Create a Virtual Environment**
This is to keep your project packages separate from other Python projects.
python -m venv venv
Then activate it:
Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
You will now see something like this in your terminal:
(venv) your-computer:weather-dashboard$

**Step 3: Install All Required Libraries**
Run this command to install everything needed:
pip install -r requirements.txt
This installs:
- streamlit
- requests
- pandas
- matplotlib
- seaborn

**Step 4: Get a Free API Key from OpenWeatherMap**
Visit: https://openweathermap.org/api
Sign up (free)
Go to your profile > API keys
Copy your API key
Now open weatherproject.py in any code editor and replace this line:
API_KEY = "your_api_key_here"
With:
API_KEY = "your_actual_api_key"

**Step 5: Run the App**
In the terminal, type:
streamlit run weatherproject.py
This will open the app in your browser at http://localhost:8501.










