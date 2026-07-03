<div align="center">

# 📚 EduVerse — Interactive Learning Dashboard

### *A feature-rich, single-page e-learning platform built with vanilla HTML, CSS & JavaScript*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.4-528DD7.svg?style=flat-square&logo=fontawesome&logoColor=white)](https://fontawesome.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

> **EduVerse** is a comprehensive, interactive learning dashboard designed to give students a modern, feature-rich platform for managing their online education — all in a single self-contained HTML file with zero dependencies beyond a CDN icon pack.

### 🌐 [**Live Demo → anasq2003.github.io/Course-Dashboard**](https://anasq2003.github.io/Course-Dashboard/)

[🔗 View Repository](https://github.com/AnasQ2003/Course-Dashboard) · [🐛 Report Bug](https://github.com/AnasQ2003/Course-Dashboard/issues) · [✨ Request Feature](https://github.com/AnasQ2003/Course-Dashboard/issues)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌗 **Dark / Light Mode** | Toggle between a sleek dark theme and a clean light mode instantly |
| 📊 **Learning Dashboard** | Overview stats: Active Courses, Overall Progress %, Time Spent, Achievements |
| 📚 **My Courses** | Enrolled course cards with progress bars, ratings, lesson counts, and Continue/Start buttons |
| 📖 **Course Catalog** | Full course grid with status badges (New / Popular / Featured) across all 6 subjects |
| 📋 **Course Detail Modal** | Per-course lesson list with completion checkmarks and a "Continue Learning" CTA |
| 📈 **Progress Analytics** | Completion rate, streak counter, Course Distribution donut chart, Monthly Progress bar chart |
| 🏆 **Achievements** | Unlocked badges — Fast Learner, Perfect Score, 7-Day Streak |
| 📝 **Assignments** | Pending (overdue, upcoming) and Completed assignment tracker with scores |
| 📅 **Learning Calendar** | Month view calendar with Today's Schedule (live sessions, study groups, self-paced time) |
| ⚙️ **Settings** | Account profile edit, avatar upload, notification toggles, password change, Two-Factor Auth |
| 🔔 **Notifications** | Real-time bell badge with in-app alerts (Assignment Due, New Course, Achievement Unlocked) |
| 🔐 **Auth Modals** | Login / Sign Up modal with session persistence + Logout confirmation dialog |

---

## 🖥️ Tech Stack

EduVerse is a **zero-build, zero-backend** single-file application:

| Technology | Role |
|---|---|
| **HTML5** | Semantic page structure, modal dialogs, sidebar navigation |
| **CSS3** | CSS Custom Properties (design tokens), Flexbox / Grid layouts, smooth transitions |
| **Vanilla JavaScript** | SPA routing logic, DOM manipulation, chart rendering, localStorage persistence |
| **Font Awesome 6.4** | Icon library loaded from CDN |
| **Canvas API** | Donut chart (Course Distribution) and bar chart (Weekly Activity / Monthly Progress) |

No frameworks. No bundlers. No npm. Just open `index.html` and go.

---

## 🚀 Getting Started

```bash
git clone https://github.com/AnasQ2003/Course-Dashboard.git
cd Course-Dashboard
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or with a live server:
```bash
python -m http.server 5500
# http://127.0.0.1:5500/index.html
```

---

## 📂 Project Structure

```
Course-Dashboard/
├── index.html                        # 🏠 Entire application — HTML + CSS + JS in one file
├── Screenshot_2025-07-20_234002.png  # Dashboard — dark mode overview
├── Screenshot_2025-07-20_234015.png  # Dashboard — charts & notifications (dark)
├── Screenshot_2025-07-20_234029.png  # Dashboard — light mode
├── Screenshot_2025-07-20_234050.png  # Course detail modal — lesson list (light)
├── Screenshot_2025-07-20_234059.png  # Courses page — all course cards (light)
├── Screenshot_2025-07-20_234113.png  # Course detail modal — lesson progress (dark)
├── Screenshot_2025-07-20_234125.png  # Progress analytics page (light)
├── Screenshot_2025-07-20_234137.png  # Assignments page (light)
├── Screenshot_2025-07-20_234157.png  # Calendar page (light)
├── Screenshot_2025-07-20_234216.png  # Settings — account profile (light)
├── Screenshot_2025-07-20_234229.png  # Settings — notifications & security (dark)
├── Screenshot_2025-07-20_234242.png  # Settings — account profile (dark)
├── Screenshot_2025-07-20_234257.png  # Logout confirmation modal (dark)
├── Screenshot_2025-07-20_234312.png  # Login / Sign Up modal (dark)
└── README.md
```

---

## 🎨 Design System

```css
:root {
  --primary:       #6c5ce7;   /* Purple — brand accent */
  --primary-light: #a29bfe;   /* Soft purple — hover states */
  --secondary:     #00cec9;   /* Teal — secondary actions */
  --dark:          #2d3436;   /* Near-black — dark mode base */
  --light:         #f5f6fa;   /* Off-white — light mode base */
  --success:       #00b894;   /* Green — completed states */
  --warning:       #fdcb6e;   /* Amber — pending/overdue */
  --danger:        #d63031;   /* Red — destructive actions */
}
```

---

## 📸 Screenshots

### Dashboard

**Dark Mode — Stats, Courses & Charts**
![Dashboard dark](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234002.png)

---

**Dark Mode — Scrolled (Progress chart, Weekly Activity, Notifications)**
![Dashboard dark scrolled](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234015.png)

---

**Light Mode — Stats, Courses & Charts**
![Dashboard light](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234029.png)

---

### Courses & Course Detail

**All Courses Grid**
![Courses page](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234059.png)

---

**Course Detail Modal (Light)**
![Course detail modal light](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234050.png)

---

**Course Detail Modal (Dark)**
![Course detail modal dark](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234113.png)

---

### Progress & Analytics

**Learning Analytics**
![Progress page](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234125.png)

---

### Assignments & Calendar

**Assignments**
![Assignments page](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234137.png)

---

**Learning Calendar**
![Calendar page](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234157.png)

---

### Settings

**Account Settings (Light)**
![Settings light](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234216.png)

---

**Account Settings (Dark)**
![Settings dark](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234242.png)

---

**Notifications & Security**
![Settings notifications](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234229.png)

---

### Auth Flows

**Login Modal**
![Login modal](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234312.png)

---

**Logout Confirmation**
![Logout confirm dialog](https://raw.githubusercontent.com/AnasQ2003/Course-Dashboard/main/Screenshot_2025-07-20_234257.png)

---

## 🧭 Navigation

```javascript
function showSection(sectionId) {
  document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
  document.getElementById(sectionId).classList.add('active');
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
}
```

---

## 📊 Charts

```javascript
function drawDonutChart(canvas, data, colors) {
  const ctx = canvas.getContext('2d');
  // arc segments + center label
}

function drawBarChart(canvas, data, colors) {
  const ctx = canvas.getContext('2d');
  // fillRect() bars with spacing
}
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'feat: add AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

---

<div align="center">

Made with ❤️ by [AnasQ2003](https://github.com/AnasQ2003)

⭐ If you find this project useful, please give it a star!

</div>
