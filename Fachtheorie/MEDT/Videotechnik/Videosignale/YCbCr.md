
sowohl Farbmodell als auch [[Komponentensignal]]

Y = Helligkeitswert
Cb = Differenz aus Blau und Helligkeit
Cr = Differnez aus Rot und Helligkeit

Konvertierung von RGB zu YCbCr siehe [[Farbkonvertierung]]

### Komponentensingal
ITU Standard ITU-R BT.709

- Y: 74,25 MHz
- Cb, Cr: 37,125 MHz (weil 4:2:2)
- 24,25,30,50,60 FPS
- 1080 16:9 oder 720 16:9
- Quantisierungstiefe: 8 oder 10 Bit
- 4:2:2 Unterabtastung
- 16-235 Wertebereich (bei 8 bit) (Farben 16-240?)
- Sync-Signal im Headroom

Abtastung bei 4:2:2
![[Pasted image 20250427171449.png]]

### Unterschied zu YUV (laut Chat)

**YUV**

- Kommt ursprünglich aus dem analogen Fernsehen.
- **Y** steht für Helligkeit (Luminanz, also wie hell/dunkel ein Pixel ist).
- **U** und **V** enthalten die Farbinformationen (Chrominanz).
- Idee: Das menschliche Auge ist viel empfindlicher für Helligkeit als für Farbe → spart Bandbreite, wenn man Farbe weniger genau speichert.
    

**YCbCr**

- Kommt aus der digitalen Welt (z.B. JPEGs, Videoformate).
- Ähnlich aufgebaut: 
    - **Y** ist wieder Helligkeit. 
    - **Cb** ist der Unterschied zwischen Blau und Helligkeit.
    - **Cr** ist der Unterschied zwischen Rot und Helligkeit.
- YCbCr ist also eine digitale Version von YUV, mit kleinen mathematischen Anpassungen.