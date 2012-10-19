Master in progress
======

Skrevet av Even Stene og Marius Nedal Glittum

## TODO
Fremdriftsplan ligger på gdocs. Skal ha en fungerende prototype innen 15.desember

Vi ønsker å benytte GitHub som integrasjon, da GitHub har et stort og forholdsvis enkelt API å forholde seg til. 
Dette krever dog at testgruppen må ønske å bruke GitHub som versjonskontrollverktøy. GitHub er allerede et veletablert og mye brukt versjonskontrollsystem, noe mange allerede har vært borti, så dette burde ikke være. 

Tekniske valg: Benytter Grails til å lage en web-app som kan brukes på flere platformer. 

Funksjoner: Integrere PeacefulBanana med Git. Dette gjøres ved at brukeren redirectes til OAUTH siden til Github. Github returnerer oauth tokenet som vi da kan bruke på brukernes vegne til å hente ulike data som ligger på github. Dette være seg milestones/deliveries/commits/tags/labels osv osv. Utfordringen ligger i hvilken informasjon vi skal bruke og hvordan denne kan brukes for å promotere refleksjon. Hva slags data skal brukeren selv legge inn utenom github og hvordan skal denne deles/brukes for å promotere refleksjon. Ikke sikkert all informasjonen fra github er relevant for vårt prosjekt. Vi må velge hvilke deler vi skal bruke og hvordan. 
Teste applikasjonen som et utviklingsverktøy for smidige team i IT2901 faget på NTNU.   

Utfordringer i den eksisterende timeline appen: 1. Scaffolding, det er for generelt å ta notater. Man skriver hva som helst som ikke nødvendigvis hjelper til refleksjon.  
2. Koble data sammen for deling. Hva skal deles og når det er delt hva skal det brukes til som bidrar til refleksjon.  

