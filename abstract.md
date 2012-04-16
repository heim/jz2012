Tittel: (bra om du kommer på noe kulere)
Å sette opp en prodserver er enkelt (og automatisk)

Til Abstract:
Er du lei av en lang og tung vei for å få applikasjonen din ut i prod? Ta kontrollen selv! Applikasjonsdrift behøver ikke være vanskelig, ihvertfall ikke hvis du har noenlunde vanlig webapp. Vi viser deg hvordan du kan sette opp et fullverdig prodmiljø for appen din og teste det ut lokalt på maskinen din, før du kan kjøre det ut på en eller flere ekte servere. I DevOps-ånd vil vi automatisere det hele i størst mulig grad med verktøy som VirtualBox, Vagrant og Puppet.

Til outline:
Vet ikke hva vi må fylle inn her men tenker på et program som ser ca ut som nedenfor. Syns alt bør foregå live hvis vi klarer det, alt blir så mye mye kulere da.

- Bakgrunn 
 - Vi utviklere er lei av at det skal være tungt å deploye applikasjonene våre
 - Nevne  eksempler fra egne prosjekter der vi vi har appdrift selv og hvordan vi syns det fungerer
 - Virtuelle miljøer og provisjonering, gjerne med clouddservere gjør at prodmiljøer for nye apper er enkelt å sette opp
- Vi har eller lager en enkel rails eller java webapp
 - kjører den opp lokalt
 - ønsker å få denne ut i et prodmiljø
- Vi starter med virtualbox og vagrant og får opp en prodlik server
 - Viser fram virtualbox og vagrant men har alt mest mulig klart lokalt slik at vi kan kjøre opp en server in no time
 - Vi setter opp puppet slik at vi kan provisjonere 
- Vi provisjonerer alt vi trenger til denne boksen. Feks, apache/nginx, my/postgres sql, java/ruby
 - gjør alt med puppet-manifests.
- Bruker et enkelt ferdig laget deploymentscript slik at deployment til serveren blir lett også
 - må kunne deploye sykt lett til serveren slik at vi kan deploye nye versjoner av appen vår, gjerne heroku style
- Når alt kjører fett på boksen provisjonerer vi dette til en cloud-server og lar appen kjøre der
(- tviler på at det blir tid, men hvis det blir det kan vi legge inn litt overvåkning av appen med feks nagios også)
- Til slutt viser vi ressurser
 - linker til bøker og rammeverk
 - link åpent github repo med alt vi nettopp har vist frem slik at alle kan prøve seg frem på egen hånd


Jeg tror vi har et par utfordringer, men at disse er overkommerlige:
- Vi er innom ganske mange rammeverk/teknologier som kan bli litt mye for folk. Vi får prøve å forklare kort hva alt er, og heller gjøre det klart at man som publikum ikke må skjønne alt 100%, men at prinsippet er at dette ikke er vanskelig eller behøver å ta lang tid.
- Hvis vi skal gjøre alt live kommer det nok til å bli en del venting når servere skal starte opp og ting skal installeres (provisjoneringen). Det kan hende vi kan løse dette ved å kjøre en del snakking imens de tyngste kommandoene skal gå, og gjerne svare på spørsmål fra salen.

Bare ring meg for avklaringer så sender vi inn det her!

