# 🕰️ Real-Time Analog Clock

A simple and elegant **Analog Clock** built using **HTML**, **CSS**, and **Vanilla JavaScript**. The clock displays the current system time with smoothly rotating hour, minute, and second hands — updated in real time.

--- 

## 🔧 Technologies Used

- ✅ HTML5
- ✅ CSS3 (flexbox, transformations)
- ✅ JavaScript (Date object, real-time update via `setInterval()`)
  
## 💡 Features

- ⏱️ Real-time analog clock synced with system time
- 🎨 Smooth hand rotation using CSS transform and JavaScript calculations
- 📱 Fully responsive and centered design
- 💻 No external libraries or frameworks used

---
## 🧠 How It Works

- `JavaScript` fetches the current time using `new Date()`
- Calculates the degree of rotation for each hand:
  - Hour hand: `((hours % 12) + minutes / 60) * 30`
  - Minute hand: `(minutes + seconds / 60) * 6`
  - Second hand: `seconds * 6`
- Updates the CSS transform rotation using `setInterval()` every second

---

## 🗂️ Project Structure

analog-clock/
├── index.html
├── style.css
├── script.js
