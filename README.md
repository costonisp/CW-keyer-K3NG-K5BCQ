# K3NG - K5BCQ cw_keyer
<p><a href="https://github.com/costonisp/k3ng_cw_keyer/blob/master/Nederlands.md">Link  naar de Nederlandse Readme file.</a></p>

This fork of the K3NG Keyer is prepared for a group of PI4DEC members who made this project with K5BCQ hardware.
The software documentation is located here:  https://github.com/k3ng/k3ng_cw_keyer/wiki


The hardware documentation can be found here: https://www.qsl.net/k5bcq/Kits/Keyer.pdf

The used PCB:
<p><a target="_blank" rel="noopener noreferrer" href="https://tweakers.net/ext/f/6bzPBrxRlagxyuC68xlKo4fC/full.jpg"><img src="https://tweakers.net/ext/f/6bzPBrxRlagxyuC68xlKo4fC/medium.jpg" alt="K5BCQ - PCB" style="max-width:100%;"></a></p>   
<p></p> 


The PCB can be ordered from K5BCQ here:  https://www.qsl.net/k5bcq/Kits/Kits.html
<p></p> <p></p> 
The schematic:
<p><a target="_blank" rel="noopener noreferrer" href="https://tweakers.net/ext/f/elTAO6eseECHqjtvumKuSjQS/full.jpg"><img src="https://tweakers.net/ext/f/elTAO6eseECHqjtvumKuSjQS/medium.jpg" alt="Schematic" style="max-width:100%;"></a></p>   

When studying the schematic, we at PI4DEC were suspicious of the use of R23 (100 ohm) in the audio input circuit, the so called Goertzel Filter, where it is parallel to C6 (0.1uF). It does not look right to have a resistor at this place because it will pull the bias voltage at analog input A0 lower. Normally this bias voltage should be 1/2 Vcc or 2.5 volt. Because of the DC path to ground over R23 and potmeter R8 (20K) the bias will go below 2 volt depending on the setting of R8.
<p></p>

So we have tested de decoding circuit with and without R23 while potmeter R8 was set halfway. It appeared that removing R23 worked positively out on the decoding quality. So we advice to not use or remove resistor R23



A 3D-PRINT BOX for the keyer:

<p><a target="_blank" rel="noopener noreferrer" href="https://tweakers.net/ext/f/4uz7q5ou7S5ftBeucGr7EiRL/full.jpg"><img src="https://tweakers.net/ext/f/4uz7q5ou7S5ftBeucGr7EiRL/medium.jpg" alt="3D prototype box" style="max-width:100%;"></a></p> 

This is the 3D-box prototype, not very beatifull printed but it fits very well.
<p><img src="https://tweakers.net/ext/f/EGXxkDKps2yvm56MR3zzpouV/full.jpg"></P>

The files for this 3D box for this keyer can be found on Tinkercad.com

The BOX : https://www.tinkercad.com/things/8LZc6XmkHG3-box-for-k3ng-k5bcq-cw-keyer

The LID : https://www.tinkercad.com/things/4jNfGvMzsKl-lid-on-box-k3ng-k5bcq-keyer



THIS PAGE IS A WORK IN PROGRESS.
