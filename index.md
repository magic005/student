---
layout: base
title: I'm Ansh
hide: true
---

<style>
    /* Subtle enhancements */
    .badge-group a img {
        transition: transform 0.2s ease, box-shadow 0.2s ease;
        border-radius: 6px;
    }
    .badge-group a img:hover {
        transform: translateY(-2px);
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .button-tile {
        padding: 10px 20px;
        border-radius: 8px;
        font-weight: 600;
        box-shadow: 1px 2px 5px rgba(0, 0, 0, 0.08);
        transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .button-tile:hover {
        transform: scale(1.03);
        cursor: pointer;
    }

    .section-title {
        margin-top: 30px;
        font-size: 1.4em;
        border-bottom: 2px solid #eee;
        padding-bottom: 6px;
        color: #1e88e5;
    }

    .footer-note {
        text-align: center;
        font-size: 0.9rem;
        color: #777;
        margin-top: 40px;
    }
</style>

# Hi, I'm Ansh.

Welcome to my space — where I explore code, build things, and share what I learn.

---

### <span class="section-title">🛠️ Development Environment</span>

> Coding starts with tools. Here are the main ones I use:

<div class="badge-group" style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="https://github.com/Open-Coding-Society/student">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://open-coding-society.github.io/student">
        <img src="https://img.shields.io/badge/GitHub%20Pages-327FC7?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages">
    </a>
    <a href="https://kasm.nighthawkcodingsociety.com/">
        <img src="https://img.shields.io/badge/KASM-0078D4?style=for-the-badge&logo=kasm&logoColor=white" alt="KASM">
    </a>
    <a href="https://vscode.dev/">
        <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode">
    </a>
</div>

---

### <span class="section-title">📈 Class Progress</span>

> These are some of the projects I've been working on. Check them out!

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="{{site.baseurl}}/snake" style="text-decoration: none;">
        <div class="button-tile" style="background-color: #DFFFD6; color: #034803;">
            🐍 Snake Game
        </div>
    </a>
    <a href="{{site.baseurl}}/turtle" style="text-decoration: none;">
        <div class="button-tile" style="background-color: #FFE0E0; color: #6F0000;">
            🐢 Turtle Graphics
        </div>
    </a>
</div>

---

### <span class="section-title">🌐 Open Coding Society</span>

> I'm part of the Open Coding Society — a community for learning and creating.

<p style="color: #2A7DB1;">Check out our socials: <a href="https://opencodingsociety.com" style="color: #2A7DB1; text-decoration: underline;">opencodingsociety.com</a></p>

---

### <span class="section-title">🤝 Get in Touch</span>

> Interested in collaborating, learning, or chatting?

- 💬 [Message me on GitHub](https://github.com/Open-Coding-Society/student)  
- 🧠 Learn with us at [Open Coding Society](https://opencodingsociety.com)  
- 📧 Reach out via our [contact form](https://opencodingsociety.com/#contact)

---

<p class="footer-note">Built with 💻 and ☕ by Ansh</p>

<div class="mermaid">
flowchart TD
  A[Start] --> B{Is it stupid?}
  B -- Yes --> C[Do it anyway]
  B -- No  --> D[Also do it anyway]
  C --> E[Profit]
  D --> E
</div>
