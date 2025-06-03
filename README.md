# 🌿 Gazdasági informatika - Feladatok

Modern, responsive webes alkalmazás gazdasági informatika feladatok és megoldások megjelenítésére. **Természetes tudás, modern technológiával** - Zöld-teal színpalettával és sötét akcentusokkal.

## 🚀 Jellemzők

- **🌱 Természet-inspirált design** - Zöld-teal gradiens háttér, sötét akcentusok
- **Fully responsive** - Desktop és mobil optimalizálva
- **Gombos navigáció** - Intuitív feladat típus és feladat váltás
- **Két oszlopos layout** - Desktop: kérdés bal oldal, válasz jobb oldal
- **Mobil optimalizált** - Minimális padding, teljes képernyő kihasználás
- **Keyboard shortcuts** - 1-4 számok feladat típus váltáshoz, nyíl billentyűk navigáláshoz

## 🎯 Technológiák

- **HTML5** - Szemantikus markup
- **CSS3** - Modern styling, flexbox, grid, nature-inspired gradients
- **Vanilla JavaScript** - Dinamikus tartalom betöltés
- **JSON** - Feladat adatok tárolása
- **Poppins font** - Modern tipográfia

## 📁 Fájl struktúra

```
gazdinfo/
├── index.html          # Fő alkalmazás
├── styles.css          # Természet-inspirált CSS stílusok
├── tasks.json          # Feladat adatok
├── images/             # Feladat képek
│   ├── kerdes_1_1.png
│   ├── valasz_1_1.png
│   └── ...
└── README.md           # Dokumentáció
```

## 🔧 Használat

1. **Helyi szerver indítása:**
   ```bash
   python -m http.server 8000
   ```

2. **Böngészőben megnyitás:**
   ```
   http://localhost:8000
   ```

3. **Navigáció:**
   - Feladat típus választás: 1-4 számozott gombok
   - Feladatok között: kis számozott gombok vagy nyíl billentyűk
   - Keyboard shortcuts: 1-4 (típus váltás), ←→ (navigáció)

## 📱 Responsive Design

### Desktop (1200px+)
- Két oszlopos layout
- Nagy gombok (65px)
- Bőséges padding-ek

### Tablet (768px-1200px)
- Egy oszlopos layout
- Közepes gombok (55px)
- Adaptív spacing

### Mobil (480px-768px)
- Kompakt design
- Kis gombok (50px)
- Minimális padding-ek
- Teljes szélességű képek

### Kis mobil (-480px)
- Ultra kompakt
- Extra kis gombok (32px)
- 5px padding-ek
- Optimalizált tipográfia

## 🎨 Design System - Természet Téma

### Színpaletta
- **Primary**: #16a085 (teal)
- **Secondary**: #27ae60 (emerald zöld)
- **Dark**: #1a252f (sötét erdei)
- **Accent**: #00d2ff (világos teal)
- **Gradients**: Erdei zöld → Teal → Emerald átmenetek
- **Text**: #1a252f (természetes sötét)

### Tipográfia
- **Font**: Poppins (Google Fonts)
- **Weights**: 400, 500, 600, 700, 800
- **Responsive**: 1.8rem → 1.1rem

### Természetes Komponensek
- **Gombok**: Zöld gradiens, hover animációk
- **Kártyák**: Természetes árnyékok, organikus kerekítések
- **Képek**: Responsive, természetes keretezés
- **Színes szekciók**: Erdei zöld (kérdések) + Teal (válaszok)

## 📊 Feladat típusok

1. **🌱 Első feladat típus** - Matematikai optimalizációs feladatok
2. **🌿 Második feladat típus** - Ütemezés gráf Gantt diagramjának és komponens gráfjainak meghatározása
3. **🍃 Harmadik feladat típus** - Folyamhálózat-szintézis probléma
4. **🌳 Negyedik feladat típus** - Folyamat szintézis probléma

## 🛠️ Testreszabás

### Új feladat típus hozzáadása
1. `tasks.json` szerkesztése
2. Új típus objektum létrehozása
3. Feladatok hozzáadása a `tasks` tömbhöz

### Képek hozzáadása
1. Képek elhelyezése az `images/` mappába
2. JSON-ban a kép útvonal frissítése
3. Támogatott formátumok: PNG, JPG, SVG

### Színpaletta módosítás
1. `styles.css` szerkesztése
2. CSS változók módosítása (`:root` szekcióban)
3. Természetes színek: zöldek, tealek, erdei színek

## 📖 Fejlesztési jegyzetek

- **CSS Grid** és **Flexbox** kombinációja
- **Mobile-first** responsive design
- **Természet-inspirált CSS változók** konzisztens stílus érdekében
- **Vanilla JS** - minimális függőségek
- **Accessibility** támogatás (focus outline-ok)
- **Zöld-teal color scheme** - természetes, modern megjelenés

## 🚀 Jövőbeli fejlesztések

- [ ] Sötét erdei téma (dark mode)
- [ ] Keresés funkció természetes ikonokkal
- [ ] Bookmark rendszer
- [ ] Export funkció
- [ ] Offline támogatás
- [ ] Progress tracking zöld progress barokkal

## 📞 Kapcsolat

**🌿 Természetes tudás, modern technológiával** - Gazdasági informatika feladatgyűjtemény

---

*Készítve természet-inspirált design-nal és modern web technológiákkal* 🌱💻 