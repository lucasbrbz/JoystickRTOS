| Supported Targets | ESP32 |
| ----------------- | ----- |

# ESP32-based Bluetooth Joystick using FreeRTOS

This application uses FreeRTOS APIs to create a Bluetooth HID device, using the standard Bluetooth protocol (also known as BT). It is heavily based on Espressif ``bluetooth/esp_hid_device`` example from ESP IDF v4.4.6.

This project is associated with the RTOS classes of the Embedded Systems postgraduate program at SENAI São Paulo.

## How to Use

The BT HID device plays as a normal joystick. When the connection is successfully established, users can follow the usage below to operate the 'mouse'.

```
########################################################################
BT hid mouse demo usage:
You can input these value to simulate mouse: 'q', 'w', 'e', 'a', 's', 'd', 'h'
q -- click the left key
w -- move up
e -- click the right key
a -- move left
s -- move down
d -- move right
h -- show the help
########################################################################
```

### Hardware Required

* A development board with ESP32 SoC (e.g., ESP32-DevKitC, ESP-WROVER-KIT, etc.)
* A USB cable for Power supply and programming
* 2x Biaxial Joystick modules KY-023
* 4x Push buttons
* 1x Accelerometer/Gyroscope module MPU-6050
* 1x Green LED

See [Development Boards](https://www.espressif.com/en/products/devkits) for more information about it.

### Configure the Project

### Build and Flash

Build the project, flash it to the board and run monitor tool in a oneliner:

```
idf.py flash monitor -p COM*
```

(To exit the serial monitor, type ``Ctrl-]`` or ``Ctrl-ç`` in ABNT2 keyboards.)

See the [Getting Started Guide](https://idf.espressif.com/) for full steps to configure and use ESP-IDF to build projects.

## Example Output

```
...
```

## Troubleshooting

For any technical queries, please open an [issue](https://github.com/lucasbrbz/joystickRTOS/issues) on GitHub. We will get back to you soon.
