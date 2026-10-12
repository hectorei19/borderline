# Borderline

Geography grid game: name a country or territory that matches each row and column (250 to choose from). Every grid is checked so it can always be completed, whatever answers are given.
Solo, pass-and-play on one phone, or online rooms (up to 4 phones) via Firebase Realtime Database.

Files:
- `index.html` – the whole game (country data and flags included).
- `firebase-config.js` – your Firebase web config (paste it in).
- `database.rules.json` – rules to paste in Firebase → Realtime Database → Rules.

## Credits

- Country data: [mledoze/countries](https://github.com/mledoze/countries) (npm `world-countries`), Open Database License (ODbL) 1.0. Adapted: some names shortened; a few borders, official languages, currencies and capitals corrected; Antarctica removed; "drives on the left" and "over 100 million people" lists added by hand.
- Flags: [flag-icons](https://github.com/lipis/flag-icons), MIT License.
- Fonts: Big Shoulders Display, Barlow Semi Condensed, JetBrains Mono (Google Fonts, SIL Open Font License).
- Online rooms: Firebase Realtime Database.
