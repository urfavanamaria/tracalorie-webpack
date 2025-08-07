# Tracalorie 2.0 — Webpack Edition 🍽️

A modern calorie tracking app rebuilt with **modular JavaScript**, **Webpack**, and **Babel**. This version refactors the original vanilla JS project into a scalable, production-ready app with improved performance and maintainability.

🔗 [Live Demo](https://tracalorie2-webpack.netlify.app)


---

## 🚀 Features

- Add meals and workouts with calorie values
- Visual progress bar and calorie alerts
- Filter, reset, and clear all entries
- Persistent data using `localStorage`
- Responsive UI with SCSS styling
- Modular architecture using ES6 modules
- Webpack bundling and Babel transpilation
- Clean separation of concerns (MVC pattern)

---

## 🛠️ Tech Stack

- JavaScript (ES6+)
- HTML5 & SCSS
- Webpack (v5)
- Babel
- LocalStorage API
- Bootstrap (optional)
- Netlify (for deployment)

---

## 📚 Based On

This project is based on Brad Traversy's [Modern JavaScript From The Beginning](https://www.udemy.com/course/modern-javascript-from-the-beginning/learn/lecture/37196408#overview) course and adapted from his original Tracalorie tutorial.

---

## 📦 Installation

```bash
git clone https://github.com/urfavanamaria/tracalorie-webpack.git
cd tracalorie-webpack
npm install
npm run build
```
Then open dist/index.html in your browser or deploy to a static host like Netlify.

## 📁 Project Structure

``` bash
tracalorie-webpack/
├── src/
│   ├── js/
│   │   ├── models/
│   │   ├── views/
│   │   ├── controllers/
│   │   └── index.js
│   └── style.scss
├── dist/
├── package.json
├── webpack.config.js
└── .gitignore
```
## 📄 License

This project is licensed under the [MIT License](LICENSE).
