# ESP32 HTTP Server Example

ESP32 emqx MQTT Broker example: control 2 LEDs on ESP32 from a MyMQTT apps .

Use [Wokwi for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=wokwi.wokwi-vscode) to simulate this project.

## Building

This is a [PlatformIO](https://platformio.org) project. To build it, [install PlatformIO](https://docs.platformio.org/en/latest/core/installation/index.html), and then run the following command:

```
pio run
```

## Simulating

To simulate this project, install [Wokwi for VS Code](https://marketplace.visualstudio.com/items?itemName=wokwi.wokwi-vscode). Open the project directory in Visual Studio Code, press **F1** and select "Wokwi: Start Simulator".

Once the simulation is running, open MyMQTT to control the LEDs.
To control blue LED, publish to topic "dre2214/blue" with payload "on" or "off".
Same goes to green LED, publish to topic "dre2214/green" with payload "on" or "off" also.

