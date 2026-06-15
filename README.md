# BRM — Bruder Resume Maker

A free, browser-based resume builder. No account. No backend. No cost.  
Fill in your details, pick a template, download a PDF.

**Built by [Bruder Motion](https://brudermotion.com)**

---

## Features

- **6-step form** — Personal info, Summary, Experience, Education, Skills, and a final review
- **Live preview** — Updates in real time as you type
- **Two templates** — Modern Dark and Classic White, switchable at any time
- **Accent color picker** — Customize the color across both templates
- **PDF download** — High-quality export, exactly as shown in the preview
- **Save progress** — Export your data as JSON and import it back later
- **Auto-save** — Your data is saved to localStorage between sessions
- **AI enhancements** *(optional)* — Enhance your summary, bullet points, and get skill suggestions using your own Anthropic API key. The app works fully without it.

---

## Usage

No install. No dependencies. Just open the file.

**Option 1 — GitHub Pages**

Visit the live link and start building.

**Option 2 — Run locally**

```
git clone https://github.com/letmebuildappz/brm
```

Open `index.html` in any browser. That's it.

---

## AI Features (Optional)

The ✦ AI buttons use the Anthropic API to:
- Rewrite your professional summary
- Improve individual bullet points
- Suggest relevant skills based on your role

To use them, click **AI Key** in the header and enter your Anthropic API key.  
Your key is stored only in your browser — never sent anywhere except directly to Anthropic's API.

Get a key at [console.anthropic.com](https://console.anthropic.com)

The app is fully functional without an API key.

---

## Stack

- Vanilla HTML, CSS, JavaScript — no framework
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for PDF generation (CDN)
- Google Fonts (Inter) via CDN
- Anthropic API for optional AI features
- Zero backend — runs entirely in the browser

---

## Part of the Bruder Motion Open-Source Apps

| App | Description |
|-----|-------------|
| [Say It For Me](https://github.com/letmebuildappz/say-it-for-me) | Text-to-speech tool |
| [Résumé Roast](https://github.com/letmebuildappz/resume-roast) | AI resume feedback |
| [Explain My Bill](https://github.com/letmebuildappz/explain-my-bill) | Bill breakdown tool |
| [DigiTally](https://github.com/letmebuildappz/digi-tally) | Cloud-synced bill tracker |
| [PassGen](https://github.com/letmebuildappz/passgen) | Password generator |
| **BRM** | Resume builder |

---

## License

MIT — free to use, modify, and share.
