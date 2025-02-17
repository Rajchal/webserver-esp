# ESP32 HTTP Server

This project demonstrates how to create a simple HTTP server using the ESP32 microcontroller. The server can handle basic HTTP requests and serve web pages to clients.

## Features

- Handles GET and POST requests
- Serves static files (HTML, CSS, JavaScript)
- Simple API for interacting with the ESP32

## Requirements

- ESP32 development board
- Arduino IDE or PlatformIO
- Wi-Fi network

## Installation

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/webServer-esp.git
    ```
2. Open the project in your preferred development environment (Arduino IDE or PlatformIO).
3. Install the necessary libraries:
    - ESPAsyncWebServer
    - AsyncTCP
4. Configure your Wi-Fi credentials in the `config.h` file:
    ```cpp
    #define WIFI_SSID "your-ssid"
    #define WIFI_PASSWORD "your-password"
    ```
5. Upload the code to your ESP32 board.

## Usage

1. Connect your ESP32 to the same Wi-Fi network as your computer.
2. Open the Serial Monitor to find the IP address of your ESP32.
3. Open a web browser and navigate to the IP address of your ESP32.
4. You should see the web page served by the ESP32 HTTP server.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)
- [AsyncTCP](https://github.com/me-no-dev/AsyncTCP)
