# ot-sensor-network

An OpenThread based sensor/actuator network for home.

## OT Node Types

1. Sensor Nodes
2. Actuator Nodes
3. Range extender Nodes (plugged into AC outlet)
4. NCP 

## Hardware 

- nRF8240-dongle for sensor nodes and NCP
- Raspberry Pi for border router

## Software

- Zephyr RTOS based firmware
- MQTT ?
- Protocol buffers for data transport ?
- Mobile app via Flutter
- Web dashboard
- AWS IoT?

## Requirements

- Wide coverage for multiple floors via mesh network
- Power optimisation for battery operated nodes
- Secure and easy provisioning via mobile app 
- Security (TLS)
- Firmware update over air (OTA)

# Sensor Nodes

Here are the different types of sensor nodes to be built.

## 1. Soil Moisture  

This is a capacitative moisture sensor that uses traces on a PCB. 

## 2. Motion  

Motion detection based on PIR sensor.

## 3. Temperature/Humidity 

Temperature humdity measurements 

## 4. Low Resolution Video

1-2 frames per sec low res video.

## 5. IR Blaster

Send commands to a devices that use IR (infrared) receivers.

