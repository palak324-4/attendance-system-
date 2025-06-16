# 🎓 Attendo - Student Attendance Dashboard

Welcome to **Attendo**, a simple and dynamic **Student Attendance Management System** built using **HTML, CSS, and JavaScript**. This project includes:

* A modern **login page** where students enter their name and 12-digit registration number
* A personalized **dashboard page** that displays individual attendance details using `sessionStorage`
* Clean UI and interactive charts powered by **Chart.js**

## 📊 Features

* Student-specific login validation (no backend required)
* Real-time chart visualizations for Present vs Absent data
* Fine calculation displayed dynamically
* Uses only **frontend stack** (HTML, CSS, JS + sessionStorage)
* Responsive and mobile-friendly design

## 📂 Project Structure

```
attendance-management-system/
├── login.html           # Login page
├── dashboard.html       # Dashboard after successful login
├── README.md            # Project documentation
├── /img                 # Images if needed (optional)
└── /css /js             # (optional folders if separating code)
```

## 🪓 How to Use

1. Open `login.html` in Live Server or deploy it (see below).
2. Enter a **valid student name and 12-digit registration number** from the hardcoded list.
3. You'll be redirected to `dashboard.html` which displays that student's data.

## 🔎 Sample Students

```js
const studentsData = [
  { name: "Sharandeep Singh", reg: "231949508553", ... },
  { name: "Khushpreet Kaur", reg: "231949508532", ... },
  ... // 20 students
];
```

## 🌐 GitHub Pages Deployment

To deploy your project online via **GitHub Pages**:

### 1. Push to GitHub

Make sure your project is pushed to a **GitHub repository**.

### 2. Rename Entry Point

* Rename your entry file `login.html` to `index.html`
* Make sure `dashboard.html` is in the same root folder

### 3. Enable GitHub Pages

* Go to your repo settings
* Scroll to **"Pages"** section
* Select `main` branch and `/root` as source
* Click **Save**

Your site will be hosted at:

```
https://your-username.github.io/your-repo-name/
```

### 4. Test URL

Once deployed, visit:

```
https://your-username.github.io/your-repo-name/index.html
```

Make sure redirection to `dashboard.html` works.

## ⚙️ Technologies Used

* **HTML5** - Markup for pages
* **CSS3** - Styling and layout
* **JavaScript (ES6)** - Logic and sessionStorage
* **Chart.js** - Graphs and data visualization

## ✉️ Contact

For questions or contributions, contact \[Your Name] at \[[your.email@example.com](mailto:your.email@example.com)] or raise an issue.

---

Built with ❤️ by Students, for Students.
