# IoT Project README

This project is an IoT (Internet of Things) project that consists of code snippets written in multiple programming languages to enable different functionalities.

## Python Code (Raspberry Pi)

The Python code snippet, located in `python_code.py`, is designed to run on a Raspberry Pi. It performs the following tasks:

- Imports the required libraries: `RPi.GPIO` and `time`.
- Sets up the Raspberry Pi GPIO.
- Retrieves data from the Thingspeak API using an API key and channel ID.
- Parses the response data and checks if a specific condition is met.
- Controls a GPIO pin based on the condition.

To run the Python code, make sure you have the required libraries installed, update the API key and channel ID, and execute the `python_code.py` file on the Raspberry Pi.

## PHP Code (Web Server)

The PHP code snippets are used in a web server environment. The project includes two PHP files: `post_data.php` and `view_data.php`.

### post_data.php

The `post_data.php` file receives HTTP POST data from an ESP32 device, validates the API key, and stores the received data in a MySQL database. It performs the following tasks:

- Connects to a MySQL database using the provided credentials.
- Receives POST data, including an API key, from an HTTP POST request.
- Validates the API key and stores the received data in the database.

To use the `post_data.php` file, replace the database credentials and host it on a web server.

### view_data.php

The `view_data.php` file retrieves data from a MySQL database and displays it in an HTML table. It performs the following tasks:

- Connects to a MySQL database using the provided credentials.
- Retrieves data from the database.
- Displays the retrieved data in an HTML table.

To use the `view_data.php` file, replace the database credentials and host it on a web server.

## Arduino Code (ESP32)

The Arduino code snippet, located in `arduino_code.ino`, is designed to run on an ESP32 device. It performs the following tasks:

- Sets up the DHT temperature and humidity sensor.
- Connects to a Wi-Fi network.
- Sends HTTP GET requests to a specified server with temperature and humidity data.
- Prints the HTTP response code and payload.

To use the Arduino code, make sure you have the required libraries installed, update the Wi-Fi settings and server address, and upload the code to an ESP32 device.

## Additional Files

The project also includes additional files such as `dht.php`, `sensor1.php`, and `index.html`. These files are related to storing and viewing sensor data in a MySQL database and displaying it on a web page.

Please refer to the respective code files for more detailed information and instructions on how to use each snippet.

