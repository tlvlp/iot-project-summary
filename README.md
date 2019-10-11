# iot-project-summary

# Project summary

# Server side API 

# MCU side API

reference implementation

# Deployment 
Deployment details can be found at the project's [iot-server-deployment](https://github.com/tlvlp/iot-server-deployment) repository

# Service details
| Service | Details | |
| :--- | :--- | :--- |
| [iot-api-gateway](https://github.com/tlvlp/iot-api-gateway) | The main API for the project encapsulating the other services| Frontend |
| [iot-portal](https://github.com/tlvlp/iot-portal) | A heavily experimental Vaadin based implementation of the API | Fontend | 
| [iot-mqtt-client](https://github.com/tlvlp/iot-mqtt-client) | The back-end services' link to the MQTT broker and the MCUs | Backend | 
| [iot-unit-service](https://github.com/tlvlp/iot-unit-service) | Implements the MCU side of the API, handling all Units | Backend |
| [iot-reporting-service](https://github.com/tlvlp/iot-reporting-service) | Stores input data and generates reports on demand | Backend |
| [iot-scheduler-service](https://github.com/tlvlp/iot-scheduler-service) | Stores and executes scheduled tasks in the form of API calls | Backend |

# 