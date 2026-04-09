# VRealM 
  
> A modern Virtual Reality landing page built with **React** and **Tailwind CSS**, deployed on Vercel.

🔗 **Live Demo:** [vrealm.vercel.app](https://vrealm.vercel.app)

---

## 🚀 Features
  
- **Responsive Design** — Fully optimized for mobile, tablet, and desktop screens
- **Modern UI** — Clean, immersive design aesthetic tailored for the VR/XR space
- **Smooth Animations** — Scroll-triggered transitions and hover effects
- **Component-Based Architecture** — Modular React components for easy customization
- **Utility-First Styling** — Styled entirely with Tailwind CSS
- **Fast Performance** — Optimized build deployed on Vercel's edge network

---  

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React](https://react.dev/) | UI library |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [Vite](https://vitejs.dev/) | Build tool & dev server |
| [Vercel](https://vercel.com/) | Hosting & deployment |

---

## 📁 Project Structure

```
vrealm/
├── public/ 
│   └── assets/          # Static assets (images, icons)
├── src/
│   ├── components/      # Reusable React components
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── Features.jsx
│   │   ├── Pricing.jsx
│   │   ├── Testimonials.jsx
│   │   └── Footer.jsx
│   ├── App.jsx          # Root component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles / Tailwind directives
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json
```

---

## ⚡ Getting Started

### Prerequisites

- **Node.js** v18 or higher
- **npm** or **yarn**

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/vrealm.git

# 2. Navigate into the project directory
cd vrealm

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

The app will be running at `http://localhost:5173`.

---

## 📦 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

---

## 🚢 Deployment

This project is deployed on **Vercel**. Any push to the `main` branch triggers an automatic deployment.

To deploy your own fork:

1. Fork this repository
2. Go to [vercel.com](https://vercel.com) and import the repo
3. Vercel will auto-detect the Vite + React setup
4. Click **Deploy** — done!

Alternatively, deploy with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/vrealm)

---

## 🎨 Customization

### Colors & Theme

Edit `tailwind.config.js` to update the color palette, fonts, or extend the default theme:

```js
// tailwind.config.js
export default {
  theme: {
    extend: {
      colors: {
        primary: '#6C63FF',
        accent: '#00D4FF',
      },
      fontFamily: {
        sans: ['Inter', 'sans-serif'],
      },
    },
  },
}
```

### Content

Update the text, images, and copy directly inside the component files under `src/components/`.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your branch: `git checkout -b feature/awesome-feature`
3. Commit your changes: `git commit -m 'Add awesome feature'`
4. Push to the branch: `git push origin feature/awesome-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)
- [Vercel](https://vercel.com/)
- Icons by [Lucide](https://lucide.dev/) / [React Icons](https://react-icons.github.io/react-icons/)

---

<p align="center">Made with ❤️ and a VR headset</p>
