# Weather Station using Node.js and Raspberry Pi

This is a simple weather station project that reads temperature and humidity data using a DHT11 sensor connected to a Raspberry Pi. The data is displayed on a web interface served by a Node.js server.

## Features:
- Real-time temperature and humidity data
- Simple web interface
- Auto-refreshing data every 5 seconds

## Components:
- Raspberry Pi
- DHT11/DHT22 Sensor
- Jumper wires

## Setup Instructions:
1. Clone this repository.
2. Run `npm install` to install the required dependencies.
3. Connect the DHT11/DHT22 sensor to the Raspberry Pi.
4. Start the server using `node server.js`.
5. Open your browser and go to `http://<your_raspberry_pi_ip>:3000/` to view the weather data.

## Project Structure:
- `server.js`: The Node.js server code.
- `index.html`: The front-end HTML page.

