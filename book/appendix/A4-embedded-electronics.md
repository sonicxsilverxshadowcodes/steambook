# A4: Embedded Electronics

**Appendix – Going Further**

---

## What Is “Embedded”?

**Embedded** means “built inside something.” **Embedded electronics** means the **circuits and small computers** that are built **inside** everyday devices—not a laptop or phone you use as a “computer,” but the hidden brain and sensors inside a washing machine, a car, a remote control, or a toy. The device has one main job (wash clothes, open the door, play a tune), and the embedded system runs the program that does that job. Usually we never see the circuit; we only see buttons, lights, and the device’s behaviour.

---

## Where Do We Find Embedded Systems?

| Device | What the embedded system does |
|--------|--------------------------------|
| **Washing machine** | Runs the motor, fills water, heats, times the cycle, beeps when done. |
| **Car** | Engine control, brakes (ABS), airbags, dashboard, keys. |
| **Remote control** | Sends infrared or radio signals when you press a button. |
| **Microwave** | Controls time, power, turntable, and the magnetron (heating). |
| **Traffic light** | Switches red, yellow, green on a timer or from a sensor. |
| **Smart watch** | Measures heart rate, steps, shows time, connects to phone. |

So embedded electronics are everywhere: home, car, school, and pocket.

---

## What’s Inside?

An embedded system usually has:

- A **microcontroller** or small **processor** (like on an Arduino) that runs the program.
- **Inputs** — Buttons, sensors (temperature, light, motion), or signals from other parts.
- **Outputs** — Motors, LEDs, display, speaker, or signals to other parts.
- **Power** — Battery or power supply.

The program is stored in **memory** on the chip and runs in a **loop**: read inputs → decide what to do → set outputs → repeat. That is the same idea as **setup()** and **loop()** on Arduino.

---

## Why It Matters

Embedded systems make devices **smart** and **automatic**. They also need to be **reliable** (a car brake or medical device must work correctly) and often **efficient** (low power so batteries last). Learning about circuits, microcontrollers (e.g. Arduino), and simple programming is the first step toward understanding how these systems work and maybe designing them one day.

---

## Key Points

- **Embedded electronics** = circuits and small computers **inside** a device (washing machine, car, remote, toy).
- They have a **microcontroller**, **inputs** (sensors, buttons), and **outputs** (motors, LEDs, display).
- The program runs in a **loop**: read inputs → decide → set outputs.
- They are everywhere and make devices automatic and “smart.”
