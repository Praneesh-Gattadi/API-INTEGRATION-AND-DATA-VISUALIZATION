# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Gattadi Praneesh

*INTERN ID*: CT04DM1319

*DOMAIN*: Python Programming

*DURATION*: 4 Weeks

*MENTOR*: NEELA SANTOSH

# Weather Dashboard with Streamlit & OpenWeatherMap API

This project is a Weather Dashboard built using Python and Streamlit. It integrates with the OpenWeatherMap API to fetch real-time 
weather data, and uses Matplotlib for data visualization. The dashboard displays current weather conditions along with mock historical 
trends for temperature, humidity, and precipitation.

## Features

- Fetch real-time weather data from **OpenWeatherMap**
- Visualize temperature, humidity, and precipitation trends using **Matplotlib**
- Generate **mock historical data** based on current weather
- Download weather data as a **CSV file**
- Simple and responsive **Streamlit UI**
- Error handling and **API key protection** using `.env` file
- Caching with `@st.cache_data` for better performanc

## Technologies Used

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Matplotlib](https://matplotlib.org/)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [pandas](https://pandas.pydata.org/)
- [dotenv](https://pypi.org/project/python-dotenv/)

🚀 Getting Started (Step-by-Step Guide)
Follow these instructions to set up and run the Weather Dashboard on your local machine.

**Prerequisites**
Before you begin, ensure you have the following installed:
Python 3.8+: Download Python
Git: Download Git (optional, for cloning)
OpenWeatherMap API key: Free API key from openweathermap.org

**1. Clone or Download the Repository**
Using Git (recommended):
git clone https://github.com/yourusername/weather-dashboard.git
cd weather-dashboard
Or, download the ZIP file from GitHub and extract it.

**2. Set Up a Virtual Environment (Optional but Recommended)**
Create a virtual environment named "env"
python -m venv env
Activate the virtual environment
On Windows: env\Scripts\activate
On macOS/Linux: source env/bin/activate

**3. Install Python Dependencies**
Make sure you are in the project folder, create a txt file as:
streamlit
requests
pandas
matplotlib
python-dotenv
Save this as requirements.txt.

**4. Get Your OpenWeatherMap API Key**
Sign up at https://openweathermap.org/api
Go to your profile > API Keys
Copy your default API key (or generate a new one)

**5. Create a .env File for Your API Key**
Create a .env file in the root folder of your project:
OPENWEATHER_API_KEY=your_api_key_here #paste your own api key
❗ Important: Never commit your .env file to GitHub. Add it to .gitignore.
Example .gitignore entry:
.env

**6. Run the Weather Dashboard**
Start the app using Streamlit:
streamlit run app.py # replace filename with app.py
You should see a new tab open in your browser at http://localhost:8501, showing the weather dashboard.

#OUTPUT

![Image](https://github.com/user-attachments/assets/bb60e79c-873a-4226-acc7-cf7e443f6e3f)


![Image](https://github.com/user-attachments/assets/3cf8a3e6-b61b-4cc7-a67f-d1d53a410254)


![Image](https://github.com/user-attachments/assets/9e2e5f88-239c-4b53-bfde-96e32fd94a6c)
















