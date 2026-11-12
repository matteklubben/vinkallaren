# 🍷 Vinkällarens Säkerhetsvalv – Digitalt Escape Room

Ett mobilanpassat escape room i tre akter med 9 separata sidor, byggt i ren HTML, CSS och JavaScript – redo att läggas upp direkt på **GitHub Pages**.

## 📁 Filstruktur
* `index.html` – Startsida + Akt 1, Steg 1 (Sifferchiffer)
* `akt1-etikett.html` – Akt 1, Steg 2 (Välj rätt vinetikett utifrån arkivanteckning)
* `akt1-morse.html` – Akt 1, Steg 3 (Blinkande morsekod -> avslöjar **Siffra 1**)
* `akt2-memory.html` – Akt 2, Steg 1 (Memoryspel med styrpilar/touch)
* `akt2-reglage.html` – Akt 2, Steg 2 (Ställ in röd/vit druva)
* `akt2-matte.html` – Akt 2, Steg 3 (Symbolekvation -> avslöjar **Siffra 2**)
* `akt3-labyrint.html` – Akt 3, Steg 1 (Labyrintspel med pilknappar)
* `akt3-simon.html` – Akt 3, Steg 2 (Simon Says-sekvens -> avslöjar **Siffra 3**)
* `final.html` – Slutsida med hela den tresiffriga koden & konfetti
* `config.js` – **Här ställer du in er tresiffriga kod!**
* `style.css` – Gemensam mobiloptimerad design

## 🔧 Så ställer du in din egen kod
Öppna filen `config.js` och ändra siffrorna högst upp så att de matchar ert fysiska hänglås:
```javascript
const VAULT_CONFIG = {
  digit1: "7",
  digit2: "4",
  digit3: "9"
};
```

## 🚀 Så lägger du upp på GitHub Pages (gratis på 2 minuter)
1. Skapa ett nytt publikt repository på GitHub (t.ex. `vinkallaren`).
2. Ladda upp alla filer från den här mappen direkt i roten på repot.
3. Gå till **Settings** -> **Pages** i repot.
4. Under **Source / Branch**, välj `main` (och `/ (root)`) och klicka på **Save**.
5. Efter ca 1 minut får du en publik länk (t.ex. `https://dittnamn.github.io/vinkallaren/`).
6. Skapa en QR-kod till den länken och fäst på trälådan!
