# pranav-ai-portfolio
# 🤖 AI Voice Controlled Portfolio

An interactive **AI-powered developer portfolio website** that allows recruiters to explore projects using voice commands.

This portfolio is not a normal website — it behaves like a product demo.

Users can:

* Speak commands
* Navigate sections
* View GitHub repositories automatically
* Listen to AI responses

---

## 🚀 Live Features

### 🎤 Voice Assistant

The built-in assistant listens and responds using speech synthesis.

Supported commands:

| Command         | Action                   |
| --------------- | ------------------------ |
| "open skills"   | Scroll to skills section |
| "open projects" | Show projects            |
| "open contact"  | Show contact info        |

---

### 📦 Automatic GitHub Project Sync

The website fetches repositories directly from GitHub API.

No manual project update required.

Every time a new repo is uploaded → it appears automatically.

---

### 🌌 Animated Background

Three.js powered star-field background provides modern UI experience.

---

### 🧠 Smart Project Cards

Each repository card displays:

* Project Name
* Description (or language fallback)
* Direct source code link

---

## 🛠️ Tech Stack

| Technology           | Purpose           |
| -------------------- | ----------------- |
| HTML5                | Structure         |
| CSS3                 | Glassmorphism UI  |
| JavaScript           | Logic             |
| Three.js             | 3D Background     |
| Web Speech API       | Voice recognition |
| Speech Synthesis API | AI speaking       |
| GitHub REST API      | Project fetching  |

---

## 📁 Project Structure

```
portfolio/
 ├── index.html
 ├── README.md
 └── updated.resume (2).pdf
```

---

## ⚙️ Setup & Run

### Option 1 — GitHub Pages (Recommended)

1. Upload files to a public repository
2. Go to **Settings → Pages**
3. Select branch: `main`
4. Open generated link:

```
https://yourusername.github.io/repository-name/
```

---

### Option 2 — Local Run

Voice commands may not work locally due to browser security.

```
Right click → Open with Live Server
```

---

## 🔐 Permissions Required

Browser will ask:

**Microphone Access → Allow**

Without permission, AI assistant cannot listen.

---

## 📡 API Used

GitHub Repository API:

```
https://api.github.com/users/<username>/repos
```

---

## 👨‍💻 Author

**Edula Sai Pranav Reddy**
Computer Science Engineer
Passionate about building intelligent interactive applications

---

## ⭐ Why This Project?

Most portfolios only show projects.
This portfolio **interacts with recruiters**.

It demonstrates:

* Frontend engineering
* API integration
* Voice interface design
* User experience thinking

---

## 📜 License

This project is open source and free to use for learning purposes.
