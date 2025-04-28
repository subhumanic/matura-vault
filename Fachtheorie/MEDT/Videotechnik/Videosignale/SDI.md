#numbers 

Kodierung: NRZI = Non Return To Zero Inverted -> 1 = Pegeländerung
Amplitude: 800 mV

![[Pasted image 20250427172440.png]]

#### Wertebereiche bei HD SDI
Y und Cb/Cr werden parallel zu je 10 bit in 20 bit Wort abgebildet
-> 20bit (Y Cb) -> 20 bit (Y Cr) -> 20bit (Y Cb) ...

Wertebereiche: 0-3 und 1020-1023 für Steuerwörter (zb Zeilensprung)
(kinda inconsistent wenns 20bit Wörter sind dann werden die Wörter ja von Steuerwörtern unterbrochen bei 1020-1023)

![[Pasted image 20250427173632.png]]

#### Signalqualität

Worauf zu achten ist:
- Störungen/Noise -> Rise und Fall-Time an den Flanken
- Jitter (Fluktuation)
- 800 mV Amplitude
- Overshoot unter 10%
- Frequenzbereich
- Intervalldauer

![[Pasted image 20250427174245.png]]

