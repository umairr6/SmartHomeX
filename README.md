SmartHomeX V1 🏠

Purpose: To provide simple and convenient control of household electrical appliances through a mobile application.

Key Features

- Control 4 appliances: 2 lights, a fan, and a socket.
- Turn appliances ON/OFF using a mobile app.
- Local Wi-Fi connectivity.
- Appliance status monitoring.

System Overview

The mobile app communicates with an ESP32 over a local Wi-Fi network. The ESP32 controls a 4-channel relay module to switch appliances ON or OFF.

Appliance Control Workflow

1. The user selects an appliance in the mobile app.
2. The app sends a control request to the ESP32 over Wi-Fi.
3. The ESP32 activates or deactivates the corresponding relay.
4. The appliance switches ON or OFF.
5. The app retrieves and displays the appliance status.

Project Status

Prototype / Development

SmartHomeX — Making Everyday Living Smarter.
