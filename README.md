
# HackerHardware.net 🖧

**Hardware · Hacks · Zen · Tao**  
*A recursive platform where hardware meets philosophy: builds, logs, and minimal interfaces.*

---

## 🚀 What Is This?

**HackerHardware.net** is the `main()` layer that unifies:
- ⚙️ Hardware builds (Hackbox Mini, Canary Box, etc.)
- 📝 Daily debug logs in Hugo’s `content/debug/`  
- 🧠 Essays and `/tao` explorations—where circuits become scrolls.  

It’s a static Hugo‑based site (hosted on GitHub Pages), a live chronicle of build experiments, framing theory, and recursive structure. Everything is indexable, resumable, and minimalist.

---

## 📦 Features

- **Publish‑as‑you‑go**: Add Markdown logs, components, utils—Hugo builds everything.  
- **Debug log timeline**: Git‑stamp your reflections, goals, and bugs. CSS renders them like terminal blocks.  
- **Tao endpoint at `/tao`**: A recursive shell interface with ink‑scroll art.  
- **Product catalog framework**: YAML‑backed product pages, easy WooCommerce embed.  
- **Visual experimentation**: DALL·E headers, schematic images, brand assets auto‑imported to `/static/`.  

---

## 🚧 Quick Start

### Prerequisites
- Install [Hugo Extended v0.100+] (required if using image processing).  
- Git, Node.js (optional tooling), and DALL·E API access.

### Getting Started
```bash
git clone https://github.com/youruser/hackerhardware.net.git
cd hackerhardware.net
hugo server --disableFastRender

Visit http://localhost:1313/ and test: /, /tao, /debug/, /logs/, /products/.
```

### Adding Content
	1.	hugo new debug/YYYY-MM-DD.md
	2.	Fill out frontmatter:

title    = "debug_log: 2025-08-05"
date     = 2025-08-05T09:00:00+10:00
tags     = ["debug","sprint"]
mood     = ":zap: 7/10"
focus    = "🧠 Zoned In"
milestone = "Sprint 1"        # optional


	3.	Write the entry, add <!--more--> to force summary.
	4.	Commit and run git push to auto‑deploy via GitHub Actions (see .github/workflows/).

⸻

## 🔍 Project Structure
```bash
/config.toml          # site config & frontmatter defaults
/content/
  /debug/            # your daily intel / logs
  /logs/             # in‑depth cases (e.g., Hackbox build, Canary Box gc())
  /utils/            # framework spec, `main_function.md`, `zen_of_dir.md`
  /products/         # product YAML + description
/layouts/
  /debug/list.html    # grouped mood‑rich index
/static/
  /css/debug.css      # terminal style for meta blocks
  /img/               # drop schematic .pngs or DALL·E SVGs
```

⸻

## 🧠 Design & Voice

The site itself is a device. It speaks in code and prose.
- Use main_function.md under /utils/ to expose your recursive manifesto.
- /tao is minimal and shell‑like; graphics are optional aesthetic framing.
- Avoid bulk prose; use bullet logs, tagged moods, and showcases (images, gallery).

⸻

## 🛠 Contributing

Earth‑class openness is not yet complete
- Fork & PR: fixes to logs, templates, or styles
- Add new debug log entry for your
- Submit DALL·E art variations for
- Please follow Contributor Covenant v2.1.

⸻

## 📅 Daily Workflow
	1.	Write a debug log nightly with mood, bugs, and goals.
	2.	Check /manage/ or /tao for architecture alignment.
	3.	Iterate: write, push, ship—even if small.

⸻

## 📦 License

Unlicense / Public Domain (your work, your logic, your mind).
In other words: do whatever you want, as long as the idea remains free.

⸻

## 🙏 Acknowledgements
   •   README structure inspired by best practices for high‑impact open-source projects
   •   README flow borrowed from Hugo personal‑website templates and developer portfolios
   •   README readability principles based on writing for technical and non-technical audiences alike

