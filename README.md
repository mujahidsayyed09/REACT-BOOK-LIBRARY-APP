# 📚 React Book Library App

A dynamic and responsive Book Library System built with React, React Router, Redux, and Vite.  
It allows users to browse, search, filter, view, and add books with full state management using Redux.

## 🔗 Live Demo  
👉 [View on GitHub Pages](https://mujahidsayyed09.github.io/REACT-BOOK-LIBRARY-APP/)

---

## 🚀 Features

- 🔍 Search books by title or author
- 🗂 Filter books by category
- 📖 View detailed book information
- ➕ Add new books using a form
- ♻️ State management with Redux
- 🌐 Dynamic routing using React Router
- 🖼️ GitHub Pages deployment

---

## 🛠️ Tech Stack

- React
- Vite
- Redux Toolkit
- React Router
- CSS (Custom styling)
- GitHub Pages

---

## 🧑‍💻 Getting Started

### ✅ Prerequisites

- Node.js (v18 or higher recommended)
- npm

### 📦 Installation

1. **Clone the repo**  
```bash
git clone https://github.com/mujahidsayyed09/REACT-BOOK-LIBRARY-APP.git
cd REACT-BOOK-LIBRARY-APP
```

2. **Install dependencies**  
```bash
npm install
```

3. **Start development server**  
```bash
npm run dev
```

4. Visit in browser:  
[http://localhost:5173](http://localhost:5173)

---

## 🚢 Deployment (GitHub Pages)

To deploy the project to GitHub Pages:

### 1. Add the `homepage` field to `package.json`:

```json
"homepage": "https://mujahidsayyed09.github.io/REACT-BOOK-LIBRARY-APP"
```

### 2. Ensure this is in your `vite.config.js`:

```js
export default defineConfig({
  base: "/REACT-BOOK-LIBRARY-APP/",
  plugins: [react()],
})
```

### 3. Add these scripts in `package.json`:

```json
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

### 4. Install the deploy package:

```bash
npm install gh-pages --save-dev
```

### 5. Deploy:

```bash
npm run deploy
```

---

## 🧩 Folder Structure

```
vite-project/
│
├── public/
│   └── 404.html              # Redirect fallback for GitHub Pages
│
├── src/
│   ├── components/           # All component files
│   ├── redux/                # Redux slices and store
│   └── utils/                # mockData and helpers
│
├── dist/                     # Production build output (auto-generated)
├── vite.config.js            # Vite config with GitHub Pages base
├── package.json              # Project metadata and scripts
└── README.md
```

---

## 🧪 Testing

- Try searching for partial book titles or authors.
- Filter by any category.
- Add a new book using the form and verify it appears in the list.
- Try opening a route like `/book/2` directly or refreshing it on GitHub Pages.

---

## 📬 Contact

For any questions or suggestions, feel free to reach out:  
📧 mujahidsayed203@gmail.com  
🔗 [GitHub](https://github.com/mujahidsayyed09)
