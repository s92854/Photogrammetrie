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

$$n<sub>1</sub> * sin(\alpha) = n<sub>2</sub> * sin(\beta)$$

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
$tan(\Omega)={s' \over 2c}$

## Öffnungswinkel
$tan(\alpha)={d' \over 2f}$

Lichtstärke:
$Lichtstärke = Relative Öffnung = {d \over f}$
$Blendenkennzahl k = {f \over d}

![blenden](https://github.com/s92854/Photogrammetrie/assets/134683810/f8ab5f1f-7fcf-463d-9b62-e08a0bf547a6)
![schärfen](https://github.com/s92854/Photogrammetrie/assets/134683810/be042c7b-a71b-4dbd-bbf5-4554db170ad1)
![schärfentiefe](https://github.com/s92854/Photogrammetrie/assets/134683810/d3d59faf-8b20-4461-9a32-71432c2faf9c)

So lange die Unschärfekreise eines abgebildeten Objekts nicht größer wird als die Auflösungsgrenze, werden die Objekte als scharf wahrgenommen (weil das Auge die Auflösungsgrenze nicht erreicht hat).

$$u' = {a<sub>h</sub> - a<sub>v</sub> \over a<sub>h</sub> + a<sub>v</sub>} * {f^2 \over k * (a - f)}$$

$$t = a<sub>h</sub> - a<sub>v</sub> = {2 * u' * k * (1 + m<sub>b</sub>) \over m<sub>b</sub>^2 - ({u'k \over f})^2)}$$

> k = Blendenkennzahl; m<sub>b</sub> = Blendenmaßstabszahl; u' = Zerstreuungskreis = ${1 \over 1500}s'$

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

$I' = I * cos^4(\tau) = E(\tau) = E * cos^4(\tau)$

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
Treten durh Abweichungen vom mathematischen Modell der Zentralperspektive auf
* Verkippung der Bildebene gegenüber der optischen Achse
* Verformung der Bildebene
* Ablenkung der Strahlen aufgrund von asymmetrischer Linsenanordnung/Blendenplazierung

### Liniensystem
* Verschiebung der Projektionszentren
   * Eintrittswinkel nicht mehr gleich Austrittswinkel > optische Verzeichnung
   * Hauptstrahl nicht mehr senkrecht auf Bildebene > Definierung eines mathematischen Projektionszentrums (neben physikalischem)

O<sub>M'</sub> steht senkrecht im Abstand c über Bildebene: $\tau = \tau'$

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/7dc501d0-a5df-4737-96b0-9e0b413e0957)

### Reale Optische Abbildung

![reale optische abbildung](https://github.com/s92854/Photogrammetrie/assets/134683810/3df12f3d-3d5b-415f-a1cb-e6baa7f05fa9)

$r' = tan(\tau) * c + \Delta r'$

## Radialsymmetrische Verzeichnung
* größter Einfluss auf die Abbildungsfehler
* entsteht durch Brechungsänderungen an den Linsen des Objektivs

![radialsym_verz](https://github.com/s92854/Photogrammetrie/assets/134683810/0842491b-4d8b-484a-97c6-b84cb11849fd)
![radial](https://github.com/s92854/Photogrammetrie/assets/134683810/a37baffe-4e0f-4287-8241-182d93ce2ea7)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/eac8cc87-9d78-4bb7-8279-8ec98444ca47)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/11b240ff-9f45-4aff-a5a6-31cab7b5e06b)

### Modellierung der Verzeichnung
Conray-Koeffizenten: $\Delta r'rad = K0 * r' + K1 * r'^3 + K2 * r'^5 + K3 * r'^7$

Seidel-Reihe: $\Delta r'rad = A1 * r'3 + A2 * r'^5 + A3 * r'7 + ...$

Korrektur der Bildkoordinaten x und y: $\Delta x' = x' * {\Delta r'rad \over r'}$
$\Delta y' = y' * {\Delta r'rad \over r'}$

## Asymmetrie und Tangentiale Verzeichnung
dezentrale Linsen können asymmetrische und tangentiale Verzeichnungen hervorrufen
$\Delta x'tan = B1 * (r'^2 + 2rx'^2) + 2B2 * x' * y'$

$\Delta y'tan = B2 * (r'^2 + 2y'^2) + 2B1 * x' * y'$
> r = radialer Abstand vom Bildhauptpunkt

## Affine Verzeichnung und Scherung der Koordinatenachsen
Bildkoordinatensystem nicht orthogonal und dessen Koordinatenachsen sind ungleichmäßig skaliert

$\Delta x'aff = C1 * x' + C2 * y'$

$\Delta y'aff = 0$

In der Praxis angewendet:

$\Delta x'aff = C1x'$

$\Delta x'shear = C2y'$

$\Delta y'aff = -C1y'$

$\Delta y'shear = C2x'$

## Punktverwaschung (Punktspreizfunktion / point spread function)
* wie werden punktförmige Objekte in Bildebene dargestellt
* Einflüsse durch:
   * Apertur (Öffnungswinkel der Optik)
   * Temperatur

## Entwicklung/Erstellung eines Bildes
### Photochemische Bildaufzeichnung
* Emulsion auf einem Schichtträger
* chemische Entwicklung, Fixierung des Bildträgers
* Entwicklung des Positives
### Photoelektrische Bildaufzeichnung
* Sensoren registrieren die einfallende Lichtenergie
* versch. techn. Realisierungen

## Objekt und Bild
### Objekt
* Kontinuierliche Geometrie und Radiometrie (Helligkeitsverlauf)
### Analoge Fotografie
* kann diese Eigenschaft größten Teils wiedergeben
### Digitale Fotografie
* Objekte werden auf einer diskreten Anzahl von Elemente abgebildet > **Abtastung / Diskretisierung**
* Radiometrische Informationen werden ebenfalls in definierte Grauwertstufen abgebildet > **Quantisierung**

## CCD-Sensoren
CCD = Charge Coupled Device
Pixel sind Sensoren, die die einfallenden Photonen registrieren
* "Eimerprinzip" > registrierte Ladungen auslesen und weiter verarbeiten > limitiertes Fassungsvermögen
* Kenngröße Fassungsvermögen: Full-Well > wird zusammen mit Gain und Bildtiefe bestimmt
* Anzahl an Photonen, die eine Grauwertstufe definieren: **Gain**

## Bildtiefe / Bittiefe
* Anzahl der Grauwerte > $2^n$ mögliche Grauwerte

### CCD-Anpassungen
* Lücken zwischen aktiven Sensorelementen > dort aufkommende Photonen werden nicht registriert > Plazieren von Mikrolinsen, um "Pixel fill factor" zu erhöhen

## CMOS
Complementary metal oxide semi-conductor
Vorteile gegenüber CCD:
* geringerer Energieverbrauch
* geringe Herstellungskosten
* direkte Adressierbarkeit von Sensorelementen
* schnelles Auslesen (durch direkte Verarbeitung der Information am Pixel - Auslesesequenzen entfallen)
* hoher Dynamikumfang

## Digitale Farbbilder
Farb-Pixel wird in mehrere Sektoren unterteilt
* Farbkalibrierung ist schwierig
* Auflösung ist reduziert
* Photogrammetrisch muss man beachten mit welcher Wellenlänge man arbeitet

## (Pixel-) Auflösung
* Pixelauflösung = Fläche, die ein Pixel im Objektraum abdeckt
* Auflösungsvermögen wird über physikalische Pixelgröße, Kamerakonstante, Abstand zum Objekt berechnet

## Koordinatensysteme
Unterscheidung in:
* Bildkoordinatensystem
* Kamerakoordinatensystem
* Objektkoordinatensystem
* Übergeordnete Koordinatensysteme

sowie
* rechtshand, linkshand KS
* orthogonale, kartesische, geographische KS
* 2D und 3D KS

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/826faed1-cd63-4390-94b1-2706791a0c8b)

### Analoge Bildkoordinatensysteme

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/0f471e27-373e-47e6-a1b3-b51761e83097)

### Digitales Bildkoordinatensystem
Die Position eines Punktes P' in der Bildmatrix ist in Pixelkoordinaten exakt definiert

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/48043fbf-6c30-4e0d-bdb9-e04b4fae9e03)

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/bd4cefc5-c8a4-4bad-a0aa-81f384f7a298) ![image](https://github.com/s92854/Photogrammetrie/assets/134683810/1c4b918b-30e7-4f0c-9c4c-464454be929b)

### Kamerakoordinatensystem

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/2ae89486-851b-48b0-afa1-7de5af7d311e)

$$P'(x'P \mid y'P \mid -c)$$

$$\vec{P'} = {\begin{bmatrix} x'P \\ y'P \\ z'P \end{bmatrix}} + Korrekturen$$

> Korrekturen: Kameraverzeichnung (Optik), Bildebenenverformung (Bildträger)

Translation:

$$\vec{O} = {\begin{bmatrix} X0 \\ Y0 \\ Z0 \end{bmatrix}}$$

Beschreibung der Kameraausrichtung im Objektraum kann über Winkel beschrieben werden: Rotation um drei Winkel

### Rotationsmatrizen in der Ebene

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/7d06de22-b175-48cc-9f04-663793b35f25)

$$\vec{f(x,y,\theta)} = {\begin{bmatrix} x' \\ y' \end{bmatrix}}$$

$cos \theta = {Ankathete \over Hypothenuse}$

$sin \theta = {Gegenkathete \over Hypothenuse}$

$x1' = x * cos \theta$

$\Delta x = y * sin \theta$

$x' = x1' + \Delta x = x * cos \theta + y * sin \theta$

&nbsp;

$y1' = y * cos \theta$

$\Delta y = x * sin \theta$

$y' = y * cos \theta - x * sin \theta$

&nbsp;
<!--
$${\begin{bmatrix} x' \\ y' \end{bmatrix}} = {\begin{bmatrix} cos \theta \\  \\ sin \theta \\ \mid \\ -sin \theta \\  \\ cos \theta \end{bmatrix}} * {\begin{bmatrix} x \\ y \end{bmatrix}}$$

$${\begin{bmatrix} x \\ y \end{bmatrix}} = {\begin{bmatrix} cos \theta \\  \\ -sin \theta \\ \mid \\ sin \theta \\  \\ cos \theta \end{bmatrix}} * {\begin{bmatrix} x' \\ y' \end{bmatrix}}$$
-->

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/4a07173b-8b42-415d-9496-b9389c7561b0)

## Rotationsmatrizen
* lineare Kombinationen von trigonometrischen Funktionen
* Rotation um drei Koordinatenachsen > Transformation in ein beliebig orientiertes Koordinatensystem

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/bb6d7d4f-3a75-47e7-ba94-f9c984dca3a5)

Reihenfolge der Rotationen muss bekannt sein, denn Rotationen sind nicht eindeutig.

### Rotation & Translation

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/663102ba-df1d-4da2-83c5-518747bef4da)
![image](https://github.com/s92854/Photogrammetrie/assets/134683810/75ab4571-8545-45df-a6b9-b3b8427e5a99)

## Innere Orientierung
* Alle Kameraparameter die das mathematische Modell der Kamera möglichst genau bestimmen
   * Korrektur von Kamera- und Sensorungenauigkeiten
   * Korrektur der Messwerte
   * Koordinaten des Bildhauptpunktes (x<sub>0</sub>,y<sub>0</sub>)
   * Kamerakonstante (c)
   * Parameter zur Beschreibung der Verzeichnungen/Abbildungsfehler ($\Delta x, \Delta y$)

$$\vec{P'} = {\begin{bmatrix} x'P \\  \\ y'P \\ -c \end{bmatrix}} = {\begin{bmatrix} xP \\  \\ yP \\  \\ 0 \end{bmatrix}} + Korrekturen$$

### Bildhauptpunkt H'
* Lotfußpunkt des Projektionszentrums im Bildkoordinatensystem (x'<sub>0</sub>, y'<sub>0</sub>)
### Kamerakonstante c
* Lotrechter Abstand des Projektionszentrums von der Bildebene (in negativer Z-Richtung des Bildkoordinatensystems)
### Parameter zur Beschreibung von Abbildungsfehlern

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/9e650f07-1397-449f-bf11-5e8d769ab177)


## Äußere Orientierung
* Beschreibt die Position & Lage der Kamera in Bezug auf das Zielkoordinatensystem
* 6 + 1 Parameter
   * Drei Koordinaten des Kamerastadnpunktes (X<sub>0</sub>, Y<sub>0</sub>, Z<sub>0</sub>)
   * Drei Rotationswinkel für Orientierung gegenüber dem Modell-KS ($\phi, \omega, \kappa$)
   * Zeit (t)

### Stabilität der Kamerageometrie
Innere Geometrie wird beeinflusst durch:
* Fokussierung
* Objektivwechsel/Brennweitenänderung (Zoom)
* Umgebungstemperatur
* Luftfeuchte
* Technische Hilfsmittel zur Bildstabilisierung
* Mechanische Beeinflussung

### Kalibrierungsverfahren
* Laborkalibrierung
   * hohe Genauigkeit durch Hersteller; langzeitig
   * Goniometer = Winkelmesser, Minipulator = nodal bench (Rotation), Kollimator = stellt scheinbar unendlich entferntes in endlichem Abstand dar
* Testfeldkalibrierung
   * Analytische Kalibration durch Auswertung von festen Punktfeldern
   * zeitlich begrenzt kalibriert
   * Bestimmung der inneren Orienterung durch Bündelblockausgleich
* Simultankalibrierung
   * Modellierung der Parameter für jede Aufnahme
   * instabil und variierende Parameter

### Plumblines
Gerade Linien > Anhand der Wölbungen der Linien in der Aufnahme sind Ausgleichungen möglich

### Prinzip der Kalibrierung
Bekannt:
* raumliche Verteilung der Punkte
* Entferungne zwischen den Punkten
* Punkte gleichmäßig & bildformatfüllend angeordnet

### Simultankalibrierung
* Kamerastandpunkte und Parameter der inneren Orientierung werden simultan über eine Ausgleichung bestimmt

### Selbstkalibrierung
* Simultankalibrierung ohne explizites Testfeld, nur mit photogrammetrischer Techniken

## Fluglageparameter
* Querneigung (Rollwinkel; *roll*): $\omega$
* Längsneigung (Nickwinkel; *pitch*): $\varphi$
* Kantung (Gier-/ Kurswinkel; *yaw*): $\kappa$

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/9b0d053a-80bc-491d-bd09-77b042e52e22)

### Kameratypen
* Analoge Kameras (photochemisch)
* Digitale Kameras (photoelektrisch)
* Flächensensoren
* Zeilensensor

### Bildformate & Aufnahmewinkel
* Kleinformat, Mittelformat, Großformat
* Schmalwinkel, Normalwinkel, Weitwinkel

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/6fb951e3-ba92-4ef2-97b8-efde7f4b22e5)

### Messkamera
* Kamerakonstante durch fest eingebautes, nicht fokussierbares Objektiv konstant
* Bildebene senkrecht zu optischer Achse
* Verzeichnungsfreies Objektiv ($\Delta r' < 4 µm$) > Bildhauptpunkt = Bildmittelpunkt
* ebene Bildfläche durch Glasplatten oder mechanische Bildverebnung (Andrucksystem)
* optionale Zusatzeinrichtungen zur geodätischen Messung von Passpunkten

## Digitale Luftbildkameras
### Anforderungen
* geometrische, radiometrische und spektrale Auflösung

### Flächensensoren
* 1 großflächiger CCD-Chip (Butterflytyp)
* Patchworktyp
* Bayer-Sensor (RGB Pixelmuster)
* einzelne CCD-Chips für jeden Farbkanal

### Zeilensensoren /-scanner
* Sensoren mit einer Zeile oder Mehrzeilenscanner

#### Butterflytyp
* Aufnahme des panchromatischen Bildes

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/e22c27f5-4d9e-44bd-ba67-5952a67f860d)

### Aufnahmekonfiguration
... ist abhängig von
* Objekt
* geforderter Genauigkeit
* verfügbaren Aufnahmesystemen
* verfügbaren Auswertsystemen

## Stereobildkonfiguration

![stereokonfig](https://github.com/s92854/Photogrammetrie/assets/134683810/d904217e-422b-40f5-9cb3-8449ee2bf5ce)

## Kollinearitätsgleichungen

$$\xi = \xi<sub>0</sub> - c * {r11(X - X0) + r21(Y - Y0) + r31(Z - Z0) \over r13(X - X0) + r23(Y - Y0) + r33(Z - Z0)}$$

$$\eta = \eta<sub>0</sub> - c * {r12(X - X0) + r22(Y - Y0) + r32(Z - Z0) \over r13(X - X0) + r23(Y - Y0) + r33(Z - Z0)}$$

![main_picture](https://github.com/s92854/Photogrammetrie/assets/134683810/efd7e353-a8de-4f7f-bc2b-3a0c01d8f4a3)

> Unbekannt: Koordinaten P, Vektor zu P, Informationen

### Bildrauminformationen
> Kamerakonstante, Bildhauptpunktkoordinate (blau)

<!--
$c,H(\xi 0,\eta 0)$
-->

> Beobachtung der Bildkoordinate (lila)

<!--
$P'(\xi,\eta)$
-->

> Parameter der Abbildungsverzeichnung > 3D-Vektor im Kamera-KS (gelb)

<!--
$\vec{P'} = {\begin{bmatrix} \xi 0 - \xi - \Delta \xi \\ \mid \\ \eta 0 - \eta - \Delta \eta \\ \mid \\ -c \end{bmatrix}}$
-->

> Ort der Kamera als Vektor (brün)

<!--
$\vec{O} = {\begin{bmatrix} X0 \\ \mid \\ Y0 \\ \mid \\ Z0 \end{bmatrix}}$
-->

> Rotation des Kamera-KS in das Objekt-KS (rot)

<!--
$\vec{R} = {\begin{bmatrix} ... \\ \mid \\ R(\omega,\phi,\kappa \\ \mid \\ ... \end{bmatrix}}$
-->

![formeln](https://github.com/s92854/Photogrammetrie/assets/134683810/8f58e227-b4ea-4317-bc9f-e3898855b67f)
![ksys](https://github.com/s92854/Photogrammetrie/assets/134683810/edf5ea18-79a9-4c5d-90b0-8d618cae2304)

### Punktbestimmung
![punktbestimmung](https://github.com/s92854/Photogrammetrie/assets/134683810/84bdeeaa-5901-45ad-8999-bd287b042690)

### Umstellen der Kollinearitätsgleichung

![kgl](https://github.com/s92854/Photogrammetrie/assets/134683810/8e541d63-9b62-48d3-a7ed-30517e53d4f7)

## 3D-Rekonstruktion
* mind. 2 Bilder > 2*x, 2*y > 3 Unbekannte bestimmbar
* Basis muss zwischen Aufnahmestandorten existieren, sowie genügend großer Konvergenzwinkel

## Photogrammetrischer Normalfall
* parallele Aufnahme senkrecht zur Basis

![photo_norm](https://github.com/s92854/Photogrammetrie/assets/134683810/5857cc22-e9d2-4ace-bb46-d5040655b732)
![stereo_norm](https://github.com/s92854/Photogrammetrie/assets/134683810/763036f3-aa73-464c-8ff7-6c9fdf53210f)

Es gilt:

X<sub>01</sub> = Y<sub>01</sub> = Z<sub>01</sub> = Y<sub>02</sub> = Z<sub>02</sub> = 0

X<sub>02</sub> = B; $\omega$<sub>1</sub> = $\omega$<sub>2</sub> = $\kappa$<sub>1</sub> = $\kappa$<sub>2</sub> = $\phi$<sub>1</sub> = $\phi$<sub>2</sub> = 0

Daher Vereinfachung der Kollinearitätsgleichungen:

$$\xi = \xi<sub>0</sub> - c * {r11(X - X0) \over r33(Z)}$$

$$\eta = \eta<sub>0</sub> - c * {r22(Y) \over r33(Z)}$$

Kamera 1:

$$\xi<sub>1</sub> = \xi<sub>0</sub> - c * {X \over Z}$$

$$\eta<sub>1</sub> = \eta<sub>0</sub> - c * {Y \over Z}$$

$$X = Z * {\xi<sub>1</sub> - \xi<sub>0</sub> \over -c}$$

$$Y = Z * {\eta<sub>1</sub> - \eta<sub>0</sub> \over -c}$$


Kamera 2:

$$\xi<sub>2</sub> = \xi<sub>0</sub> - c * {X - B \over Z}$$

$$\eta<sub>2</sub> = \eta<sub>0</sub> - c * {Y \over Z}$$

$$X = B + Z * {\xi<sub>2</sub> - \xi<sub>0</sub> \over -c}$$

$$Y = Z * {\eta<sub>2</sub> - \eta<sub>0</sub> \over -c}$$

## Höhenbestimmung aus einer Parallaxe
Gleichsetzen beider X Gleichungen, Umstellen nach Z

$$Z = {-cB \over \xi 1 - \xi 2}$$


## Orientierung nach Kernstrahlen
* homologe Strahlen müssen sich im Objektraum schneiden
* Bildpaar muss relativ orientiert sein

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/bcf8c9b8-573d-4000-988a-d4bce6d61391)

![kernstrahlorientierung](https://github.com/s92854/Photogrammetrie/assets/134683810/3815d1e7-874b-4942-b1bb-b930e93cee2e)

* Kernstrahlen: H<sub>1</sub>' und H<sub>2</sub>', bzw. H<sub>1</sub>'' und H<sub>2</sub>''
* Orientierung:
   * Auffinden der Bildhauptpunkte
   * Übertragen in die Nachbarbilder
   * Ausrichten der Kernstrahlen auf einer Geraden

## Photogrammetrische Produkte
### 2D
* Bildmosaike
   * gleiche KS und Orientierungen
* Bilder in Epipolargeometrie
   * Eingrenzung des Suchbereichs homologer Punkte
* Karten
   * konstanter Maßstab in der Ebene
   * Orthophoto und TrueOrthophoto
   * Transformation von einer Zentralprojektion in eine Parallelprojektion

#### Orthophoto
* auf topographisches Geländemodell entzerrt
* Objekte (Häuser, Bäume, Autos) werden nicht erfasst > verzerrter Maßstab in diesen Bereichen

#### TrueOrthophoto
* Entzerrung auf digitalem Oberflächenmodell > konstanter Maßstab

### 3D
* Geländemodelle
   * Digitale Geländemodelle (DGM)
   * Digitale Terrain Modelle (DTM)
* Oberflächenmodelle
   * Digitale Oberflächenmodelle (DOM)
* Objektmodelle
   * 3D City Models
* Figurenmodelle

## Entzerrung
1. Bildaufnahme mit Kamera: **Zentralprojektion** > untersch. Maßstab
2. Karte/ entzerrtes Bild (Orthobild): **Parallelprojektion** > konstanter Maßstab

* Gerätetechnische Einteilung (Entwicklung)
   * Graphische Entzerrung
   * Optische (optisch-photographische) Entzerrung
   * Analytische Entzerrung
   * Digitale Entzerrung
* Mathematisch-methodische Einteilung (Berechnung)

> exakt oder Näherung? Wiederherstellung der Orientierung? Dimension: ebene oder räumliche Entzerrung? Direkte oder indirekte Entzerrung?

### Ebene Entzerrung
* 2D-Transformation
* keine Wiederherstellung der Orientierung
   * Ähnlichkeitstransformation (4 Parameter)
   * Affine Transformation (Polynom 1. Grades, 6 Parameter)
   * Polynomtransformation vom Grad n ((n+1)(n+2) Parameter)
   * Projektive Transformation (8 Parameter pro Bilinearfacette)
   * Bilineare Transformation (8 Parameter)

![lagefehler](https://github.com/s92854/Photogrammetrie/assets/134683810/0f434d70-0b6c-44c2-9440-52aefba8df69)

Vergleich ebener Entzerrungen:

![ebene-entzerrungen](https://github.com/s92854/Photogrammetrie/assets/134683810/5f46213d-0e6e-486c-ba74-3cfeb47f941e)

### Räumliche Entzerrung
* Wiederherstellung der Orientierung
* Projektion auf Bezugsfläche
* Differentielle Entzerrung (exaktes Verfahren)

Kollinearitätsgleichungen stellen Beziehung zwischen Bild und Objektraum her > Innere und Äußere Orientierung benötigt

![image](https://github.com/s92854/Photogrammetrie/assets/134683810/25cc9774-ec21-49ca-bfa3-cf394149f80c)

Je nach geometrischer Bezugsfläche ist räumliche Entzerrung genauer als ebene Entzerrung

#### Geometrische Bezugsflächen
* Ebene
* Digitales Geländemodell
* natürliches Gelände
* digitales Oberflächenmodell
* Flächen geometrischer Körper > Abwicklung Zylinder

### Differenzielle Entzerrung
Räumliche, Differenzielle, Digitale Entzerrung sind zwar keine Synonyme, aber die räumliche Entzerrung wird zumeist differenziell (auch digital) durchgeführt
**Differenzielle Entzerrung**: kleine Bildelemente (individuelle Berechnung für jeden Pixel > Wiederherstellung der inneren Orientierung (Pixelsystem vs. Bild-KS)

### Näherungsverfahren
* i.d.R. kein Entzerrungsverfahren
* i.d.R. keine Wiederherstellung der Orientierung

|   Pro    |  Contra  |
|----------|----------|
| kein Oberflächenmodell nötig    | Vereinfachung > Genauigkeitsverlust|
| keine Orientierungsparameter nötig| |

