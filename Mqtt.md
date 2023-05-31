# Working with MQTT 

MQTT (Message Queuing Telemetry Transport) is a lightweight  messaging protocol  designed for IoT (Internet of Things) and  M2M  (Machine-to-Machine) communication. It was originally developed by  IBM  in 1999. MQTT uses a client/server architecture, where clients connect to a broker, which acts as a message distributor and manages the communication between clients. The protocol supports Quality of Service (QoS) levels, which determine the level of assurance for message delivery.
The  MQTT protocol  is designed to be simple, efficient, and reliable, making it well-suited for use in  constrained environments, such as those found in embedded systems, sensors, and mobile devices. It uses a publish/subscribe messaging pattern, where devices can subscribe to topics and receive messages published to those topics.


# How to use

Simply clone the [github link](https://github.com/Pouria-Empire/MQTT_Encrypt). **Remember to chenge the topics** and then install the requierments.txt using "pip install -r requierments.txt" command, then run the "mqtt_subscriber.by" and after that when you run the "mqtt_publisher.py" you can see the passing messages between mqtt publisher and subscriber. In the following part you must implement the mqtt_subscriber in the ESP32 module. then you can pass message from you laptop to the module. 
mqtt subscriber reads the mesage and mqtt publisher write the messages. you should implement a subscriber on mqtt and run mqtt_publisher.py to recieve a message. Here is the steps:
 1. Install [git](https://git-scm.com/download/win) in windows
 2. Install python if not installed
 3. Use the command below : `git clone https://github.com/Pouria-Empire/MQTT_Encrypt`
 4. This repo contains examples of relay and temp
 5. Run the mqtt_pubisher.py and mqtt_subscriber.py to see what happends
 6. Use the exmples and implement your code :)

## Encrypted version

For implementing the AES algorithm to Encrypt and Decrypt using the following [github link](https://github.com/Pouria-Empire/AES32) for downloading the library and exmple encryption code. Remember use this library because I edited that library to work currectly.
