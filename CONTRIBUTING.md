# 🤝 Contributing to DORAAI

First off, thank you for considering contributing to **DORAAI**! 🎉

We welcome contributions of all kinds, including bug fixes, new features, documentation improvements, UI enhancements, and performance optimizations. Every contribution helps make DORAAI better.

---

# 📋 Table of Contents

- Code of Conduct
- Getting Started
- Project Setup
- Branch Naming Convention
- Coding Guidelines
- Commit Message Convention
- Pull Request Process
- Reporting Issues
- Feature Requests
- Need Help?

---

# 📜 Code of Conduct

Please be respectful, constructive, and inclusive.

By participating in this project, you agree to:

- Be respectful to everyone.
- Welcome new contributors.
- Provide constructive feedback.
- Focus on improving the project.

---

# 🚀 Getting Started

## 1. Fork the Repository

Click the **Fork** button on GitHub.

## 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/DORAAI-MAIN.git
cd DORAAI-MAIN
```

## 3. Create a New Branch

```bash
git checkout -b feature/your-feature-name
```

Example branch names:

```
feature/ai-builder
feature/payment-gateway
fix/login-error
fix/navbar-responsive
docs/update-readme
refactor/api-cleanup
```

---

# ⚙️ Project Setup

## Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run the backend:

```bash
npm start
```

---

## Frontend

```bash
cd frontend
npm install
```

Create a `.env` file:

```env
VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
```

Run the frontend:

```bash
npm run dev
```

---

# 💻 Coding Guidelines

Please follow these guidelines:

- Write clean and readable code.
- Follow the existing project structure.
- Use meaningful variable and function names.
- Avoid unnecessary comments.
- Keep components modular and reusable.
- Remove unused imports before committing.
- Test your changes before submitting a PR.

---

# 🎨 Frontend Guidelines

- Use React functional components.
- Keep components reusable.
- Use Tailwind CSS for styling.
- Store global state in Redux where appropriate.
- Keep pages inside the `pages` folder.
- Keep reusable UI inside the `components` folder.

---

# 🛠 Backend Guidelines

- Keep controllers lightweight.
- Validate request data.
- Use middleware for authentication.
- Handle errors gracefully.
- Follow RESTful API conventions.

---

# 📝 Commit Message Convention

Follow Conventional Commits:

```
feat: add AI website generator

fix: resolve login issue

docs: update README

style: improve dashboard UI

refactor: optimize payment controller

test: add authentication tests

chore: update dependencies
```

---

# 🔀 Pull Request Process

Before creating a Pull Request:

- Ensure your code builds successfully.
- Test your changes locally.
- Update documentation if necessary.
- Resolve merge conflicts.
- Keep PRs focused on a single feature or fix.

When submitting your PR, include:

- A clear description of the changes.
- Screenshots for UI changes (if applicable).
- Linked issue number (e.g., `Closes #12`).

---

# 🐞 Reporting Bugs

When opening a bug report, please include:

- Operating System
- Browser (if applicable)
- Steps to reproduce
- Expected behavior
- Actual behavior
- Error logs (if available)
- Screenshots (optional)

---

# 💡 Feature Requests

Feature requests are always welcome.

Please include:

- A clear description of the feature.
- Why it would be useful.
- Possible implementation ideas (optional).

---

# 📂 Project Structure

```
backend/
frontend/
README.md
CONTRIBUTING.md
LICENSE
```

---

# ⭐ Good First Issues

If you're new to open source, consider working on:

- Documentation improvements
- UI enhancements
- Bug fixes
- Responsive design improvements
- Code cleanup
- Performance optimizations

---

# 🙌 Recognition

Every contributor is appreciated. Thank you for helping improve DORAAI!

Happy Coding! 🚀
