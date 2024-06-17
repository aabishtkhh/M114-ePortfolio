# Lösung zu BILDER_KOMPRIMIEREN

### 1. Bestimme die Farben:

- RGB 255/255/255 entspricht Weiss und ergibt in YCbCr: 1-0-0
- RGB 0/0/0 entspricht Schwarz und ergibt in YCbCr: 0-0-0
- Y:0, Cb:0.5, Cr:0 entspricht der Farbe: Rot
- Y:0, Cb:-0.5, Cr:0 entspricht der Farbe: Grün
- Y:0, Cb:0, Cr:0.5 entspricht der Farbe: Blau
- Y:0, Cb:0, Cr:-0.5 entspricht der Farbe: Grün
- Y:0.3, Cb:0.5, Cr:-0.17 entspricht der Farbe: Rot

### 2: Umwandlung von RGB in Graustufen

- RGB-Werte (Hellblau): R=33, G=121, B=239
- Graustufenwert: 106

### 3. Berechnen sie, wieviel Speicher eingespart wird, wenn ein Bild mit Subsampling 4:1:1 komprimiert wird.

50% (Original: 300% Farbinformation, Subsampling: 150%)

### 4. RGB und YCrCb:

a. Kann man durch die Bildumwandlung vom RGB- in den YCbCr-Farbraum Speicherplatz einsparen?
Die Umwandlung von RGB zu YCbCr ermöglicht durch effizientere Farbkompression Speicherplatzersparnis.

b. Kann ein Beamer ein Bikld im YCbCr-Farbbereich darstellen?
Ein Beamer kann Bilder im YCbCr-Farbraum nicht direkt anzeigen, sondern wandelt sie in RGB um.

c. Wie rechnet man ein Farbbildes in ein Graustufenbild um?
Ein Farbbild wird in ein Graustufenbild umgerechnet, indem die RGB-Werte jedes Pixels entsprechend ihrer Helligkeit gewichtet werden.

d. Warum hat bei der Umwandlung eine Farbbildes in ein Graustufenbild der Grünanteil am meisten Gewicht?
Der Grünanteil hat bei der Umwandlung in ein Graustufenbild das meiste Gewicht, da das menschliche Auge empfindlicher auf grünes Licht reagiert.

### 5. Chroma-Subsampling:

a. Warum verschlechtert sich die Bildschärfe von 4:1:1-Subsampling gegenüber 4:4:4-Subsampling nicht?
Keine Verschlechterung, da Luminanzkanal unverändert bleibt.

b. Ein quadratisches 24-Bit-RGB-Bild mit einer Kantenlänge von 1000 Pixel soll mit 4:1:1 unter
Es wäre 50%.

### 6. JPEG-Komprimierung

a. Was ist der erste Schritt bei der JPG-Komprimierung?
Umwandlung von RGB in YCbCr, gefolgt von Subsampling

b. Führt die DCT-Transformation zu einer Datenreduktion?
Keine direkte Datenreduktion, Quantisierung benötigt.

c. Warum erhält man bei einer sehr starken Bildkomprimierung sogenannte Block-Artefakte?
Durch 8x8 Block-Quantisierung und anschließende Angleichung der Farbwerte innerhalb der Blöcke.

### 7. Codecs und Containern

a. Was ist der Unterschied zwischen Intraframe- und Interframe-Komprimierung?

- Intraframe: Innerhalb eines Bildes.
- Interframe: Über eine Bildserie.

c. Bei welcher Filmsequenz bietet die Interframekomprimierung mehr Potential zur Datenreduzierung:
i. 30 Sekunden-Szene mit Faultier auf Nahrungssuche?

- Wenige Bewegung
- Potential zur Datenreduzierung

ii. 30 Sekunden-Szene mit Zieleinfahrt beim Formel-1-Rennen?

- Viele und schnelle Bewegungen
- Potential zur Datenreduzierung

d. Sehen sie Parallelen zwischen Datenbackupkonzepten und Interframe-Komprimierung?

- Full Backup: Alle Daten werden vollständig gesichert.

- Incremental Backup: Nur die Änderungen seit dem letzten Backup werden gesichert.

- Differential Backup: Alle Änderungen seit dem letzten vollständigen Backup werden gesichert.

e. Was versteht man unter GOP25?
Group of Pictures, wo jedes 25. Bild ein vollständiges Bild ist
