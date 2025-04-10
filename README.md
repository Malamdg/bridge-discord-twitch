# Bridge Discord ↔ Twitch

**Bridge Discord Twitch** is a full-stack project designed to create a real-time communication bridge between Discord and Twitch. It features a modern Angular frontend with an integrated Node.js backend, and a separate PHP-based back office for managing data and interactions with the database.

---

## 📦 Project Structure

```text
bridge-discord-twitch/
├── frontend
│   ├──frontend-angular/     # Angular frontend + backend-node (Node.js + Socket.IO)
│   └── backend-node/        # Node.js backend communicating with front (Socket.IO) and PHP (HTTP)
├── backend-php/             # PHP back office with database access
├── .gitmodules              # Git submodules configuration
└── (deployment scripts, CI/CD configs, etc.)
```

---

## ⚙️ Technologies
- Angular (frontend)
- Node.js + Socket.IO (real-time server communication)
- PHP (back office and database management)
- Git Submodules (modular project structure)
- Optionally: Docker (recommended), CI/CD for deployment

---

## 🚀 How to Clone This Project

Clone the main deployment repository with submodules:

```bash
git clone --recurse-submodules https://github.com/Malamdg/bridge-discord-twitch.git
```

To update submodules later:

```bash
git submodule update --remote --merge
```

---

## 🧱 Project Philosophy
> The development discussions for this project have been conducted in French and English, as it is a personal initiative currently being structured.
> The core idea is to properly separate the different components — frontend, Node.js backend, and PHP back office — while keeping a central deployment repository for clarity and maintainability.
> SSH authentication is used for Git operations, and the current setup relies on Git submodules to allow independent updates and versioning of each part.
> This project is also an opportunity for me to experiment with Docker development and deployment.

---

## 🤖 AI Usage

This `README.md` file was generated and structured with the assistance of **ChatGPT**, to ensure clarity, consistency, and to save time during the documentation process.

While a language model has been used to improve documentation quality, **the core concepts, code architecture, and implementation choices are fully human-driven**. The use of AI will be kept to a minimum throughout the project, and limited to:

- Enhancing documentation and formatting
- Improving code comments for clarity
- Assisting with debugging suggestions
- Expanding the scope of tests to ensure optimal coverage and catch edge cases that might have been overlooked

This project is fundamentally designed and built by a human developer, with AI acting only as a support tool for auxiliary tasks.

---

## 📫 Contact

For inquiries, suggestions, or collaboration opportunities, feel free to contact me at:

Email: malamqcfd@gmail.com

GitHub: https://github.com/Malamdg

---

## 📄 License
This project is licensed under the MIT License — feel free to use, modify, and contribute.

---

### Notes 

> ℹ️ AI tools like ChatGPT were used during this project for support tasks only (e.g., documentation and test suggestions). Core design and implementation remain human-driven. For learners, I recommend using AI primarily as a guide or companion — solving problems yourself remains the most effective way to grow as a developer.
> 
> Always take AI-generated solutions with a critical eye. Language models are general-purpose tools and may offer answers that are not entirely accurate or applicable to your specific context. Verifying, testing, and understanding every solution remains essential.

