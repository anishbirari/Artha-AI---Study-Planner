<div align="center">

# Artha AI - Study Planner

**A gold-and-black study planner for students. Plan your week, track deadlines, focus with a Pomodoro timer and watch your consistency grow.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-D4AF37?style=flat)
![No dependencies](https://img.shields.io/badge/dependencies-none-D4AF37?style=flat)

[**Live demo**](https://your-username.github.io/artha-ai-study-planner/) · [Report a bug](../../issues) · [Request a feature](../../issues)

</div>

---

## Table of contents

- [About](#about)
- [Features](#features)
- [Getting started](#getting-started)
- [How to use it](#how-to-use-it)
- [How streaks work](#how-streaks-work)
- [Your data](#your-data)
- [Tech stack](#tech-stack)
- [Project structure](#project-structure)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## About

Artha AI - Study Planner is a personal planner I built as a first-year B.Tech AI/ML student to organise my own study routine. It is a single HTML file with no frameworks, no build step and no sign-up. Open it in a browser and start planning.

## Features

| | Feature | What it does |
|---|---|---|
| 📅 | **Weekly timetable** | Plan study blocks for every day by subject and topic, with planned hours per day. |
| ✅ | **Task and deadline tracker** | Assignments, exams and revision with due dates, priority levels and overdue flags. |
| ⏱ | **Pomodoro timer** | Focus, short break and long break sessions. Finished focus sessions are logged automatically. You can also log time by hand. |
| 🔥 | **Streaks and goals** | Set a daily study goal and keep your current and best streak going. |
| 📈 | **Three progress charts** | A glowing 10-day momentum chart, a 7-day bar chart and a 30-day trend line, all in gold and black. |
| 🎨 | **Custom subjects** | Add any subject you like and give it its own colour. |
| ⚙️ | **Settings** | Change your daily goal and the timer lengths. |

## Getting started

No installation is needed.

```bash
# 1. Clone the repository
git clone https://github.com/your-username/artha-ai-study-planner.git

# 2. Go into the folder
cd artha-ai-study-planner

# 3. Open index.html in your browser
```

You can also just download `index.html` and double-click it.

### Host it free with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
4. After a minute or two your site is live at `https://your-username.github.io/artha-ai-study-planner/`.

## How to use it

1. **Today:** see your schedule and the next tasks due. Pick a subject, press **Start** and study. Each finished focus session is added to your progress.
2. **Week:** open **Add a study block**, choose the day, time and subject, and build your timetable.
3. **Tasks:** add assignments, exams and revision with a due date and priority. Tick them off when done.
4. **Progress:** check your streak, your charts and your time per subject. Add new subjects and change your goal and timer lengths here.

The app opens with sample data so you can see how everything looks. Press **Clear sample data** at the top to start with an empty planner.

## How streaks work

A day counts toward your streak when you study for at least **20 minutes** (focus sessions and manually logged time both count). If you have not studied yet today, your streak stays alive until the day ends.

## Your data

Everything is saved in your browser's local storage. Nothing is sent to a server, so your data stays on the device and browser you use. Clearing your browser's site data will also clear your planner.

## Tech stack

- HTML, CSS and vanilla JavaScript, with no frameworks or build tools
- Charts drawn by hand as inline SVG
- Fonts from Google Fonts: Bricolage Grotesque, DM Sans and JetBrains Mono

## Project structure

```text
artha-ai-study-planner/
├── index.html        # the whole app (markup, styles and logic)
├── LICENSE
└── README.md
```

## Roadmap

- [x] Weekly timetable
- [x] Task and deadline tracker
- [x] Pomodoro timer with automatic logging
- [x] Streaks, goals and progress charts
- [x] Custom subjects
- [ ] Exam countdowns
- [ ] Notes for each subject
- [ ] Monthly study heatmap
- [ ] Export and import your data as a file

## Contributing

Ideas and improvements are welcome.

1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-idea`
3. Commit your changes: `git commit -m "Add your idea"`
4. Push the branch: `git push origin feature/your-idea`
5. Open a pull request.

## License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.

## Author

**Anish Birari**
B.Tech AI/ML student

- GitHub: [@your-username](https://github.com/anishbirari)
- LinkedIn: [your-linkedin-profile](https://www.linkedin.com/in/Anish-Birari)

---

<div align="center">

If this project helps you, please give it a ⭐

</div>
