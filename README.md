# Pinguïn Plet

Een browserspel waarin je als pinguïn ijsblokken schuift om spookjes plat te drukken. Zet de vier diamanten op een rij voor een grote bonus!

**Speel online:** https://anneb.github.io/pinguinplet/

## Spelregels

- Duw een ijsblok weg: het glijdt door tot het ergens tegenaan botst en drukt onderweg spookjes plat.
- Meerdere spookjes met één blok levert steeds meer punten op (400, 800, 1600, 3200).
- Zit een blok vast, dan breekt duwen het ijs. Diamanten zijn onbreekbaar.
- Een level is gehaald als alle spookjes geplet zijn, of als de vier diamanten horizontaal of verticaal op een rij staan (+5000).
- Snel klaar levert een tijdbonus op. Elke 30.000 punten krijg je een extra leven.
- Spookjes die niet bij je kunnen, eten zich door het ijs heen.

Kies op het startscherm een moeilijkheid: Makkelijk, Normaal of Moeilijk.

## Besturing

| Actie | Toetsenbord | Joystick / gamepad | Mobiel |
|---|---|---|---|
| Lopen | Pijltjes of WASD | Stick, kruisje of hat-switch | Knoppen of vegen |
| Duwen / breken | Spatie | Elke knop | DUW-knop of tikken |
| Pauze | P of Esc | Start | |
| Geluid aan/uit | M | | Knop in de balk |
| Muziek aan/uit | N | | Knop in de balk |

Joystick: druk na het laden één keer op een knop, zodat de browser hem herkent.

## Lokaal spelen

Alles zit in één bestand zonder afhankelijkheden. Open `index.html` direct in de browser; een webserver is niet nodig. Geluid en muziek worden met de Web Audio API in de browser gegenereerd.
