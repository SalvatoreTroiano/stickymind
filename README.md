# 📝 StickyMind

**App di note in stile Post-it** — funziona offline, installabile come app su telefono e desktop.

🔗 **[Demo live →](https://TUO_USERNAME.github.io/stickymind/)**

---

## ✨ Funzionalità

- 🗒️ Crea note in stile Post-it con titolo e testo
- 🎨 8 colori di sfondo + 8 colori per il testo
- 🏷️ Categorie personalizzabili
- 📌 Pin delle note importanti
- 🔍 Ricerca full-text
- 📱 Layout responsive (mobile, tablet, desktop)
- 💾 Salvataggio automatico nel browser (localStorage)
- 🌐 Funziona **completamente offline** (Service Worker)
- 📲 **Installabile come app** su iOS, Android, Windows, Mac

---

## 🚀 Pubblicare su GitHub Pages

### 1. Crea il repository

```bash
git init
git add .
git commit -m "feat: initial StickyMind release"
```

### 2. Crea un repo su GitHub

Vai su [github.com/new](https://github.com/new) e crea un repo pubblico chiamato `stickymind`.

### 3. Collega e pubblica

```bash
git remote add origin https://github.com/TUO_USERNAME/stickymind.git
git branch -M main
git push -u origin main
```

### 4. Attiva GitHub Pages

1. Vai su **Settings** → **Pages** nel tuo repository
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`
4. Clicca **Save**

Dopo qualche minuto l'app sarà live su:
```
https://TUO_USERNAME.github.io/stickymind/
```

---

## 📲 Installare l'app

### Su Android (Chrome)
1. Apri l'URL nel browser
2. Tocca il menu `⋮` → **"Aggiungi a schermata Home"**
3. Oppure aspetta il banner in basso

### Su iPhone/iPad (Safari)
1. Apri l'URL in Safari
2. Tocca **Condividi** `⎋` → **"Aggiungi a schermata Home"**

### Su Desktop (Chrome/Edge)
1. Apri l'URL
2. Clicca sull'icona **⊕** nella barra degli indirizzi
3. Clicca **Installa**

---

## 🗂️ Struttura file

```
stickymind/
├── index.html      # App completa (single file)
├── manifest.json   # Configurazione PWA
├── sw.js           # Service Worker (cache offline)
├── README.md       # Questo file
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    ├── favicon-16x16.png
    └── favicon-32x32.png
```

---

## 🛠️ Tecnologie

- HTML5 / CSS3 / Vanilla JavaScript
- Progressive Web App (PWA)
- Service Worker per cache offline
- localStorage per persistenza dati
- Google Fonts (Caveat + DM Sans)

---

## 📄 Licenza

MIT — libero di usare, modificare e distribuire.
