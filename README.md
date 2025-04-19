# 🧠 AI-Social-OSINT – AI Powered Social Media Intelligence Toolkit

AI-Social-OSINT is a modular and extensible OSINT framework that automates information gathering from popular social media platforms. Built with AI-based analysis, it detects behavioral patterns, sentiment, and high-level insights from public user data. Perfect for ethical hacking, cyber investigations, red team assessments, and academic research.

---

## 🚀 Features

- 🔍 Multi-platform scraping (Twitter, Instagram, GitHub, etc.)
- 🧠 AI-driven behavioral and psychological profiling
- 📊 Generates JSON and HTML reports
- 📂 Modular scraper architecture (`scraper_modules/`)
- 🔐 No login or API key required (passive OSINT)
- 🧪 CLI-based operation – simple & fast

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/ai-social-osint.git
cd ai-social-osint
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the main engine from CLI:
```bash
python osint_engine.py --target username --platform twitter
```

Available arguments:

| Flag             | Description                              |
|------------------|------------------------------------------|
| `--target`       | Target username or profile handle        |
| `--platform`     | Platform to scan (twitter, instagram...) |
| `--report`       | Output report format (`json`, `html`)    |
| `--analyze`      | Run AI-driven profile analysis           |

Example:
```bash
python osint_engine.py --target elonmusk --platform twitter --report json --analyze
```

---

## 🧠 AI Profiling

- Personality trait estimation
- Behavioral tone detection
- Posting habits
- Language patterns

These are generated in `/reports/` as structured output.

---

## 📁 Project Structure

```
ai-social-osint/
├── osint_engine.py         # Main orchestrator
├── analyzer.py             # AI-based inference module
├── scraper_modules/        # Platform-specific crawlers
├── reports/                # Output directory (json/html)
├── requirements.txt
└── README.md
```

---

## 📜 License

MIT License © 2025 Burak BALTA
