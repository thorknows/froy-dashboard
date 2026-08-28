# Frøy dashboard

Komplett, statisk dashboardprototype for Frøy. Hele løsningen ligger i `index.html`:

- logo som innebygd SVG
- designsystem og responsivt oppsett
- alle sju dashboardfaner
- hardkodede dashboarddata med Snowflake som kilde
- CSS og JavaScript uten rammeverk eller byggetrinn

## Åpne løsningen

Du kan åpne `index.html` direkte i nettleseren.

For lokal server:

```bash
python3 -m http.server 8000
```

Åpne deretter `http://localhost:8000/froy-dashboard/` dersom serveren startes fra mappen over prosjektet, eller `http://localhost:8000/` dersom den startes inne i prosjektmappen.

## Claude Code

Pakk ut ZIP-filen, åpne mappen i terminalen og start Claude Code derfra. Dashboardet har ingen avhengigheter som må installeres. Alle data som vises i løsningen er samlet i `index.html`.

Eksterne nettadresser i filen er kun klikkbare lenker til relevante Frøy-artikler. De brukes ikke til å laste dashboardets design, logo, kode eller data.
