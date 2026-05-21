# Tabata-timer
Tabata timer for workouts
# ⏱️ Tabata / Intervallum Időzítő Webalkalmazás

Egy letisztult, modern, sötét módos (Dark Mode) **Tabata és Intervallum Időzítő** webalkalmazás magyar nyelven. Kifejezetten mobiltelefonos használatra optimalizálva, de asztali böngészőkben is tökéletesen működik. 

A projekt különlegessége, hogy **egyetlen HTML fájlból áll**, nem igényel külső függőségeket vagy letöltött hangfájlokat, mert a hangokat a böngésző beépített szintetizátorával (Web Audio API) állítja elő.

---

## ✨ Főbb funkciók

* **Teljesen testreszabható időzítések:** Visszaszámlálás, Bemelegítés, Munkavégzés, Pihenő, Szettek és Ciklusok száma, Ciklusok közötti pihenő, valamint Levezetés.
* **Azonnali, automatikus indítás:** A *Mentés és Indítás* gomb megnyomása után az app azonnal átvált az órára és elindítja a felkészülést.
* **Profi hangjelzések fázisonként:** 6-féle különböző elektronikus hanghatás (Csipogás, Mély jelzés, Dupla, Tripla, Sci-Fi Lézer vagy Néma), amelyek fázisonként külön-külön konfigurálhatók.
* **Erőteljes Duda (Horn) effekt:** Minden visszaszámlálás utolsó másodpercében (váltáskor) egy masszív, többszólamú dudahang jelzi a fázis végét.
* **Dupla vizuális visszajelzés:** Modern SVG alapú haladási gyűrűk. A belső kör az aktuális fázis idejét, a külső zöld kör pedig a teljes edzésből eltelt összidőt mutatja.
* **PWA-szerű élmény:** Mobilböngészőből közvetlenül hozzáadható a kezdőképernyőhöz, így applikációként futtatható.

---

## 🚀 Telepítés és használat offline

Mivel az alkalmazás egyetlen önálló fájl, nincs szükség bonyolult telepítésre:

1. Töltsd le a `index.html` fájlt.
2. Kattints rá duplán a számítógépeden vagy a telefonodon.
3. Az időzítő azonnal megnyílik a böngésződben, és **teljesen offline (internet nélkül is) működik**.

---

## 🌐 Élő elérés (GitHub Pages)

Ha szeretnéd online használni vagy megosztani a telefonoddal:
1. Kapcsold be a **GitHub Pages** funkciót a Repository beállításaiban (*Settings -> Pages*).
2. Válaszd ki a `main` branch-et és mentsd el.
3. Az időzítőd elérhető lesz a következő linken:  
   `https://<felhasznalonev>.github.io/<projekt-neve>/`

---

## 🛠️ Felhasznált technológiák

* **HTML5** – Strukturált, szemantikus felépítés.
* **CSS3** – Modern CSS változók, Flexbox elrendezés és reszponzív dizájn.
* **JavaScript (ES6+)** – Állapotkezelés, folyamatos időléptetés és dinamikus UI frissítés.
* **Web Audio API** – Szintetizált audio-effektek generálása valós időben, külső `.mp3` fájlok nélkül.

---

## 📝 Licensz

Ez a projekt szabadon felhasználható, alakítható és terjeszthető (MIT Licensz). Jó edzést kívánok! 💪
