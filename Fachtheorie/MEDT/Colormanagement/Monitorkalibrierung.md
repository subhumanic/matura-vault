
### Software
DisplayCal + Argyll (wird mit DisplayCal mitinstalliert)

### Hardware
typischerweise werden Kolorimeter statt Spektralfotometer verwendet

Spektralfotometer sind für Messung von Körperfarben ausgelegt und verfügen über 31 Filter um gesamtes wahrgenommenes Spektrum abzudecken

Kolorimeter verfügen über 3 Filter (RGB)
Kolorimeter sind nicht geeignet Metametrie zu erkennen (2 Farben die bei unterschiedlicher Lichteinstrahlung gleich aussehen)

Geräte von X-Rite eignen sich
(X-Rite i1 Diplay Pro ist ein Spektralfotometer, das aber auch von Displaycal für Monitorkalibrierung verwendet werden kann)

### Korrekturdaten vor Messung
Es müssen 2 Korrekturtabellen eingebunden werden:
- Korrekturtabelle des Kolorimeters
- auf Monitor (Panel-Typ, etc.) abgestimmte Korrekturtabelle

### Messung
basierend auf Messbedingungen des Nutzers wird eine Messung und Korrektur vorgenommen.

durch manuelle Einstellungen am Monitor und Kalibrierungskurven wird versucht die Messbedingung so exakt wie möglich zu erreichen

daraus wird dann ICC-Profil erstellt das von EBV-Software geladen wird und Farben dementsprechend angepasst dargestellt werden

> [!warning] check i ned ganz

![[Pasted image 20250421161411.png]]

### Typische Kalibrierungseinstellungen

- **Farbraum:** sRGB
- **Tonwertkurve:** 2,2  
- **Weißluminanz:** 80 cd/m² (Nits)  
- **Weißpunkt:** D65 – 6500 K (x = 0.3127, y = 0.3290)  
- **Primärvalenzen:**  
  - Rot: x = 0.64 / y = 0.33  
  - Grün: x = 0.30 / y = 0.60  
  - Blau: x = 0.15 / y = 0.06  
- **Zweck:** Standard RGB  

---

- **Farbraum:** ITU-R BT.709
- **Tonwertkurve:** 2,2 bzw. 2,4 laut ITU-R BT.1886  
- **Weißluminanz:** 100 cd/m² (Nits)  
- **Weißpunkt:** D65 – 6500 K (x = 0.3127, y = 0.3290)  
- **Primärvalenzen:**  
  - Rot: x = 0.64 / y = 0.33  
  - Grün: x = 0.30 / y = 0.60  
  - Blau: x = 0.15 / y = 0.06  
- **Zweck:** Video HDTV-Standard (Rec.709)  

---

**Farbraum:** ITU-R BT.2020
- **Tonwertkurve:** 2,4 laut ITU-R BT.1886  
- **Weißluminanz:** 100 cd/m² (Nits)  
- **Weißpunkt:** D65 – 6500 K (x = 0.3127, y = 0.3290)  
- **Primärvalenzen:**  
  - Rot: x = 0.708 / y = 0.292  
  - Grün: x = 0.17 / y = 0.797  
  - Blau: x = 0.131 / y = 0.046  
- **Zweck:** Video Standard UHDTV (Rec.2020)  

---

**Farbraum:** ECIrgb
- **Tonwertkurve:** 1,8  
- **Weißluminanz:** 120 cd/m² (Nits)  
- **Weißpunkt:** D50 – 5000 K (x = 0.3457, y = 0.3585)  
- **Primärvalenzen:**  
  - Rot: x = 0.67 / y = 0.33  
  - Grün: x = 0.21 / y = 0.71  
  - Blau: x = 0.14 / y = 0.08  
- **Zweck:** Druckvorstufe (ECI-Standards)  

---

**Farbraum:** AdobeRGB
- **Tonwertkurve:** 2,2  
- **Weißluminanz:** 160 cd/m² (Nits)  
- **Weißpunkt:** D65 – 6500 K (x = 0.3127, y = 0.3290)  
- **Primärvalenzen:**  
  - Rot: x = 0.64 / y = 0.33  
  - Grün: x = 0.21 / y = 0.71  
  - Blau: x = 0.15 / y = 0.06  
- **Zweck:** Medienneutrale Workflows  

---

**Farbraum:** P3-DCI
- **Tonwertkurve:** 2,6  
- **Weißluminanz:** 48 cd/m² (Nits)  
- **Weißpunkt:** 6300 K (x = 0.314, y = 0.351)  
- **Primärvalenzen:**  
  - Rot: x = 0.680 / y = 0.320  
  - Grün: x = 0.265 / y = 0.690  
  - Blau: x = 0.150 / y = 0.060  
- **Zweck:** Kinostandard (DCI)  

---

**Farbraum:** P3-D65
- **Tonwertkurve:** 2,2  
- **Weißluminanz:** 100 cd/m² (Nits)  
- **Weißpunkt:** D65 – 6500 K (x = 0.3127, y = 0.3290)  
- **Primärvalenzen:**  
  - Rot: x = 0.680 / y = 0.320  
  - Grün: x = 0.265 / y = 0.690  
  - Blau: x = 0.150 / y = 0.060  
- **Zweck:** Kinostandard Bildschirmdarstellung (DCI)  

---

**Farbraum:** ROMM RGB (ProPhoto RGB)
- **Tonwertkurve:** 1,8  
- **Weißluminanz:** 160 cd/m² (Nits)  
- **Weißpunkt:** D50 – 5000 K (x = 0.3457, y = 0.3585)  
- **Primärvalenzen:**  
  - Rot: x = 0.734 / y = 0.265  
  - Grün: x = 0.159 / y = 0.840  
  - Blau: x = 0.036 / y = 0.0001  
