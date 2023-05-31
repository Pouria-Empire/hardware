# Working with Relay

Relays are programmable switches that can be used to control ON/OFF electrical devices. The relay can be programmatically controlled by ESP32, which can control high voltage devices by using a relay.
To control a relay with ESP32, you can use a relay board which contains not only the relay but also some additional electronics that allow us to directly control the relay from a digital pin of a microcontroller (in our case, the ESP32).
To control a relay using ESP32, you just need to send HIGH and LOW signals as you would do to control an LED. The setup function runs once when you press reset or power the board. We can initialize digital pins as an output in the setup function. The loop function runs over and over again forever.
![Image of Relay](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8CkeIq8zWpf8aD7Edn297XnKM7TA_IeX9UA&usqp=CAU)

# How to use

As the below image you must connect pins **vcc, gnd, In1**  to there equivalant pins in the board. wee need to use one of pins **In1 or In2** because we use one of the switch. same as led just define the digital pin  and write HIGH or LOW to it.  
![enter image description here](https://s8.uupload.ir/files/screenshot_2023-05-31_140145_ml47.png)
