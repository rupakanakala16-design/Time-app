# ⏰ Dynamic Time — Modern Digital Clock

A beautiful and responsive **Dynamic Time Web App** that displays the current time, date, and contextual greeting with an automatically changing **day/night theme**.

The project combines a clean glassmorphism-inspired interface with real-time JavaScript functionality to create a simple but visually polished digital clock experience.

---

## ✨ Features

### 🕐 Real-Time Digital Clock
- Displays the current time in `HH:MM:SS` format.
- Updates automatically every second.
- Uses the user's local system time.
- Smooth animated separators between hours, minutes, and seconds.

### 📅 Live Date Display
Displays the current:
- Day of the week
- Month
- Date
- Year

Example:

> Monday, September 25, 2026

The date is generated dynamically using JavaScript.

### 👋 Smart Greeting

The application automatically changes the greeting according to the current time:

| Time | Greeting |
|------|----------|
| 🌅 Morning | Good Morning |
| ☀️ Afternoon | Good Afternoon |
| 🌙 Evening | Good Evening |
| 🌌 Night | Good Night |

### 🌞 Automatic Day/Night Mode

The interface automatically switches between light and dark themes.

**Day Mode**
- Light background
- Sun icon
- Purple/blue gradient typography
- Bright glass card

**Night Mode**
- Dark navy background
- Moon icon
- Green/cyan gradient typography
- Dark glass card

The transition happens automatically based on the current hour.

---

## 🎨 Modern UI Design

The application uses a modern glassmorphism-inspired design with:

- 🪟 Transparent glass card
- 🌫️ Backdrop blur
- ✨ Soft shadows
- 🔮 Gradient typography
- 🌈 Radial background effects
- 🎯 Rounded corners
- 🖱️ Hover elevation effect
- 💫 Smooth transitions
- 📱 Responsive layout

The clock card slightly lifts when the user hovers over it, creating a subtle interactive effect.

---

## 🌗 Theme Logic

The application determines whether it is daytime or nighttime using the current hour.

```javascript
const isNight = hours >= 18 || hours < 6;
