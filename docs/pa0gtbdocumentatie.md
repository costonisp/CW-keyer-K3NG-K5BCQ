### Arduino voor radioamateurs__ Deel 10  - - (door Cor Struyk paogtb@veron.nl)

# K3NG – CW Memory Keyer met CW Decoder

Het afgelopen jaar ben ik door vele Radio-Amateurs benaderd met de vraag of er naast de eerder gepubliceerde aparte CW decoders en de CW Keyboard-Keyer, ook iets gecombineerd zou kunnen worden.
Welnu, dat was iets waar ik zelf ook al langer naar uit keek, om een goed ontwerp met “alles in een” te vinden, wat voldoende gedocumenteerd was en ook geschikt voor nabouw

Al langer was ik bezig om informatie te verzamelen op basis van het CW Keyer ontwerp van K3NG Waarvan diverse varianten op basis van een Arduino Nano of een Arduino Mega2560 te vinden zijn.
Veel ontwerpen gaan echter alleen uit van het CW keyer concept zonder aandacht te schenken aan de CW decoder. 
De meeste ontwerpen op basis van een Arduino Mega2560 zijn ook gebaseerd op het principe van een extra shield met knoppen en aansluitingen voor een normale morse sleutel en/of Paddels met hierbij een PS2-keyboard
aansluiting voor de instellingen van de geheugens of om CW te verzenden.

### Het K3NG zelfbouw ontwerp van Kees, K5BCQ
Eind 2018 viel mijn oog op het concept “Big CW Keyer K3NG” van Kees, K5BCQ, die bezig was om een zelfbouwproject te ontwikkelen op basis van het K3NG Memory Keyer principe, maar waarbij alle opties die maar mogelijk zijn op dit concept, inclusief zouden zijn.

Het basisontwerp van K3NG bestaat uit een op Arduino gebaseerde CW (Morse Code) keyer. Het betreft een zeer flexibel opgezet ontwerp met veel opties, wat echt kan concurreren met vergelijkbare commercieel verkrijgbare producten. Omdat het op basis van de Arduino Open Source code is gebaseerd, kan het volledig op de individuele wensen van gebruikers worden afgestemd.
Kees, K5BCQ, ontwierp voor het totaalconcept, met alle mogelijke opties, een dubbelzijdige printplaat waarop alles onderdelen, inclusief de Arduino Microcontroller en een keuze uit divers3e afmetingen displays, is voorzien.
Ik had het geluk dat ik als een van zijn Beta-testers mocht fungeren !  Ik heb 2 versies van het totaal-concept gebouwd, met nu dit definitieve ontwerp als eindresultaat.

### De opties welke in dit zelfbouwproject K3NG keyer zijn inbegrepen, bestaan uit :

    • CW-snelheid instelbaar van 1 tot 999 WPM. 
    • Maximaal zes selecteerbare zender sleutellijnen. ( waarvan 2 uitgevoerd op de print) 
    • Programmering en interfacing via USB-poort ("command line interface") 
    • USB of PS2 toetsenbord interface voor CW toetsenbord operatie zonder een computer. 
    • Logging en Contest Program Interfacing via K1EL Winkey 1.0 en 2.0 interface protocol emulatie.
    • Command Line Interface (CLI) 
    • PTT-uitvoeringen met instelbare lead-, tail- en hangtijden. 
    • LCD Display aansluiting. 16x2, 16x4 en 20x4 LCD displays zijn mogelijk.  Zowel parallel als I2C bus aansluiting. 
    • Tot 12 geheugens met macro's. ( 7 met knoppen uitgevoerd op de print)
    • Het gebruik van Serienummers. ( bv voor Contesten).
    • CW toetsenbord (via een terminal server programma zoals Termite of de Arduino Serial monitor). 
    • Snelheid instelbaar met een “Rotary Encoder”. Snelheid is ook instelbaar met commando's QRSS en HSCW. 
    • Baken en  Fox modus. 
    • Iambic A en B. 
    • Diverse morse sleutel modus instellingen( standaard, Ultimatic, Iambic, etc..)
    • CMOS Super Keyer Iambic B Timing. 
    • Paddle reverse. 
    • Hellschreiber modus (toetsenbord verzenden, geheugen macro, baken) Farnsworth Timing. 
    • Instelbare frequentie-sidetone.  
    • Command modus voor het gebruik van de paddel om instellingen te wijzigen, programma herinneringen, enz. 
    • Keying Compensation. 
    • Dah naar Dit ratio aanpassing. 
    • Diverse CW oefen modus. 
    • Geheugen stapelen. 
    • "Dead Operator Watchdog". 
    • Automatische spatie instelling
    • Woordspatie instelling. 
    • Voorgeprogrammeerde en zelf instelbare Prosigns
    • Opslag van alle gemaakte instellingen
    • Blijvende opslag van de meeste instellingen. 
    • CW Ontvangst Decoder met Goertzel Filter.
    • Slaapstand. 
    • USB-muis ondersteuning. 
    • Mayhew LED Ring Support Alfabet Verzendpraktijk. 
    • USB-toetsenbord HID (Human Interface Device) Interface (Keyer = toetsenbord voor uw computer)
    • 3x4 of 4x4 toetsenbord voor diverse toepassingen  
    
### Hardware opbouw van het K5BCQ ontwerp

**H**et hele ontwerp is opgebouwd rondom een kleinere versie  van de Arduino Mega2560, namelijk de Arduino Mega2560 Pro Mini. | ![](Arduino2560Mini.jpg)
----------- | --------------


Deze verkleinde uitvoering is qua capaciteit en mogelijkheden gelijk aan zijn grote broer, de Mega2560.  Van deze versie Arduino, bestaan meerdere uitvoeringen. Alleen de “Zwarte printplaat” 
uitvoering van bijvoorbeeld Robotdyn, met mini-USB aansluiting is de juiste versie.  Let daar op als je dit project gaat bouwen !.

<u>Opmerking </u> : 
Er zijn ook aanbiedingen op diverse websites te vinden, waarbij de benodigde dubbele Pin headers al in de levering zijn inbegrepen. Een kwestie van even verder kijken dus.

### Het Schema

![](schema.jpg)

In bovenstaand schema, zijn alle benodigde onderdelen en aansluitingen zoals deze voor de printplaat benodigd zijn ingetekend.

### De printplaat

![](printplaat.jpg)
