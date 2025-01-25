# flutter_weather_app

A Flutter weather app that uses the weatherapi.com API to fetch weather data.

## Features

- Fetches current weather data for a specified location.
- Displays temperature, humidity, wind speed, and weather conditions.
- Simple and intuitive user interface.

## Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/flutter_weather_app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flutter_weather_app
    ```

3. Install the required dependencies:

    ```bash
    flutter pub get
    ```

4. Open [constants.dart](http://_vscodecontentref_/0) and replace `YOUR_API_KEY` with your actual API key from weatherapi.com:

    ```dart
    const String apiKey = 'YOUR_API_KEY';
    ```

5. Run the app on your preferred device or emulator:

    ```bash
    flutter run
    ```

## Project Structure

- [lib](http://_vscodecontentref_/1): Contains the main source code for the Flutter app.
  - [api.dart](http://_vscodecontentref_/2): Handles API requests to fetch weather data.
  - `constants.dart`: Contains constant values used throughout the app.
  - `homepage.dart`: Defines the UI for the homepage.
  - `main.dart`: Entry point of the application.
  - `weathermodel.dart`: Defines the data model for weather data.

- [android](http://_vscodecontentref_/3): Contains the Android-specific files and configurations.
- [ios](http://_vscodecontentref_/4): Contains the iOS-specific files and configurations.
- [linux](http://_vscodecontentref_/5): Contains the Linux-specific files and configurations.
- [macos](http://_vscodecontentref_/6): Contains the macOS-specific files and configurations.
- [web](http://_vscodecontentref_/7): Contains the web-specific files and configurations.
- [windows](http://_vscodecontentref_/8): Contains the Windows-specific files and configurations.
- [test](http://_vscodecontentref_/9): Contains the unit tests for the app.

## Dependencies

- `http`: A package for making HTTP requests.
- `provider`: A package for state management.
- `flutter_launcher_icons`: A package for customizing app icons.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any inquiries or feedback, please contact [grefielkent@gmail.com](mailto:grefielkent@gmail.com).
