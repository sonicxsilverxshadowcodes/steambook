# Chapter 12: Events – Making Apps Respond

**Part 2: Computational Thinking | Grade 6**

---

## What Is an Event?

An **event** is **something that happens** in the app (or in the world that the app can detect). When that thing happens, we can tell the app to **run a set of blocks**. So events are the “triggers” that make the app respond: “When this happens, do that.” Without events, the app would not know *when* to show a message, play a sound, or change the screen. Events connect **user actions** or **system actions** to **our code**.

| Term | Meaning |
|------|---------|
| **Event** | Something that happens (e.g. button clicked, screen opens) |
| **Event handler** | The blocks we attach to an event (what to do when it happens) |
| **Trigger** | The event that starts the code |

**Real-life examples:**

- **Button clicked** → User taps a button; we run blocks that might show “Thank you!” or add 1 to the score.
- **Screen opens** → When the user opens a screen, we run blocks that load data or set initial text.
- **Slider moved** → When the user drags a slider, we run blocks that change volume or brush size.

---

## Button Click Event

If you want something to happen **only when the user taps a button**, you use a **when Button Click** (or “when ButtonName Click”) block. You then attach all the blocks that should run when that button is tapped. For example:

- “When Button1 is clicked → set Label1 text to ‘Hello!’”
- “When Submit is clicked → get the text from TextBox1, check if it is correct, then show a message.”

The **event block** is the one that says “when [this component] [this action].” Everything connected under it runs **in order** when the event occurs.

| Step | What we do |
|------|------------|
| 1 | Add a button to the screen (in the designer) |
| 2 | In the blocks editor, find “when ButtonName Click” |
| 3 | Snap the blocks we want (e.g. set label, play sound) inside or under this event |
| 4 | When the user taps the button, those blocks run |

**Real-life link:** On a website, “Submit” or “Login” is a button. Clicking it is an event; the site then runs code to check your input and show the next page. In our app, we do the same with “when Button Click.”

---

## Why Events Are Important

Without events:

- The app would not know **when** to react. It might run some code once at start and then do nothing when the user taps or types.
- Buttons, sliders, and text boxes would not **do** anything when the user interacts with them.
- The app would feel “dead”—no response to taps or input.

With events:

- We connect **user actions** (tap, type, slide) to **our instructions** (show message, change screen, update variable).
- The app becomes **interactive** and **responsive**.

So **events** are what make an app **reactive**: something happens → the app runs the right blocks → the user sees the result.

| Without events | With events |
|----------------|-------------|
| App may run once and stop | App responds each time the user does something |
| Buttons do nothing | Buttons run the blocks we set |
| Not interactive | Interactive |

---

## Other Common Events

Besides “when Button Click,” we often use:

| Event | When it runs |
|-------|----------------|
| **When Screen opens** | When the user first sees this screen (e.g. load data, set initial text) |
| **When Slider value changes** | When the user moves the slider (e.g. change volume, brush size) |
| **When TextBox text changes** | When the user types or deletes text (use carefully; can run very often) |
| **When Image or icon is clicked** | When the user taps that element |
| **When Canvas is touched/dragged** | When the user draws or touches the drawing area |

Choosing the **right event** is important. For “do this when the user taps Submit,” we use **Button Click**. For “do this when the screen loads,” we use **Screen opens**.

---

## A Little History

- **Event-driven programming** became central when computers started using **graphical user interfaces (GUIs)**—windows, buttons, menus. Instead of the program asking “what did the user type?” in a loop, the system would **notify** the program: “the user clicked this button.” This is the **event-driven** model.
- **Alan Kay** and others at Xerox PARC, and later **Apple** and **Microsoft**, helped popularise GUIs and events. Today almost every app and website is built around events (click, scroll, type, etc.).

---

## One Level Higher: Event Loop and Thread

Behind the scenes, the device is always running an **event loop**: it waits for something to happen (tap, timer, network response). When an event occurs, the **operating system** or **framework** delivers it to your app, and your **event handler** (the blocks you wrote) runs. Usually this runs on the **main thread** (the main sequence of execution). So when you tap a button, your “when Button Click” blocks run in that loop. If those blocks take too long (e.g. a very heavy calculation), the app might seem to “freeze” because the main thread is busy. For now, keeping event handlers **short and simple** (e.g. update a label, change a variable) keeps the app responsive. Understanding “event → handler runs → done → wait for next event” helps you see why the **order** of blocks inside one event matters, but events themselves can happen in **any order** (whatever the user does).

| Idea | Meaning |
|------|---------|
| **Event loop** | The system keeps waiting for events and then runs the right handler |
| **Handler** | The blocks that run when an event occurs |
| **Main thread** | Where UI and most event handlers run; keep it quick so the app stays responsive |

---

## Key Points to Remember

- An **event** is something that happens (e.g. button clicked, screen opens, slider moved).
- We use **when [component] [action]** to run blocks **only when** that event happens.
- **Button Click** is used when we want something to happen on a button tap.
- **Without events**, the app would not respond to user actions; **with events**, it becomes interactive.
- Other useful events: Screen opens, Slider value change, Canvas touch.

---

## Multiple Choice Questions

1. An event is  
   (a) only a number  
   (b) something that happens in the app (e.g. button clicked)  
   (c) only a variable  
   (d) only a colour  

2. To make something happen when a button is tapped we use  
   (a) only a variable  
   (b) “when Button Click” (or similar) event block  
   (c) only a label  
   (d) only a math block  

3. Without events, the app  
   (a) runs faster  
   (b) cannot respond to user actions (buttons, etc. do nothing)  
   (c) always shows the same screen  
   (d) only uses variables  

4. “When Screen opens” runs  
   (a) only when the app is closed  
   (b) when the user first sees that screen  
   (c) only when a button is clicked  
   (d) only once in the app’s life  

5. “When Slider value changes” runs  
   (a) only at start  
   (b) when the user moves the slider  
   (c) only when the screen closes  
   (d) only for buttons  

6. Events are important because they  
   (a) only store numbers  
   (b) tell the app when to run which code (make the app interactive)  
   (c) only draw shapes  
   (d) only play sound once  

7. The blocks we attach to an event are called  
   (a) only variables  
   (b) the event handler (what to do when the event happens)  
   (c) only labels  
   (d) only screens  

8. A trigger is  
   (a) only a number  
   (b) the event that starts the code (e.g. button click)  
   (c) only a colour  
   (d) only a text  

9. GUI stands for  
   (a) General User Input  
   (b) Graphical User Interface (windows, buttons, etc.)  
   (c) only games  
   (d) only variables  

10. Event-driven programming means  
    (a) the program runs only once  
    (b) the program reacts when events happen (click, type, etc.)  
    (c) there are no buttons  
    (d) there are no variables  

11. If we want to load data when the user opens a screen we use  
   (a) only Button Click  
   (b) “When Screen opens” (or similar)  
   (c) only a slider  
   (d) only a label  

12. When the user taps a button,  
   (a) nothing happens unless we added a “when Button Click” handler  
   (b) the blocks in the “when Button Click” handler run  
   (c) only the app closes  
   (d) only the variable is deleted  

13. “When Canvas is touched” is used for  
   (a) only buttons  
   (b) drawing apps (user draws or touches the canvas)  
   (c) only sliders  
   (d) only labels  

14. The event loop  
   (a) only runs once  
   (b) keeps waiting for events and runs the right handler when something happens  
   (c) only counts variables  
   (d) only draws the screen  

15. Keeping event handlers short helps  
   (a) make the app slower  
   (b) keep the app responsive (no freezing)  
   (c) only use more memory  
   (d) only add more buttons  

16. We can have  
   (a) only one event per app  
   (b) many events (different buttons, screen open, slider, etc.)  
   (c) no events  
   (d) only one button  

17. The order of events depends on  
   (a) only the programmer  
   (b) what the user does (which button they tap, when they move the slider)  
   (c) only the first event  
   (d) only the last event  

18. “When TextBox text changes”  
   (a) runs only when the app starts  
   (b) runs when the user types or deletes text (can run very often)  
   (c) runs only when the screen closes  
   (d) runs only for buttons  

19. Interactive means  
   (a) the app never changes  
   (b) the app responds to user actions (taps, typing, etc.)  
   (c) the app has no buttons  
   (d) the app has no events  

20. Alan Kay and others worked on  
   (a) only batteries  
   (b) GUIs and event-driven ideas (e.g. at Xerox PARC)  
   (c) only resistors  
   (d) only wires  

21. Main thread is where  
   (a) only the battery runs  
   (b) UI and most event handlers run  
   (c) only the internet runs  
   (d) only sound runs  

22. When we “attach” blocks to an event we  
   (a) delete them  
   (b) snap them under the event block so they run when the event happens  
   (c) only copy them  
   (d) only colour them  

23. A responsive app  
   (a) never reacts  
   (b) reacts quickly to user actions (taps, etc.)  
   (c) only runs once  
   (d) has no events  

24. “When Image is clicked” runs when  
   (a) the screen opens  
   (b) the user taps that image/icon  
   (c) only the slider moves  
   (d) only the app closes  

25. Events connect  
   (a) only numbers  
   (b) user actions (or system actions) to the code we want to run  
   (c) only colours  
   (d) only labels  

---

**Answers:** 1-b, 2-b, 3-b, 4-b, 5-b, 6-b, 7-b, 8-b, 9-b, 10-b, 11-b, 12-b, 13-b, 14-b, 15-b, 16-b, 17-b, 18-b, 19-b, 20-b, 21-b, 22-b, 23-b, 24-b, 25-b.
