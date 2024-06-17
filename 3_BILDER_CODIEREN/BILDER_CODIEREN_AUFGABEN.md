# Lösung zu BILDER_CODIEREN AUFGABEN

### 1. Bestimme die Farben:

- RGB(255, 255, 255) entspricht Farbe: Weiss
- RGB(0,0,0) entspricht Farbe: Schwarz
- RGB(252,178,91) entspricht Farbe: Safrangelb
- #FF0000 entspricht Farbe: Rot
- #00FF00 entspricht Farbe: Grün
- #0000FF entspricht Farbe: Blau
- #FFFF00 entspricht Farbe: Gelb
- #00FFFF entspricht Farbe: Cyan
- #FF00FF entspricht Farbe: Magenta
- #000000 entspricht Farbe: Schwarz
- #FFFFFF entspricht Farbe: Weiss
- #00BC00 entspricht Farbe: Dunkelgrün

### 2. Bestimmen sie die Farben für die folgenden prozentualen CMYK-Angaben

- C:0%, M:100%, Y:100%, K:0% entspricht Farbe: Rot
- C:100%, M:0%, Y:100%, K:0% entspricht Farbe: Grün
- C:100%, M:100%, Y:0%, K:0% entspricht Farbe: Blau
- C:0%, M:0%, Y:100%, K:0% entspricht Farbe: Gelb
- C:100%, M:0%, Y:0%, K:0% entspricht Farbe: Cyan
- C:0%, M:100%, Y:0%, K:0% entspricht Farbe: Magenta
- C:100%, M:100%, Y:100%, K:0% entspricht Farbe: Schwarz
- C:0%, M:0%, Y:0%, K:100% entspricht Farbe: Schwarz
- C:0%, M:0%, Y:0%, K:0% entspricht Farbe: Weiss
- C:0%, M:46%, Y:38%, K:22% entspricht Farbe: Dunkelrosa

### 3. Berechnen sie den theoretischen Speicherbedarf in Bit und in Byte eines unkomprimierten RGB-Bildes mit der Grösse 640 x 480 und 8Bit Auflösung pro Farbkanal.

Um den Speicherbedarf eines unkomprimierten RGB-Bildes zu berechnen, benötigen wir die Bildgröße, die Anzahl der Farbkanäle und die Auflösung pro Farbkanal

- <b>Bildgröße (Pixel):</b> 640 x 480 = 307200 Pixel -<b> Speicherbedarf pro Pixel:</b> 8 Bit × 3 = 24 Bit pro Pixel (Ein Pixel besteht aus drei Farbkanälen (RGB) und jeder Kanal hat eine Auflösung von 8 Bit)
- <b>Gesamtspeicherbedarf in Bit:</b> 307200 Pixel × 24 Bit / Pixel = 7372800 Bit
- <b>Gesamtspeicherbedarf in Byte:</b> 7372800 Bit / 8 = 921600 Byte

### 4. Webseitengestaltung

Die empfohlenen Bildformate sind JPG für den Hintergrund und SVG oder PNG für das Logo.

### 5. Was ist die Pixelauflösung horizontal und vertikal?

- Horizontale Auflösung: 2546 Pixel
- Vertikale Auflösung: 1591 Pixel

### 6. Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixel mit 600dpi. Wie gross in cm wird dieses?

Grösse in Zoll: Anzahl der Pixel / DPI

2000 / 600 = 3.3 Zoll = 8.47 cm

### 7. Berechnen sie den Speicherbedarf für ein unkomprimiertes Einzelbild im HD1080p50-Format bei einer True-Color-Farbauflösung.

- <b>Anzahl der Pixel:</b> 1920 × 1080 = 2.073.600 Pixel
- <b>Speicherbedarf pro Pixel:</b> 24 Bit / Pixel = 3 Byte / Pixel
- <b>Gesamtspeicherbedarf für ein Bild:</b> 2.073.600 Pixel × 3 Byte/Pixel = 6.220.800 Byte

  6.220.800 Byte = 6.220.800×8 Bit = 49.766.400 Bit

### 8. Welchen Speicherbedarf aus einer HD (Massvorsatz im IEC-Format) hat das Video aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten?

Speicherbedarf: 52.14 GiB

### 9. Ihre Digitalkamera bietet für die Speicherung ihrer Bilder die beiden Formate RAW und JPG an. Wo liegen die Unterschiede und was sind die Verwendungszwecke?.

<b>RAW:</b>

- Speichert alle Bildinformationen, die vom Sensor erfasst werden
- Mehr Speicherbedarf
- Professionelle Fotografie, Nachbearbeitung

<b>JPEG:</b>

- Verwendet verlustbehaftete Kompression
- Weniger Speicherbedarf
- wird im Alltag verwendet

### 10.Technische Vorgaben für YouTube-Uploads

<b>Container:</b> MP4

<b>Bildrate:</b> 24, 25, 30, 48, 50, 60 fps (Frames per Second)

<b>Farbauflösung: </b> 4:2:0

<b> Videocodec: </b> H.264

<b> Audiocodec: </b> AAC-LC

<b> Maximale Bitrate: </b>
1080p: 8 Mbps für SDR, 10-12 Mbps für HDR

<b> Rechtliche Einschränkungen: </b>

Urheberrechtlich geschützte Inhalte dürfen nicht ohne Genehmigung verwendet werden.

### 11. Was ist der Unterschied zwischen dem Interlaced Mode und dem Progressive Mode?

- <b> Interlaced:</b> Halbbilder (Ungerade Zeilen / Gerade Zeilen)
- <b> Progressiv:</b> Ganze Bilder

### 12. Was versteht man unter Artefakten und welche kennen sie?

Sie sind Strukturen im Bilder durch Komprimierungen. Ein Bekanntes wäre Moiré-Effekt und Blockingartefakte.

### 13. Datenrate für HD1080i50 Video

1.24416 Gbps

### 14. Nach wie vielen Minuten unkomprimierten HD1080i50 Video wäre eine DVD-5 (Single-Layer DVD mit 4.7GB) voll?

Nach 30 Sekunden also 0.5 Minuten.

### 15. Was ist der Unterschied zwischen einem Codec und einem Mediencontainer?

- <b>Codec: </b> Komprimiert und dekomprimiert Audio- und Videodaten.

- <b>Mediencontainer: </b> Beinhaltet verschiedene Datenströme (Video, Audio, Untertitel) in einer Datei.

### 16. Fragen zum AD-Wandler-Video

- a. Warum benötigt man AD-Wandler?
  Um analoge Signale (z.B. Ton, Licht) in digitale Signale zu konvertieren, die von Computern verarbeitet und gespeichert werden können.

- b. Warum geht eine A/D-Wandlung immer mit einem Datenverlust einher?
  Aufgrund der Diskretisierung und Quantisierung, bei denen kontinuierliche Werte in diskrete Werte umgewandelt werden, was zu einem Verlust von Detailinformationen führt.

- c. Gibt eine höhere oder eine niedrigere Samplingrate eine präzisere Abbildung des Originals? Begründen Sie!
  Eine höhere Samplingrate gibt eine präzisere Abbildung des Originals, da sie mehr Datenpunkte pro Sekunde erfasst und somit feinere Details und höhere Frequenzen des analogen Signals genauer wiedergeben kann.
