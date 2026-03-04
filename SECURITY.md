# Security Policy

Beveiliging is een topprioriteit voor YNG.

## Vulnerability Reporting
Heb je een beveiligingslek gevonden of een kwetsbaarheid ontdekt? 
- Stuur direct een e-mail naar: security@yng.nl.
- Open **geen** publieke issues voor kwetsbaarheden om misbruik te voorkomen.

## Richtlijnen
- **Secrets:** Commit nooit `.env` bestanden, API-keys of wachtwoorden naar de repo. Gebruik hiervoor de `.gitignore`.
- **Dependencies:** Houd de `package.json` up-to-date en draai regelmatig een audit (`npm audit`).
- **Privacy:** Gebruikersdata wordt vertrouwelijk behandeld en niet gedeeld met derden.

## Disclosure
We streven ernaar om binnen 48 uur op meldingen te reageren. We vragen je om kwetsbaarheden niet publiek te maken voordat er een fix beschikbaar is.