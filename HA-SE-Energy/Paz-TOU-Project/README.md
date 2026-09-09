# Paz-TOU-Project

## Overview
The Paz-TOU-Project is designed to manage time-of-use (TOU) energy consumption settings within a Home Assistant environment. This project allows users to define different rates or schedules for energy consumption based on the time of day, optimizing energy usage and costs.

## Project Structure
The project consists of the following files:

- **packages/tou.yaml**: Configuration for time-of-use (TOU) settings, defining different rates or schedules for energy consumption based on the time of day.
  
- **configuration.yaml**: The main configuration file for Home Assistant, including settings for various integrations, components, and the overall setup of the Home Assistant instance.
  
- **automations.yaml**: Defines automation rules for Home Assistant, specifying triggers, conditions, and actions to automate tasks based on certain events or states.
  
- **scripts.yaml**: Contains scripts that can be executed in Home Assistant, allowing for the automation of sequences of actions.
  
- **customize.yaml**: Used to customize the appearance and behavior of entities in Home Assistant, allowing for modifications to attributes and icons.

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Ensure that Home Assistant is installed and running.
4. Copy the contents of the `packages/tou.yaml` file into your Home Assistant configuration.
5. Restart Home Assistant to apply the changes.

## Additional Information
For more details on configuring Home Assistant, refer to the official documentation at [Home Assistant Documentation](https://www.home-assistant.io/docs/).