
Deze 'fork' van de K3NG Keyer is gemaakt voor een groep PI4DEC leden dit project gemaakt hebben met de K5BCQ pcb.

Software documentatie staat hier:  https://github.com/k3ng/k3ng_cw_keyer/wiki

Hardware documentatie staat hier: https://www.qsl.net/k5bcq/Kits/Keyer.pdf

De gebruikte PCB:
<p><a target="_blank" rel="noopener noreferrer" href="https://tweakers.net/ext/f/6bzPBrxRlagxyuC68xlKo4fC/full.jpg"><img src="https://tweakers.net/ext/f/6bzPBrxRlagxyuC68xlKo4fC/medium.jpg" alt="K5BCQ - PCB" style="max-width:100%;"></a></p>   
<p></p> 


De PCB kan besteld worden bij K5BCQ :  https://www.qsl.net/k5bcq/Kits/Kits.html
<p></p> <p></p> 
Het schema:
<p><a target="_blank" rel="noopener noreferrer" href="https://tweakers.net/ext/f/elTAO6eseECHqjtvumKuSjQS/full.jpg"><img src="https://tweakers.net/ext/f/elTAO6eseECHqjtvumKuSjQS/medium.jpg" alt="Schematic" style="max-width:100%;"></a></p>   

Tijdens het bekijken van het schema vonden sommige PI4DEC leden de functie van R23 (100 ohm) in het audio input circuit raadselachtig. In het schema is dit aangegeven als een zgn. Goertzel Filter, R23 parallel met C6 (0.1uF). De aanwezigheid van R23 hier lijkt nutteloos of zelfs foutief omdat deze de biasspanning op analoge ingang A0 omlaag trekt. Normaal is deze bias spanning 1/2 Vcc of 2.5 volt. Omdat R23 i.c.m. potmeter R8 een DC pad naar massa geeft zal de bias onder 2 volt gaan, afhankelijk van de stand van R8.
<p></p>

We hebben wat testen gedaan met en later zonder R23 terwijl potmeter R8 halverwege stond. Bij drie verschillende boards bleek dat het weghalen van R23 positief uitwerkte op de decodeer eigenschappen. Daarom raad ik aan om R23 niet te monteren of indien reeds geplaatst deze te verwijderen. R23 op deze plaats is nutteloos en doet meer kwaad dan goed.



A 3D-PRINT BOX for the keyer:

<p><img src="https://github.com/costonisp/CW-keyer-K3NG-K5BCQ/blob/master/k5bcq.jpg" alt="3D prototype box" style="max-width:100%;"></a></p> 

Dit is het 3D geprintte prototype v/h kastje, niet erg mooi geprint maar de maat is goed en de print met display past exact.


The files voor ket kastje en de deksel staan op Tinkercad.com

Hastje: https://www.tinkercad.com/things/8LZc6XmkHG3-box-for-k3ng-k5bcq-cw-keyer

Deksel : https://www.tinkercad.com/things/4jNfGvMzsKl-lid-on-box-k3ng-k5bcq-keyer


Werk in uitvoering..........
