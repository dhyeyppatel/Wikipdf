# Wikipdf
# Wikipedia to PDF

Convert any Wikipedia article into a clean, print-ready PDF — instantly and for free!

## 🌐 Live Demo

**[Visit Now](https://your-github-username.github.io/wikipedia-to-pdf)**  
*(Replace with your actual GitHub Pages link)*

---

## ✨ Features

- 📄 Convert any Wikipedia article to PDF
- 🌍 Supports 300+ languages (like `en`, `hi`, `es`, `de`, etc.)
- ⚠️ Alerts user if the article is not available in selected language
- ✅ Shows "File is on the way" message on successful download trigger
- ❌ Displays a friendly "System hiccup" error message if something goes wrong
- 🎨 Clean, theme-based UI with user-friendly experience
- ⚡ Fast, free, and doesn’t require login

---

## 🛠️ How It Works

1. Enter the article title (e.g., `Artificial Intelligence`)
2. Enter language code (e.g., `en` for English, `hi` for Hindi)
3. Click **Download PDF**
4. If the article exists, a clean PDF opens in a new tab
5. If it doesn’t exist, you’ll be alerted to try another language

---

## 📦 Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- Wikipedia REST API  
  `https://{lang}.wikipedia.org/api/rest_v1/page/pdf/{query}`

---

## 📥 Setup Locally

```bash
git clone https://github.com/your-github-username/wikipedia-to-pdf.git
cd wikipedia-to-pdf
open index.html
