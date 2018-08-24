# ideer-slutprojekt-js18

## Beskrivning

### Syfte

Syftet med det här repot är att samla idéer och förslag på eventuella slutprojekt.

Istället för att välja grupp först, och därefter besluta sig för vad gruppen ska ha för slutprojekt, kan det vara lättare att välja grupper utifrån vad alla är intresserade av att utveckla.

På så sätt undviker vi förhoppningsvis missnöjda gruppmedlemmar som känner att slutprojektet inte alls ligger i linje med vad hen vill göra.

Tanken är att alla här får lägga upp idéer och förslag – högt som lågt, lätt som svårt, möjligt som omöjligt – som alla sedan kan hjälpa till att spinna vidare kring.

### Intressanta projekt

Om man känner att ett projekt låter intressant får man gärna lägga till sitt namn under _intressenter_, och känner man att ett projekt inte längre är intressant tar man bara bort sitt namn. No hard feelings så klart, tanken är att hålla det så öppet som möjligt.

Tycker man att en idé låter intressant men känner sig osäker på om den ens går att genomföra, eller om man bara vill börja experimentera lite, får man gärna skapa ett repo för att börja testa sig fram. Lägg i så fall in en länk till repot för det projektet så att alla får tillgång till det.

### Spin-offs / contributions

Bygg gärna vidare på varandras projekt och idéer, men om någon/några har kommit en bit på vägen kan det vara klokt att fråga sig för innan ni pushar omfattande ändringar.

Om ett projekt börjar få en tydlig grupp (oavsett vem som kom på idén) är det fritt fram att skapa ett nytt repo på någon av era egna GitHub-konton för att driva projektet vidare.

### Gruppinfo

Lägg gärna till en kommentar under rubriken _grupper_ om ni har skapat en grupp och valt att driva projektet vidare inom gruppen.

Lägg in vilka som ingår i gruppen, och länka till er grupps projektrepo (för att vi andra ska kunna följa projektet, inte för att vi ska gå in och contributa).

Om några mot förmodan redan har skapat en grupp och ett projekt så får ni gärna lägga till det för allas vetskap. Ni behöver inte skapa en ny projektidé där ni beskriver ert projekt här, men lägg in gruppmedlemmar, projektnamn och länk under _grupper_.

### Övrigt

Tanken är att det ska vara fritt fram för alla att bidra som dom vill, helt prestigelöst och förutsättningslöst. Vill man bidra är man välkommen, vill man inte så tar ingen illa upp.

MIT License, så håll det öppet, ärligt och snyggt.

---

## Medverka

Välj mellan att:

1. Klona ned repot, lägg till ädringar i README.md, och pusha ändringarna till _master_ branch.
2. Ändra direkt i README.md här på GitHub.

```bash
git clone https://github.com/javascriptst18/ideer-slutprojekt-js18.git
cd ideer-slutprojekt-js18

# Sätt upstream första gången ni pushar med '-u'
git push -u origin master
```

Länktips:

[Markdown Cheatsheet - Hur man skriver markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

## Grupper

| Projektnamn                | Gruppmedlemmar                                    | URL                                              |
| -------------------------- |---------------------------------------------------| ------------------------------------------------ |
| DARE                       | Peder, Gustav, Johannes, Kajsa                    | [Projektlänk](https://github.com/javascriptst18) |
| Spel                       | Markus, Jens, Anton                               | [Projektlänk](https://github.com/javascriptst18) |
| Chat App                   | Vicente, Alan, Igor                               | [Projektlänk](https://github.com/javascriptst18) |

---

## Projektidéer

### 1. Nyhetsapp (exempel)

#### Beskrivning

En nyhetsapp där man kan välja att:

1. Läsa nyheterna som vanligt i ett nyhetsflöde (nyheter från ett API)
2. Få nyheterna upplästa (text-to-speech API)
   - Välj kategori (ekonomi, kultur, sport, etc.)
   - Välj antal nyheter att få upplästa (senaste 10, gårdagens mest lästa, etc.)
   - Välj med vilket intervall nyheter ska bli upplästa (ex. var 5 minut)

#### Länkar

Här är några länkar för inspiration, förslag på tekniker, ramverk, bibliotek, APIer, etc.

[![alt text](https://img.youtube.com/vi/ExVdnT1wqVk/maxres2.jpg)](https://youtu.be/ExVdnT1wqVk?t=3m45s 'J.A.R.V.I.S. App')

[News API](https://newsapi.org/)

[Google Cloud text-to-speech API](https://cloud.google.com/text-to-speech/docs/basics)

[Microsoft Azure text-to-speech API](https://azure.microsoft.com/en-us/services/cognitive-services/text-to-speech/)

[ResponsiveVoice.JS](https://responsivevoice.org/)

#### Intressenter

- Lägg till ditt namn här

#### Repos

Länka eventuella repos här om någon börjat bygga/testa/experimentera utifrån idén.

---

### 2. Ärendehanteringssystem

#### Beskrivning

En ärendehanteringsapplikation är man kan ta emot och hantera kundrelaterade cases

1. Ta emot, kategorisera och hantera kundcases
2. Man ska kunna ändra status på cases
3. Appen är kopplad till mail inbox
4. Inloggninssystem med olika roller/behörigheter (t.ex.: admin, manager, support, kund, mm)
5. Möjlighet att kolla på historiken samt olika rapporter om kundcases (responstid, lösning, mm)

#### Länkar

Här är några länkar för inspiration, förslag på tekniker, ramverk, bibliotek, APIer, etc.

[Fresh Desk](https://freshdesk.com)

[Zen Desk](https://www.zendesk.com)

#### Intressenter

- Vicente Tirado

#### Repos

Inte ännu

---

### 3. Öl-app från Brewdog

#### Beskrivning

(Det blir på engelska då jag skriver en dårlig mix av norsk och svenska, och for att det låter bättre..)

An app for Brewdog beer lovers! Either you like to drink or brew.

1. Search for your favourite beer based on several different parameters
2. Match with your favourite food
3. Find recipes to brew your favourite beer
4. Log in and become a part of a community where you can rate, comment and discuss beer in general, or maybe post your own recipe
5. ..and much more.

En liten pitch från mig där alltså.. man kan såklart utöka appen med flera funktioner om man hinner :)

Jag tänker fokusera på bra funktionalitet och att prosjektet är gjenomförbart.

#### Länkar

API: https://punkapi.com/documentation/v2

#### Intressenter

- Marie Honningdalnes

---

### 4. Goodreads för podcast

#### Beskrivning

En app för att registrera poddar och poddavsnitt man lyssnat på, där man kan skriva omdömen och sätta betyg, diskutera med andra osv. Som Goodreads är för läsning och TV Time för tv-serier.

Förfinar lite mer på idéen frammåt.

#### Intressenter

- Carl-Axel Hallgren
- Kajsa Lindholm

---

### 5. Non-dating app

#### Beskrivning

En app där man kan träffa folk utan att dejta, som känner av var jag är och jag kan skriva typ:

`Sitter på centralen, tåget är försenat och jag har en kortlek.`

`Jag tänkte ta en vända i elljusspåret men tycker det är lite otäckt när det är mörkt, sällskap sökes.`

`Har bokat teater, sällskapet magsjuk men biljetten betald.`

`Hjälper du mig att köra till tippen bjuder jag på middag.`

Sen kan man se alla inbjudningar som finns runt där man befinner sig.
Man ska kunna välja kön och mellan vilka åldrar.

#### Intressenter

- Namn här

---

### 6. Utflyktsapp

#### Beskrivning

En app som känner av var på kartan jag är, så kan jag fylla i om jag går, cyklar eller åker bil och hur lång tid eller hur lång sträcka jag vill förflytta mig.

Tex en timma eller 15 mil och då ser var jag hamnar då, i alla väderstreck. Man ska även kunna välja väderstreck.

Tycker den skulle vara användbar när man har husbil/husvagn och är på väg genom Europa, på tex Autobahn och vill köra i kanske två timmar, vart hamnar jag då?

Eller om man vill åka en sväng när man är på ett nytt ställe, för att se vart man hamnar på en timma eller 15 mil.

Eller om man är på ett nytt ställe och vill gå en hundpromenad eller ta en cykeltur på en timma och man inte känner till omgivningen.

Då ser man vart man hamnar, så man inte går och går och vips är man i ett industriområde.

#### Intressenter

- Namn här

---

### 7. Namnlös app

#### Beskrivning

Hade varit smart att ha en app där det hela går tillväga ungefär såhär.

- Skapa kategorier som passar i ens liv. Hushåll, hund etc.
- Fota kvittot, appen digitaliserar texten.
- Själva delandet av kvittot fungerar med enkelt "drag & drop". Dvs man klickar på raden som lyder ex "Tomater 1 kg 26kr" och drar å släpper sen den över vilken kategorii man vill att den utgiften ska hamna i. Kanske även så att raden med tomater då försvinner från kvittot? Så att man enkelt ser vad man sorterat och inte.

#### Intressenter

- Namn här

---

### 8. Migrändagbok

#### Beskrivning

Migrändagbok/Humördagbok/Smärtdagbok på svenska

#### Intressenter

- Namn här

---

### 9. App för lästa böcker

#### Beskrivning

En app där jag enkelt kan lägga till de böcker jag redan har läst. De appar jag har sett idag bygger på köphistorik, dvs då kommer inte alla med, bara de från denna site.

Förslag på vad jag kanske vill läsa utifrån vad jag läst.

#### Intressenter

- Namn här

---

### 10. Global Reseplanerare

#### Beskrivning

En bokningsapp för alla tåg (eller andra transportsätt förutom flyg) i Europa. Har inte letat så noga men det senaste har jag hört om många som tycker att det är väldigt krångligt att ta sig runt i Europa om man inte vill flyga.

#### Intressenter

- Namn här

---

### 11. Carbon Footprint / Klimatapp

#### Beskrivning

En app som jämför och håller koll på klimatavtrycket av saker man gör och köper. Jag tror vi alla måste lära oss mer att värdera klimatavtryck på samma sätt som vi värderar våra pengar. Typ hur mycket co2 motsvarar en bok, en öl, en taxiresa etc.

Informationen finns säkert därute, men vore så användbart att alltid ha detta tillgängligt och väl presenterat i appform.

#### Intressenter

- Namn här

---

### 12. Parkeringsapp

#### Beskrivning

Tror du skulle kunna tjäna pengar på en app som samlar ihop alla olika jäkla parkeringsappar i en och samma. Så kan man betala och sköta allt via en app istället för en massa olika

#### Intressenter

- Namn här

---

### 13. App för schema / planering

#### Beskrivning

Schema app för skola/vardag/arbete uppbyggt av bildstöd. Även med stöd för timstock.
Fördjupning: om man väljer ett lektionspass i skolan så ser man även vad man förväntas göra på den lektionen.

Stöd för kamera för att kunna fota in uppgifter.

Tänkt målgrupp: yngre barn med behov av extra stöd, träningsskolor, gruppboenden osv.

#### Intressenter

- # Namn här

* Carl-Axel Hallgren (Dock inte om målgrupp är barn, mer intresserad av en app för den professionella)

---

### 14. App för recept

#### Beskrivning

En app där man kan spara sina recept som man googlat fram. Nu sparar man ju oftast ett bokmärke till länken men man tappar tyvärr många recept när sidor flyttas eller bloggar läggs ner. (liknande ska vara Stowr eller Paprikaapp)

#### Intressenter

- Namn här

---

### 15. Event app

#### Beskrivning

En app som märker ut events på en karta i närheten av användaren eller på sökt plats.
Det här alltså samma event app ide som min grupp hade under UX dagarna.

Möjliga api:er att hämta event data från:
tickster.com (api nyckel finns)

#### Intressenter

- Felipe

---

### 16. What's Beef

## Beskrivning

En applikation som kategoriserar och listar alla aktuella fejder mellan kändisar som pågår. Man ska kunna enkelt se fejdens ursprung, när den senaste händelsen ägde rum och vad det handlade om. Man ska även kunna se de senaste fejderna samt de äldsta fejderna samt de längst pågående. Gärna med en horisontell tidslinje där man enkelt kan få en överblick över händelseförloppet. Man ska kunna klicka sig vidare på en av dessa kändisar och se relaterade fejder samt vilka fejder som denne kändis mer är med i. Bonus är om varje fejd har _"shade points"_ där varje inloggad användare kan rösta på hur pass infekterad fejden är.

#### Intressenter

* Jesper Orb

---
