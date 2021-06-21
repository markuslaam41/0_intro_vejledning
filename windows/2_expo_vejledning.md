# Opsætning af expo Windows - React native Mobil apps

#### En forudsætning for at kunne installere expo er at man hentet node
- Hent den anbefalede version(LTS) af Node ved at trykke på følgende link: https://nodejs.org/en/
- Du kan tjekke om du allerede har node ved at skrive `node -v` i terminalen. Hvis terminalen returnerer med en versionsbeskrivelse, er alt i orden og du kan hoppe til næste punkt i denne vejledning. 

####Anvend den officielle guide til at installere expo. Guiden findes på følgende link: https://docs.expo.io/get-started/installation/

- Når installationen er færdig, skal du hente expo app'en fra din AppStore.
 
- App-ikonet kan ses på billedet herunder:
  ![expo](billeder/expoIcon.png)


#### Nu er du klar til at lave dit første projekt! 
- Følg guiden der findes på følgende link: https://docs.expo.io/get-started/create-a-new-app/

#### Kør dit først expo projekt!
1. find den mappe du vil oprette dit første projekt, og træk den mappe ned i terminalen, så mappe navnet står til venstre prompten
   ![img.png](billeder/img.png)

2. Skriv nu `expo init projektnavn` og vælg blank
3. Find nu dit `projektnavn` og åben det i webstorm, og derefter i webstorms terminal kør
   `npm start`
   ![img.png](billeder/screenshot4.png)

4. Nu skal et vindue med expo intefacet åbne og tryk nu på tunnel i venstre side for at scanne din første app.
   ![](billeder/screenshot5.png)

5. resultatet skulle være at du skal se denne tekst `Open up App.js to start working on your app!`
6. Prøv at ændre i webstorm filen app.js og se teksten ændre sig
