# Competition Apnea Timer

A free, lightweight online stopwatch built for **static apnea (STA)** competition timing. Track breath hold time, surface protocol, and card time — all from a single button.

🌐 **Try it live:** [https://apneatimer.app](https://apneatimer.app)

---

## Features

- **Breath Hold Timer** — High-precision stopwatch (MM:SS:ms) for timing the athlete's static apnea performance.
- **Surface Protocol Timer** — Automatically starts when the hold is stopped, tracking the surface protocol phase.
- **Card Timer** — Runs alongside the SP timer and can be stopped independently to record card presentation time.
- **Session Log** — Every completed session is saved to `localStorage` and displayed in a persistent log with hold and SP times.
- **Single-Button Flow** — One large button cycles through all phases: START → STOP (hold) → STOP SP → STOP TIMER → RESET.
- **Mobile-Friendly** — Fully responsive design that works on phones, tablets, and desktops.
- **Zero Dependencies** — Pure HTML, CSS, and vanilla JavaScript in a single file. No frameworks, no build step.

## How It Works

| Step | Button Label | What Happens |
|------|-------------|--------------|
| 1 | **START** | Breath hold timer begins |
| 2 | **STOP** | Hold timer stops; SP and Card timers start simultaneously |
| 3 | **STOP SP** | Surface protocol timer stops; Card timer keeps running |
| 4 | **STOP TIMER** | Card timer stops; session is logged |
| 5 | **RESET** | All timers reset to `00:00:00` |

## Getting Started

No build tools or dependencies required. Simply open the file in a browser:

```bash
# Clone the repository
git clone https://github.com/alexhedstrom/competition-apnea-timer.git

# Open in your browser
open index.html
```

Or visit **[apneatimer.app](https://apneatimer.app)** to use it instantly.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage for session persistence

## License

© 2026 [Alex Hedström](https://alexhedstrom.com). All rights reserved.
