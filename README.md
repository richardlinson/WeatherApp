# Weather App

A simple desktop weather application built with Python and Tkinter. Enter a city
to view its current temperature, weather conditions, humidity, and wind speed
using the OpenWeather API.

## Requirements

- Python 3
- An OpenWeather API key
- Tkinter (included with most standard Python installations)

## Setup

Install the Python dependency:

```powershell
python -m pip install -r requirements.txt
```

Set your API key in PowerShell, then launch the app:

```powershell
$env:OPENWEATHER_API_KEY = "your_api_key"
python weatherapp.py
```

On macOS or Linux, set the environment variable with:

```sh
export OPENWEATHER_API_KEY="your_api_key"
python weatherapp.py
```

Keep your API key private. Do not commit it to the repository.
