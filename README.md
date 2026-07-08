# Mini Regulated Power Supply (AC to DC)

## Description

The Mini Regulated Power Supply (RPS) is a compact hardware project designed to convert AC input into an adjustable DC output ranging from **0 V to 60 V**. The circuit consists of an AC input stage, a bridge rectifier, filtering capacitor, and MOSFET-based voltage regulation to provide a stable DC output suitable for powering electronic circuits and laboratory experiments. The schematic was designed using **EasyEDA**, and the project demonstrates the fundamentals of AC-to-DC power conversion, voltage rectification, filtering, and regulation.

## Components Used

* 4 × 1N4007 Rectifier Diodes
* 1 × 0.47 µF / 250 V Capacitor
* 1 × 470 µF / 50 V Electrolytic Capacitor
* 1 × MOSFET (Voltage Regulator)
* 1 × 10 kΩ Potentiometer
* 1 × 330 kΩ Resistor
* 1 × 220 kΩ Resistor
* 2 × 10 kΩ Resistors
* 1 × 47 kΩ Resistor
* PCB designed using EasyEDA
* AC Input Supply

## Features

* Converts AC input into regulated DC output.
* Adjustable output voltage from **0 V to 60 V**.
* Compact and simple circuit design.
* Low-cost electronic components.
* Suitable for learning rectification and voltage regulation concepts.
* Easy to fabricate and assemble.

## Working Principle

The AC input is first converted into pulsating DC using a full-wave bridge rectifier built with four 1N4007 diodes. The rectified output is smoothed by a filter capacitor to reduce voltage ripple. A MOSFET-based regulation stage, controlled by a potentiometer, allows adjustment of the output voltage. The regulated DC output can then be used to power various low-power electronic circuits and prototype projects.

## Applications

* Electronics laboratory experiments
* DIY electronics projects
* Embedded systems testing
* Educational demonstrations
* Prototype power supply
* Low-power circuit development

## Software Used

* EasyEDA (Schematic and PCB Design)

## Output

* **Input:** AC Supply
* **Output:** Adjustable DC Voltage (0–60 V)

## Repository Contents

* Circuit Schematic (PDF)
* PCB Design Files
* Hardware Images
* Output Images
* Project Documentation

## Note

This project is intended for educational and learning purposes. If the circuit is connected directly to mains AC, appropriate safety precautions must be followed, as high-voltage circuits can be hazardous.
