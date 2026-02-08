# Chapter 16: Motion & Game Coding (PictoBlox)

**Part 2: Computational Thinking | Grade 6**

---

## What Is the X-Axis?

In games and animations we often move characters or objects on the **stage** (the screen). To describe **position** we use **coordinates**. The **x-axis** is the **horizontal** line: it goes **left and right**. Usually:

- **x = 0** is at the centre or at the left edge (depending on the tool).
- **Increasing x** (positive) often means **right**.
- **Decreasing x** (negative) often means **left**.

So the **x-axis** is about **horizontal movement**: left ↔ right.

| Term | Meaning |
|------|---------|
| **X-axis** | Horizontal direction (left ↔ right) |
| **x coordinate** | Position along that line (e.g. x = 100 means 100 steps to the right of 0) |
| **Horizontal** | Left–right (like the horizon) |

**Real-life link:** In a side-scrolling game, when the character runs to the right, its x value increases. When it runs left, x decreases. In PictoBlox (or Scratch), “change x by 10” moves the sprite to the right.

---

## Meaning of “Change x by 3”

In PictoBlox (and tools like Scratch), we have **motion blocks**. One of them is **“change x by [number]”**.

- **Change x by 3** → The sprite (character or object) moves **3 steps** in the **positive x direction**. If positive x is to the right, the sprite moves **to the right**.
- **Change x by -5** → The sprite moves **5 steps** in the **negative x direction** (usually **to the left**).

So “change x by 3” means: add 3 to the current x position → the character moves **to the right** (in the usual coordinate system). There is also **“change y by”** for **vertical** movement (up/down). **Y-axis** is vertical: up ↔ down.

| Block (idea) | Effect (typical) |
|--------------|-------------------|
| **Change x by 3** | Move 3 steps to the right |
| **Change x by -3** | Move 3 steps to the left |
| **Change y by 3** | Move 3 steps up |
| **Change y by -3** | Move 3 steps down |

---

## Why Motion Blocks Matter

Motion blocks are used for:

- **Games** — Move the player, enemies, or objects (e.g. “change x by 5” when the right arrow key is pressed).
- **Animations** — Make a character walk, a ball bounce, or an object slide across the stage.
- **Interactive stories** — Move characters to different parts of the screen when the user clicks or when the story proceeds.

So motion blocks are the **building blocks of movement** in games and animations. Without them, nothing would move on the stage.

| Use | Example |
|-----|---------|
| **Games** | Player moves left/right with arrow keys; “change x by -10” when left key pressed |
| **Animations** | Character walks: repeat “change x by 2” many times, or use “move 10 steps” |
| **Stories** | Character moves to a new position when user taps “Next” |

**Real-life example:** In a simple racing or running game, pressing the right key runs “change x by 5” every time the key is held, so the character moves right across the screen.

---

## PictoBlox in Short

**PictoBlox** is a block-based coding environment (based on Scratch ideas) that supports **robotics** and **animation**. You can:

- Use **motion blocks** (change x, change y, move, turn).
- Use **events** (when key pressed, when sprite clicked).
- Use **control** (repeat, if–then) and **looks** (say, change costume).
- Connect to **hardware** (e.g. Arduino, sensors) in some versions.

So the same ideas—**events**, **blocks**, **variables**, **motion**—that we use in app building also appear in PictoBlox for games and animations.

---

## A Little History

- **Scratch** (MIT, 2007) introduced block-based coding with a **stage**, **sprites**, and **motion blocks** (move, turn, go to x y, change x by, change y by). It became very popular in schools.
- **PictoBlox** (by STEMpedia and others) extended this with **robotics** and **Arduino** integration so that students can code both on-screen characters and real robots. The **x and y** coordinate system and motion blocks work the same way in many such tools.

---

## One Level Higher: Velocity and Position

In real physics and in advanced games, we often think in terms of **velocity** (speed in a direction) and **position**:

- **Position** = where the sprite is (x, y).
- **Velocity** = how much position changes per unit time (e.g. “change x by 5” every 0.1 seconds → horizontal speed of 50 units per second).

So “change x by 3” is like giving the sprite a **velocity** for one step: it moves 3 units in the x direction. In a loop (e.g. “forever: change x by 3”), the sprite keeps moving—that is **constant velocity** in one direction. Games also use **acceleration** (velocity changes over time) for things like jumping or gravity, but the basic idea is: **motion blocks update position**, and doing that repeatedly gives the illusion of movement.

| Idea | Meaning |
|------|---------|
| **Position (x, y)** | Where the sprite is on the stage |
| **Velocity** | How much position changes per step (or per second) |
| **“Change x by 3”** | Update x position by 3 (one step of movement) |

---

## Key Points to Remember

- The **x-axis** is **horizontal** (left ↔ right). **Change x by 3** moves the sprite **to the right** (in the usual setup).
- **Motion blocks** (change x, change y, move, turn) are used in **games**, **animations**, and **interactive stories**.
- **PictoBlox** is a block-based tool (like Scratch) with motion, events, and optional robotics.
- **Position** is (x, y); **“change x by”** updates position—repeating it gives continuous movement (like velocity).

---

## Multiple Choice Questions

1. The x-axis is  
   (a) vertical (up–down)  
   (b) horizontal (left–right)  
   (c) only at the centre  
   (d) only for colours  

2. “Change x by 3” usually moves the sprite  
   (a) down  
   (b) to the right  
   (c) up  
   (d) only in place  

3. Motion blocks are used for  
   (a) only text  
   (b) games, animations, and interactive stories  
   (c) only variables  
   (d) only labels  

4. The y-axis is  
   (a) horizontal  
   (b) vertical (up–down)  
   (c) only at the centre  
   (d) only for x  

5. “Change x by -5” usually moves the sprite  
   (a) to the right  
   (b) to the left  
   (c) up  
   (d) down  

6. PictoBlox is  
   (a) only a game  
   (b) a block-based coding tool (like Scratch) with motion and optional robotics  
   (c) only for typing code  
   (d) only a calculator  

7. In a game, to move the character right we often  
   (a) only change colour  
   (b) use “change x by” a positive number (e.g. change x by 5)  
   (c) only set a variable  
   (d) only use a label  

8. Position on the stage is given by  
   (a) only x  
   (b) (x, y) coordinates  
   (c) only colour  
   (d) only a variable name  

9. Velocity in games is related to  
   (a) only colour  
   (b) how much position changes (e.g. change x per step)  
   (c) only the sprite name  
   (d) only the stage size  

10. Scratch was developed at  
    (a) a game company  
    (b) MIT  
    (c) only for robots  
    (d) only in 2020  

11. “Change y by 3” usually moves the sprite  
   (a) left  
   (b) up (if positive y is up)  
   (c) right  
   (d) only in place  

12. Motion blocks include  
   (a) only “set variable”  
   (b) change x, change y, move, turn  
   (c) only “when green flag”  
   (d) only “say”  

13. In an animation, repeating “change x by 2” makes the sprite  
   (a) stop  
   (b) move continuously in one direction (e.g. right)  
   (c) only blink  
   (d) only change colour  

14. PictoBlox can connect to  
   (a) only the internet  
   (b) hardware like Arduino (in some versions)  
   (c) only a printer  
   (d) only a keyboard  

15. Horizontal means  
   (a) up–down  
   (b) left–right  
   (c) only at centre  
   (d) only diagonal  

16. The stage is  
   (a) only a variable  
   (b) the area where sprites move and are drawn  
   (c) only a block  
   (d) only a label  

17. A sprite is  
   (a) only a number  
   (b) a character or object that can move and have costumes  
   (c) only a colour  
   (d) only the stage  

18. “Go to x: 0 y: 0”  
   (a) only changes colour  
   (b) moves the sprite to position (0, 0)  
   (c) only sets a variable  
   (d) only repeats  

19. Constant velocity means  
   (a) the sprite stops  
   (b) the sprite moves by the same amount each step (e.g. change x by 3 every time)  
   (c) only the colour changes  
   (d) only the stage changes  

20. Motion blocks update  
   (a) only variables  
   (b) the sprite’s position (x, y) or direction  
   (c) only labels  
   (d) only the app name  

21. In a side-scrolling game, the player often moves  
   (a) only up and down  
   (b) left and right (and maybe up/down) using x and y  
   (c) only in circles  
   (d) only with the mouse  

22. STEMpedia is associated with  
   (a) only games  
   (b) PictoBlox and educational robotics/coding  
   (c) only resistors  
   (d) only batteries  

23. “Turn 15 degrees” is a  
   (a) only variable block  
   (b) motion block (rotation)  
   (c) only text block  
   (d) only logic block  

24. Repeating “change x by 3” in a loop gives  
   (a) no movement  
   (b) continuous movement in one direction  
   (c) only one move  
   (d) only a blink  

25. Coordinates (x, y) help us  
   (a) only set colours  
   (b) know where the sprite is and how to move it  
   (c) only type text  
   (d) only clear the stage  

---

**Answers:** 1-b, 2-b, 3-b, 4-b, 5-b, 6-b, 7-b, 8-b, 9-b, 10-b, 11-b, 12-b, 13-b, 14-b, 15-b, 16-b, 17-b, 18-b, 19-b, 20-b, 21-b, 22-b, 23-b, 24-b, 25-b.
