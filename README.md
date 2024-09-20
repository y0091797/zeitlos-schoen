# Website Kosmetik - "Zeitlos Schön"

## Domain Setup:
- Provider: GoDaddy.com
- Nameserver (by Cloudflare):
  - elmo.ns.cloudflare.com
  - jade.ns.cloudflare.com
- Domain: www.kosmetikinstitut-zeitlos-schoen.de

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

## SSL/TLS - Configuration
- Cloudflare
- Settings [ Full / Full strict ]
- Zertifikatsausteller: Google Trust Services

## Cloudflare Einstellungen
- Always Use HTTPS: activated
- Cache leeren -> for Troubleshooting

## Häufige Probleme
- certificate-error 526
- SSL-certificate not accessible

