##.Smart Home Automation

## Project explanation

This project implements home automation using ESP32, Sinric Pro,and integrates with voice assistants like Google Home and Alexa.
It allows manual control of four relays through TTP touch sensors and provides real-time feedback.

##Table Of content

1) Getting started
   -Pre requisits
   -installation
2) Configuration
3) Usage
4) Troubleshooting

1)Getting Started

Prerequisites
Arduino IDE installed.
ESP32 Board Support installed.
ArduinoJson Library installed.
arduinoWebSockets Library installed.
Sinric Pro Library installed.

2)Installation 

Clone the repository.

-git clone https://github.com/your-username/your-repo.git

  -Open the project in Arduino IDE.
  -Set up your preferences in the code (Wi-Fi credentials, Sinric Pro API key, etc.).
  -Upload the code to your ESP32.

3)Configuration

Update the following variables in the code with your specific details:

#define WIFI_SSID         "YOUR-WIFI-NAME"    
#define WIFI_PASS         "YOUR-WIFI-PASSWORD"
#define APP_KEY           "YOUR-APP-KEY"
#define APP_SECRET        "YOUR-APP-SECRET"

#Enter device IDs, GPIO pins for relays and switches.

4) Usage

  -Power on your ESP32.
  -Ensure your Wi-Fi is connected.
  -Open the Serial Monitor to monitor device status and troubleshoot.

