# IT Arhitekture: Sistem za rezervacijo terminov v brivnici

## Funckionalnosti
- Upravljanje uporabniških računov (stranke in brivci)
- Rezervacija, spreminjanje in odpoved terminov
- Avtomatsko pošiljanje opomnikov pred dogovorjenim terminom

## Uporabniki 
### Stranke (končni uporabniki)
- Registracija in prijava v uporabniški račun
- Rezervacija obiska
- Prejemanje opomnikov pred terminom

### Brivci
- Pregled prihajajočih rezervacij

## Storitve
### Uporabniki (REST API)
- Upravljanje uporabniških računov in avtentikacije
- Shranjevanje podatkov v lastni podatkovni bazi

### Rezervacije (gRPC)
- Upravljanje rezervacij (ustvarjanje, urejanje, brisanje)
- Shranjevanje podatkov v lastni podatkovni bazi


### Obvestila (Message Broker)
- Pošiljanje opomnikov in obvestil


