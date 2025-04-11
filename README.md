# 🛠️ Mini CNC Plotter using Old CD Drives

A DIY Mini CNC Plotter built from recycled CD/DVD drives, Arduino, and simple hardware. This compact plotter is capable of drawing basic vector graphics, text, or logos on paper with precision using stepper motors from old optical drives.

## 📌 Features

- ✏️ Draws 2D vector graphics with a pen
- ♻️ Built with recycled CD/DVD drive mechanisms
- 🔌 Controlled via Arduino Uno + CNC Shield or custom driver circuit
- 🎮 Accepts G-code commands from software like Inkscape + G-code plugin or Universal G-code Sender

## 🧰 Components Used

- 2× CD/DVD drive stepper motor assemblies (X and Y axes)
- 1× Servo motor (for Z-axis pen up/down)
- 1× Arduino Uno
- CNC Shield + A4988 Drivers **or** custom stepper driver circuits (optional)
- External 12V power supply (or USB power for low load)
- Mini breadboard/wires
- Pen/pencil holder (3D printed or DIY)

## 🖥️ Software & Tools

- Arduino IDE
- Inkscape with G-code plugin
- Universal G-code Sender (UGS)
- GRBL firmware for Arduino

## 📦 How to Build

1. **Disassemble CD drives** – Extract the stepper motor assemblies.
2. **Build Frame** – Mount X and Y axes orthogonally using acrylic sheets or cardboard.
3. **Attach Pen Mechanism** – Use a servo motor to raise/lower the pen for drawing.
4. **Wire Up Electronics** – Connect motors to CNC Shield and upload GRBL firmware to Arduino.
5. **Generate G-code** – Use Inkscape to convert images/text to G-code.
6. **Send G-code to Plotter** – Use UGS or similar sender to control the machine.

## 🔧 Circuit Diagram

> Add your circuit diagram image or link here.

## 📽️ Demo

> Embed a GIF or YouTube video showing the plotter in action.

## 📁 File Structure

