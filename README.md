# HABOVKA 3D – Skutočná mapa (Veľká Oravská Edícia)

3D WebGL hra s reálnou mapou obce **Habovka** (Orava, Slovensko) postavená na knižnici **Three.js** a dátach z **OpenStreetMap**.

## 🎮 Herné módy
1. **Prežiť štvorkolky (Normal):** Vyhýbanie sa splašeným štvorkolkám a traktorom na dedinských cestách, zbieranie oštiepkov, eur a halušiek.
2. **Prežiť plavisko (Hard):** Na lúkach a poliach sa rozlievajú plaviská, ktoré hráča spomaľujú a uberajú život.
3. **Jelene na lúke (Extreme):** Stáda splašených jeleňov prebiehajúce cez obec, červené varovné pásy a rýchly úskok.
4. **Útok zombie (Survival):** Nočná dedina v hmle. Zombíci vyliezajú z polí a idú po hráčovi. Tlačidlom **ÚDER / VIDLY** (`F`/`E`) sa brániš.
5. **Habovské štvorkolky (Jazda):** Sadni priamo na štvorkolku! Rýchla jazda dedinou (až 24 m/s), drift v zákrutách na Blatnej a tlačidlo **NITRO**.
6. **Útek pred medveďom (Smrekovica):** Rúti sa za tebou hladný medveď zo Smrekovice. Tlačidlom **HODIŤ SYR** odhadzuješ návnady na jeho spomalenie.
7. **Krumplová brigáda (Minihra):** Na poli pri Blatnej zbieraj zemiaky (krumple) a odnášaj ich na vlečku traktora Zetor na čas!
8. **Rozvoz balíkov (Kuriér):** Doručovanie objednávok na skutočné súpisné čísla a ulice Habovky na čas.
9. **Nevojsť do slepej uličky (Impossible):** Nočný orientačný beh ku kostolu cez reálnu sieť ciest s penalizáciou za slepé uličky.

## 🏔️ Oravská atmosféra a novinky (Balíky A & B)
- **Originálny oravský bačovský skin:** Goralský klobúk so stuhou a pierkom, košeľa s výšivkou, kožuštek (lajblík), bačovský opasok a krpce.
- **Živá dedina & NPC:** Sliepky pobehujúce popri cestách, ovce pasúce sa na lúkach a dedinčania pri plotoch s vtipnými oravskými hláškami.
- **Traktor Zetor s vlečkou:** Pomalý zelený traktor s nákladom sena premávajúci po obci, dymiaci výfuk a hlboký klaksón.
- **Časticové efekty:** Stúpajúci dym z komínov dreveníc a chalúp, kúsky prachu spod nôh a kolies štvorkolky.
- **8-bitová folklórna hudba:** Chiptune melódia *"Na Orave dobre, na Orave zdravo"* s možnosťou vypnutia v nastaveniach.
- **Počasie:** Voľba počasia v nastaveniach (Deň, Súmrak, Noc, Dážď s kalužami, Zima so snehom).

## 💾 Ukladanie (Save systém)
- Automatické ukladanie do `localStorage` každých 10 sekúnd a pri pauze.
- Každý mód má vlastné uloženie (postup, skóre, vzdialenosť, inventár).

## 🚀 Spustenie
Hra je úplne samostatná v jednom súbore `index.html`. Stačí otvoriť v ľubovoľnom prehliadači:
```bash
python3 -m http.server 8080
```
A otvoriť v prehliadači `http://localhost:8080`.
