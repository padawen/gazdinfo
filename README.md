# 🧮 Gazdasági informatika -  feladatok

## Mi a pokol ez?

Ez egy webes alkalmazás, ami azért született, hogy ne kelljen a Discord szerverről származó feladatokat keresgélni, mint valami neandervölgyi. Tele van optimalizálási feladatokkal, gráfokkal, meg egyéb matematikai rémségekkel, amiket a Discord szerverről gyűjtöttünk össze. ChatGPT is segített pár helyen átírni a szöveget, mert hát miért ne?

## 🚀 Hogy működik ez a műszörnyeteg?

### Most már bonyolultabb, de jobb:
1. **Bedobsz egy feladat típust** - Van 4 darab, mint a Beatles (majdnem)
2. **Ha task_2-t választod:** Először kiválasztod a szekciót (Ütemezés gráf vagy Receptgráf) - igen, felosztottuk mert túl sok volt egyben
3. **Kiválasztasz egy konkrét feladatot** - Van több, mert lustán csináltuk
4. **Megnézed a feladatot** - Bal oldalon, mint ahogy egy normális ember olvasna
5. **Csekkolod a megoldást** - Jobb oldalon, amikor feladod
6. **Nagyítod a képeket** - Mert ki a szar tudja elolvasni azt a hangyabetűt?

### A nagy újítás v2.0 🎉
**SZAKÍTÁS!** A második feladattípus most két részre van osztva:
- **Ütemezés gráf** (volt task_1 és task_4)
- **Receptgráf** (volt task_2 és task_3)

Mert hát ki a fene akarja az összes receptet és ütemezést egy kupacban? Nem vagyunk barbárok.

## 🎯 Navigáció (avagy hogyan ne tévedj el ebben a káoszban)

- **Számbillentyűk**: Feladat típus váltás (1-4, mint a TV csatornák a kőkorszakban)
- **Nyíl billentyűk**: Feladatok között ugrálás (←→)
- **Escape**: Modal bezárása (menekülés)
- **Egér**: Kattints bármire, ami gombnak néz ki
- **Új szar**: Task_2-nél először a zöld szekció gombokra kattintasz, aztán a kék feladat gombokra

## 🔧 Hogyan indítsd el ezt a remekmű(vet)?

```bash
# Ha van Python a gépeden (és ha nincs, mi a szar csinálsz?)
python -m http.server 8000

# Aztán nyisd meg a böngésződben:
http://localhost:8000
```

Ha nincs Python, akkor töltsd le, vagy menj vissza Windows 95-re.

## 📁 Mi van ebben a káoszban?

```
gazdinfo/
├── index.html          # A főhadiszállás
├── theories.html       # Elméleti kérdések (ha unatkozol)
├── styles.css          # Szépítő szarok (zöld és kék minden)
├── theories.css        # Elméleti kérdések szépítése
├── tasks.json          # Itt laknak a feladatok (reorganizálva)
├── theories.json       # Itt laknak az elméleti kérdések
├── images/             # Képek új rendszerben
│   ├── task_1/         # Első típus mappája
│   │   ├── subtask_1/  # question.png, answer.png
│   │   ├── subtask_2/  # question.png, answer.png
│   │   └── subtask_3/  # question.png, answer.png
│   ├── task_2/         # Második típus mappája (felosztva)
│   │   ├── subtask_1/  # Ütemezés gráf task 1
│   │   ├── subtask_2/  # Receptgráf task 1
│   │   ├── subtask_3/  # Receptgráf task 2
│   │   └── subtask_4/  # Ütemezés gráf task 2
│   ├── task_3/         # Harmadik típus mappája
│   └── task_4/         # Negyedik típus mappája
├── theories/           # Elméleti válaszok
├── documents/          # PDF dokumentumok (Elovizsga.pdf, Gazdasagi-informatika.pdf)
└── README.md           # Ez itt, amit most olvasol és röhögsz rajta
```

**Feladat típusok (most már szép nevekkel):**
- **Task 1**: Maximális folyam → Minimális feszítő fa → Legrövidebb út
- **Task 2 (két részre osztva)**: 
  - Ütemezés gráf 
  - Receptgráf
- **Task 3**: Vegyes gazdinfo szörnyűségek
- **Task 4**: Minimális feszítőfa → Legrövidebb út → Max flow

## 📚 Elméleti kérdések (ha még mindig nem untad ki magad)

**Hogyan működik?**
- Kattints a "📚 Elméleti kérdések" gombra
- Látod a kérdéseket harmonika stílusban
- Kattints egy kérdésre → megnyílik a válasz
- Van "Összes megnyitása/bezárása" gomb lustáknak

## 📱 Mobil kompatibilitás (mert ki ül ma már gép elé?)

Igen, mobilon is működik! A gombok most már nem kicsik, mint a szúnyog farka. Négyszögletes gombok, amikre rá lehet tapintani anélkül, hogy mellé nyomnál. Nincs hover effekt, nincs árnyék, nincs semmilyen felesleges szar - csak tiszta, egyszerű design.

## 🎨 Miért zöld és kék minden?

Mert:
- Zöld = szekció gombok (természet, pénz, minden jó)
- Kék = feladat gombok (mint az ég, mint a tenger, mint a szomorúság amikor matekot tanulsz)
- Minden más szürke, mert az élet is az

## 🛠️ Új feladat hozzáadása

Ha új feladatot akarsz:
1. Szerkeszd a `tasks.json`-t (JSON az új TXT)
2. Csinálj egy új `task_X/subtask_Y/` mappát az `images/` alatt
3. Dobj be `question.png` és `answer.png` fájlokat (vagy `answer_2.png` ha több válasz van)
4. Imádkozz, hogy működjön
5. Ha nem, akkor blame ChatGPT

## 🤷 Gyakran Ismételt Kérdések (FAQ - Frequently Asked Szarságok)

**K: Miért nem látom a képeket?**
V: Mert nem szerverről futtatod. Ez nem PowerPoint.

**K: Miért ilyen bonyolult a task_2 navigációja?**
V: Mert túl sok feladat volt egy helyen. Most legalább van rendszer.

**K: ChatGPT csinálta az egészet?**
V: Nem, csak átírt pár szöveget. A matek emberi szenvedés marad.

**K: Miért nincs dark mode?**
V: Mert az élet se dark mode. Szokd meg.

**K: Hogy működik az URL handling az új rendszerrel?**
V: Jó kérdés, majd kitaláljuk.

---

*Készítette: Valaki, aki túl sokat lógott a Discord szerveren és most próbálja weboldalon keresztül továbbadni a szenvedést. 2025-ben, amikor ChatGPT még segített a szövegírásban.* 

*P.S.: Ha hibát találsz, az ChatGPT hibája. Ha minden működik, az emberi zseni.*