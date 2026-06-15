# ☁️ Co je Cloudflare?

Školní webová stránka zpracovaná jako součást zadání předmětu kybernetické bezpečnosti.
Stránka vysvětluje, co je Cloudflare, k čemu slouží a popisuje vybrané služby.

🔗 **Živá verze:** [ladislavpl.github.io/cloudflare_web](https://ladislavpl.github.io/cloudflare_web/)

---

## 📋 Obsah stránky

| Sekce | Popis |
|---|---|
| **Co je Cloudflare?** | Stručné vysvětlení (2–4 věty) |
| **K čemu slouží?** | Čtyři hlavní oblasti – bezpečnost, výkon, dostupnost, soukromí |
| **Statistiky** | Klíčová čísla – 20 % provozu internetu, 300+ datových center |
| **Vybrané služby** | CDN, DDoS ochrana, DNS resolver, SSL/TLS, WAF, Cloudflare Pages |

---

## 🗂️ Struktura projektu

```
cloudflare_web/
├── index.html   # Hlavní HTML soubor stránky
├── style.css    # Vlastní styly (vanilla CSS, tmavý motiv)
└── README.md    # Tento soubor
```

---

## 🛠️ Použité technologie

- **HTML5** – sémantická struktura (`<main>`, `<nav>`, `<header>`, `<footer>`, `<article>`, `<section>`)
- **Vanilla CSS** – vlastní styly, CSS proměnné, Grid layout, responzivní design
- **Google Fonts** – písmo Inter (400, 600, 700, 900)
- **GitHub Pages** – bezplatný hosting statických stránek

---

## ✅ Technické funkce

### SEO
- `<title>` s klíčovými slovy
- `<meta name="description">` a `<meta name="keywords">`
- `<link rel="canonical">` – kanonická URL
- Strukturovaná data **JSON-LD** (schema.org `WebPage` + `Organization`)

### Open Graph & X (Twitter) Cards
- `og:title`, `og:description`, `og:url`, `og:type`, `og:locale`, `og:site_name`
- `twitter:card`, `twitter:title`, `twitter:description`

### Přístupnost (WCAG 2.2 AA)
- **Skip link** „Přejít na hlavní obsah" (WCAG 2.4.1)
- ARIA landmarks: `role="navigation"`, `role="banner"`, `role="main"`, `role="contentinfo"`, `role="region"`
- `aria-label` a `aria-labelledby` na všech sekcích a interaktivních prvcích
- `aria-hidden="true"` na dekorativních emoji
- `:focus-visible` outline pro klávesnicové uživatele (WCAG 2.4.7)
- `prefers-reduced-motion` – respektuje systémové nastavení animací (WCAG 2.3.3)
- `rel="noopener noreferrer"` na externích odkazech

---

## 🚀 Spuštění lokálně

Stránka je čistý HTML/CSS soubor bez závislostí – stačí otevřít `index.html` v prohlížeči:

```bash
# Nebo pomocí VS Code rozšíření Live Server
# Klikněte pravým tlačítkem na index.html → Open with Live Server
```

---

## 📖 Zdroje

- [cloudflare.com](https://www.cloudflare.com) – oficiální web Cloudflare
- [schema.org](https://schema.org) – strukturovaná data
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/) – přístupnostní standardy
- [ogp.me](https://ogp.me) – Open Graph protokol

---

*Autor: Ladislav Jaromír Pleštil · 2026*
