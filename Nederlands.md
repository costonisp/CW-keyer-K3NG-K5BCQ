
Deze 'fork' van de K3NG Keyer is gemaakt voor een groep PI4DEC leden die dit project gemaakt hebben met de K5BCQ pcb.

Software documentatie staat hier:  https://github.com/k3ng/k3ng_cw_keyer/wiki

Hardware documentatie staat hier: https://www.qsl.net/k5bcq/Kits/Keyer.pdf

De gebruikte PCB:
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/pcb_layout.jpg"><img src="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/pcb-thumbnail.jpeg" alt="K5BCQ - PCB" style="max-width:100%;"></a></p>   
<p></p> 


De PCB kan besteld worden bij K5BCQ :  https://www.qsl.net/k5bcq/Kits/Kits.html
<p></p> <p></p> 
Het schema:
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/Schematic_BIG-Keyer_Sheet-1_20190329121109.pdf"><img src="https://tweakers.net/ext/f/elTAO6eseECHqjtvumKuSjQS/medium.jpg" alt="Schematic" style="max-width:100%;"></a></p>   

Tijdens het bekijken van het schema vonden enige PI4DEC leden de functie van R23 (100 ohm) in het audio input circuit raadselachtig. In het schema is dit aangegeven als een Goertzel Filter, R23 parallel met C6 (0.1uF). De aanwezigheid van R23 hier lijkt nutteloos of zelfs foutief omdat deze de biasspanning op analoge ingang A0 omlaag trekt. Normaal is deze bias spanning 1/2 Vcc of 2.5 volt. Omdat R23 i.c.m. potmeter R8 een DC weg naar massa geeft zal de bias onder 2 volt gaan, afhankelijk van de stand van R8. 
<p></p>

We hebben wat testen gedaan met en later zonder R23 terwijl potmeter R8 halverwege stond. Bij drie verschillende boards bleek dat het weghalen van R23 positief uitwerkte op de decodeer kwaliteit. Daarom raad ik aan om R23 niet te monteren of indien reeds geplaatst deze te verwijderen. R23 op deze plaats is nutteloos en doet meer kwaad dan goed.



Een 3D-PRINT BOX voor de keyer:


<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/photo-1.jpg"><img src="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/photo-1tn.jpg" alt="3D prototype box" style="max-width:100%;"></a></p> 

<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/photo-2.jpg"><img src="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/photo-2tn.jpg" alt="3D prototype box" style="max-width:100%;"></a></p> 
Dit is het 3D geprintte kastje, de deksel is met een primer-spuitbus gespoten.


The files voor ket kastje en de deksel staan op Tinkercad.com

Kastje   : https://www.tinkercad.com/things/8LZc6XmkHG3-box-for-k3ng-k5bcq-cw-keyer


<p><img src="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/images/deksels.jpg" alt="3D prototype box" style="max-width:100%;"></a></p> 
Indien de as van de rotary encoder te kort is gebruik dan deksel2 met een groter gat, zodat een 14mm diameter knop verzonken op de as past.

Deksel-1: https://www.tinkercad.com/things/4jNfGvMzsKl-lid-on-box-k3ng-k5bcq-keyer

Deksel-2: https://www.tinkercad.com/things/jEVnRsXiihz-lid-big-hole-k3ng-k5bcq-keyer

In de rand v/h kastje zijn gaten voorzien waarin deze draadbussen passen:

https://www.conrad.nl/p/bopla-gewindebuchsen-dodge-m3x65-draadbus-messing-messing-1-stuks-540005

Zodat het deksel met M3 boutjes vastgezet kan worden.
