# KDU-ČSL Webová stránka

Oficiální webová prezentace **KDU-ČSL** (Křesťanská a demokratická unie – Československá strana lidová).

## 🎨 Design

- **Barevné schéma**: Světle žluté pozadí s modrými nadpisy
- **Typografie**: Profesionální, čitelné fonty (Segoe UI, Helvetica)
- **Efekty**: Hover animace, smooth scroll, parallax efekty
- **Responzivní**: Funguje na mobilech, tabletech i počítačích

## 📋 Sekce

1. **Hero** - Úvodní sekce s hlavním sdělením
2. **O nás** - Představení strany a hlavních hodnot
3. **Historie** - Časová osa od roku 1919 do současnosti
4. **Naši lidé** - Předsednictvo a zástupci strany
5. **Dokumenty** - Stanovy, programy, aktuality
6. **Kontakt** - Kontaktní informace a formulář

## 🚀 Spuštění lokálně

### Jednoduchý způsob (Python)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Poté otevřete prohlížeč na adrese: `http://localhost:8000`

### Nebo pomocí Node.js
```bash
# Nainstalujte http-server globálně
npm install -g http-server

# Spusťte server
http-server -p 8000
```

### Nebo pomocí VS Code
1. Nainstalujte rozšíření "Live Server"
2. Pravým tlačítkem na `index.html`
3. Zvolte "Open with Live Server"

## 📁 Struktura projektu

```
tobbydobby/
├── index.html          # Hlavní HTML soubor
├── styles.css          # CSS styly
├── script.js           # JavaScript funkce
├── assets/             # Složka pro obrázky
│   ├── README.md       # Instrukce pro obrázky
│   └── .gitkeep        # Zachování složky v git
└── README.md           # Tento soubor
```

## 🖼️ Přidání obrázků

Nahrajte obrázky do složky `assets/`:

- `logo.png` - Logo strany
- `hero-image.jpg` - Hlavní obrázek
- `predseda.jpg` - Foto předsedy
- `history-*.jpg` - Historické fotografie
- `news-*.jpg` - Obrázky aktualit
- A další... (viz `assets/README.md`)

## 🌐 GitHub Pages

Stránka je nasazena na GitHub Pages a dostupná na:
`https://[váš-username].github.io/[název-repo]/`

## 🛠️ Technologie

- **HTML5** - Sémantická struktura
- **CSS3** - Moderní styly a animace
- **JavaScript** - Interaktivita (vanilla JS, bez frameworků)
- **Responzivní design** - Mobile-first přístup

## ✨ Funkce

- ✅ Smooth scroll mezi sekcemi
- ✅ Scroll-snap efekt
- ✅ Hover animace na kartách a tlačítkách
- ✅ Sticky navigace
- ✅ Mobilní hamburger menu
- ✅ Formulář s validací
- ✅ Timeline animace
- ✅ Lazy loading obrázků
- ✅ Parallax efekt
- ✅ Fade-in animace

## 📝 Poznámky

- Formulář je demo - pro ostrý provoz připojte backend
- Obrázky jsou placeholdery - nahraďte skutečnými fotografiemi
- Odkazy vedou na oficiální web kdu.cz
- Obsah je převzat z oficiálních zdrojů KDU-ČSL

## 📞 Kontakt

**KDU-ČSL**
Palác Charitas
Karlovo náměstí 5
128 00 Praha 2

Tel: 226 205 111
Web: https://kdu.cz

## 📄 Licence

© 2025 KDU-ČSL. Všechna práva vyhrazena.

---

**Vytvořeno s důrazem na kvalitu, přístupnost a moderní webový design.**
