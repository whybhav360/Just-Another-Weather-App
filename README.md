☁️ Flutter Weather App

Real-Time Weather App built with Flutter & OpenWeatherMap

A modern, production-ready weather application developed using Flutter that delivers real-time and hourly weather insights through the OpenWeatherMap API. This project demonstrates strong fundamentals in asynchronous programming, REST API integration, responsive UI design, and Material Design 3.

Designed as a portfolio project to showcase clean architecture, API handling, and UI scalability.

🔑 Key Highlights (Why This Project Matters)

Built with real-world API integration

Implements asynchronous data fetching using FutureBuilder

Uses Material Design 3 (Dark Theme) for a modern UX

Responsive layout handling edge cases like screen overflow

Clean, readable, and scalable Flutter codebase

📱 Features:

🌡️ Live Weather Information

Current temperature

Humidity

Wind speed

Atmospheric pressure

⏱️ Hourly Forecast

Horizontally scrollable forecast cards

Time-formatted data using intl

🎨 Modern UI

Material 3 dark theme

Consistent typography and spacing

Smooth scrolling with overflow-safe layouts

🔄 Dynamic Refresh

Weather data refreshes automatically on app load

Designed to be easily extended with pull-to-refresh or caching

🛠️ Tech Stack

Framework: Flutter
Language: Dart
API: OpenWeatherMap

Packages

http – REST API communication

intl – Date and time formatting

🧠 Concepts Demonstrated

Asynchronous programming (Future, async/await)

REST API consumption and JSON parsing

Stateless & Stateful widget management

Responsive UI and layout constraints

Clean separation of UI and data logic

Error-safe scrolling and layout design

🚀 Getting Started
Prerequisites

Flutter SDK

OpenWeatherMap API key

Installation
git clone https://github.com/whybhav360/Just-Another-Weather-App
cd weather-app
flutter pub get

API Key Setup

Create a file named Secrets.dart:

String openWeatherAPIKey = 'YOUR_API_KEY_HERE';


Note: API keys are excluded from version control for security.

Run the App
flutter run

📸 Screenshots

<img width="1080" height="2400" alt="Screenshot_20260102_165844" src="https://github.com/user-attachments/assets/484559a2-703b-463f-95ec-3264aeeb80b0" />


![gif](https://github.com/user-attachments/assets/49e1ada9-76d4-457d-b68d-bf2c1d7f6c6f)



👤 Author

Vaibhav Madaan
Android & Flutter Developer | Mobile + AI Enthusiast

This project is part of my mobile development portfolio, focusing on real-world API usage and scalable UI design.
