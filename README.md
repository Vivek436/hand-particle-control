# ThreeJS Hand Particles 🎇

An interactive **hand-controlled 3D particle system** built with **Three.js** and **MediaPipe Hands**. Move your hand in front of the camera to control particle position, rotation, size, and smoothly switch between beautiful particle templates like **Galaxy, Heart, Saturn, Wave, and Spiral**.

> ✨ Designed for portfolios, creative coding demos, and interactive web experiments.

---

## 🚀 Live Demo

After deployment on Netlify, your live demo will be available at a URL like:

```
https://your-site-name.netlify.app
```

---

## 🧠 Features

* 🖐 **Real-time hand tracking** using MediaPipe
* 🌌 **20,000+ particles** rendered with Three.js
* 🎨 Multiple particle templates:

  * Galaxy 🌀
  * Heart ❤️
  * Saturn 🪐
  * Wave 🌊
  * Spiral 🌪️
* 🎚 Smooth motion & velocity-based interpolation
* 🤏 Pinch gesture to control particle size
* 🎥 Live webcam preview
* ⌨️ Keyboard + 🖱 mouse fallback controls
* ⚡ Optimized & fully client-side (no backend)

---

## 🛠 Tech Stack

* **HTML5 / CSS3 / JavaScript**
* **Three.js** – 3D rendering
* **MediaPipe Hands** – hand tracking
* **WebGL** – GPU accelerated graphics
* **Netlify** – deployment

---

## 📁 Project Structure

```
threejs-hand-particles/
│── index.html
│── README.md
```

> This is a **pure static project**, no build tools required.

---

## ▶️ How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/your-username/threejs-hand-particles.git
```

2. Open the project folder

```bash
cd threejs-hand-particles
```

3. Open `index.html` in your browser

4. Allow **camera permission** when prompted

✅ That’s it!

---

## 🌐 Deploy on Netlify (Drag & Drop)

1. Go to **[https://www.netlify.com/](https://www.netlify.com/)**
2. Login / Sign up
3. Click **Add new site → Deploy manually**
4. Drag & drop the project folder

🎉 Your site will be live instantly!

---

## ⌨️ Controls

### Hand Gestures

* ✋ Move hand → Move particles
* 🤏 Pinch (thumb + index) → Change particle size
* ↔ Hand position → Switch templates automatically

### Keyboard

* ⬅️ / ➡️ Arrow keys → Change templates
* Space → Reset position

### Mouse (Testing mode)

* Hold mouse button + move → Control particles

---

## ⚙️ Performance Tips

If performance drops on low-end devices, reduce particle count:

```js
const COUNT = 12000;
```

---

## 📸 Permissions

This project requires **camera access** for hand tracking.

Runs perfectly on **HTTPS (Netlify default)**.

---

## 💼 Use Case

* Portfolio project
* Creative coding showcase
* Interactive art installation
* WebGL / Three.js learning project

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Author

**Vivek Sharma**
Creative Frontend Developer | Three.js Enthusiast

---

⭐ If you like this project, don’t forget to **star the repository**!
