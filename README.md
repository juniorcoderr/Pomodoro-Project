## 🕒 Pomodoro Timer – Productivity App using Python & Tkinter

This is a simple and effective **Pomodoro Timer** application built using Python's `tkinter` library for GUI (Graphical User Interface). It's designed to help you **boost your productivity** by using the Pomodoro Technique — a time management method that alternates focused work sessions with short and long breaks.

---

### 📌 What is the Pomodoro Technique?

The **Pomodoro Technique** involves:
- **25 minutes** of focused work
- **5 minutes** short break
- After **4 work sessions**, take a **20-minute long break**

This technique helps reduce mental fatigue and keeps you consistently productive.

---

### 🧠 Key Concepts Covered

This project is perfect for beginners to learn:

#### ✅ Tkinter GUI
- Creating windows with `Tk()`
- Using widgets like `Label`, `Button`, and `Canvas`
- Handling layouts with `grid()`
- Loading and displaying images with `PhotoImage`

#### ✅ Python Programming
- Using **functions**, **conditionals**, and **loops**
- Working with **global variables**
- Using **math functions** like `math.floor()` for time formatting
- Scheduling timed events using `window.after()` for countdown logic

#### ✅ Pomodoro Logic
- Keeps track of work and break sessions using a **rep counter**
- Automatically switches between **Work**, **Short Break**, and **Long Break**
- Shows a **checkmark** (✔) after each completed work session for motivation

---

### 🖼 UI Preview

The UI includes:
- A **Tomato image** (classic Pomodoro symbol)
- A **countdown timer**
- **Start** and **Reset** buttons
- A label to show how many Pomodoros you’ve completed (✔)

> 🔺 Note: Make sure to include `tomato.png` in the project folder for the image to load correctly. Otherwise, the app will still work, but the image won’t show.

---

### 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pomodoro-timer.git
   cd pomodoro-timer
   ```

2. Make sure Python is installed:
   ```bash
   python --version
   ```

3. Run the application:
   ```bash
   python main.py
   ```

---

### 📁 Project Structure

```
pomodoro-timer/
│
├── main.py         # Main application file
└── tomato.png      # (Optional) Image for the timer UI
```

---

### 💡 Ideas for Improvements

- Add **custom time settings** (user inputs duration)
- Add **sound alerts** at the end of sessions
- Track completed sessions over multiple days
- Create a **dark mode** or **theme switcher**

---

### 🙌 Acknowledgements

This project is inspired by the Pomodoro productivity technique and built to help beginners practice Python and Tkinter in a fun way.

---

### 📜 License

Feel free to fork, modify, and use it in your own projects.
