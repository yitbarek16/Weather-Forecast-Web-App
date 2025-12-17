# Weather Forecast Web Application

## Overview

This Weather Web Application is a Django-based app that provides real-time weather information for any city using the OpenWeatherMap API. It displays current temperature, weather conditions, and icons through a clean and responsive interface.

## Features

- 🏙️ Search for current weather conditions in any city.
- 🌡️ Displays temperature, weather description, and an icon.
- 🔐 Handles API errors gracefully with default data and error messages.
- 📱 Responsive design using Bootstrap for a modern and clean user interface.

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (via Bootstrap)
- **API Integration**: OpenWeatherMap API
- **HTTP Client**: Requests

## Requirements

- Python 3.x
- Django 3.x or higher
- An active API key from [OpenWeatherMap](https://openweathermap.org/).

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yitbarek16/Weather-Forecast-Web-App.git
   
2. **Create and activate a virtual environment**:
     ```bash
     python -m venv venv
     source venv/bin/activate

3. **Install the requirements**
    ```bash
    pip install -r requirements.txt

4. **Add your OpenWeatherMap API key**:
   url = 'https://api.openweathermap.org/data/2.5/weather?q={}&units=metric&appid=YOUR_API'

5. **Run database migrations**:
     ```bash
     python manage.py migrate

6. **Start the development server**:
     ```bash
     python manage.py runserver
     
7. **Access the application**:
     Open your web browser and navigate to http://127.0.0.1:8000/.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---
Let's stay in touch! Feel free to connect with me on LinkedIn:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yitbarektesfaye)
