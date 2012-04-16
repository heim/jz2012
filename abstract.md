Tittel: (bra om du kommer på noe kulere)
Sky-klar drift for utviklere!

Til Abstract:
Er du lei av en lang og tung vei for å få applikasjonen din ut i prod? Ta kontrollen selv! Applikasjonsdrift behøver ikke være vanskelig. Vi viser deg hvordan du kan sette opp et fullverdig produksjonslikt utviklingsmiljø for din applikasjon din og test det ut lokalt på maskinen din, før du kan kjører det ut i skya. 
I DevOps-ånd vil vi vise hvor raskt og smertefritt dette kan være. Stikkord er automatisering, infrastruktur som kode og automatisk deployment med hjelp av puppet for konfigurasjonsstyring, vagrant for lokal virtualisering og Amazon EC2 som prodmiljø. Vil du lære om hvordan du kan rigge infrastrukturen din for kontinuerlige leveranser? Da er dette foredraget for deg!

Til outline:

 Tidsplan:
 * Intro til teknologiene (10 min)
 * Oppsett av lokalt utviklingsmiljø (15 min)
 * Oppsett av prodmiljø (10 min)
 * Deployment av app (10 min)
 * Endring av app  og infrastruktur i prod (5 min)
 * Spørsmål fra salen


Expected auduence:
  Utviklere og driftere som ønsker å lære seg å styre infrastruktur med Puppet og produksjonssette kontinuerlig, eller som ønsker seg en introduksjon til Puppet generelt.
  Vi ønsker å vise deg hvordan man kan komme fra null til skya på èn kort time, hvor lett det er å endre eksiterende infrastruktur og hvordan lokal virtualisering av prodlikt miljø hjelper deg på veien til å levere kontinuerlig.


Equipment:

 Det er fint om vi kan få disponere to projektorer da vi gjerne vil vise flere ting samtidig.

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



