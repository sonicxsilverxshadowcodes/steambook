# Chapter 6: Resistor Color Code – Reading Values

**Part 1: Electronics & IoT | Grade 6**

---

## Why Are There Colors on Resistors?

Resistors are often small—smaller than a grain of rice in many circuits. Writing numbers on them would be hard to read. So instead, **coloured bands** are painted on the resistor. Each colour stands for a number or a multiplier. By reading the bands in order, we can find the **resistance value** and the **tolerance** (how much the real value may differ from the marked value). This system is used all over the world, so anyone can read a resistor even if they do not speak the same language.

| Reason | Explanation |
|--------|-------------|
| **Size** | Resistors are too small for clear numbers |
| **Standard** | Same code everywhere (international) |
| **Information** | Value and tolerance both from bands |

**Real-life link:** When you build a circuit from a diagram that says “use a 330 Ω resistor,” you pick a resistor and read its bands to check it really is 330 Ω (or close, within tolerance).

---

## How Many Bands?

Most common resistors have **4 bands**, but some have **5 bands** (for more precise values). We will focus on the **4-band** code.

| Band order (4-band) | Meaning |
|---------------------|--------|
| **1st band** | First digit of the value (0–9) |
| **2nd band** | Second digit of the value (0–9) |
| **3rd band** | Multiplier (power of 10, or how many zeros) |
| **4th band** | Tolerance (how much the value can vary, in %) |

Sometimes the 4th band is **gold** or **silver**; if there is no 4th band, tolerance is often 20%.

---

## The Color Code Table

Memorise this table (or keep it handy). The same colours are used for digits and for multiplier/tolerance, but the position tells us what they mean.

| Colour | Digit | Multiplier | Tolerance |
|--------|-------|------------|-----------|
| Black | 0 | 10⁰ = 1 | — |
| Brown | 1 | 10¹ = 10 | ±1% |
| Red | 2 | 10² = 100 | ±2% |
| Orange | 3 | 10³ = 1000 | — |
| Yellow | 4 | 10⁴ = 10,000 | — |
| Green | 5 | 10⁵ = 100,000 | ±0.5% |
| Blue | 6 | 10⁶ = 1,000,000 | — |
| Violet | 7 | 10⁷ | — |
| Grey | 8 | 10⁸ | — |
| White | 9 | 10⁹ | — |
| Gold | — | 0.1 | ±5% |
| Silver | — | 0.01 | ±10% |
| No band | — | — | ±20% |

**How to read:** Value = (1st digit)(2nd digit) × multiplier. Then add the unit: Ω (ohms), kΩ (kilo-ohms = 1000 Ω), or MΩ (mega-ohms = 1,000,000 Ω).

---

## Examples of Reading Resistor Values

**Example 1:** Bands are **Orange, Orange, Brown, Gold**

- 1st digit: Orange = **3**
- 2nd digit: Orange = **3**
- Multiplier: Brown = **10**
- Value = 33 × 10 = **330 Ω**
- Tolerance: Gold = **±5%**

So the resistor is **330 Ω ± 5%**. The actual value can be between about 313 Ω and 347 Ω.

**Example 2:** Bands are **Brown, Black, Red, Gold**

- 1st digit: Brown = **1**
- 2nd digit: Black = **0**
- Multiplier: Red = **100**
- Value = 10 × 100 = **1000 Ω = 1 kΩ**
- Tolerance: Gold = **±5%**

**Example 3:** Bands are **Brown, Black, Orange, Gold**

- 1st + 2nd: **10**
- Multiplier: Orange = **1000**
- Value = 10 × 1000 = **10,000 Ω = 10 kΩ**

| Bands (1st, 2nd, 3rd, 4th) | Value | Tolerance |
|----------------------------|-------|-----------|
| Orange, Orange, Brown, Gold | 330 Ω | ±5% |
| Brown, Black, Red, Gold | 1 kΩ | ±5% |
| Brown, Black, Orange, Gold | 10 kΩ | ±5% |
| Brown, Black, Yellow, Gold | 100 kΩ | ±5% |
| Brown, Black, Green, Gold | 1 MΩ | ±5% |

---

## Which End to Start From?

Sometimes it is hard to know which end is “first.” Tips:

- The **tolerance** band (gold or silver) is usually at one **end**. Start from the **opposite** end.
- The first band is often **closer** to one end; tolerance is at the other end.
- Gold and silver are **never** used for the first two digits, so if you see gold/silver, that is the tolerance end.

---

## Why Tolerance Matters

Tolerance tells us how much the **actual** resistance can differ from the **marked** value. A 330 Ω ± 5% resistor might be 313 Ω, 330 Ω, or 347 Ω. For an LED circuit, that is usually fine. For very precise circuits (e.g. some measuring instruments), we use resistors with **smaller tolerance** (e.g. ±1% or ±0.5%), which may have **5 bands** instead of 4.

| Tolerance | Meaning | Use |
|-----------|--------|-----|
| ±20% | Value can vary a lot | Old or cheap parts |
| ±5% (gold) | Common; good for most projects | LED circuits, simple projects |
| ±1% (brown) | Closer to marked value | When accuracy matters |

---

## A Little History

- **Colour coding** for electronic components became common in the early 20th century when radio and telephone equipment used many small parts.
- The **international** colour code helped factories and engineers around the world use the same parts. Today it is part of standards set by organisations like the IEC (International Electrotechnical Commission).

---

## One Level Higher: 5-Band Resistor Code

In a **5-band** resistor, the first **three** bands are digits, the **fourth** is the multiplier, and the **fifth** is tolerance. This allows values like 1.23 kΩ or 100 Ω with ±1% to be shown clearly.

| Band (5-band) | 1st | 2nd | 3rd | 4th | 5th |
|---------------|-----|-----|-----|-----|-----|
| Meaning | 1st digit | 2nd digit | 3rd digit | Multiplier | Tolerance |

Example: Brown, Black, Black, Brown, Brown → 100 × 10 = 1000 Ω = 1 kΩ, ±1%.

---

## Key Points to Remember

- Resistors use **colour bands** because they are too small for numbers.
- **4-band:** 1st digit, 2nd digit, multiplier, tolerance. Value = (1st)(2nd) × multiplier.
- **Gold** = ±5%, **Silver** = ±10% tolerance. Start reading from the end **opposite** to the tolerance band.
- **10 kΩ** = 10,000 Ω; **100 kΩ** = 100,000 Ω. Use the colour table to read any 4-band resistor.

---

## Multiple Choice Questions

1. Resistors use colour bands because  
   (a) they look nice  
   (b) they are too small to print numbers clearly  
   (c) they are only for decoration  
   (d) they are always black  

2. In a 4-band resistor, the first band gives  
   (a) tolerance  
   (b) the first digit of the value  
   (c) the multiplier only  
   (d) the unit  

3. The third band in a 4-band resistor is the  
   (a) first digit  
   (b) second digit  
   (c) multiplier  
   (d) tolerance  

4. Gold in the fourth band usually means  
   (a) 0 Ω  
   (b) ±5% tolerance  
   (c) 10 Ω  
   (d) high resistance  

5. Orange, Orange, Brown, Gold gives  
   (a) 33 Ω  
   (b) 330 Ω  
   (c) 3300 Ω  
   (d) 3.3 Ω  

6. Brown, Black, Red, Gold gives  
   (a) 10 Ω  
   (b) 100 Ω  
   (c) 1000 Ω (1 kΩ)  
   (d) 10,000 Ω  

7. 10 kΩ is the same as  
   (a) 10 Ω  
   (b) 100 Ω  
   (c) 10,000 Ω  
   (d) 100,000 Ω  

8. Tolerance tells us  
   (a) the colour of the resistor  
   (b) how much the actual value can differ from the marked value  
   (c) the current rating  
   (d) the voltage rating  

9. Black in the digit position means  
   (a) no value  
   (b) 0  
   (c) 10  
   (d) infinite  

10. Brown in the first band means digit  
    (a) 0  
    (b) 1  
    (c) 2  
    (d) 5  

11. Red as multiplier means  
    (a) ×1  
    (b) ×100  
    (c) ×1000  
    (d) ×10  

12. Silver in the fourth band means tolerance  
    (a) ±5%  
    (b) ±10%  
    (c) ±20%  
    (d) ±1%  

13. To read the value we start from the end  
    (a) next to the tolerance band  
    (b) opposite to the tolerance band  
    (c) in the middle  
    (d) anywhere  

14. Brown, Black, Orange, Gold gives  
    (a) 1 kΩ  
    (b) 10 kΩ  
    (c) 100 kΩ  
    (d) 100 Ω  

15. A 100 kΩ resistor has value  
    (a) 100 Ω  
    (b) 1000 Ω  
    (c) 100,000 Ω  
    (d) 10 Ω  

16. Green as a digit means  
    (a) 4  
    (b) 5  
    (c) 6  
    (d) 3  

17. Yellow as multiplier means  
    (a) ×10  
    (b) ×100  
    (c) ×1000  
    (d) ×10,000  

18. A 5-band resistor has  
    (a) 3 digits, then multiplier, then tolerance  
    (b) 2 digits only  
    (c) no tolerance  
    (d) only one digit  

19. ±1% tolerance is often shown by the colour  
    (a) gold  
    (b) silver  
    (c) brown  
    (d) black  

20. The colour code is used  
    (a) only in one country  
    (b) internationally  
    (c) only for large resistors  
    (d) only for variable resistors  

21. Violet as a digit means  
    (a) 5  
    (b) 6  
    (c) 7  
    (d) 8  

22. Blue as multiplier means  
    (a) ×10  
    (b) ×100  
    (c) ×1,000,000  
    (d) ×1  

23. If the third band is Gold (as multiplier), we multiply by  
    (a) 10  
    (b) 0.1  
    (c) 1  
    (d) 100  

24. Grey as a digit means  
    (a) 7  
    (b) 8  
    (c) 9  
    (d) 0  

25. White as a digit means  
    (a) 0  
    (b) 9  
    (c) 1  
    (d) 10  

---

**Answers:** 1-b, 2-b, 3-c, 4-b, 5-b, 6-c, 7-c, 8-b, 9-b, 10-b, 11-b, 12-b, 13-b, 14-b, 15-c, 16-b, 17-d, 18-a, 19-c, 20-b, 21-c, 22-c, 23-b, 24-b, 25-b.
