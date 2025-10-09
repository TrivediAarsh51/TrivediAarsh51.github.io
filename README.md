# 🧠 Single-file Terminal Portfolio

A minimalist **interactive terminal-style portfolio**, built entirely in a **single HTML file** — no frameworks, no build tools, no external JavaScript dependencies.

![screenshot](https://repository-images.githubusercontent.com/1072892475/15c0a081-98bd-46c9-9e08-8eee168d8928) <!-- Optional screenshot -->

---

## 🚀 Overview

This project emulates a classic command-line interface inside a browser.  
Users can type commands like `help`, `about`, or `skills` to explore sections of the portfolio.

Everything — from the ASCII banner to the typing animation — is implemented with pure HTML, CSS, and vanilla JavaScript.

---

## ✨ Features

- 💻 **Single-file simplicity** – fully self-contained in one `.html` file  
- ⚡ **Typing animation** – smooth simulated terminal typing  
- 🧠 **Command history** – navigate with arrow keys like a real CLI  
- ⌨️ **Autocomplete** – press `Tab` to see or complete available commands  
- 🎨 **Retro aesthetic** – green-on-black terminal with OCR-A / Roboto Mono style  
- 🧩 **Font Awesome integration** – clean icons for skills and tech stack  
- 🧼 **Persistent banner** – banner reappears after `clear` command  
- 🔗 **Clickable links** – contact and project URLs open in a new tab

---

## 🧰 Commands

| Command | Description |
|----------|-------------|
| `help` | Displays all available commands |
| `about` | Short introduction |
| `skills` | Core skills and areas of expertise |
| `technologies` | Tools, platforms, and environments |
| `projects` | Highlighted personal projects |
| `contact` | Contact links (email, GitHub, LinkedIn, etc.) |
| `clear` | Clears the screen and restores the banner |

---

## ⚙️ Customization

1. **Edit your information**  
   Inside the `<script>` section, update the `commands` object:
   ```js
   about: `I'm Free Space — an IT professional passionate about automation and efficient systems.`,
   contact: `<i class="fa-solid fa-envelope"></i> <a href="mailto:your@email.com">your@email.com</a>`
