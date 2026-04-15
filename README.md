# Adjustable Light Sensor (LDR + 555 Timer)

## 📌 Overview

This project implements an **adjustable light-sensitive switching circuit** using an LDR, a potentiometer, and a 555 Timer IC. The system detects ambient light intensity and automatically turns an LED ON or OFF based on a user-defined threshold. The sensitivity of the circuit can be tuned using the potentiometer, making it adaptable for different lighting conditions.



## ⚙️ Features

* Automatic light detection using LDR
* Adjustable sensitivity via potentiometer
* Stable switching using 555 Timer IC
* Simple, low-cost analog design
* Suitable for real-world automation applications



## 🔧 Components Used

* LDR (Light Dependent Resistor)
* Potentiometer
* 555 Timer IC
* LED
* Resistors
* Capacitor
* Power Supply (5V–9V)


## 🧠 Working Principle

The LDR and potentiometer form a voltage divider that generates a voltage corresponding to ambient light intensity. This voltage is fed into the 555 Timer IC, which operates as a comparator.

* In **bright conditions**, the LDR resistance decreases, causing the output to remain OFF.
* In **low-light conditions**, the LDR resistance increases, and once the voltage crosses the threshold set by the potentiometer, the 555 Timer switches the LED ON.

The potentiometer allows fine-tuning of the switching point, enabling precise control over when the LED activates.


## 🎯 Applications

* Automatic street lighting
* Night lamps
* Light-activated switches
* Energy-efficient lighting systems
* Basic sensor interfacing projects



## 📷 Preview


