# Weather Station Monitoring System

![Project Status](https://img.shields.io/badge/Status-Completed-success.svg)
![C Version](https://img.shields.io/badge/C17-blue.svg)
![ESP Version](https://img.shields.io/badge/ESP8266-yellow.svg)
![ACS Version](https://img.shields.io/badge/ACS712-red.svg)
![Arduino](https://img.shields.io/badge/Arduino-UNO-lightgreen.svg)
![ArduinoIDE Version](https://img.shields.io/badge/ArduinoIDE-2.1.1-grey.svg)
![Adafruit](https://img.shields.io/badge/AdafruitIO-black.svg)
![Zapier](https://img.shields.io/badge/Zapier-orange.svg)
![License](https://img.shields.io/badge/License-MIT-red.svg)


![Weather Station Image](https://user-images.githubusercontent.com/83889037/265812357-5ac1a871-d814-44b7-9641-197e8cdf0aca.png)

## Table of Contents
- [Description](#description)
- [Hardware Components](#hardware-components)
- [Software Components](#software-components)
- [Installation](#installation)
- [Usage](#usage)
- [Data Visualization](#data-visualization)
- [Contributing](#contributing)
- [License](#license)


## Description
The Weather Station Monitoring System is an IoT-based project that allows you to monitor weather conditions in real-time. It collects data using various sensors and sends it to the ThingSpeak cloud platform for storage and visualization. This README provides an overview of the project's components, setup, and usage.


## Features

- Real-time monitoring of weather conditions.
- Rainfall detection with the FC-37 Raindrop Sensor.
- Data storage and visualization on ThingSpeak.
- Data analysis with Jupyter Notebook.


## Getting Started

1. Clone this repository.
2. Upload the Arduino sketch to your NodeMCU with WiFi and ThingSpeak credentials.
3. Connect the hardware as per the provided schematics.
4. Access ThingSpeak for data visualization.
5. Analyze data using the included Jupyter Notebook.


## Hardware Components
- NodeMCU 8266
- FC-37 Raindrop Sensor
- Breadboard
- Jumper wires
- Micro USB Cable

## Software Components
- Arduino IDE
- Windows Operating System
- Cloud Platform: ThingSpeak
- Jupyter Notebook

## Installation
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/weather-station.git


1) Install Arduino IDE if you haven't already from Arduino's official website.

2) Upload the Arduino sketch to your NodeMCU 8266 board using the Arduino IDE. Make sure to set up your WiFi credentials and ThingSpeak API keys in the sketch.



## Usage
1) Connect the hardware components as per the provided schematics (add schematics or wiring instructions to the repository).

2) Power up the NodeMCU using the Micro USB cable.

3) The NodeMCU will start collecting data from the FC-37 Raindrop Sensor and send it to ThingSpeak at regular intervals.

4) Access your ThingSpeak channel to visualize and analyze the collected data.

Data Visualization
You can analyze and visualize the weather data using Jupyter Notebook. The provided Jupyter Notebook file, weather_data_analysis.ipynb, contains code for data visualization and analysis. Follow these steps:

1) Install Jupyter Notebook on your machine if you haven't already.

2) Open the weather_data_analysis.ipynb notebook in Jupyter Notebook.

3) Run the cells in the notebook to generate visualizations and insights from your weather data.

## [CODE_OF_CONDUCT](https://github.com/raj007-star/Weather-Station-/blob/b9c31eb4c9e591762a629b10611b67041309f7bf/CODE_OF_CONDUCT.md)

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1) Fork the repository.
2) Create a new branch for your feature or bug fix.
3) Make your changes and test thoroughly.
4) Commit your changes with clear commit messages.
5) Push your branch to your fork.
6) Create a pull request to the main repository's main branch.


## License
This project is licensed under the MIT License - see the LICENSE file for details.


Make sure to replace `insert_image_url_here` with the URL of an image that showcases your Weather Station hardware setup.

Feel free to customize this template to fit your project's specific details and requirements. Including clear instructions, documentation, and visuals will help users understand and use your project effectively.


## Contact

For questions or collaborations, contact [Swarnava Gayen](swarnavagayen@email.com).










