# ⏱️ Modern Stopwatch

**Track every second with accuracy and style.**

Welcome to the Modern Stopwatch – a simple, responsive, and beginner-friendly web application built using HTML, CSS, and JavaScript. It allows users to start, stop, reset, and record multiple lap times.

---

## 📱 What You Can Do

- ▶️ **Start the Stopwatch** – Begin tracking the elapsed time.
- ⏸️ **Stop the Stopwatch** – Pause the timer without losing the recorded time.
- 🔄 **Reset the Timer** – Clear the stopwatch and return it to zero.
- 🏁 **Record Lap Times** – Save multiple lap timings while using the stopwatch.
- ⏱️ **View Detailed Time** – Displays hours, minutes, seconds, and milliseconds.
- 📜 **Scrollable Lap History** – View all recorded lap times in one place.

---

## 🏠 Stopwatch Interface

When you open the application, you will see:

- A stopwatch heading
- A digital time display
- Hours, minutes, seconds, and milliseconds labels
- Start/Stop button
- Reset button
- Lap button
- Lap history section

The interface uses a modern glassmorphism design with smooth gradients, shadows, and button animations.

---

## ▶️ Start and Stop

The Start and Stop functions are controlled using the same button.

1. Click **Start** to begin the stopwatch.
2. The button automatically changes to **Stop**.
3. Click **Stop** to pause the stopwatch.
4. Click **Start** again to continue from the paused time.

The stopwatch does not restart from zero when paused.

---

## 🏁 Lap Time

The Lap button allows you to record the current stopwatch time.

1. Start the stopwatch.
2. Click the **Lap** button.
3. The current time will be added to the lap history.
4. New lap times will appear at the top of the list.

> 💡 The Lap button will not record a time when the stopwatch is at zero.

---

## 🔄 Reset Stopwatch

Click the **Reset** button to:

- Stop the running timer
- Reset the displayed time to `00:00:00:00`
- Remove all recorded lap times
- Change the Stop button back to Start

---

## ⏱️ Time Format

The stopwatch displays time in the following format:

```text
Hours : Minutes : Seconds : Milliseconds
```

Example:

```text
00:05:24:38
```

This represents:

- 00 Hours
- 05 Minutes
- 24 Seconds
- 38 Hundredths of a second

---

## 🎨 Responsive Design

The stopwatch works properly on:

- Desktop computers
- Laptops
- Tablets
- Mobile phones

The layout, text size, and buttons automatically adjust based on the screen size.

---

## 🛠️ Technologies Used

- **HTML5** – Creates the structure of the stopwatch.
- **CSS3** – Provides styling, responsiveness, gradients, and animations.
- **JavaScript** – Handles the timer, buttons, time calculation, and lap records.

---

## 📂 Project Structure

```text
Modern-Stopwatch/
│
├── index.html
└── README.md
```

The HTML, CSS, and JavaScript code are included in a single `index.html` file.

---

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Locate the `index.html` file.
4. Open `index.html` in any web browser.
5. Click the **Start** button to begin using the stopwatch.

No installation or additional software is required.

---

## 💻 How It Works

The stopwatch uses JavaScript's `Date.now()` method to calculate the elapsed time.

- `setInterval()` updates the displayed time every 10 milliseconds.
- `Date.now()` calculates the time passed since the stopwatch started.
- DOM manipulation updates the stopwatch display and lap history.
- Event listeners control the Start, Stop, Reset, and Lap buttons.

---

## 📚 Learning Outcomes

This project helped me practise:

- HTML page structure
- CSS styling and responsive design
- JavaScript functions
- DOM manipulation
- Event handling
- Time calculations
- Dynamic element creation
- Button state management
- Front-end web development

---

## ❓ Frequently Asked Questions

**Q: Can I pause and continue the stopwatch?**  
A: Yes. Click **Stop** to pause it and click **Start** again to continue from the same time.

**Q: Why is the Start button changing to Stop?**  
A: The same button is used for both starting and stopping the stopwatch.

**Q: Can I record multiple lap times?**  
A: Yes. You can click the Lap button multiple times to record different lap timings.

**Q: What happens when I click Reset?**  
A: The timer returns to zero, the stopwatch stops, and all lap records are removed.

**Q: Does the stopwatch work on mobile phones?**  
A: Yes. The application is fully responsive and works on mobile phones, tablets, laptops, and desktop computers.

---

## 📝 Feedback

Suggestions and improvements are always welcome. Feel free to create an issue or contribute to this repository.

---

## 👨‍💻 Author

**Karthikeyan K U**

---

**Start tracking your time! ⏱️**
