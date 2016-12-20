#Design element#

[Här](theme-selector) kan du välja ett tema.

##Dark structure##

**Uppfyllda krav:** 4, 7, 9, 6

Här använder jag en bakgrundsbild som upplevs strukturellt. Dessutom så använder jag borders för att fördela innehåll och ge min egen touch till sidan. Alltind är centrerad och så har jag keyframes som ändrar opacity. Så ser den ut:

    @keyframes opacity {
        from {opacity: 1}
        to {opacity: 0.95}
    }

##Widescreen##

**Uppfyllda krav:** 3, 8, 10

Här använder jag ett foto som bakgrundsbild. Sidan sträcker sig över hela sidans bredd. Dessutom så har jag lyckats med att få bort massa med smabbfixa såsom **{max-width: 100%}**.

##Light-gradient##

**Uppfyllda krav:** 5

Här så finns det inte mycket att berätta, använder linear-gradient i min light tema. 
