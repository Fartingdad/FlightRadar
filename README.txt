FLYGRADAR – iPhone
===================

Detta är en lokal, mobilanpassad webb-app/PWA som visar flyg runt din position.

SNABBASTE SÄTTET PÅ IPHONE
1. Packa upp ZIP-filen i appen Filer.
2. För stabil GPS behövs HTTPS eller localhost. En ren file://-öppning kan blockera platsåtkomst i Safari.
3. Kör mappen med en lokal webbserver-app på iPhone, exempelvis en app som kan servera filer på localhost.
4. Öppna localhost-adressen i Safari.
5. Tryck Dela > Lägg till på hemskärmen.

ALTERNATIVT, ENKLAST I PRAKTIKEN
Lägg filerna på en kostnadsfri statisk HTTPS-värd, till exempel GitHub Pages eller Cloudflare Pages. Appen körs fortfarande helt i webbläsaren och behöver ingen egen backend.

FUNKTIONER
- GPS-baserad radar
- Valbar radie 5–250 nautiska mil
- Koncentriska radarringar
- Klickbara flygplanssymboler
- Callsign, ICAO-hex, registrering, flygplanstyp, höjd, fart, kurs, vertikalhastighet, squawk och avstånd
- Automatisk uppdatering var 10:e sekund
- Airplanes.live primärt, ADSB.lol som reserv
- Installerbar som PWA

BEGRÄNSNINGAR
- Internet krävs för kartplattor och flygdata.
- Datatäckningen beror på ADS-B/MLAT-mottagare i området.
- Datakällorna är externa och kan ändra CORS, begränsningar eller villkor.
- Airplanes.live anger max 250 NM och högst 1 förfrågan/sekund. Appen frågar normalt var 10:e sekund.
- Avsedd för informations- och hobbybruk, inte navigation eller flygsäkerhetskritisk användning.
