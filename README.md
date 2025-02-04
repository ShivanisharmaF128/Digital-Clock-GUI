# Digital-Clock-GUI-Using- Python

A simple **Digital Clock** built using **Python and Tkinter**. This GUI-based clock displays the current time in a stylish format.

<img src="https://github.com/ShivanisharmaF128/Digital-Clock-GUI/blob/main/digital.clock.jfif" alt="Digital Clock Preview" width="600">

---

## 📌 Objective
The main objective of this project is to create a **real-time updating digital clock** using Python’s Tkinter module. It is a great beginner-friendly project to understand **GUI development** and **time handling** in Python.

---

## 📝 Overview
- The clock updates **every 200 milliseconds** to show accurate real-time information.
- **Tkinter** is used for GUI development.
- Uses the **time.strftime()** function to format time properly.
- Background color, text color, and font style are customized for a modern look.

---

## 📜 Code Explanation
1. **Tkinter Window Initialization** → Creates a main application window.
2. **Time Formatting** → Uses `time.strftime("%I:%M:%S %p")` to get current time.
3. **Label Configuration** → Displays time in a large **Century Schoolbook** font.
4. **Auto Update Function** → Calls `present_time()` every **200ms** to refresh the time.

---

## ⚙️ Prerequisites
Make sure you have **Python installed** on your system.

**To check Python installation:**
```sh
python --version



