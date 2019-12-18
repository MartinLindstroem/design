---
---
Rapport laddningstider
=======================

Den här rapporten är gjord som en uppgift i kursmoment 5 i kursen design. Uppgiftens syfte är att analysera laddningstiderna på tre olika webbplatser, jämföra dessa och se hur dem kan förbättras.

Urval
-------------------

Webbplatserna som valts för undersökningen är Ica.se, Coop.se och Lidl.se. Webbplatserna valdes eftersom dom är inom samma kategori, mat, och strukturen på hemsidorna är väldigt snarlika så att dom är lätta att jämföra.

Metod
-------------------

Metoden för att utföra undersökningen går ut på att besöka varje hemsida, ta upp devtools och network fliken för att mäta den totala laddningstiden, antalet resurser samt sidans totala storlek. Detta görs tre gånger på varje sida och sedan tas snittvärdet och dokumenteras i ett google kalkylark. Sedan körs varje webbplats i PageSpeed Insights för att se vilket värde dom får och även för att se vilka rekommendationer för förbättring varje sida får.


Resultat
------------------------

#####Ica

<img src="image/ica.png?w=500&h=300" alt="ica bild">

Länk till [ica.se](https://www.ica.se/)

Icas poängindex på PageSpeed Insights är 4 på mobil och 48 på dator.

Med devtools så visar det sig att hemsidan använder 162 resurser och den sammanlagda storleken på dessa resurser är på 5.1MB. Det tar i snitt 5.64 sekunder att ladda klart sidan.

Webbsidan skulle kunna förbättras genom att

#####Lidl

<img src="image/lidl.png?w=500&h=300" alt="lidl bild">

Länk till [lidl.se](https://www.lidl.se/sv)

Lidls poängindex på PageSpeed Insights är 25 på mobil och 83 på dator.

Lidl använder 244 resurser som sammanlagt är 4.0MB stora. Att ladda klart sidan tar i snitt 2.93 sekunder.

#####Coop

<img src="image/coop.png?w=500&h=300" alt="coop bild">

Länk till [coop.se](https://www.coop.se/)

Coops poängindex på PageSpeed Insights är 26 på mobil och 75 på dator.

Antalet resurser för coop ligger på 86 och den sammanlagda storleken för dessa är 4.1MB. Det tar i snitt 6 sekunder att ladda klart sidan.

Analys
----------------------

Efter att ha analyserat de tre webbplatserna så visar det sig att ica och coop ungefär har en lika lång laddningstid runt 6 sekunder, det skiljer sig i snitt enbart 0.2 sekunder medans lidl har en snabbare laddningstid på runt 3 sekunder.

De vanligaste förbättringsåtgärderna för detta urvalet av webbplatser verkar vara att ta bort resurser som blockerar renderingen, ta bort oanvänd css, skjuta upp inläsningen av bilder som inte visas på skärmen och skicka bilder i modernare bildformat.

Följande är en rangordning av webbplatserna baserat på deras prestanda:

1. Lidl (PageSpeed poäng: mobil: 25 | dator: 83)(Laddningstid: 2.93 sekunder)
2. Coop (PageSpeed poäng: mobil: 26 | dator: 75)(Laddningstid: 6.0 sekunder)
3. Ica (PageSpeed poäng: mobil: 4 | dator: 48)(Laddningstid: 5.64 sekunder)



[Länk till kalkylark med data](https://docs.google.com/spreadsheets/d/1UdGwyoNycmrCCDI1uPYRwggch0E_8BXygODGHP0-ja0/edit#gid=0)


Mina egna gränser för snabba webbplatser är nog runt 3 sekunder och under. Då känns den ganska snabb. Sidor som tar längre än 6 sekunder tycker jag oftast känns långsamma. Mitt urval av webbplatser klarar min gräns hyffsat. Lidl känns ganska snabb och även om coop tar runt 6 sekunder att ladda så ritar den upp hela sidan efter runt 3 sekunder och sedan tar den ytterligare någon sekund innan allt är laddat men det märks inte förutom om man tittar i network i devtools. Ica känns däremot lite på gränsen. Det är inte så att man blir irriterad men den känns inte snabb.

Övrigt
-------------------------
Rapporten är skriven av Martin Lindström
