[README.md](https://github.com/user-attachments/files/25869789/README.md)
# Secure Path

Interaktivní edukativní hra zaměřená na kyberbezpečnost, vytvořená jako maturitní projekt.

---

## O projektu

**Secure Path** je jednostránková webová aplikace (HTML/CSS/JavaScript) simulující vzdělávací hru, ve které hráč čelí reálným kybernetickým hrozbám a učí se na ně správně reagovat. Projekt vznikl jako součást maturitní práce na téma *Návrh počítačové hry v oblasti kyberbezpečnosti*.

Cílová skupina: žáci středních škol ve věku 12–19 let.

---

## Obsah hry

Hra obsahuje **5 modulů**, každý se **3 interaktivními scénáři** (celkem 15 otázek):

| Modul | Téma | Scénáře |
|-------|------|---------|
| 01 | Phishing | Podezřelý e-mail od banky, SMS od dopravce, Resetování hesla |
| 02 | Malware | Neznámá aplikace ke stažení, Makro v dokumentu, Oprávnění aplikace |
| 03 | Ransomware | Zašifrovaný počítač, Podezřelý soubor v archivu, Zálohování dat |
| 04 | Sociální inženýrství | Falešná IT podpora, CEO fraud, Tailgating |
| 05 | Hesla & účty | Volba hesla + 2FA, Správce hesel, Únik přihlašovacích dat |

---

## Funkce

- Postupné odemykání modulů — každý modul vyžaduje správnou odpověď k odemčení dalšího
- Okamžitá zpětná vazba s vysvětlením po každé odpovědi
- Kontextové widgety simulující reálné situace (e-mailový klient, SMS, systémová varování)
- Progress bar sledující postup v modulu i celkový postup hrou
- Závěrečná obrazovka se souhrnem splněných modulů
- Bez externích závislostí — spustitelné přímo v prohlížeči

---

## Technologie

- **HTML5** — struktura aplikace
- **CSS3** — layout (CSS Grid), animace, vizuální styl
- **JavaScript (Vanilla)** — herní logika, navigace mezi obrazovkami, stavový management
- **Google Fonts** — Rajdhani, Share Tech Mono

---

## Spuštění

Žádná instalace není potřeba. Stačí stáhnout soubor a otevřít v prohlížeči přes odkaz: https://arcanoxyz.github.io/securepath/

```bash
git clone https://github.com/your-username/secure-path.git
cd secure-path
# otevřít secure-path-final.html v prohlížeči
```

Nebo jednoduše stáhnout `secure-path-final.html` a otevřít dvojklikem.

---

## Struktura projektu

```
secure-path/
├── secure-path-final.html   # celá aplikace v jednom souboru
└── README.md
```

---

## Vizuální design

Aplikace využívá *dark terminal* estetiku inspirovanou prostředím příkazové řádky:

- Tmavé pozadí `#0c0e12` s akcentní modrou `#3db8ff`
- Typografie: **Rajdhani** (nadpisy) + **Share Tech Mono** (UI, kód)
- CSS Grid layout se striktním oddělením kontextu a voleb odpovědí
- Scanline overlay a ambientní gradientní osvětlení

Grafický design a prototyp byly vytvořeny ve spolupráci s nástrojem umělé inteligence **Claude** (claude-sonnet-4-6, Anthropic) prostřednictvím rozhraní [claude.ai](https://claude.ai).

---

## Autor

**Adam Běhávka**
Maturitní projekt 2026 — obor 18-20-M/01 Informační technologie
Academic School Uherské Hradiště
Vedoucí práce: Ing. Jakub Rak, Ph.D.

---

## Licence

Tento projekt byl vytvořen pro účely maturitní práce. Volné použití pro vzdělávací účely.
