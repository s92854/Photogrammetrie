# Grundlagen der Photogrammetrie: Zusammenfassung
## Eigenschaften
* berührungslos
* Bestimmung von Form, Größe, Lage von Objekten
* Rekonstruktion von Ebenen mit 1 Bild, räumliche Rekonstruktion mind. 2 Bilder die jeden Bereich eines Objekts abdecken

"Photogrammetrie ist ein indirektes Messverfahren zur Bestimmung der Lage, Form und Größe von Objekten sowie der Veränderung des geometrischen Zustandes dieser Objekte aus zentralperspektivischen Bildern der Objekte."

## Einteilung
* Einzelbildphotogrammetrie
* Stereophotogrammetrie
* Mehrbildphotogrammetrie

## Aufnahme- und Auswertemethoden (Entwicklungsstufen)
* Analoge Photogrammetrie (Photochemische Aufnahme)
* Analytische Photogrammtrie (Photochemische Aufnahme und anschließende Digitalisierung)
* Digitale Photogrammetrie (Photoelektrische/digitale Aufnahme)

## Der Photogrammetrische Prozess

![photogrammetrischer prozess](https://github.com/s92854/Photogrammetrie/assets/134683810/14082a79-f697-4209-937e-b9ebb761e960)

## Digitale Photogrammetrie

![digitale photo](https://github.com/s92854/Photogrammetrie/assets/134683810/383c40ca-dcbc-4bd3-9e95-5f0bd89bdab5)

## Gebiete der Photogrammetrie
* Grafik, Bildverarbeitung, Mathe, Physik, Informatik
* Signalverarbeitung (digitale Photogrammetrie), Bildmustererkennung
* Ausgleichsrechnungen, Ingenieurvermessung

## Prinzip der Photogrammetrie

![Prinzip](https://github.com/s92854/Photogrammetrie/assets/134683810/febc809c-76cb-440f-811f-c52b7ba423fa)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/c35c2822-1997-42a8-8038-f23778f8d615)

![prinzip 2](https://github.com/s92854/Photogrammetrie/assets/134683810/27e5bf76-d440-4dbc-a3b6-71da49c09afe)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/81543bc9-51a0-413f-a88d-950cdec149e0)

## Lichtbrechung
$$ n = {C<sub>Luft</sub> \over C<sub>Medium</sub>} $$
> C: Lichtgeschwindigkeit
> n: Brechzahl

$$ n<sub>1</sub> * sin(\alpha) = n<sub>2</sub> * sin(\beta) $$

## Reflektion
* Bei ungünstigen Verhältnissen der Brechungszahlen resultiert eine Reflektion
* bei der spiegelnden Reflektion gilt: $\alpha = \beta$

## Dispersion
* Verschiedene Wellenlängen (Farben) breiten sich unterschiedlich schnell aus > unterschiedliche Brechzahlen für jede Wellenlänge > Aufspaltung des Lichts in Spektralfarben

## Beugung des Lichts
= Störung der Lichtausbreitung, bei:
* Lochblenden (kreisförmige Durchgänge)
* Kanten
* Gittergrenzen
--> Beugungsmuster

## Stereoskopisches (räumliches) Sehen
### Natürlich
* Verschmelzen zweier Bilder zu einem Raumbild
* Stereoskopische Parallaxe
    * nicht größer als 1,3 gon, damit Raumbild als Gesamtheit wahrgenommen werden soll; für $\epsilon > 1,3 gon$ zerfällt entweder Vorder- oder Hintergrund in zwei Bilder
* Stereoskopische Sehschärfe
    * definiert als kleinster noch wahrnehmbarer Winkel $\epsilon$
    * ca. 5'' - 10''. Monokulare Sehschärfe ca. 30''
    * deutliche Sehweite von 25: stereoskopische Sehschärfe 6-12μm; monokulare Sehschärfe: 40μm

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/2c648cf3-3c2d-41b6-b1fe-c89eae8f52b6)


### Künstlich
Verhältnisse der Zentralprojektion der Aufnahme werden künstlich wiederhergestellt.

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/d808e89d-5a55-417b-bccf-1c2bafa343bf)

Als homologe Punkte bezeichnet man jene Punkte, in denen sich beide homologe Strahlen schneiden.

Bedingungen:
* dieselbe Szene, verschiedene Aufnahmeorten in gleichem Maßßstab
* Aufnahmekonfiguration entspricht ungefähr photogrammetrischem Normalfall
* Jedem Auge wird ein Bild gezeigt > so, dass sich die von den Augen ausgehenden homologen Strahlen in den Objektpunkten vor dem Beobachter im Raum schneiden

# Optik
* Abbildung des realen Objekts auf einem Sensor geschieht über optisches System (Linsen- oder Spiegelsystem)
* davor sitzt eine Blende: reguliert einfallendes Licht und Schärfentiefe des Bildes (scharfer Bereich vor und hinter dem Objekt)
Die auf den Sensor einfallende Lichtmenge ist proportional der Blendenöffnung und der Belichtungszeit

### Lochkamera
* Lichtstrahlen werden in der Lochebene gebündelt. Es entsteht eine gerade Verbindung zwischen Objekt und Bild --> Zentralprojektion

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/047349c7-f24a-481e-aeae-c7b20417f268)
![Lochkamera](https://github.com/s92854/Photogrammetrie/assets/134683810/e4580f78-89e1-42ab-aa75-c0ce9b12532d)

vereinfachte Darstellung:

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/a651ef65-69af-4f3a-9cc0-29fa6529a2a6)

### Begriffe der optischen Abbildung

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/f132e432-caad-4a0b-80fe-b0797f9e7b31)

### Abbildungsgleichung und -maßstab

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/67d7769f-22a5-41f6-8808-1278b5d31542)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/a1921540-f464-4619-80e8-2369782e2d41)

m<sub>b</sub>: Bildmaßstabszahl   (dient der Bestimmung notwendiger Aufnahmeparameter)

M<sub>b</sub>: Bildmaßstab: 1:m<sub>b</sub>

## Formatwinkel
Der Formatwinkel gibt an, welchen Winkel man im Raum mit einer Optik abdeckt (FOV - Field of View)
$$tan(\Omega)={s' \over 2c}$$

## Öffnungswinkel
$$tan(\alpha)={d' \over 2f}$$

Lichtstärke:
$$Lichtstärke = Relative Öffnung = {d \over f}$$

![blenden](https://github.com/s92854/Photogrammetrie/assets/134683810/f8ab5f1f-7fcf-463d-9b62-e08a0bf547a6)
![schärfen](https://github.com/s92854/Photogrammetrie/assets/134683810/be042c7b-a71b-4dbd-bbf5-4554db170ad1)
![schärfentiefe](https://github.com/s92854/Photogrammetrie/assets/134683810/d3d59faf-8b20-4461-9a32-71432c2faf9c)

So lange die Unschärfekreise eines abgebildeten Objekts nicht größer wird als die Auflösungsgrenze, werden die Objekte als scharf wahrgenommen (weil das Auge die Auflösungsgrenze nicht erreicht hat).

$$u' = {a<sub>h</sub> - a<sub>v</sub> \over a<sub>h</sub> + a<sub>v</sub>} * {f^2 \over k * (a - f)}$$

$$t = a<sub>h</sub> - a<sub>v</sub> = {2 * u' * k * (1 + m<sub>b</sub>) \over m<sub>b</sub>^2 - ({u'k \over f})^2)}$$

> k = Blendenzahl; m<sub>b</sub> = Blendenmaßstabszahl; u' = Zerstreuungskreis = ${1 \over 1500}s'$

## Radiometrische Abbildungsverzeichnung
### Einfluss der Blende
* Lichtmenge, die auf die Bildebene trifft
* Position der Projektionszentren
* Schärfentiefe
* kann chromatische Längsfehler verringern
### Radiometrisch   (Messen von eletkromagnetischer Strahlung)
* Lichtabfall (Vignettierung)
* Über- / Unterbelichtung
* Chromatischer Längs-/Querfehler

#### Lichtabfall
* Beleuchtungsstärke E oder Intensität I fällt mit zunehmendem Winkel von der Bildmitte ($\tau$) zum Bildrand hin ab

$$I' = I * cos^4(\tau) = E(\tau) = E * cos^4(\tau)$$

#### Vignettierung
* verursacht durch optische (Linse oder Blende) oder mechanische Verdeckungen (Objektivränder)
* schwächere Beleuchtung in Richtung des Bildrandes

### Chromatische Abberation
Lichtbrechung erfolgt durch unterschiedliche Wellenlängen unterschiedlich stark > Verschiebung der Farben
-> Hohe Blende stellt Strahlen stärker parallel > Verringerung des Effekts

![chrom_abberation](https://github.com/s92854/Photogrammetrie/assets/134683810/af36fa64-e2bf-430b-a5bc-98c047aac5eb)
![korrektur chrom_abberation](https://github.com/s92854/Photogrammetrie/assets/134683810/6840c2f7-2a6f-4f4a-8f07-57d2e01c75f5)

Unterscheidung in Längs- und Querfehler
Längsfehler erzeugen Unschärfen
Querfehler erzeugen Farbsäume (s.o.)

### Beugungsunschärfe

![beugungsunschärfe](https://github.com/s92854/Photogrammetrie/assets/134683810/647bcc73-1dba-42db-a78e-324367d04974)

## Geometrische Abbildungsverzeichnung
