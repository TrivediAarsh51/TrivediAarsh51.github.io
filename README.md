# 🧠 lynx6six Terminal Portfolio

[![Live Demo](https://img.shields.io/badge/demo-online-green?style=for-the-badge&logo=github)](https://lynx6six.github.io/Single-file-Terminal-Portfolio/)

A minimalist **interactive terminal-style portfolio**, built entirely in a **single HTML file** — no frameworks, no build tools, no external JavaScript dependencies.

🎮 **Live Demo:**  
👉 [https://lynx6six.github.io/Single-file-Terminal-Portfolio/](https://lynx6six.github.io/Single-file-Terminal-Portfolio/)

![screenshot](https://repository-images.githubusercontent.com/1072892475/15c0a081-98bd-46c9-9e08-8eee168d8928) <!-- Optional screenshot, replace or remove -->

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
   about: `I'm lynx6six — an IT professional passionate about automation and efficient systems.`,
   contact: `<i class="fa-solid fa-envelope"></i> <a href="mailto:your@email.com">your@email.com</a>`
   ```

2. **Change the font or theme**  
   Swap the font link in the `<head>` for another monospaced option:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
   ```
   Adjust `background-color` or `color` in the CSS for a different aesthetic.

3. **Add or remove commands**  
   Just add new key/value pairs to the `commands` object:
   ```js
   commands["music"] = "Currently listening to: Gojira 🎸";
   ```

---

## 🛠️ How to Run

Simply open the HTML file in your browser:

```bash
open index.html
```

Or use a simple local server (optional):
```bash
python3 -m http.server
```

Then visit [http://localhost:8000](http://localhost:8000)

---

## 💡 Future Ideas

- Move command data into a `data.json` file and load dynamically  
- Add smooth “boot-up” animation or terminal intro  
- Optional dark/light theme toggle  
- Integration with real project data from GitHub API  

---

## 📦 Repository

👉 **GitHub:** [github.com/lynx6six/Single-file-Terminal-Portfolio](https://github.com/lynx6six/Single-file-Terminal-Portfolio)

---

## 🪪 License

This project is open-source and free to use under the [MIT License](LICENSE).  
Credit appreciated if you use or modify this template!

---

### 💬 Acknowledgements

- Fonts: [Google Fonts](https://fonts.google.com/)  
- Icons: [Font Awesome](https://fontawesome.com/)  
- Concept & design: [**lynx6six**](https://github.com/lynx6six)
