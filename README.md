# Website Kosmetik - "Zeitlos Schön"

## Domain Setup:
- Provider: GoDaddy.com
- Domain: www.komsetikinstitut-zeitlos-schoen.de

## Hosting:
- Platform: GitHub Pages
- Repository: y0091797/zeitlos-schoen (github.io)
- HTTPS: Bei Gelegenheit aktivieren

## DNS-Einträge bei Cloudflare (Google-Konto):
- A-Records:
  - @ -> 185.199.108.153
  - @ -> 185.199.109.153
  - @ -> 185.199.110.153
  - @ -> 185.199.111.153

- CNAME-Record:
  - www -> y0091797.github.io
 
- DomainConnect:
  - _domainconnect -> _domainconnect.gd.domaincontrol.com

## SSL/TLS - Konfiguration
- Cloudflare
- Einstellungen [ Full / Full strict ]
- Zertifikatsausteller: Google Trust Services

## Cloudflare Einstellungen
- Always Use HTTPS: Aktiviert
- Cache leeren -> Bei Problemen

## Häufige Probleme
- Zertifikats-Fehler 526
- SSL Zertifkat nicht verfügbar

