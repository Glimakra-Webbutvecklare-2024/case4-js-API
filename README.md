# case4 js API

## Introduktion
I caset ska ni arbeta individuellt och skapa en applikation (webbsida) som visualiserar data som hämtas från ett API. Applikation ska visualisera data som kan hämtas via ett API som ni själva väljer.

Att visualisera data innebär i praktiken att ni med HTML, CSS och JavaScript ska skapa ett dynamiskt galleri med det innehåll från det API ni väljer.

Det ska vara en applikation som har header, footer, nav och andra lämpliga sematiska element. Första gången applikationen visas ska den fungera som en landningssida som hanterar sökningar. Sidan ska också ha en genomgående design som passar till det API ni väljer. 

## Val av API
Ni väljer helt själva API:et. Ni kan välja ett som ni hittar på nätet men här finns några ni kan undersöka.

- https://api.nasa.gov/, NASAs API
- https://api.openweathermap.org/, OpenWeatherMap API
- https://api.unsplash.com/, Unsplash API
- https://pokeapi.co/, Pokemon API
- https://www.thecocktaildb.com/api.php, The Cocktail DB
- https://swapi.dev/, Star Wars API

## Grundläggande Krav
- Applikationen ska vara responsiv och fungera på **både desktop och mobil**.
- Applikationen ska vara en SPA (Single Page Application) och använda sig av JavaScript för att byta ut innehåll utan att ladda om sidan. Användaren upplever olika sidor men i bakgrunden är det en enda sida som skiftar innehåll (view).
- Applikationen ska ha en header, footer, nav och andra lämpliga sematiska element.
- Applikationen ska ha en landningssida som hanterar sökningar.
- Applikationen ska ha en view som visar resultatet av sökningen.

## Utmaningar
- Applikationen ska ha en view som visar en detaljerad beskrivning av ett objekt.
- Applikationen ska ha en loading spinner medans data hämtas.
- Applikationen ska stödja någon form av inställningsbar sortering. (T.ex Bokstavsordning, datum, antal, etc)

## Design Krav
- Applikationen ska ha en genomgående design som passar till det API ni väljer.
- ...

## Namngivningsprinciper när du kodar
använd latinska tecken för variabelnamn och funktioner (camelCase)
skriv kommentarer med egna ord i din kod (så vi vet att ni förstår er egen kod)
korrekt formaterat kod

## Om koden i applikationen
Applikationen får inte använda externa ramverk, utan det är "vanilla" JavaScript och CSS som gäller. Dela upp struktur, innehåll, design och logik. Använd externa filer för CSS och JavaScript.

## Så börjar du
Skapa ett privat repo på GitHub och koppla det till din lokala utvecklingsmiljö. Under projektet - senast 1 februari bjuder du in dina lärare. Se Settings -> Manage access -> Add people

Bjud in följande användare till ert case repo:

- frozenbanana (Henry)
- andsju (Anders)
- addkolon (Mattias)

## Inlämning och redovisning
- Preliminärt datum för redovisning av caset är den 13 februari kl 08:45. Feedback följer under vecka 7.
- Caset ska finnas färdigt i ett Gihub repo i samband med redovisningen
- Tänk på att inte visa console.log() i ett färdigt projekt.

Förbered 5 minuters redovisning enligt följande mall:

- visa wireframes skisser
- demonstrera applikationen
- visa exempel på annan funktionalitet (ex ngn av utmaningarna)
- berätta vad du är mest nöjd med (design, kod, struktur...)
- berätta vad du skulle vilja att applikationen kan göra, men inte hunnit att koda
- redovisning sker i bokstavsordning (förnamn A-Ö)
