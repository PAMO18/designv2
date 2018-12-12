---
---
Rapport kmom05: Laddningstid
=========================

I denna rapport ska jag analysera 3 olika webbsidor och studera laddningstider och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag har valt följande webbsidor för att analysera:

1. [SVT](https://www.svt.se)
2. [Aftonbladet](https://www.aftonbladet.se)
3. [Eurosport](https://www.eurosport.se)

Jag valde dessa webbsidor eftersom de är väldigt populära nyhetssajter och har många bilder samt annat innehåll, tex. reklam, som kommer påverka laddningstider och användbarhet rejält.

Metod
-----------------------

För att kunna testa laddningstider ordentligt ska jag använda Google PageSpeed, Developer verktygen i Firefox samt MacOS skärmdumps verktyg.  Jag ska lagra mätningar i en Google kalkylark som länkas i rapporten.  Jag ska göra varje mätning i Firefox 3 gånger och rapportera sidans laddningstid, antal resurser och sidans totala storlek.

Resultat
-----------------------

Google kalkylark länk: **[Mätningar](https://docs.google.com/spreadsheets/d/1DAhrUQNe1doyvfWK64kvO4L92EHE9pFJsE_fngRGWD4/edit?usp=sharing)**

<h3 style="text-align: center; border-bottom: none">SVT</h3>

[FIGURE class="websites center" src=image/SVT.png?w=550]

SVT verkar ha en optimerad sida, fast den har många bilder och artiklar på första sidan så laddar den väldigt snabbt.  Webbplatsen kan förbättra sig genom att ta bort höger kolumnen som har mindre relevanta nyheterna, men sidan har råd med detta med redan snabba laddningstider.  Högst upp på listan av förbättringsmöjligheter, i desktop läge, på Google PageSpeed finns *”Defer offscreen images”*, vilket betyder att man inte behöver ladda bilder som är offscreen vilka användaren inte kan se.

<h3 style="text-align: center; border-bottom: none">Aftonbladet</h3>

[FIGURE class="websites center" src=image/Aftonbladet.png?w=550]

Aftonbladet är en tung sida att ladda och kan definitivt bli bättre.  Mindre reklam skulle hjälpa till eftersom dessa tar säkert 25-50% av innehållet och är stora bilder där vissa har små videoklipp som rullar kontinuerligt.  Högst upp på listan av förbättringsmöjligheter, i desktop läge, på Google PageSpeed finns *”Eliminate render-blocking resources, Resources are blocking the first paint of your page. Consider delivering critical JS/CSS inline and deferring all non-critical JS/styles”*.

<h3 style="text-align: center; border-bottom: none">Eurosport</h3>

[FIGURE class="websites center" src=image/Eurosport.png?w=550]

Eurosport laddar relativt snabbt och har inte så många resurser som aftonbladet, med det är reklam här med som tar mycket plats och resurser.  Sidan är också full av information så den skulle kunna förbättras genom att banta ned det som visas samtidigt på skärmen.  Högst upp på listan av förbättringsmöjligheter, i desktop läge, på Google PageSpeed finns *”Eliminate render-blocking resources”*.

Analys
-----------------------

När det gäller desktop betygen Google PageSpeed, så har alla sidor en ”fast” betyg, 90–100 poäng.  SVT och Aftonbladet är lika med 98 poäng följt av Eurosport med 92.  Om vi tittar på de mobila betygen så ser det väldigt annorlunda ut.  Bara en webbsida har en ”average” betyg, Aftonbladet med 60 poäng.  SVT är näst bäst med ett betyg på 41, ”slow”, föjlt av Eurosport på 26, ”slow”.  Så detta bevisar att alla webbsidor beter sig annorlunda på mobila enheter jämfört med desktop versionen, där alla är mycket sämre.

När man kollar på mätningar på Firefox, i desktop läge på MacOS, så ser vi att sidor med mindre resurser har bättre laddningstider.  SVT har den snabbast laddningstid, 3,24s, följt av Eurosport med 4,23s och sist Aftonbladet med 5,22s.  Antal resurser är i samma ordning där SVT har minst resurser.  Men en intressant detalj är sidans totala storlek, där Eurosport har den minsta storleken av alla.

Resultaten visar att alla webbsidor har bra och väl godkända resultat i desktop läge, där SVT laddar snabbast och har ett väldigt högt betyg från PageSpeed testet.  Men aftonbladet verkar har den snabbaste mobila sida med det högsta mobilbetyget på PageSpeed testet.  
Eurosport har mycket text och statistik samt många små och stora bilder, men känns ändå snabbt att bläddra igenom.  SVT har väldigt lite reklam och innehållet är för det mest stora bilder med lite text.  På Aftonbladet och Eurosport är det reklam som sticker ut mest, det här är den största förbättring dessa två sidor kan göra, minska antal reklam.  På den mobila fronten kan alla sidor göra bättre.  Eftersom alla sidor använder bilder så är bättre bildoptimeringen nödvändigt för att kunna leverera en snabb och användarvänlig upplevelse.

Bedömning
-----------------------

Nu ska jag rangordna webbplatserna baserat på deras mätvärden och utse en vinnare.

1.	**[SVT](https://www.svt.se)**
2.	[Eurosport](https://www.eurosport.se)
3.	[Aftonbladet](https://www.aftonbladet.se)

På mina mätningar så har SVT den snabbast laddningstiden och tar minst resurser samt är näst bäst när det gäller totala storlek.  Den känns snabb att bläddra genom och har minst reklam.  När det gäller Aftonbladet så är den sämst i mina mätningar på alla områden, men bäst, enligt Google PageSpeed, på mobila enheter.  För mig så vinner **SVT** med stora marginaler.

En accepterad gräns för laddningstider, enligt mig, är under 5 sekunder, men helst emellan 2-4s.  Kommer en webbsida över 5s så känns det segt och är oftast långsamt att bläddra igenom.  Så SVT och Eurosport har acceptabla laddningstider och även när man bläddrar igenom dessa två så känns de snabba.  Aftonbladet däremot har ej acceptabla laddningstider och är inte så rolig att bläddra igenom där mycket innehåll är reklam.

Övrigt
-----------------------

Denna rapport är skriven av:

Paul Moreland
