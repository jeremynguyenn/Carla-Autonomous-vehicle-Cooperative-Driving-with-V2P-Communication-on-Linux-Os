# Carla Connected Mobility vs Autonomous Driving
A simple scenario to demonstrate where an autonomous vehicle cannot avoid a crash, while via vehicle-to-pedestrian (V2P) communication the crash can be avoided.

This scenario is made for demonstration purposes only.

## Autonomous Driving Mode

[demo1](https://github.com/jeremynguyenn/Carla-Autonomous-vehicle-Cooperative-Driving-with-V2P-Communication-on-Linux-Os/blob/main/Demo/Autonomous_Driving_Mode.gif)

By using autonomous driving only, the vehicle cannot avoid the crash.
<br><br>

## Connected Mobility Mode

[demo2](https://github.com/jeremynguyenn/Carla-Autonomous-vehicle-Cooperative-Driving-with-V2P-Communication-on-Linux-Os/blob/main/Demo/Connected_Mobility_Mode.gif)

By using additional network devices with vehicle-to-pedestrian communication (V2P), the vehicle receives the trajectory of the pedestrian, determines an intersection of both and reacts much earlier than in the first scenario. The crash is avoided in this scenario.

## Setup
- Carla 0.9.13
- Ubuntu 20.04
- Python 3.8.10

## Installation
Run `pip install -r requirements.txt`

## Launching
Inside the src folder, run `python3 main.py` for the autonommous driving mode. 
Add the flag `--connected_mobility` for V2P communication.
