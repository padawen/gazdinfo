# 🌿 Gazdasági informatika - Feladatok

## Mi a fene ez?

Ez egy webes alkalmazás, ami azért született, hogy a gazdasági informatika feladatokat ne kelljen papírlapokon keresgélni, mint valami ősember. Modern technológiával, természetes tudással - meg persze egy csomó zöld színnel, mert a természet jó.

## 🚀 Hogy működik ez a szörnyeteg?

### Alapvetően így megy:
1. **Bedobsz egy feladat típust** - Van 4 darab, mint a Beatles tagjai
2. **Kiválasztasz egy konkrét feladatot** - Ha van több, mert néha lustábbak voltunk
3. **Megnézed a feladatot** - Bal oldalon, mint ahogy olvasni szoktál
4. **Csekkolod a megoldást** - Jobb oldalon, ha elakadtál
5. **Nagyítod a képeket** - Mert ki tudja elolvasni azt a pici szöveget?

### A nagy újítás 🎉
**VÉGRE!** Ha a feladat képére kattintasz, nem tudsz átcsúszni a megoldás képeire! Mert mi értelme lenne a titoknak, ha egyből láthatnád a válaszokat? Ez olyan, mintha a keresztrejtvényben elölről olvasnád a megfejtéseket.

## 🎯 Navigáció (avagy hogyan ne tévedj el)

- **1-4 számbillentyűk**: Feladat típus váltás (mint a TV csatornák)
- **Nyíl billentyűk**: Feladatok között ugrálás (←→)
- **Escape**: Modal bezárása (menekülés a nagyított képből)
- **Egér**: Kattints bármire, ami gombnak néz ki

## 🔧 Hogyan indítsd el ezt a szépséget?

```bash
# Ha van Python a gépeden (és miért ne lenne?)
python -m http.server 8000

# Aztán nyisd meg a böngésződben:
http://localhost:8000
```

Ha nincs Python, akkor... hát, ideje lenne telepíteni, nem? 😏

## 📁 Mi van ebben a mappában?

```
gazdinfo/
├── index.html          # A fő színhely, ahol minden történik
├── theories.html       # Elméleti kérdések oldala 
├── styles.css          # Szépítő cuccok (zöld mindenek)
├── theories.css        # Elméleti kérdések stílusai
├── tasks.json          # Itt laknak a feladatok
├── theories.json       # Itt laknak az elméleti kérdések
├── images/             # Feladat képek helye
│   ├── kerdes_1_1.png  # Első típus első feladat képe
│   ├── valasz_1_1.png  # És a hozzá tartozó válasz
│   └── ...             # És így tovább, mint a végtelen
├── theories/           # Elméleti kérdések válasz képei
│   ├── 1.png           # Első elméleti kérdés válasza
│   ├── 2.png           # Második elméleti kérdés válasza
│   ├── ...             # És így tovább 7-ig
│   └── 7.png           # Hetedik elméleti kérdés válasza
└── README.md           # Ez itt, amit most olvasol
```

## 📚 Mi az az elméleti kérdések rész?

Ahogy a neve is mutatja, itt vannak az elméleti kérdések!

**Hogyan működik?**
- Kattints a "📚 Elméleti kérdések" gombra a főoldalon
- Látod a kérdéseket akordeon (harmonika) stílusban
- Kattints egy kérdésre → megnyílik a válasz képpel
- Van "Összes megnyitása/bezárása" gomb, ha lusták vagytok egyesével kattintgatni

## 📱 Mobil kompatibilitás

Igen, mobilon is működik! Mert hát ki a fene ül ma már asztali gép előtt tanulni? A telefon a jövő, az asztali gép a múlt (kivéve ha játszani akarsz, de az más tészta).

## 🎨 Miért zöld minden?

Mert a természet zöld. A pénz is zöld. A gazdasági informatika is... oké, ez nem zöld, de legalább a weblap az. Plusz jól néz ki, és ki nem szereti a természetet? (Retorikiai kérdés volt.)

## 🛠️ Testreszabás

Ha új feladatot akarsz hozzáadni:
1. Szerkeszd a `tasks.json`-t
2. Dobd be a képeket az `images/` mappába
3. Imádkozz, hogy minden jól működjön
4. Ha nem, akkor legalább tanultál valamit

## 🤷 Gyakran Ismételt Kérdések

**K: Miért nem látom a képeket?**
V: Mert valószínűleg nem indítottad el szerverről. Ez nem egy Word dokumentum.

**K: Miért olyan lassú?**
V: Talán mert 1998-ból való a internetod? Vagy csak túl sok Chrome tabot nyitottál meg.

**K: Miért zöld minden?**
V: Lásd fentebb. Természet. Pénz. Stílusos. Érted.

**K: Hogyan adok hozzá új feladatot?**
V: JSON szerkesztés. Ha nem tudod mi az, akkor... Google is your friend.

---

*Készítette: Valaki, aki tudja hogy néz ki egy számítógép belülről. 2025-ben, amikor még létezett az internet.* 