# pg6301-innlevering-Sakelig
pg6301-innlevering-Sakelig created by GitHub Classroom

## Oppgave tekst:

Denne innleveringen er anbefalt, men ikke påkrevd for å ta eksamen (PG6301 har ingen obligatoriske øvelser)

Dersom du gjør innleveringen vil du få verdifull input og kontroll opp mot eksamen. Innleveringen skal gjøres parvis. Det er tillatt og anbefalt at man samarbeider med andre par for å hjelpe hverandre.

Målet med innleveringen er at man skal kjøre en webapplikasjon på skytjenesten Heroku. Applikasjonen skal være en quiz der brukeren får et quiz-spørsmål og skal velge riktig svar.

Applikasjonen skal vise at dere behersker:

Parcel
React
React Router
Jest
Github Actions
Coveralls
Express
Heroku
Oppsummert:

Få en Parcel til å bygge en React applikasjon
Få React Router til å navigere rundt i applikasjonen
Få React til å hente og lagre informasjon til et API
Få Github Actions til å kjøre Jest-testene og publisere coverage til Coveralls
Få Heroku til å publisere websidene
Express-serveren skal ha følgende API:

GET /api/question - returnerer et tilfeldig spørsmål med { id, category, question, answers }
POST /api/question - tar inn { id, answer } og returnerer "true" eller "false"
Dere kan ta utgangspunkt i følgende eksempel på spørsmål, men dere må endre på formatet som returneres til klienten slik at klienten ikke vet hvilket alternativ som er riktig: https://quizapi.io/ (Lenker til en ekstern side.)

For å få vurdert innleveringen dere løse den med følgende GitHub classroom og alle gruppedeltagerne skal levere link i Canvas: https://classroom.github.com/a/lCmgaF2I (Lenker til en ekstern side.)

 ### Client side
 * [ ] Create a react app with parcel
 * [ ] Make react app run as expected /w parcel
 * [ ] Configure babel so that the react app runs properly with jest and babel
 * [ ] Make first passing test
 * [ ] Set up github actions
 * [ ] Connect coveralls with github actions and make a badge
 * [ ] Get status badge saying tests is passing
 * [ ] Get status badge from coveralls
 * [ ] Let coveralls read tests with jest --coverage

### Server side
 * [ ] Make server listen to port 3000
 * [ ] Running express server
 * [ ] Let server serve react app
 * [ ] Fetch questions from /api/question
 * [ ] Make a post request that match the random question from GET and return true or false
 * [ ] Make score stored with cookies
