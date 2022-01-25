# cookies
Samler all info, retningslinje og sample kode relatert til informasjonskapsler for adb.


## Oppdatere JSON
- Sett opp en pullrequest med dine endringer så får vi testa jsonen før den merges inn.
- Benytt eksisterende format. 
- Dersom en cookie med samme id eksisterer med samme attributter, legg til navnet i lista over applikasjoner for cookien. 
- Dersom den eksisterer men din applikasjon har andre attributter, sjekk hvilken som er riktig. Hvis din f.eks har 2 år utløpsdato er din gammel versjon og id blir da cookienavn-old (typisk for _ga og _ga-old, der vi ikke har fått oppdatert levetiden på alle) 
- Har du en cookie som bør byttes ut eller fjernes, men ikke er helt der ennå - skriv "på vei ut" som en del av beskrivelsen. 
- Har du hatt en cookie som er fjernet, men som ikke nødvendigvis har blitt renset bort hos brukerene ennå (hvis ikke sletting er på plass), skriv "utgått" i beskrivelsen
- Det er også noen som bør omdøpes eller endre lagringsområde. Skriv i beskrivelsen hva de skal endres til senere. F.eks "byttes ut med"
- Alt er bedre enn ingenting. Har du ikke all data om en cookie? Legg inn det du har, så supplerer vi etterhvert! 
