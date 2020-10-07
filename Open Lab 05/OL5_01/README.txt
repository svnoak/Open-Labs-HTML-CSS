Instruktioner:

1) Ni ska efterlikna de tre exempebilder som finns (A, B, C).
2) Ni kommer ha en färdig HTML-fil att utgå ifrån. Skapa sedan en CSS-fil per bild så att vi sedan kan enkelt skifta mellan dessa och se de olika varianterna.

Begränsningar:

* Ni får inte skriva "grid-template-columns/rows: 1fr 1fr 1fr ...", utan ni ska istället använder av någonting som heter "repeat", för att slippa skriva "1fr" flera gånger. Läs mer här: https://yoksel.github.io/grid-cheatsheet/#section-repeat
* I exempelbilderna B och C ser ni en yta mellan alla rutorna, denna görs med hjälp av "gap". Läs mer här: https://yoksel.github.io/grid-cheatsheet/#section-gap
* I exempelbild C så är det ingen scroll, här kan det vara bra att ha "box-sizing" i åtanke: https://www.w3schools.com/css/css3_box-sizing.asp

Notis: attributet "box-sizing: border-box;" gör så att ett elements höjd och bredd räknas _inklusive_ dess padding och border. Annars är det bara innehållet (text/bild) som styr höjd och bredd.