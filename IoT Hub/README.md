# IoT Hub 

Quickstarts and tutorials from working with IoT Hub

## Tutorial & QuickStarts Completed

### Quickstart: Send telemetry from a device to an IoT hub and monitor it with the Azure CLI
https://learn.microsoft.com/en-us/azure/iot-hub/quickstart-send-telemetry-cli

In this tutorial I created an IoT Hub and simulated and IoT Device using the Azure CLI. I was able to monitor events in the Azure CLI and also send a message to the Device using the Azure CLI commands. I was also able to update the properties of the Devices Digital Twin and view the metrics in the Azure Portal. 

### Tutorial: Send telemetry from an IoT Plug and Play device to Azure IoT Hub
https://learn.microsoft.com/en-us/azure/iot/tutorial-send-telemetry-iot-hub

In this Tutorial I had a look at what a Plug And Play device is with Azure IoT hub and used IoT Explorer to setup new devices. I then used the Device SDK to setup a temperature sensor and then further view the telemetry in IoT Explorer with filtering for individual components on the registered device. 

### Quickstart: Control a device connected to an IoT hub
https://learn.microsoft.com/en-us/azure/iot-hub/quickstart-control-device

In this quickstart I used the sample C# project to run a device and connect that device to a Hub. I further then issues calls to change the settings on that device to change the telemetry interval. 

# Source Code For Supporting Project

git clone https://github.com/Azure/azure-iot-sdk-csharp.git

## Changes To Original Code

No change to the original code. THerefore the local folder for that code has been excluded in the gitignore file. 

