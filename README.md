# Weather Project ☀️🌧️

A Django-based weather application that fetches real-time weather data and 5-day forecasts for multiple cities using the OpenWeatherMap API.

## Features ⚡

- **Real-Time Weather Data**: Fetches and displays current weather conditions for user-specified locations.
- **Responsive Design**: User-friendly interface compatible with various devices.
- **Modular Structure**: Organized codebase for scalability and maintainability.

## Technologies Used 🛠️

- **Backend**: Python (Django Framework)
- **Frontend**: HTML, CSS
- **API**: OpenWeatherMap

## Installation ⚙️

1. **Clone the repository**:

   ```bash
   git clone https://github.com/rajkelawala/Weather_project.git
   cd Weather_project
   ```

2. **Create and activate a virtual environment**:

     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Create migrations**:

   ```bash
   python manage.py makemigrations
   ```

5. **Apply migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

7. **Access the application**:

   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage 🎯

- **Search for Weather Information**: Enter the desired city or location in the search bar to retrieve current weather data.
- **View Weather Details**: The application displays temperature, humidity, weather conditions, and more.

## Project Structure  📂

```
Weather_project/
├── wether_project/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── wether_app/
│   ├── __pycache__/
│   ├── migrations/
│   ├── static/
│   │   ├── style.css
│   ├── templates/
│   │   ├── city_weather.html
│   │   ├── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│
├── .gitignore
├── db.sqlite3
├── manage.py
└── requirements.txt
```

## Contributing 🌍

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch**:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make your changes and commit them**:

   ```bash
   git commit -m 'Add some feature'
   ```

4. **Push to the branch**:

   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Open a Pull Request**.

## License 📝

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact 📩

Developed by Raj Kelawala. For any inquiries or feedback, please contact me at [rajkelawala28@gmail.com](mailto:rajkelawala28@gmail.com).

