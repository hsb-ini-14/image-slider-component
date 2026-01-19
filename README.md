# Image Slider Component

An animated and responsive **Image Slider Component** built with **React, Vite, and Tailwind CSS**.
This project demonstrates smooth transitions, random rotation effects, and dynamic content switching.

🔗 **Live Demo:** [https://hsb-ini-14.github.io/image-slider-component/](https://hsb-ini-14.github.io/image-slider-component/)

---

## ✨ Features

* 🎞️ Smooth animated image transitions
* 🔄 Next / Previous navigation controls
* 🎲 Random rotation effect for inactive slides
* 📱 Fully responsive layout
* 🎨 Styled with Tailwind CSS
* ⚡ Built using Vite for fast development

---

## 🛠️ Tech Stack

* **React** – UI components & state management
* **Vite** – Fast build tool & dev server
* **Tailwind CSS** – Utility-first styling
* **Lucide React** – Icon set
* **GitHub Pages** – Deployment

---

## 📁 Project Structure

```text
image-slider-component/
├── public/
│   └── images/
│       ├── image-1.jpg
│       ├── image-2.jpg
│       ├── image-3.jpg
│       ├── image-4.jpg
│       └── image-5.jpg
├── src/
│   ├── components/
│   │   ├── BG.jsx
│   │   └── Slider.jsx
│   ├── data.js
│   ├── App.jsx
│   └── main.jsx
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/hsb-ini-14/image-slider-component.git
cd image-slider-component
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start the development server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 🌍 Deployment to GitHub Pages

This project is deployed using **gh-pages**.

### Steps used:

1. Install gh-pages

```bash
npm install --save-dev gh-pages
```

2. Set base path in `vite.config.js`

```js
export default defineConfig({
  base: "/image-slider-component/",
});
```

3. Add scripts to `package.json`

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

4. Deploy

```bash
npm run deploy
```

---

## 🧩 How It Works

* Images and descriptions are stored in a central `data.js` file
* The slider uses React `useState` to track the active index
* Tailwind utility classes handle animations and layout
* Inactive images get random rotation for a stacked-card effect

---

## 📸 Preview

> Screenshots to be added 

---

## 🙌 Acknowledgements

* Icons by [Lucide React](https://lucide.dev/)
* Styling powered by [Tailwind CSS](https://tailwindcss.com/)
* Build tool by [Vite](https://vitejs.dev/)

---

## 👤 Author

**Harsh Singh Bhaduria**

* GitHub: [https://github.com/hsb-ini-14](https://github.com/hsb-ini-14)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub — it really helps! 😊
