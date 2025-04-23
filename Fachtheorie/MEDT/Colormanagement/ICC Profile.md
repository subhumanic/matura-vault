
ICC = International Color Consortium

![[Pasted image 20250420211320.png]]

**Profilklassen:**
- Named Color (Vollton)
- Colorspace
- Device Link
- Input
- Output
- Display

## Matrix

Matrix-Profile sind 3x3 Matrizen zwischen denen transformiert wird.
Es werden Weißwert und Primärvalenzen  (siehe [[CIE Normvalenz]]) definiert.

Wobei jede Reihe der Matrix eine Primärvalenz definiert und sich der Weißwert aus der Summe der Primärvalenzen ergibt -> Farbtemperatur ist also schon in Primärvalenzen einberechnet.

zusätzlich zur Matrix wird auch eine Gamma-Kurve (Tone Reproduction Curve) definiert, die die Helligkeitsverteilung bestimmt. Dadurch wird die Definition von [[Arbeitsfarbräume]] abgedeckt.

## LUT

Lookup Tables = Tabellen mit "Stützpunkte" (Interpolationsebenen) zur Konvertierung

- je mehr Stüzen desto genauer
- es wird nicht mathematisch transformiert sondern in Tabelle gesucht
- nicht für Arbeitsfarbräume geeignet
- wenn gesuchter Wert zwischen zwei Stützpunkten liegt, wird interpoliert

sRGB und Adobe-RGB sind als Matrizen aufgebaut (siehe [[Arbeitsfarbräume]]), CMYK-Profile als LUTs (ergibt Sinn weil CMYK-Profile für Druck und so)