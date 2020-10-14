Instruktioner:

(Kolla videon först)

1) Vi har en breakpoint på 500px.
2) Vid denna breakpoint blir vår navigation en kolumn och författarnamnen dyker upp. Tips: elementet <span> är ett inline-element som lämpar sig för att markera upp en bit text.
3) Vid denna breakpoint dyker ett meddelande upp ("Attention! ...").

Tips 1: Det är en vit border mellan navigationslänkarna, hur hade du löst detta? Ett förslag är att ge alla border-right förutom det sista.
Tips 2: Bilderna i navigationen är placerade som bakgrundsbilder.
Tips 3: Angående span (ta en titt på exemplet nedan).
Tips 4: När navigationen blir en kolumn - vad händer med border-right då?

<p>This is <span class="red">som red text</span></p>
.red { color: red; }