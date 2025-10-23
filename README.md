# Reflektion

### Afstand

Jeg har igennem projektet fået vildet mig ud i lidt for rodet måder at skabe spacing mellem elementer. Jeg skulle istedet have lavet nogle konkrete regler dog gjorde jeg ikke det til at starte med da jeg i Figma syntes at afstandende varierede meget selvom det var mellem de samme elementer. Kunne blandt andet havde gjordt brug af flow.

### Layout

Jeg har valgt at bruge grid column minmax() til at skabe mit layout og give specifikke elementer lov til at "breakout". Dog syntes jeg igen her jeg gjorde det for rodet for mig selv da jeg bare kunne have lavet sådan et layout i layout filen istedet for i en section wrapper på hvert astro element.

### Grid, flex og subgrid

Jeg har benyttet alle tre og syntes ikke det gav mig nogle problemer i andet end Hero'en på forsiden. Her har jeg bl.a. også et problem med mit p elements text i li elementerne stopper for tidligt og kunne ikke finde en løsning på det.

### Brug af selectors og pseudo elementer

Jeg har brugt selectors så vidt muligt frem for class og syntes det er gået udemærket. Dog har jeg fundet ud af at det kan blive lidt kaotisk når man nester for meget eller har for mange af samme slags element til samme stylesheet. Derudover har jeg benyttet ::before og ::after for at skabe de figurer i baggrunden som skulle bruges nogle steder.

### Brug af container queueries

Jeg syntes godt min brug af container queueris kunne være bedre især fordi jeg for det meste bare har fået lavet min section som alligevel fylder 100% af width til en container også er det jo ikke meget anderledes end en normal media query. Havde jeg haft mere tid havde jeg lavet nogle wrappers til der hvor container queieries kunne havde givet mening fremfor hele skærmens width.

### Brug af custom properties og variabler

Jeg syntes brugen af custom properties og variabler giver meget god mening selvom de selvfølgelig overhovedet ikke er det samme.

### @layer

Fik desværre ikke gjordt brug af viden om cascade layers da jeg kom i tanke om det for langt inde i processen. Kan dog se hvordan det havde gjordt det næmmere at style visse elementer.

## Afrunding

Alt i alt syntes jeg min færdige udgave matcher figma designet rimeligt godt dog syntes jeg bestemt der er ting jeg kunne have gjordt bedre/smartere
