# NodeMCU-Gate-Bot-traffic-light-exe

![Screenshot 2023-07-27 034928](https://github.com/khanfar/NodeMCU-Gate-Bot-traffic-light-exe/assets/16803586/53219d4b-1f8c-471f-8157-22f91c855740)

here's a brief introduction and the features of the bot:

## Introduction

The Khanfar Gate Control System work with ALPR is a Python-based application that provides an interface to control and monitor a gate system. It uses a Flask server to handle requests and  GUI for user interaction. 
The system can send commands to a NodeMCU device to open and close the gate, and it also sends notifications to a specified Telegram chat when the gate is opened or closed.

## Features

1. **GUI Interface:** The application provides a GUI interface built , allowing users to interact with the system easily.

2. **Gate Control:** The system can send commands to a NodeMCU device to open and close the gate.

3. **Telegram Notifications:** The system sends notifications to a specified Telegram chat when the gate is opened or closed.

4. **Traffic Light Indicator:** The GUI includes a traffic light indicator that shows the current state of the gate (open or closed).

5. **Terminal Output:** The GUI includes a terminal that displays messages about the gate's status.

6. **Configuration Saving:** The system can save and load the configuration (NodeMCU IP, Telegram bot token, and Telegram chat ID) from a file.

## Pip Requirements

To run this bot, you need to have the following Python packages installed:

- `tkinter`
- `flask`
- `requests`
- `winsound`

You can install these packages using pip:

```
pip install flask requests
```

Note: `tkinter` and `winsound` are part of the standard library in Python and do not need to be installed separately.

Please note that this bot is designed to work with a specific hardware setup (a gate controlled by a NodeMCU device) and a specific software setup (a Telegram bot). 
You will need to have these set up and configured correctly for the bot to work as intended.
