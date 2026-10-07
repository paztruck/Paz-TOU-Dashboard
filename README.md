# HA-SE-Energy Project

## Overview
The HA-SE-Energy project is designed to integrate solar energy management into the Home Assistant platform. It provides a comprehensive setup for monitoring solar energy production, consumption, and battery management through various sensors and automations.

## Project Structure
The project consists of the following files:

- **packages/electricity.yaml**: Configuration for sensors related to solar energy production, consumption, and battery management. This file defines multiple sensors with their states, availability, and calculations based on other sensor readings.
- **packages/cooktop.yaml**: Cooktop power monitoring, monthly TOU energy tracking, and a high-power notification.

- **configuration.yaml**: The main configuration file for the Home Assistant setup. It includes settings for integrations, components, and other configurations necessary for the Home Assistant environment.

- **customize.yaml**: Used to customize the appearance and behavior of entities in Home Assistant. This file allows you to set friendly names, icons, and other attributes for various entities.

- **automations.yaml**: Contains automation rules for Home Assistant. It defines triggers, conditions, and actions that automate tasks based on specific events or states.

- **scripts.yaml**: Defines scripts in Home Assistant. Scripts are sequences of actions that can be executed manually or triggered by automations.

## Setup Instructions
1. Clone the repository to your local machine.
2. Ensure you have Home Assistant installed and running.
3. Place the `packages/electricity.yaml` file in the appropriate directory for your Home Assistant configuration.
4. Update the `configuration.yaml` file to include the necessary integrations and components.
5. Customize entities as needed in the `customize.yaml` file.
6. Define any automations in the `automations.yaml` file.
7. Create scripts in the `scripts.yaml` file as required.

## Usage
After setting up the project, you can monitor your solar energy production and consumption through the Home Assistant dashboard. The defined sensors will provide real-time data, and automations can help manage energy usage efficiently.

## Contributing
Contributions to the HA-SE-Energy project are welcome. Please submit a pull request or open an issue for any enhancements or bug fixes.