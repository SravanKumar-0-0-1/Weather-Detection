# Weather-Detection
# Weather App

A simple weather forecasting application built with PyQt5 that fetches real-time weather data using the OpenWeather API.

## Features
- User-friendly GUI using PyQt5
- Fetches real-time weather data
- Displays temperature, weather conditions, and emojis for easy understanding
- Handles API errors and displays meaningful messages

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt

   
   ```

## Usage

Run the application:
```bash
python App.py
```

Enter the city name in the input field and click "Get Weather" to retrieve the weather information.

## Requirements

- Python 3.x
- PyQt5
- requests
- OpenWeather API Key

## API Key Configuration
This application uses OpenWeather API. Replace the `api_key` in `App.py` with your own API key:
```python
api_key = "your_api_key_here"
```

## Error Handling
The application handles various API errors such as:
- Invalid city name
- Network issues
- API rate limits

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature-branch`).
5. Submit a pull request.

## License

This project is licensed under the MIT License.

---

Enjoy using the Weather App! ☀️🌧️❄️

![Screenshot 2025-03-08 110454](https://github.com/user-attachments/assets/5545f5e8-fe18-4695-8e6c-6b08a3e83043)
![Screenshot 2025-03-08 105634](https://github.com/user-attachments/assets/78f63e9a-db2b-49b8-963f-3c0785ee3c5d)
![Screenshot 2025-03-08 105548](https://github.com/user-attachments/assets/4811de1a-4a35-4dc5-9a57-2d6ad72459e1)



