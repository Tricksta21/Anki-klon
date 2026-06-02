# Språk-Anki Pro PWA

Mobilvennlig flashcard-app for kinesisk, koreansk og bengali.

## Inkludert
- PWA: kan legges til på hjemskjerm
- Offline etter første lasting
- Persistent lokal lagring via localStorage
- JSON backup/import
- FSRS-ish spaced repetition: stability/difficulty-basert
- Kinesisk pinyin + tonefarger
- Uttale/TTS for kinesisk, koreansk og bengali
- Eksempelsetninger + oversettelse
- Statistikker og streak
- Firebase sync-klargjøring

## Mobilbruk
Best:
1. Last opp mappen til Netlify, GitHub Pages eller Vercel.
2. Åpne URL-en på mobilen.
3. iPhone: Del → Legg til på Hjem-skjerm.
4. Android: meny → Install app / Add to Home screen.

## Firebase sync
Dette er inkludert, men må konfigureres av deg:
1. Lag Firebase-prosjekt
2. Aktiver Firestore Database
3. Sett web-app config i `firebase-config.js`
4. Deploy på nytt
5. Bruk samme Sync-ID på mobil og PC

NB: uten innlogging er Sync-ID som et delt passord. Ikke bruk sensitive data.
