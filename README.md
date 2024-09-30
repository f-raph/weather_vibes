# Weather & Vibes

This project is a Django-based web application that aggregates weather data and news headlines. It provides users with optimal times for outdoor activities based on weather conditions and displays the latest news headlines.

## Features

- Fetches and displays weather data including temperature, humidity, and conditions.
- Suggests suitable activities based on weather conditions.
- Aggregates and displays the latest news headlines.
- User-friendly interface for easy navigation.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/f-raph/weather_vibes.git
   cd weather_vibes
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

## Usage

1. **Access the application:**

   Open your web browser and go to `http://127.0.0.1:8000/`.

2. **View Weather Data:**

   - The homepage displays the current weather conditions and suggests suitable activities.

3. **View News Headlines:**

   - Scroll to the news section to see the latest news headlines.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Acknowledgements

- Weather data provided by OpenWeather.
- News headlines provided by NewsAPI.

## Contact

For any questions or suggestions, please contact f-raph.
