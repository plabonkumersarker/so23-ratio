# Senior Officer Exam — Viva Checker (Job ID: 10220)

A clean, dark-themed static web app to check written exam roll numbers against viva candidate lists for the **Senior Officer Exam (Job ID: 10220)**. Built with vanilla HTML, CSS, and JavaScript — no dependencies, no build step.

🌐 **Live Site:** [plabonkumersarker.github.io/so23-ratio](https://plabonkumersarker.github.io/so23-ratio)

---

## Features

- 🔍 **Roll Number Search** — Instantly search any written exam roll number to check viva qualification status
- 🟢 **Visual Roll Grid** — All written exam rolls displayed as color-coded cards (green = qualified, grey = not qualified)
- 📋 **Result Modal** — Clicking any roll card opens a detailed popup showing viva date, written-to-viva ratio, and competition stats
- 📊 **Ratio Distribution Graph** — Bar chart showing how many viva candidates fall in each competition ratio range, summing to the exact total viva candidate count
- 🏷️ **Summary Cards** — Each ratio range shows candidate count, group count, and percentage of total
- ⬆️ **Scroll-to-Top Button** — Quick navigation button that appears when scrolling down
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop

---

## What is the Ratio?

For each scheduled viva group, the ratio is calculated as:

```
ratio = written candidates in roll range ÷ viva candidates in that group
```

A lower ratio means less competition for that group. The graph visualizes how this ratio is distributed across all viva candidates — if you add up all the candidate counts from each bar, you get the total number of viva candidates.

> *"Don't be so serious! It's just a controversial hypothesis."*

---

## Tech Stack

- Pure **HTML5 / CSS3 / Vanilla JavaScript**
- Zero external libraries or frameworks
- Hosted via **GitHub Pages**

---

## Project Structure

```
so23-ratio/
└── index.html      # The entire app — self-contained single file
```

---

## Usage

No installation needed. Just open `index.html` in any modern browser, or visit the live site.

To deploy your own copy:
1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Your site will be live at `https://<your-username>.github.io/<repo-name>`

---

## Author

**Plabon Kumar Sarker**
[github.com/plabonkumersarker](https://plabonkumersarker.github.io/profile)

---

## Disclaimer

This tool is built for informational purposes only, based on publicly available exam result data. The ratio analysis is an unofficial hypothesis and has no bearing on the official exam process.
