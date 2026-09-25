# 📝 Sticky Notes App

A minimal, dark-themed notes-taking app built with **React** and **Tailwind CSS**. Add notes with a title and details, and delete them instantly — styled as sticky notes on a clean, responsive split-screen layout.

## 🚀 Live Demo
add-notes-app-git-main-khushi-612a.vercel.app

## ✨ Features

- **Add Notes** — Capture a note with a title and detailed description
- **Delete Notes** — Remove any note instantly with one click
- **Sticky Note UI** — Notes are styled with a sticky-note background for a fun, tactile look
- **Responsive Layout** — Split-screen form and notes view on desktop, stacked on mobile
- **Scrollable Notes Panel** — Notes list scrolls independently, keeping the layout clean

## 🛠️ Tech Stack

- **React** — Component-based UI with hooks (`useState`)
- **Tailwind CSS** — Utility-first styling
- **Vite** — Fast build tool and dev server

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Singhkhushi-17/your-repo-name.git

# Navigate to project directory
cd your-repo-name

# Install dependencies
npm install

# Start the development server
npm run dev
```

## 📁 Project Structure

```
src/
├── App.jsx        # Main app logic — form, notes state, add/delete handlers
├── main.jsx        # App entry point
└── index.css        # Tailwind CSS imports
```

## 🎯 How It Works

1. User fills in the note title and details in the form
2. On submit, a new note object is pushed to the `task` state array
3. Notes are rendered as sticky-note cards in the right panel
4. Each note has a **Delete** button that removes it from the state using its index

## 🔮 Future Improvements

- [ ] Persist notes using `localStorage` so they survive page refresh
- [ ] Add edit functionality for existing notes
- [ ] Add timestamps to each note
- [ ] Add search/filter functionality
- [ ] Form validation (prevent empty notes)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ by [Khushi Singh](https://github.com/Singhkhushi-17)
