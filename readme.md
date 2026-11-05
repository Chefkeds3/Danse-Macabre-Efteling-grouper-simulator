# 🎻 Danse Macabre - Grouper Simulator

Een interactieve webgebaseerde simulator en trainings-app voor attractieparkmedewerkers. Deze simulator simuleert het *groupen* (het optimaal indelen van bezoekers) op de 6 koorbanken van **Danse Macabre** in de Efteling.

---

## 🎯 Doel van het spel
Vul de **6 koorbanken** (elk met 3 rijen van 6 stoelen = 108 plaatsen in totaal) zo snel en efficiënt mogelijk met zo min mogelijk lege plekken. 

Je balanceert hierbij de instroom van **groepsgasten** uit de hoofdrij met **Single Riders (SR)** voor de overgebleven losse stoelen.

---

## ✨ Functionaliteiten

- **Tablet & Mobiele Weergave:** Muis- en touch-vriendelijke interface die schakelt tussen een tablet-dashboard en een mobiel overzicht.
- **Realistisch Wachtrijbeheer:** Zie direct de **1e actief wachtende groep** én een preview van de **2e groep in de rij**. 
- **Wisselen / Inhalen:** Laat de 2e groep de 1e groep passeren als deze beter past (maximaal **2 wissels per laadronde**).
- **Single Rider Beheer:** Voeg via de direct toegankelijke `+1 SR` knoppen per koorbank gericht Single Riders toe op de actieve rij.
- **Automatische SR Aanvulling:** Als een rij exact 5 bezette stoelen heeft, wordt de 6e stoel automatisch aangevuld met een Single Rider.
- **Live Stopwatch / Timer:** Houd precies bij hoe lang het duurt om een volledige laadronde van 108 plaatsen te voltooien.
- **Uitgebreide Statistieken:** Direct inzicht in het totaal aantal geplaatste groepsgasten vs. Single Riders en het bezettingspercentage.
- **Geluidseffecten:** Ingebouwde audio-feedback bij het plaatsen, wisselen en afronden (inclusief aan/uit-schakelaar).

---

## 🏆 "Grouper Precision" Puntentelling

Scoor zo hoog mogelijk door rijen slim en efficiënt in te delen:

| Actie / Prestatie | Punten |
| :--- | :--- |
| **Geplaatste Bezoeker** | `+10 pt` per geplaatst persoon (Groep of SR) |
| **Perfect Row Bonus** | `+25 pt` bonus als een rij van 6 exact vol raakt met *uitsluitend* groepsgasten (geen SR nodig) |
| **Single Rider Fix Bonus** | `+10 pt` bonus als een Single Rider precies de 6e (laatste) stoel van een rij opvult |

---

## 📐 Attractie Specificaties

- **Totaal capaciteit:** 108 zitplaatsen
- **Koorbanken:** 6 koorbanken (genummerd 1 t/m 6)
- **Capaciteit per koorbank:** 18 stoelen (3 rijen van 6 stoelen)
- **Actieve Rij Volgorde:** Rijen worden per koorbank van voren naar achteren gevuld (Rij 1 → Rij 2 → Rij 3).

---

## 🚀 Hoe te gebruiken?

1. **Direct openen:** Open het bestand `index.html` in een willekeurige moderne webbrowser (Chrome, Edge, Firefox, Safari). Geen build-stappen of afhankelijkheden vereist!
2. **GitHub Pages:** Upload de opslagstructuur naar GitHub en schakel *GitHub Pages* in via de repository-instellingen om de simulator direct via het web te spelen.

---

## 🛠️ Gebruikte Technologieën

- **HTML5 & Vanilla JavaScript** (ES6+)
- **Tailwind CSS** (via CDN)
- **Web Audio API** (voor synthetische geluidseffecten)
- **Google Fonts** (Cinzel & Inter)