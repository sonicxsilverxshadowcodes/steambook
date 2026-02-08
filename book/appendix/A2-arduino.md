# A2: Arduino

**Appendix – Going Further**

---

## What Is Arduino?

**Arduino** is a small **electronic board** that has a **microcontroller**—a tiny computer that can run one program and control pins (inputs and outputs). You connect components (LEDs, motors, sensors) to the board, write a program on a computer, and **upload** it to the Arduino. The board then runs the program on its own (even without the computer) and controls the components. Arduino is used in schools, hobbies, and prototypes because it is cheap, easy to start with, and has a lot of examples and community support.

---

## What Can You Do With It?

| Idea | Example |
|------|---------|
| **Outputs** | Turn an LED on/off, control a motor speed, drive a small display. |
| **Inputs** | Read a button, a light sensor, a temperature sensor, or a distance sensor. |
| **Logic** | “If the button is pressed, turn the LED on.” “If it’s dark, turn the light on.” |

So you can build simple robots, automatic lights, weather stations, and many small “smart” devices.

---

## How Do You Program It?

You write code (often in a language based on **C/C++**) in the **Arduino IDE** (a free program on your computer). The code has at least two parts:

- **setup()** — Runs once when the board starts (e.g. set pins as input or output).
- **loop()** — Runs again and again (e.g. read a sensor, then set an LED or motor).

You connect the Arduino to the computer with a **USB cable**, click “Upload,” and the program is sent to the board. After that, the Arduino can run without the computer if it has power (e.g. battery or USB power).

---

## A Bit of History

Arduino started in Italy (around 2005) at a design school (IDII Ivrea). The goal was to give designers and students an easy way to work with electronics and code. The hardware and software were made **open**, so many companies made compatible boards and people shared projects. That is why you see “Arduino-style” boards and lots of tutorials and projects online.

---

## Key Points

- Arduino is a small board with a microcontroller; you upload a program and it controls components.
- You can use inputs (sensors, buttons) and outputs (LEDs, motors) and write logic in code.
- You program in the Arduino IDE (C/C++ style) with **setup()** and **loop()**.
- It is popular for learning, prototyping, and small projects (robots, lights, sensors).
