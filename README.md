# Dentist API

> ⚠️ **Disclaimer**: This is a **fork** of [Dentist API](https://github.com/Dentanoid/Dentist-API), originally created and maintained by the [Dentanoid Organization](https://github.com/Dentanoid)

Welcome to the Dentist API! This API is intended to handle communication between micro services and a Dentist client.

## Getting started

This service is written in NodeJS. [Check this link for more information about NodeJS.](https://nodejs.org/en).

To run this service you need to follow the steps described below:

### Installing NodeJS using BREW

If you do not have NodeJS installed on your computer you can download both brew and NodeJS with these commands:

#### Install brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
``````

If this command does not work, [check here](https://brew.sh/).

#### Install NodeJS with brew
```
brew install node
``````

### Add .env file (in the root folder)
The .env file contains information about the MQTT broker. This informatin is best contained locally on your computer, to keep your connections private. You will have to insert a BROKER_URL (separated in to MQTT_HOST and MQTT_PORT).

For our instances of the service, we used a [HIVE](https://www.hivemq.com/mqtt/) private broker.

```
MQTT_HOST='YOUR_HOST'
MQTT_PORT='YOUR_PORT'
MQTT_PROTOCOL='YOUR_PROTOCOL'
MQTT_USERNAME='YOUR_USERNAME'
MQTT_PASSWORD='YOUR_PASSWORD'
```


### Run Dentist API
In order to build and run the Dentist API you need to type these commands in to your terminal:


```
npm install // run this command if you have not already installed npm

npm run dev
```
Congratulations! You are now running the Dentist API.
 
## Roadmap
This service will not get updated in the future, due to project being considered as closed when GU course DIT356 is finished.

## Authors and acknowledgment

- Lucas Holter
- Cornelia Olofsson Larsson
- James Klouda
- Jonatan Boman
- Mohamad Khalil
- Joel Mattson

## Project status
The service may recieve updates until 9th January 2024, and none after.
