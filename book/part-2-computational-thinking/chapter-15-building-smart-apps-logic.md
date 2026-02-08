# Chapter 15: Building Smart Apps (Logic in Real Life)

**Part 2: Computational Thinking | Grade 6**

---

## Age Calculator App – Why Age Matters

An **Age Calculator** app might ask for the user’s **birth year** (or full date) and then **calculate** their age. Age is important in real life because it:

- **Decides eligibility** — e.g. voting, driving, opening a bank account, watching certain content.
- **Helps with permissions** — Parents or apps may allow different features for different ages.
- **Affects services** — Some offers, tickets, or subscriptions are for certain age groups.

So the app is not just math; it is **logic in real life**: we take input (birth year), do a calculation (current year − birth year), and then we might show different messages or options based on the result (e.g. “You are 15” or “You are eligible for…”).

| Use of age | Example |
|------------|---------|
| **Eligibility** | “You must be 18 to register.” |
| **Permissions** | “This content is for 13+.” |
| **Services** | “Child ticket: under 12.” |

---

## Showing Output

After we calculate something (e.g. age, total, score), we need to **show** it to the user. The usual way is with a **Label** component:

- **Set Label text to** the result (e.g. “Your age is 15” or “Total: 100”).
- We can **join** text and variables: e.g. “Your age is ” + age.

So: calculate → put the result in a variable (or use it directly) → set the label text to that value (or a message that includes it).

| Component | Use |
|-----------|-----|
| **Label** | Show text and results (e.g. “Your age is 15”, “Total: 50”) |
| **Set Label text to** | Update what the label shows (number or text) |

---

## Making the App Speak (Text-to-Speech)

To **read the result aloud** we use a **Text-to-Speech (TTS)** component. We give it a piece of text (e.g. the same message we show in the label), and the device **speaks** it. So:

- Calculate the result and build a message (e.g. “Your age is 15”).
- Set the label to this message.
- Call **Text-to-Speech** with this message (e.g. “Speak [message]”).

This helps users who prefer to hear the answer (accessibility) and makes the app feel more interactive.

| Step | What we do |
|------|------------|
| 1 | Add Text-to-Speech component (designer). |
| 2 | Build the message (e.g. “Your age is ” + age). |
| 3 | Use block “Speak” or “TextToSpeech.Speak” with that message. |

---

## Showing Error Messages

When something goes wrong (e.g. user leaves the box empty, or types an invalid year), we should **show an error message** so the user knows what to fix. We can use:

- **Alert box** — A pop-up that shows a message and an OK button. Simple and clear.
- **Custom error message** — Set a label’s text to red and to a message like “Please enter your birth year” or “Invalid year.”

So: **if** the input is invalid **then** show an alert or set the label to an error message; **else** do the normal calculation and show the result.

| Method | Use |
|--------|-----|
| **Alert** | Pop-up with message and OK (e.g. “Please enter a valid year.”) |
| **Label** | Set label text to error message (and maybe change colour to red) |

---

## Case Sensitivity

Computers treat **uppercase** and **lowercase** letters as **different**. So:

- **“Admin”** and **“admin”** are not the same.
- **“Yes”** and **“yes”** are not the same.

If we check a password or a keyword (e.g. “yes” to continue), we must compare exactly as we expect, or we can **convert** the text to one case (e.g. all lowercase) before comparing. So: get the user’s text → convert to lowercase (or uppercase) → compare with “yes”. That way “Yes”, “YES”, and “yes” all work the same.

| Idea | Meaning |
|------|---------|
| **Case sensitive** | “A” ≠ “a”; “Admin” ≠ “admin” |
| **Fix** | Convert to same case before comparing, or compare with exact expected case |

---

## Clearing Inputs

After we show the result (or after an error), we often **clear** the input fields so the user can try again or enter new data. Clearing:

- **Prepares for the next user** or the next try.
- **Avoids confusion** (old value still sitting in the box).

So we use blocks like **set TextBox text to ""** (empty string) to clear the box. We might do this when the user taps “Clear” or “Calculate again,” or right after we show the result.

| When to clear | Why |
|---------------|-----|
| After showing result | Ready for next calculation |
| After error | User can correct and try again |
| When “Clear” or “Reset” is tapped | Start fresh |

---

## A Little History

- **Logic in programs** dates back to the first computers (e.g. conditional branches in code). **Grace Hopper** and others helped develop high-level languages and the idea of writing programs that “decide” based on conditions.
- **User interfaces** that show messages, alerts, and errors became standard with GUIs. **Accessibility** features like Text-to-Speech have been part of operating systems and apps for many years to help users who are blind or prefer spoken output.

---

## One Level Higher: Validation and Edge Cases

**Validation** means checking that the input is **allowed** before we use it. For an age calculator:

- Is the year a **number**?
- Is it in a **reasonable range** (e.g. 1900 to current year)?
- Is the calculated age **non-negative**?

**Edge cases** are unusual situations: e.g. birth year = current year (age 0), or user types letters instead of numbers. We handle them with **if–then** logic: if invalid → show error and maybe clear or focus the input; else → calculate and show result. Thinking about “what if the user does this?” makes the app **robust** and **user-friendly**.

| Idea | Meaning |
|------|---------|
| **Validation** | Check input (e.g. is it a number? is it in range?) before using it |
| **Edge case** | Unusual but possible input (e.g. empty, zero, wrong type) |
| **Robust** | App handles bad or unexpected input without crashing; shows a clear error |

---

## Key Points to Remember

- **Age** (and similar data) is used for **eligibility**, **permissions**, and **services**; we can build apps that calculate and react to it.
- **Show output** with **Labels** (set label text to result or message).
- **Text-to-Speech** lets the app **read the result aloud** (accessibility and interactivity).
- **Error messages**: use **Alert** or set a **label** to an error message when input is invalid.
- **Case sensitivity**: “Admin” ≠ “admin”; convert to one case or compare exactly.
- **Clear inputs** after result or error to prepare for the next try.
- **Validation** and **edge cases** make the app robust (check input, handle empty or wrong data).

---

## Multiple Choice Questions

1. Age is important for  
   (a) only games  
   (b) eligibility, permissions, and services  
   (c) only drawing  
   (d) only colours  

2. We show results to the user using  
   (a) only variables  
   (b) labels (set label text to the result or message)  
   (c) only the slider  
   (d) only the canvas  

3. Text-to-Speech is used to  
   (a) only show text  
   (b) read the result or message aloud  
   (c) only type text  
   (d) only clear the screen  

4. To show an error we can use  
   (a) only a variable  
   (b) an alert box or a label with an error message  
   (c) only the slider  
   (d) only a button  

5. “Admin” and “admin” are  
   (a) the same to the computer  
   (b) different (computers are case sensitive)  
   (c) only numbers  
   (d) only colours  

6. We clear input fields to  
   (a) only delete the app  
   (b) prepare for the next user or next try; avoid confusion  
   (c) only make the app faster  
   (d) only change colour  

7. An alert box is  
   (a) only a label  
   (b) a pop-up that shows a message (e.g. error) and OK  
   (c) only a variable  
   (d) only a slider  

8. To compare “yes” and “Yes” we can  
   (a) only use one  
   (b) convert both to lowercase (or same case) then compare  
   (c) only use numbers  
   (d) only clear the box  

9. Validation means  
   (a) only typing  
   (b) checking that input is valid (e.g. is it a number? in range?) before using it  
   (c) only drawing  
   (d) only playing sound  

10. Setting TextBox text to "" (empty string)  
    (a) only hides the box  
    (b) clears the input  
    (c) only sets a variable  
    (d) only shows an alert  

11. Edge cases are  
   (a) only the best inputs  
   (b) unusual but possible situations (e.g. empty input, zero) that we should handle  
   (c) only colours  
   (d) only buttons  

12. A robust app  
   (a) never has errors  
   (b) handles bad or unexpected input (e.g. shows error, does not crash)  
   (c) only runs once  
   (d) has no labels  

13. Grace Hopper worked on  
   (a) only hardware  
   (b) programming languages and the idea of programs that “decide”  
   (c) only batteries  
   (d) only resistors  

14. We join text and variables to show  
   (a) only numbers  
   (b) a message like “Your age is ” + age  
   (c) only the variable  
   (d) only empty text  

15. Accessibility in apps can include  
   (a) only colours  
   (b) Text-to-Speech so users can hear the result  
   (c) only buttons  
   (d) only sliders  

16. “Please enter a valid year” is an example of  
   (a) only a label for result  
   (b) an error message  
   (c) only a variable name  
   (d) only a colour  

17. After showing the result we might clear the input so that  
   (a) the app closes  
   (b) the user can enter new data or try again  
   (c) only the label disappears  
   (d) only the variable is deleted  

18. Case sensitivity affects  
   (a) only numbers  
   (b) text comparison (“A” vs “a”)  
   (c) only sliders  
   (d) only the canvas  

19. We use if–then to  
   (a) only set one variable  
   (b) show error when input is invalid, else calculate and show result  
   (c) only draw  
   (d) only play sound  

20. “Convert to lowercase” helps when  
   (a) only drawing  
   (b) we want “Yes”, “yes”, “YES” to be treated the same  
   (c) only setting numbers  
   (d) only clearing  

21. TTS stands for  
   (a) only a variable  
   (b) Text-to-Speech  
   (c) only a label  
   (d) only a button  

22. Checking “is the year between 1900 and current year?” is  
   (a) only drawing  
   (b) validation (range check)  
   (c) only clearing  
   (d) only speaking  

23. A custom error message can be  
   (a) only in the variable  
   (b) text set in a label (e.g. red colour “Invalid input”)  
   (c) only in an alert  
   (d) only a number  

24. Preparing for the next user means  
   (a) only closing the app  
   (b) clearing inputs and maybe resetting labels so the app is ready for new data  
   (c) only adding more buttons  
   (d) only changing colour  

25. Handling empty input (user left the box blank) is handling an  
   (a) only a normal case  
   (b) edge case (we should show error or ask user to enter value)  
   (c) only a variable  
   (d) only a colour  

---

**Answers:** 1-b, 2-b, 3-b, 4-b, 5-b, 6-b, 7-b, 8-b, 9-b, 10-b, 11-b, 12-b, 13-b, 14-b, 15-b, 16-b, 17-b, 18-b, 19-b, 20-b, 21-b, 22-b, 23-b, 24-b, 25-b.
