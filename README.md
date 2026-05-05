README

ArkadMaskin - Starkeeper
Syftet med projektet var att skapa en fristående mini-arkadmaskin som startar direkt i ett Unity- utvecklat spel vid uppstart av Raspberry Pi. 
Spelet är ett retro-inspirerat tower-defense där spelarna styr Tycho Brahe och försvarar observatorier Stjärneborg mot kosmiska fiender.

Målen vi skulle uppnå:
Skapa ett fullt fungerande arkadspel i Unity
Integrera spelet med fysisk styrning (joystick och knappar) 
Programmera Raspberry Pi för automatisk uppstart i spelet

Namn och Ansvarsområde
Isac Strandeus: Programmering och byggande av Raspberry Pi så den kan starta spelet direkt vid uppstart, Koppling av elektronik och sammanställning med högtalare, joystick, knappar, och externa delar utanför raspberry Pi. Programmering i Unity. Skrev hela README. 
Lisa Cato:  Programmering och byggande av Raspberry Pi så den kan starta spelet direkt vid uppstart, Koppling av elektronik och sammanställning med högtalare, joystick, knappar, och externa delar utanför raspberry Pi. Planering i Trello. Koppling mellan Raspberry Pi och Unity. Programmering i Unity
Rodi Mhafal: Störst insats och ansvar när de gäller programmeringen i Unity. Hjälpte i slutet av koppling mellan Raspberry Pi och Unity
Junie Prompaeng: Designa Cutscene och ritade gubbarna, turrets, torn och bakgrund. Programmerade lite i Unity. 

Star Keeper är ett retroinspirerat tower defense-spel utvecklat i Unity och byggt kring en fysisk arkadmaskin driven av en Raspberry Pi. Projektet kombinerar spelutveckling, hårdvaruintegration och retrodesign i ett och samma system – från kod och grafik till joystick och knappar.
Spelupplevelsen kretsar kring astronomen Tycho Brahe, som efter en kosmisk katastrof strandsätts på en okänd planet. Spelaren försvarar sin position mot fiendliga varelser genom att strategiskt placera ut torn, samla resurser och ta sig igenom allt svårare fiendevågor. Målet är att samla tillräckligt med resurser för att reparera rymdskeppet och fly planeten.
Tekniskt är projektet uppdelat i två delar. I Unity byggs spellogiken: en spelkarta med torn och fiender, ett HUD med liv och poäng, menyer samt ett komplett game over-flöde. Spelet optimeras för att köras stabilt på Raspberry Pis begränsade hårdvara. Den fysiska styrningen – joystick och knappar – kopplas in via Raspberry Pi och mappas direkt mot spelets kontroller, vilket ger en äkta arkadkänsla.
Raspberry Pi är konfigurerad för att starta direkt i spelet vid uppstart, utan synligt operativsystem. Leaderboard-data sparas i en databas, vilket ger ett återkommande inslag av tävling och motivation att förbättra sin poäng.
Projektet riktar sig till elever, lärare och teknikintresserade med ett öga för retrokultur men även såklart mot Tycho Brahe – och syftar till att visa hur modern spelutveckling kan möta klassisk arkaddesign i ett handhanterat, inbyggt system.


KOM IGÅNG
Förutsättningar
För att kunna spela spelet på själva Arkadmaskinen krävs ingen extern nerladdning eller liknande då allting ligger på Raspberry Pi. Om man vill köra de på datorn behöver man endast filerna och en python server. Man öppnar de endast genom powershell och sedan skapar sin python server så kan man spela.

Installation
Inga övriga installationer krävs

Step by Step för att köra spelet
1. Ladda ner filerna: Bild, TemplateData, Index.html
2. Öppna filen som innehåller alla 3
3. Tryck ner Shift och högerklicka
4. Öppna Powershell window
5. Skriv: python -m http.server 8000
6. Öppna valfri sökmotor
7. Skriv in länken: http://localhost:8000
8. Färdigt!

Externt material
Länkar i punktform med beskrivning till andra dokument (Google-drive, Trello, mm)
- Trello: https://trello.com/b/fM3Ga6tq/tillampad - Planering
- Dokument: https://docs.google.com/document/d/17cRBFX9_B3-d3m9HAzIyR7b5t-AhF5J3w9hHzCbXibw/edit?tab=t.0 - Första planeringen och annan information
-  Dokument: https://docs.google.com/document/d/10rnT_yb4GYDgjbrDVRlDqcuBoNok8ey4doVd2WC6K0M/edit?tab=t.0#heading=h.udyri2d3zgch  -  gya loggbok för raspberry pi kiosk läge
