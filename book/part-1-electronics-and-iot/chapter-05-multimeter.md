# Chapter 5: Measuring Electricity – Multimeter

**Part 1: Electronics & IoT | Grade 6**

---

## What Is a Multimeter?

A **multimeter** is a tool that can measure several electrical quantities in one device. The name “multi-meter” means “many measurements.” With one instrument we can measure **voltage** (push), **current** (flow), and **resistance** (opposition to flow). Some multimeters also measure continuity (whether a path is connected), and a few can measure temperature or capacitance. For Grade 6, the three main uses are: **voltage (V)**, **current (I)**, and **resistance (R)**.

| Quantity | What it is | Unit | Multimeter setting (idea) |
|----------|------------|------|----------------------------|
| **Voltage** | “Push” that drives current | Volts (V) | V or VDC / VAC |
| **Current** | Amount of charge flowing per second | Amperes (A) | A or mA |
| **Resistance** | Opposition to current | Ohms (Ω) | Ω (ohm symbol) |

**Real-life link:** When a torch stops glowing, we can use a multimeter to check if the battery still has voltage. If the voltage is too low, we change the battery. We can also check if a resistor is roughly the right value by measuring its resistance.

---

## How Do We Measure Voltage?

To measure **voltage** we connect the multimeter **in parallel** with the part we are measuring—that is, we touch the two probes to the two points between which we want to know the voltage (e.g. the two ends of a battery, or the two legs of an LED). The meter itself has very high resistance, so it does not draw much current and does not change the circuit much. We must:

- Select **Voltage (V)** on the dial.
- Choose **DC** for batteries and most small circuits, or **AC** for mains (only with proper training and safety).
- Connect **red** probe to the point that is more positive and **black** to the more negative (for DC). If we connect the wrong way, a digital meter usually shows a minus sign.

**Never measure high AC mains voltage without an adult and proper training**—it can be dangerous.

---

## How Do We Measure Current?

To measure **current**, the current must **flow through** the meter. So we **break** the circuit at one point and connect the multimeter **in series** so that all the current that goes to the component (e.g. LED) also goes through the meter. We must:

- Select **Current (A or mA)** on the dial. Start with a higher range (e.g. 200 mA) to avoid overloading the meter.
- Open the circuit (e.g. disconnect one wire) and connect the meter in series: one probe to one side, the other probe to the other side, so the current path is through the meter.
- For small circuits, use the **mA** (milliampere) range. Never connect the meter in current mode **across** a battery or power supply (in parallel)—that can blow a fuse or damage the meter.

---

## How Do We Measure Resistance?

To measure **resistance** we need the resistor **out of the circuit** (or at least not connected to a live battery or supply). When we measure resistance, the meter sends a small current through the component and measures the result. If the resistor is still in a circuit with other parts, the reading can be wrong because current might flow through other paths. So:

- **Remove** the resistor from the circuit (or disconnect one leg), or ensure the circuit is off and no other path is parallel to the resistor.
- Set the multimeter to **Ω (ohm mode)**.
- Touch the two probes to the two legs of the resistor. The meter will show the value in ohms (Ω) or kΩ (thousands of ohms).

---

## What Does “OL” or “1” Mean?

When we set the meter to resistance (Ω) and touch the probes to two points, sometimes the display shows **OL** (Over Limit) or **1** (on some digital meters) instead of a number. This usually means:

- The resistance is **very high**—higher than the range the meter can show, or
- There is **no continuous path** between the two probes (open circuit—like an open switch or a broken wire).

So **OL** or **1** does **not** necessarily mean “the resistor is broken.” It can mean:

- The two points are **not connected** (open circuit).
- We are measuring **across an open switch**.
- We are measuring **across air** (very high resistance).

If we measure a **known good resistor** and get a normal value (e.g. 330 Ω), the meter is working. If we measure across two disconnected wires and get OL, that is correct—they are not connected.

| Display | Meaning (in resistance mode) |
|---------|------------------------------|
| A number (e.g. 330, 10.5k) | Resistance in ohms or kΩ |
| **OL** or **1** | Very high resistance or open circuit (no path) |

---

## A Little History

- **Galvanometers** (in the 1800s)** **could detect or measure small currents.**
- **Multimeters** developed when engineers combined voltage, current, and resistance measurement into one portable instrument. **Donald Macadie** is often credited with inventing the first multimeter (then called “Avometer”) in the 1920s in the UK.
- **Digital multimeters (DMMs)** replaced needles with a digital display from the 1970s onward, making readings easier and more accurate.

---

## One Level Higher: Continuity and Diode Test

Many multimeters have two extra useful functions:

**Continuity (🔊 or similar symbol):** The meter beeps when the resistance between the two probes is very low (e.g. below 30 Ω). So we can quickly check if a wire is unbroken, or if two points are connected, without looking at the numbers. **No beep** can mean open circuit (broken wire or loose connection).

**Diode test:** A special mode that applies a small voltage and shows the “forward voltage” of a diode or LED. It helps to check if a diode/LED is working and which lead is positive (anode) and which is negative (cathode).

| Mode | Use |
|------|-----|
| **Continuity** | Check if a path is connected (e.g. wire not broken); beep = low resistance |
| **Diode test** | Check diode/LED and find polarity |

---

## Safety Reminders

| Do ✅ | Don’t ❌ |
|-------|----------|
| Use the correct setting (V, A, or Ω) before connecting | Measure current in parallel with a battery (can damage meter) |
| For current, connect in series and start with higher range | Touch live mains voltage without proper training |
| For resistance, disconnect from circuit or switch off power | Use a damaged meter or broken probes |
| Keep fingers away from metal probe tips when measuring | Assume “OL” always means “broken resistor” |

---

## Key Points to Remember

- A **multimeter** can measure **voltage (V)**, **current (A)**, and **resistance (Ω)**.
- **Voltage** is measured **in parallel**; **current** is measured **in series**.
- **Resistance** is measured with the component out of the circuit (or circuit off) and no parallel paths.
- **OL** or **1** in resistance mode means very high resistance or open circuit, not necessarily a broken resistor.
- **Continuity** mode beeps when there is a low-resistance path; useful for checking wires and connections.

---

## Multiple Choice Questions

1. A multimeter can measure  
   (a) only voltage  
   (b) voltage, current, and resistance  
   (c) only resistance  
   (d) only current  

2. Voltage is measured in  
   (a) Ohms  
   (b) Volts  
   (c) Amperes  
   (d) Watts  

3. To measure voltage we connect the multimeter  
   (a) in series with the component  
   (b) in parallel (across the two points)  
   (c) only to one wire  
   (d) inside the battery  

4. To measure current we connect the multimeter  
   (a) in parallel across the battery  
   (b) in series so current flows through the meter  
   (c) only to the positive terminal  
   (d) only in ohm mode  

5. Resistance is measured in  
   (a) Volts  
   (b) Amperes  
   (c) Ohms  
   (d) Hertz  

6. When the multimeter shows “OL” in resistance mode, it usually means  
   (a) the resistor is 0 Ω  
   (b) very high resistance or open circuit  
   (c) the battery is low  
   (d) the meter is broken  

7. “OL” does NOT always mean  
   (a) over limit  
   (b) the resistor is broken (it can mean open circuit or no connection)  
   (c) open circuit  
   (d) high resistance  

8. To measure resistance accurately we should  
   (a) keep the circuit on with full voltage  
   (b) remove the resistor from the circuit or switch off power  
   (c) measure only in parallel  
   (d) use only the current mode  

9. The unit of current is  
   (a) Volt  
   (b) Ohm  
   (c) Ampere  
   (d) Watt  

10. Who is credited with inventing an early multimeter (Avometer)?  
    (a) Ohm  
    (b) Macadie  
    (c) Volta  
    (d) Faraday  

11. For measuring a small LED current we use the __________ range.  
    (a) 10 A  
    (b) 200 mA or similar (small current range)  
    (c) only voltage  
    (d) only resistance  

12. Connecting the meter in current mode directly across a battery can  
   (a) measure voltage  
   (b) damage the meter or blow a fuse  
   (c) measure resistance  
   (d) show OL  

13. Digital multimeters show readings on  
   (a) a needle  
   (b) a digital display (numbers)  
   (c) a dial only  
   (d) paper  

14. Continuity mode is used to  
   (a) measure exact voltage  
   (b) check if two points are connected (often with a beep)  
   (c) measure high resistance  
   (d) measure current only  

15. Red and black probes are used to  
   (a) only hold the meter  
   (b) touch the two points where we measure (red often to positive for DC voltage)  
   (c) measure only AC  
   (d) measure only resistance  

16. When measuring DC voltage, if we connect red to negative and black to positive, a digital meter may show  
   (a) zero  
   (b) a minus sign (negative reading)  
   (c) OL  
   (d) 1 only  

17. “DMM” stands for  
   (a) Digital Multi Meter  
   (b) Direct Current Meter  
   (c) Diode Measure Mode  
   (d) Double Meter Mode  

18. To measure the voltage of a battery we set the dial to  
   (a) current (A)  
   (b) resistance (Ω)  
   (c) voltage (V) DC  
   (d) continuity only  

19. A resistor of 1 kΩ is the same as  
   (a) 1 Ω  
   (b) 1000 Ω  
   (c) 0.001 Ω  
   (d) 10 Ω  

20. Diode test mode helps to  
   (a) measure only voltage  
   (b) check a diode or LED and see polarity  
   (c) measure only current  
   (d) measure only resistance  

21. We should NOT measure mains voltage (wall socket)  
   (a) because it is DC  
   (b) without proper training and safety—it is dangerous  
   (c) because it is low  
   (d) with a digital meter  

22. In resistance mode, the meter  
   (a) sends a small current through the component  
   (b) does not use any current  
   (c) only measures voltage  
   (d) only beeps  

23. “Multi” in multimeter means  
   (a) one  
   (b) many (it can measure many quantities)  
   (c) zero  
   (d) large  

24. When we measure current, we __________ the circuit and put the meter in series.  
   (a) keep closed  
   (b) break (open)  
   (c) short  
   (d) remove the battery from  

25. A good wire between two points should show __________ in continuity mode.  
   (a) OL  
   (b) a beep (low resistance)  
   (c) high voltage  
   (d) zero current  

---

**Answers:** 1-b, 2-b, 3-b, 4-b, 5-c, 6-b, 7-b, 8-b, 9-c, 10-b, 11-b, 12-b, 13-b, 14-b, 15-b, 16-b, 17-a, 18-c, 19-b, 20-b, 21-b, 22-a, 23-b, 24-b, 25-b.
