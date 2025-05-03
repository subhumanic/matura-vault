Wir nehmen Schall nicht linear sondern ~ logarithmisch wahr
deshalb wird Schall meist in Form von dB angegeben, wobei dB eine Verhältnis Angabe ist
-> gibt an wie sehr sich ein Signal zu einem anderen Signal verändert hat
-> braucht daher eine Bezugsgröße

Lautstärke / Lautheit -> Psychogröße, auf Wahrnehmung des Menschen bezogen, in Audiotechnik also wenig relevant
### dB mit verschiedenen Bezugsgrößen
(siehe auch [[Feldgröße vs Energiegröße]])

- dB(A) -> a-gewichteter Schalldruckpegel, Bezug: 20 $\micro P$
- dBSPL -> Schalldruckpegel, Bezug: 20 $\micro P$
- dBu -> Spannung, Bezug: 0.775 V
- dBV -> Spannung, Bezug: 1 V
- dBm -> Leistung, Bezug:  1 mW
- dBW -> Leistung, Bezug: 1 W
- dBFS -> digitaler Pegel, 0 dBFS -> Vollaussteuerung am Ausgabegerät


![[Pasted image 20250503140349.png]]

### Umrechnung Größe -> Pegel
![[Pegel 2025-05-03 14.06.02.excalidraw]]

### Nennpegel
Pegel auf das eine Ausgabegerät ausgelegt ist
Europa (Studio): +4dBu
Consumer: -10dBV

### digitaler Pegel
dbFS = dB Full Scale
0 dBFS -> Vollaussteuerung am Ausgabegerät

-> Überpegelung -> Clipping (Knackgeräusche, Verzerrungen)
-> Aufnahmen immer auf -3 bis -6 dBFS pegeln

#### Clipping-Anzeige (OVER)
entweder RMS oder PEAK

**RMS** = Root Mean Square -> effektiv Wert
gibt an ob avg. Pegel über gewissen Zeitraum >= 0dBFS ist
Quadrat der einzelnen Werte -> Durchschnitt -> Wurzel
siehe auch [[RMS vs LUFS]]

**PEAK**
mind. 2 Samples in Folge haben überpegelung