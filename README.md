# HABOVKA 3D – Hra s reálnou mapou

3D hra v prehliadači (Three.js), ktorá sa odohráva v **skutočnej Habovke**: cesty, potoky, domy, súpisné čísla a ulice pochádzajú z OpenStreetMap. Všetko je v jednom súbore `index.html`, beží aj offline a nepotrebuje inštaláciu.

## Herné módy (10)
| Mód | Čo robíš |
|---|---|
| **Rozvoz balíkov** (Kuriér) | Rozvoz na skutočné adresy, séria za včasné doručenie. |
| **Dobrovoľní hasiči** (Misia) | V dedine horia stodoly. Naber vodu v potoku, uhas oheň a nenechaj zhorieť 3 stodoly. |
| **Útok zombie** (Nočná Habovka) | Nočná dedina v hmle, odrážaj zombíkov vidlami (tlačidlo ÚDER, kláves F). |
| **Habovské štvorkolky** (Jazda) | Sadni na štvorkolku a preleť dedinu. NITRO a tútanie. |
| **Útek pred medveďom** | Medveď ťa prenasleduje po zraku. Zajdi mu z dohľadu za dom alebo do lesa a stoj potichu, alebo ho nasýť 3 syrmi (tlačidlo HODIŤ SYR), vtedy odíde. Potom príde ďalší, rýchlejší. |
| **Krumplová brigáda** (Minihra) | Zbieraj zemiaky a nos ich na vlečku traktora, kým beží čas. |
| **Dedinská premávka** | Zbieraj oštiepky a uhýbaj štvorkolkám, ktoré jazdia po skutočných cestách. |
| **Rozvodnená Habovka** | Ako premávka, no lúky zaplavuje voda a berie život. |
| **Splašené stádo** | Jelene sa rútia lúkami, červený pás varuje. |
| **Nočný návrat ku kostolu** | Noc a náhodný štart. Dôjdi ku kostolu skôr, ako vyprší čas, uličky bez východu ťa stoja čas. |

## Ďalšie funkcie
- **Živá dedina:** sliepky, ovce, dedinčania, traktor, dym z komínov, prach spod nôh a kolies.
- **Hudba a počasie:** folklórna 8-bitová melódia (dá sa vypnúť), počasie Deň / Súmrak / Noc / Dážď / Zima.
- **Kamera a grafika:** 5 pohľadov (zhora, klasika, blízko, za chrbtom, 1. osoba), priblíženie, sklon, zorný uhol, citlivosť, ľavák, kvalita grafiky, počítadlo FPS.
- **Terén:** kopce ovplyvňujú rýchlosť (do kopca pomalšie). Výšky sú **modelové**, nie namerané (zdroj skutočných výšok zatiaľ chýba).
- **Názov ulice a číslo domu** popri ktorom bežíš (z OSM).
- **Zdravie:** červené lekárničky (+45 HP) sa objavujú pri cestách a šípka ❤️ ukáže najbližšiu, keď máš pod 70 % zdravia. Halušky dávajú +30 HP a po 7 s bez zásahu sa zdravie pomaly dorastie do 50 %.
- **Ukladanie:** každý mód má vlastné uloženie, automaticky každých 6 s a pri pauze. Po smrti uloženie ostane a na konci hry môžeš pokračovať (aspoň 60 % zdravia, −15 % skóre). Uloženie je len v tomto zariadení a prehliadači (`localStorage`).

## Ovládanie
Ľavý palec = pohyb, pravý palec = kamera, tlačidlá 🎥 + − = pohľad a priblíženie. Na PC: WASD / šípky, Q / E kamera, C pohľad, + / − priblíženie, Shift šprint, F akcia.

## Spustenie
Otvor `index.html` v prehliadači, alebo ho zverejni cez **GitHub Pages** (Settings → Pages → Deploy from a branch → `main` / root).

## Dáta a licencia
Mapové dáta © prispievatelia OpenStreetMap (licencia ODbL). Cesty, domy a potoky sú skutočné, výšky domov a tvary striech sú odhad.
