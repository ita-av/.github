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
### [Uporabniki (REST API)](https://github.com/ita-av/user-service)
- Upravljanje uporabniških računov in avtentikacije
- Shranjevanje podatkov v lastni podatkovni bazi

### [Rezervacije (gRPC)](https://github.com/ita-av/booking-service)
- Upravljanje rezervacij (ustvarjanje, urejanje, brisanje)
- Shranjevanje podatkov v lastni podatkovni bazi


### Obvestila (Message Broker)
- Pošiljanje opomnikov in obvestil

## Shema
![ita_shema](https://github.com/user-attachments/assets/b0d9ce78-0a20-4dd3-90b4-7100284e92fc)
