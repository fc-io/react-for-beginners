# React kurs

## Intro

### React is aweseome

### Om mig, vad jag gjort

### Disclaimer – Jag ska försöka att inte slänga mig med för många tekniska termer. Men det är svårt. Så säg till om det är något term ni inte förstår.

### Vad de ser fram emot med kursen?

### Vad har de gjort tidigare?

### Vad vi ska gå igenom i kursen

* React! Och bibliotek som behöver för att använda react effektivt.
* Node
* NPM
* Även git och github.

### Intro-föreläsning: Vad är react?

* Varför?
* Jämför med jQuery/"vanilla jasvscript".
* Snabbare template generator (men jag förstår att ni inte riktigt har koll på vad templates är, det är något som nästan dött ut som concept, det var ett annat sätt att generera "vyer")
* när vi kommit in i det lite mer, ska jag gå igenom lite mer hur react fungerar bakom kulisserna
* Visa exempel på sidor som använder react.

### Intro-föreläsning: Vad är node

Ytligt. Hur det funkar senare – different imports (commonjs vs es6)

### Intro-föreläsning: Vad är npm

Ytligt. Kommer med node.

### När react:

* React is the best tool for many things, but not all the things
* Vad löser ramverk som react? Påbyggnad på varför från ovan.
* What makes front-end exiting?/One of the problems with front-end.
* All the moving parts node vs deno vs bun. npm vs yarn vs pnpm vs npx.

### Fråga om vilka Editors de använder?
### Vad de använder för operativsystem?
### Vikten av det viktigaste är att lära sig att lära sig själv

### Verktyg
Jag vill att ni lär er använda de verktyg, som jag och alla andra programmerare använder sig av för att hitta lösningar när vi inte kan.

YouTube
Stack overflow
Documentation

ChatGPT/Github copilot

Det här är är inte fusk. Och ingen programmerare oavsett nivå ska känns sig dum för att minnet brister. Oavsett om det är gällande något basalt eller något avancerat.

### Om arbetsmarknaden
* efterfrågan på react-kunskap
* hur man tar sig dit om man vill jobba med react – första jobbet ("oftast") det svåraste,
* vad som behövs mer utöver den här kursen

### När man får jobbet – Imposter syndrom
* varför det är viktigt att känna till?
* Hur man övervinner

# Uppgifter – alla som jag går igenom ska ni också göra själva i någon form.
## Vecka 1 basics + html/css + interaktivitet 1

React basics

Ge dem en färdig-generad setup, som kan köras i browsern med hjälp av någon browser editor, för att börja snabbt med react.

### A. Hemuppgift

Fundera ut en superenkelt react program som du skulle vilja göra eller som redan finns eller

Exempel. Fröken ur. Vecka.nu (som uppdaterar vecka utan omladdning), Räkna ut många bokstäver/tecken/ord som finns i en text. (Miniräknare och TODO först stort förutom för väldigt ambitiös student)

Lägg till en commit med 3 alternativ som du rankar.

### B. Hemuppgift

Hitta en designstil som du vill insperars från i din app. Förslagsvis från något på dribbble.

Lägg till en map till ert repo, men bilder på stilen. Om ni vill ha olika stilar beroende på vilken idé ni i slutändan väljer lägg i olika mappar.

### C. Hemuppgift

Några enkla grejer som kräver enbart html och css/style kunskaper. Plus onClick and OnHover.

## Vecka 2 node + npm + interaktivitet 2
### A. Visa
Installera node
Skada en .js fil som skriver ut ditt namn i terminalen när du kör den genom node. Förklara olika typer av print outputs och

Installera chalk (https://www.npmjs.com/package/chalk), och ge ditt namn någon rolig färg

Installera senate versionen av GitHub.
Skapa funktioner som kan skriva ut din version av GitHub, npm och node och vad else vi behöver.

Skapa en funktion som skapar en readme.md fil.

skapa ett repo, commita, och ladda upp inklusive generard fil. Publikt repo. Gör mitt publikt också så de kan gå tillbaka.

### B. Hemuppgift.

Skapa en funktion som generar datum + tid. Och Lägger till det till din fil när du kör ditt program.

Och därefter en funktion som också skapar en html-fil som har samma innehåll.

### C. Visa

State, props, useState, useEffect

### D. Visa

Någon uppgift som använder state, props, useState, useEffect.

## Vecka 3 – editors + build tools

Gå igenom några olika byggverktyg. Rekommendera 1 som alla använder sig av.

Gå igenom packade.json

Gå igenom bra editor/libs för att validera och skriva kod.

### A. Visa

Visa något exempel på en enkel app, och hur flödet fungerar med byggverktyget, commita, och publisera till github pages.

Visa/Gör om html-filen från tidigare till att använda react.

Publisera till Github pages

## Vecka 4:a – CSS i React

### A. Visa

Några exempel på hur css kan användas. Fördelar, nackdelar.

### B. Hemuppgift.

Bygg er idé från ##1. Försök återspegla den design ni hittade från dribbble.

## Vecka 5 – API 1 + intro datatyper (eller kanske bara intro till datatyper) + interaktivitet 2.

Prata om refaktorering, dry och och varför komponenter är en core feature med react. Skapa ett nytt repo (bättre för repition). Dra ner/forka kod från gamla repot (förklara forka, och varför man här vill/inte vill göra det).

Skapa en intro/hemsida som kan länka till sub-projekt.

Visa hur man skapa och länka ett domännamn. (Inget de behöver göra)

Visa några publika avier.

Förklara skillnader mellan rest och GraphQL.

Visa något exempel som använder arrays/listor och hur det kan användas i react för. Förklara/repetera olika typer av lopar. Förklara varför For each och While är dåligt. Nämn lite om funktionell programmering.

### B. Hemuppgift.

De får göra något som använder ett api. Och som behöver att man använda loopar.

Klicka för att hämta, el. dylikt för att få in interaktivt.

### C. Hemuppgift.

Lägg till en loading spinner.

Publisera!

## Vecka 6 – APIer 2 – olika bibliotek för att fetcha data. Redux/react-qry/apollo/relay etc.
## Vecka 7 – Routers, transitions – Mer egna uppgifter, nivå todo eller dylikt
## Vecka 8 – Mer egna uppgifter. Repetition och förtydliganden av concept. "Avancerade concept" som concurrency, use transition,
## Vecka 9 – Ev. server side rendering. Next.js, remix och andra. Mer egna uppgifter
## Vecka 10 – Mer egna uppgifter. Slutprojekt.



---
Övriga uppgifter: någon där de får modifiera redan existerande kod
Dynamiska formulär
Skapa regex med gtp-3/copilot. Exempel för email, och eftersom ett sådant regex kan vara svårt att förstå. Skapa några manuella tester
Auth, men känns lite för mycket




