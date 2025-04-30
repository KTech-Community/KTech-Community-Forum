# KTech Community Forum

Welcome to the **KTech Community Forum**, a web-based space for knowledge-sharing and discussion, built **by developers and students** in the tech ecosystem — and **for the community itself**.

This repository hosts the source code for the website, which is published via [GitHub Pages](https://pages.github.com/).  
The forum is part of the KTech initiative, aiming to foster open collaboration, mentorship, and accessible knowledge in software development and adjacent fields.

---

## 🔍 Purpose

The KTech Community Forum serves as:

- 🧠 A space to **share articles, tutorials, and experiences**.
- 💬 A platform for **discussion, feedback, and questions**.
- 📚 A growing archive of **community-contributed knowledge**.

---

## 🚀 Live Website

The forum is deployed at:

👉 [ktech-community.com](https://ktech-community.com/forum/)


---

## 🛠 How It Works

The forum **loads articles dynamically** from another public GitHub repository. ie 👉 [KTech Community Articles](https://github.com/KTech-Community/KTech-Community-Articles)
This allows contributors to **submit articles via pull requests** without requiring access to the forum's codebase.

- Articles are stored in [KTech Community Articles](https://github.com/KTech-Community/KTech-Community-Articles) under the `articles/` folder.
- A `index.json` file in that repo lists available articles and metadata (title, date, filename).
- [ktech-community.com](https://ktech-community.com/forum/) (this repo) fetches and renders the articles using client-side JavaScript.

---

## 🧑‍💻 Contributing

We welcome contributions from all members of the community!

### To contribute an article:

1. Fork [KTech Community Articles](https://github.com/KTech-Community/KTech-Community-Articles)
2. Add your Markdown article under `articles/`