# Chapter 11: Understanding Blocks in Thunkable

**Part 2: Computational Thinking | Grade 6**

---

## What Are Blocks?

In block-based coding (e.g. Thunkable), **blocks** are small pieces that represent **instructions**. Each block tells the app to do one thing: show a message, change a number, repeat an action, or make a decision. When you **snap blocks together**, you are building a **sequence of instructions** that the app will run. So blocks are like sentences in a recipe: “When the user taps the button, set the label text to ‘Hello!’” is done by connecting a “when Button Click” block with a “set Label text to” block.

| Idea | Meaning |
|------|---------|
| **Block** | One instruction (e.g. show text, set variable, repeat) |
| **Snap together** | Order and connect blocks so they run in sequence or inside an event |
| **Program** | The full set of blocks that define what the app does |

**Real-life link:** Like following steps to make a sandwich—first take bread, then add butter, then add filling. Blocks are those steps; the order and choice of steps decide the result.

---

## Types of Blocks

Different blocks do different jobs. In Thunkable (and similar tools) we often see these **types**:

### Math Blocks

**Math blocks** work with **numbers**. They are used for:

- **Addition** (+)
- **Subtraction** (−)
- **Multiplication** (×)
- **Division** (÷)
- Sometimes **square root**, **round**, or **random number**

**Example:** “What is 15 + 27?” We use an add block with 15 and 27. Or: “Set score to score + 1” when the player scores a point.

| Operation | Use |
|-----------|-----|
| + | Add (e.g. total = price1 + price2) |
| − | Subtract (e.g. change = given − cost) |
| × | Multiply (e.g. area = length × width) |
| ÷ | Divide (e.g. average = total ÷ count) |

---

### Logic Blocks

**Logic blocks** are used for **decisions** and **conditions**. They answer “yes or no” questions (true/false) and let the app do different things in different situations.

- **If–then:** “If the score is greater than 10, then show ‘You won!’”
- **If–then–else:** “If the user is older than 18, show ‘Adult’; else show ‘Minor’.”
- **Compare:** Is A equal to B? Is A greater than B? Is the text empty?

| Use | Example |
|-----|---------|
| **Decisions** | If age ≥ 18, then allow access |
| **Conditions** | If password = “secret123”, then open screen |
| **Compare** | Is score > 100? Is name empty? |

---

### Control Blocks

**Control blocks** decide **when** and **how many times** code runs.

- **When (events):** “When Button1 is clicked,” “When screen opens,” “When slider value changes.”
- **Repeat / loop:** “Repeat 10 times: move sprite 5 steps.”
- **Wait:** “Wait 1 second” before doing the next step.

So we use them for **repeating actions** and for **running code at the right time** (when something happens).

| Use | Example |
|-----|---------|
| **Repeating** | Repeat 5 times: add 1 to counter |
| **Right time** | When button clicked → run these blocks |
| **Wait** | Wait 2 seconds, then show message |

---

### Text Blocks

**Text blocks** work with **words and messages**.

- **Join:** Combine two pieces of text (e.g. “Hello ” + name).
- **Length:** How many characters in the text?
- **Substring:** Get part of the text (e.g. first 3 letters).
- **User input:** Get what the user typed in a text box.

We use them for **labels**, **messages**, **user input**, and **displaying results**.

| Use | Example |
|-----|---------|
| **Words** | “Welcome, ” + userName |
| **Messages** | set Label text to “Correct!” |
| **User input** | get TextBox1 text |

---

## Variables

**Variables** are like **boxes** that **store information** temporarily. Each variable has a **name** (e.g. “score,” “age,” “total”) and a **value** (a number, text, or true/false). We can:

- **Set** the value: “Set score to 0” when the game starts.
- **Change** the value: “Set score to score + 1” when the player scores.
- **Use** the value: “If score > 10, show ‘You won!’”

Variables let the app **remember** things (scores, names, choices) and use them later.

| Idea | Meaning |
|------|---------|
| **Variable** | A named storage (e.g. score, age) that holds a value |
| **Set** | Give the variable a value |
| **Get** | Use the current value in a block |

**Real-life example:** In a game, “score” is a variable. When the player gets a point, we do “set score to score + 1.” The label on screen shows the value of “score.”

---

## A Little History

- **Block-based programming** for education was popularised by **Scratch** (MIT Media Lab, led by Mitchel Resnick, 2007). The idea was to let children focus on **logic and structure** instead of typing syntax.
- **App Inventor** (MIT, later maintained by MIT and others) brought blocks to **mobile app** building. **Thunkable** and similar tools extended this idea so that students can build real apps with blocks and see them on phones.

---

## One Level Higher: Algorithms and Sequence

When we arrange blocks, we are really writing an **algorithm**—a step-by-step method to solve a problem or do a task. The **order** of steps matters: “First set total to 0, then add price1 to total, then add price2 to total” gives the correct sum. If we did “add price2 to total” before setting total to 0, we would get a wrong result. So **sequence** (order of execution) is a core idea in programming. In block-based coding, the **top-to-bottom** order of blocks inside an event is the order in which they run. Understanding “first this, then that” helps you debug when the app does not do what you expect.

| Concept | Meaning |
|---------|---------|
| **Algorithm** | A clear step-by-step procedure to do a task |
| **Sequence** | Order of steps; changing order can change the result |
| **Execution** | Blocks run one after another from top to bottom (unless a loop or event interrupts) |

---

## Key Points to Remember

- **Blocks** are instructions; snapping them together builds the program.
- **Math blocks:** addition, subtraction, multiplication, division (and more).
- **Logic blocks:** decisions, conditions, if–then, comparisons.
- **Control blocks:** when to run (events), repeat, wait.
- **Text blocks:** words, messages, joining text, user input.
- **Variables** store values (numbers, text) so the app can remember and use them.
- The **order** of blocks (sequence) is part of the **algorithm** and affects the result.

---

## Multiple Choice Questions

1. Blocks in Thunkable are  
   (a) only for decoration  
   (b) instructions that tell the app what to do  
   (c) only numbers  
   (d) only colours  

2. Math blocks are used for  
   (a) only text  
   (b) addition, subtraction, multiplication, division  
   (c) only events  
   (d) only buttons  

3. Logic blocks are used for  
   (a) only drawing  
   (b) decisions and conditions (if–then)  
   (c) only sound  
   (d) only colours  

4. Control blocks are used for  
   (a) only numbers  
   (b) repeating actions and running code at the right time (events)  
   (c) only text  
   (d) only variables  

5. Text blocks are used for  
   (a) only numbers  
   (b) words, messages, user input  
   (c) only events  
   (d) only loops  

6. A variable is like  
   (a) a button  
   (b) a box that stores information temporarily  
   (c) only a label  
   (d) only a screen  

7. We can use a variable to  
   (a) only show one message  
   (b) store and change values (e.g. score, name)  
   (c) only draw  
   (d) only play sound once  

8. “If score > 10” uses  
   (a) only a math block  
   (b) logic (condition)  
   (c) only a text block  
   (d) only a variable name  

9. “When Button Click” is a  
   (a) math block  
   (b) control/event block  
   (c) only a variable  
   (d) only text  

10. “Set score to score + 1”  
    (a) only sets score to 1  
    (b) adds 1 to the current score and stores the new value  
    (c) only deletes score  
    (d) only shows score  

11. Joining “Hello ” and “World” gives  
   (a) only “Hello”  
   (b) “Hello World”  
   (c) only “World”  
   (d) a number  

12. A loop (repeat) is used to  
   (a) run code only once  
   (b) run code multiple times  
   (c) only stop the app  
   (d) only set one variable  

13. The order of blocks  
   (a) does not matter  
   (b) matters; they run from top to bottom (sequence)  
   (c) is random  
   (d) is only for looks  

14. An algorithm is  
   (a) a single number  
   (b) a step-by-step procedure to do a task  
   (c) only a colour  
   (d) only a button  

15. Scratch was developed at  
   (a) a game company  
   (b) MIT Media Lab  
   (c) only for professionals  
   (d) only in 2020  

16. “Get TextBox1 text” gets  
   (a) only a number  
   (b) what the user typed in the text box  
   (c) only the first letter  
   (d) only the colour  

17. If–then–else lets the app  
   (a) only do one thing  
   (b) do one thing if condition is true, another if false  
   (c) only repeat  
   (d) only wait  

18. “Wait 1 second” is a  
   (a) math block  
   (b) control block (timing)  
   (c) only a variable  
   (d) only text  

19. Variables help the app  
   (a) only show one screen  
   (b) remember values (e.g. score, name) and use them later  
   (c) only play music  
   (d) only change colour once  

20. Comparing two numbers (e.g. is A > B?) uses  
   (a) only text blocks  
   (b) logic blocks  
   (c) only control blocks  
   (d) only variables  

21. “Set Label text to” is used to  
   (a) only set a variable  
   (b) show text on the screen (in a label)  
   (c) only get input  
   (d) only repeat  

22. Execution order means  
   (a) the order in which blocks run  
   (b) only the number of blocks  
   (c) only the colour of blocks  
   (d) only the name of the app  

23. Thunkable and App Inventor are  
   (a) only games  
   (b) block-based app builders  
   (c) only for typing code  
   (d) only for drawing  

24. A condition is  
   (a) only a number  
   (b) a true/false check (e.g. is age ≥ 18?)  
   (c) only a sound  
   (d) only a colour  

25. “Repeat 5 times” will run the blocks inside  
   (a) 0 times  
   (b) 5 times  
   (c) once  
   (d) forever without stopping  

---

**Answers:** 1-b, 2-b, 3-b, 4-b, 5-b, 6-b, 7-b, 8-b, 9-b, 10-b, 11-b, 12-b, 13-b, 14-b, 15-b, 16-b, 17-b, 18-b, 19-b, 20-b, 21-b, 22-a, 23-b, 24-b, 25-b.
