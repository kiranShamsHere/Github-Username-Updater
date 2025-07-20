# 🙌 Contributing to GitHub Username Updater

Thank you for your interest in contributing to **GitHub Username Updater**!  
Whether you're fixing a bug, improving documentation, or suggesting new features — we appreciate your effort to make this tool better 🚀

---

## 🛠 Tech Stack

This project uses:

- **Python 3.8+**
- **Flask** (Backend framework)
- **HTML, CSS, JS** (Frontend)
- **Font Awesome** (Icons)
- **GitHub REST API v3**

---

## ⚙️ Getting Started

Follow these steps to run the project locally:

### 1. Fork the repository

Click the "Fork" button on the top right of this repo. It’ll create a copy in your GitHub account.

### 2. Clone the repo

```bash
git clone https://github.com/<your-username>/Github-Username-Updater.git
cd Github-Username-Updater
```

### 3. Set up a virtual environment (recommended)

```bash
python -m venv venv
# Activate the virtual environment:
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask app

```bash
python app.py
```

The app should now be running at:  
👉 `http://localhost:5000`

---

## 📁 Recommended Project Structure

```
📁 backend/
│  ├── app.py              # Flask backend logic
│  ├── github_utils.py     # GitHub API interaction utility
│  └── templates/
│     └── index.html       # Main HTML template

📁 static/
│  ├── style.css           # Styling
│  ├── script.js           # Frontend interactivity
│  └── darkmode-toggle.js  # Theme toggle logic

📄 requirements.txt         # Python dependencies
📄 README.md                # Project overview
📄 CONTRIBUTING.md          # Contribution guidelines
📄 LICENSE                  # MIT License
📄 .gitignore               # Git ignored files

```

---

## 🚧 Things You Can Help With

- Fix typos or improve layout of HTML/CSS
- Add client-side or backend validations
- Suggest or implement new features
- Report bugs (via [Issues](../../issues))
- Improve accessibility or responsiveness

---

## 🚀 How to Contribute

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/Github-Username-Updater.git
   cd Github-Username-Updater
   ```
3. **Create a new branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes**
5. **Stage and commit your changes**:
   ```bash
   git add .
   git commit -m "feat: add your message here"
   ```
6. **Push** to your forked GitHub repo:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request** on GitHub and wait for review ✅

---

## 🐛 Reporting Issues

- Before creating a new issue, please [search the issues](../../issues) to avoid duplicates.
- For bugs, provide steps to reproduce and screenshots if applicable.
- For enhancement ideas or improvements, describe the use-case clearly.

---

## ✨ Feature Requests

- If you have a feature in mind, feel free to open a [New Issue](../../issues/new).
- Clearly explain the feature, why it's useful, and how it improves the tool.
- Not all features may be accepted, but all ideas are appreciated.

---

## 🔧 Pull Requests

- Pull Requests must be linked to an [open issue](../../issues).
- First, **comment on the issue** asking to be assigned before starting work.
- Always work on a new branch:
  ```bash
  git checkout -b fix/your-feature-name
  ```
- Follow best practices for commit messages. Example:
  ```bash
  git commit -m "fix: correct broken link in footer"
  ```
- Push your branch and open a **Pull Request**:
  ```bash
  git push origin fix/your-feature-name
  ```
- Open a **Pull Request** and wait for review ✅
---

## 🧪 Available Scripts

| Command                  | Description                          |
|--------------------------|--------------------------------------|
| `python app.py`          | Start the Flask development server   |
| `pip install -r requirements.txt` | Install all required Python packages |
| `python -m venv venv`    | Create a virtual environment         |
| `source venv/bin/activate` / `venv\Scripts\activate` | Activate virtual environment (Linux/Windows) |
| `deactivate`             | Exit the virtual environment         |

---

## 💬 Need Help?

Feel free to [open an issue](../../issues/new) or connect on  
📬 [LinkedIn – Kiran Shams](https://www.linkedin.com/in/kiranshamshere/)

---

Thanks for being a part of this journey! 💙  
Let’s build something useful for the developer community 🚀
