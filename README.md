☁️ Flutter Weather App
A simple, elegant weather application built with Flutter that fetches real-time weather data using the OpenWeatherMap API. The app demonstrates the use of asynchronous programming, REST API integration, and Material Design 3 UI components.
📱 Features
•
Real-time Weather Data: Fetches current temperature, humidity, wind speed, and pressure.
•
Hourly Forecast: Horizontal scrollable list showing weather predictions for the upcoming hours.
•
Material Design 3: utilizes the latest Flutter dark theme for a modern look.
•
Pull to Refresh: (Implicit in FutureBuilder logic) Updates data dynamically on app load.
•
Responsive Layout: Handles scrollable content to prevent overflow errors on smaller screens.
📸 Screenshots

🛠️ Tech Stack
•
Framework: Flutter
•
Language: Dart
•
API: OpenWeatherMap API
•
Packages used:
◦
http: For making network requests.
◦
intl: For formatting time and dates.
🚀 Getting Started
Prerequisites
•
Flutter SDK installed on your machine.
•
An API Key from OpenWeatherMap.
Installation
1.
Clone the repository:

git clone https://github.com/whybhav360/Just-Another-Weather-App
cd weather-app

2.
Install dependencies:

flutter pub get

3. 
Create a Secrets.dart file
String openWeatherAPIKey = 'YOUR_API_KEY_HERE';
        