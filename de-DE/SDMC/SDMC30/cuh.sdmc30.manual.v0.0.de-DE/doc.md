---
doc_id: cuh.sdmc30.manual.v0.0.de-DE
doc_key: cuh.sdmc30.manual.v0.0
doc_type: manual
lang: de-DE
product: sdmc30
source_pdf: /Users/wangle/Documents/Python开发/说明书转换/典型文档/SDMC3/20250905_49_IDP1000330_SDMC30_SMS-EN_1_01-文档发布.pdf
source_sha256: 4069af982ce8ec1e851b6454e2a55723ab9a2085653d25a893a3655f9bd35ba0
title: Digitaler Drehstrom-Asynchronmotor-Regler SDMC30-S — Benutzerhandbuch (Deutsch)
updated_at: 2026-09-17 03:30:00
version: 0.0
---


## Digitaler Drehstrom-Asynchronmotor-Regler

![Produktabbildung des digitalen Drehstrom-Asynchronmotor-Reglers SDMC30-S](assets/images/cuh.sdmc30.manual.v0.0/page-0001-vcrop-00.png)

## SDMC30-S

## Benutzerhandbuch



---

## Urheberrechtshinweis

Nanjing CUH Science & Technology CO., Ltd. behält sich alle Rechte vor.

Alle in diesem Benutzerhandbuch enthaltenen Informationen sind Wissen unseres Unternehmens und durch das Urheberrecht sowie andere einschlägige Gesetze geschützt. CUH genießt und behält sich sämtliche durch das Urheberrecht und andere Gesetze verliehenen Rechte vor. Ohne schriftliche Zustimmung von CUH darf dieses Benutzerhandbuch weder ganz noch teilweise kopiert, übersetzt, nachgeahmt oder anderweitig genutzt werden.

## Haftungsausschluss

Sämtliche Inhalte dieses Benutzerhandbuchs beschreiben lediglich die Verwendung der von unserem Unternehmen hergestellten Produkte; sie werden nach dem Stand der Technik und dem Zustand zum Zeitpunkt der Überlassung beschrieben. Sie tragen die entsprechenden Risiken bei der Nutzung dieses Produkts. Soweit gesetzlich vorgeschrieben, übernimmt das Unternehmen keine ausdrückliche oder stillschweigende Haftung für das Produkt aufgrund dieses Benutzerhandbuchs, einschließlich, aber nicht beschränkt auf Personenschäden, Sachschäden, entgangene Gelegenheiten usw.

Sie verstehen die oben genannten Risiken ausdrücklich und stimmen zu, dass das Unternehmen – soweit gesetzlich vorgeschrieben – für keine direkten oder indirekten Schäden oder Verluste Ihnen gegenüber haftet (einschließlich, aber nicht beschränkt auf konkrete Verluste von Personen, Sachwerten, Daten usw. sowie immaterielle Verluste wie Reputation und entgangene Gelegenheiten).

Das Unternehmen behält sich vor, die in diesem Benutzerhandbuch beschriebenen Produkte ohne vorherige oder nachträgliche Ankündigung zu ändern.

---



# Vorwort

Vielen Dank, dass Sie sich für den digitalen Drehstrom-Asynchronmotor-Regler der CUH-SDMC30-Serie entschieden haben (im Folgenden kurz „der Regler“). Diese Reglerserie verwendet hochwertige Komponenten, integriert die neueste Elektroniktechnik und wurde mit leistungsstarken digitalen Signalprozessoren sorgfältig konzipiert.

Dieses Handbuch stellt die grundlegende Bedienung, die funktionale technische Beschreibung sowie typische Anwendungsbeispiele dieses Produkts vor. Es bietet Anwendern relevante Informationen zu Installation und Inbetriebnahme, Parametereinstellung, Fehlerdiagnose, Störungsbeseitigung und routinemäßiger Wartung des Reglers. Um die korrekte Installation und Verwendung dieses Reglers sicherzustellen, lesen Sie dieses Benutzerhandbuch bitte vor der Installation sorgfältig durch und bewahren Sie es ordnungsgemäß auf.

Lesen Sie unbedingt die folgenden Symbole, die Sie auf Vorsichtsmaßnahmen gegen Personenschäden und Produktschäden hinweisen.

|  |  |
|---|---|
| ⚠ GEFAHR | Die Nichtbeachtung dieses Punktes führt zu Personenschaden oder Tod. |
| ⚠ WARNUNG | Die Nichtbeachtung dieses Punktes kann zu Personenschaden oder Tod führen. |
| ⚠ VORSICHT | Die Nichtbeachtung dieses Punktes kann zu mittleren oder leichten Personenschäden führen. |
| HINWEIS | Die Nichtbeachtung dieses Punktes führt zu Schäden am Produkt und zu Sachschäden. |
| ❗ ZWINGEND | Kennzeichnet Vorsichtsmaßnahmen und Einsatzbeschränkungen, die während der Nutzung unbedingt zu beachten sind. |

**Dieses Handbuch ist für folgende Reglermodelle geeignet:**

- Digitaler Drehstrom-Asynchronmotor-Regler SDMC30-S

  (Eingang einphasig 85~250 VAC, Ausgang dreiphasig 0~220 Vrmn / 0,2 kW)

---



# Betriebs- und Lagerumgebung

## Prüfung vor der Verwendung

Jeder Regler durchläuft vor der Auslieferung eine strenge Qualitätsprüfung und wird mit stoßsicherer Verpackung versandt. Prüfen Sie nach dem Auspacken folgende Punkte:

1. Ob der Regler während des Transports beschädigt wurde.
2. Ob das Modell des Reglers dem bestellten entspricht.

## Betriebsbedingungen

Beachten Sie bitte die folgenden Hinweise, um eine optimale Leistung und eine lange Lebensdauer des Reglers sicherzustellen:

- ⚠ Gut belüftete Umgebung
- ⚠ Von Wasser, Dampf, Staub und insbesondere öligem Staub fernhalten
- ⚠ Von korrosiven oder brennbaren Gasen und Flüssigkeiten fernhalten
- ⚠ Von schwebendem Staub und Metallpartikeln fernhalten
- ⚠ Fest montieren, um Eigenschwingungen zu vermeiden
- ⚠ Von elektromagnetischen Störungen fernhalten
- ⚠ Umgebungstemperatur von 0~40 ℃ sicherstellen
- ⚠ Nur in Höhenlagen bis 2000 m verwenden

---



# Inhaltsverzeichnis

**Kapitel Ⅰ Vor der Inbetriebnahme — 1**

- 1.1 Prüfen des Lieferumfangs — 1
- 1.2 Beschreibung der Anzeigen und Tasten — 2
- 1.3 Beschreibung der äußeren Bauteile — 3
- 1.4 Beschreibung der Signalanschlüsse — 3
- 1.5 Beschreibung des Typenschilds — 4

**Kapitel Ⅱ Produktvorstellung — 5**

- 2.1 Produktvorstellung — 5

**Kapitel Ⅲ Installationsanleitung — 6**

- 3.1 Betriebsbedingungen des Reglers — 6
- 3.2 Bedienung der Tasten — 6
- 3.3 Installation und Inbetriebnahme — 7

**Kapitel Ⅳ Beschreibung der Grundfunktionen — 11**

- 4.1 Sollfrequenz einstellen — 11
- 4.2 Vorwärts- und Rückwärtslauf — 12
- 4.3 Not-Halt — 13
- 4.4 Sanftanlaufzeit — 14
- 4.5 Sanftauslaufzeit/Gleichstrombremsung — 14
- 4.6 Tastensperre — 15
- 4.7 Wiederherstellen der Werkseinstellungen — 16

**Kapitel Ⅴ Beschreibung der erweiterten Funktionen — 17**

- 5.1 Start/Stopp und Drehrichtungssteuerung des Motors — 17
- 5.2 Drehrichtungswechsel und Untersagung des Rückwärtslaufs — 18
- 5.3 Not-Halt des Motors — 19
- 5.4 Einstellung der Motor-V/F-Kennlinie — 21
- 5.5 Leistungsschutz des Motors — 22

---



# Kapitel Ⅰ Vor der Inbetriebnahme

Dieses Kapitel stellt den Inhalt der Produktverpackung, die Beschreibung der äußeren Bauteile des Reglers sowie die Typenschildinformationen des Reglers vor.

## 1.1 Prüfen des Lieferumfangs

Prüfen Sie vor der Verwendung die Vollständigkeit des Reglers und des Zubehörs. Stellen Sie fest, dass das Produkt defekt oder beschädigt ist oder Zubehör fehlt usw., wenden Sie sich bitte an unser Unternehmen.

![Regler](assets/images/cuh.sdmc30.manual.v0.0/page-0009-vcrop-00.png)

Regler ×1

![Benutzerhandbuch](assets/images/cuh.sdmc30.manual.v0.0/page-0009-vcrop-01.png)

Benutzerhandbuch ×1

![Ausgangskabel](assets/images/cuh.sdmc30.manual.v0.0/page-0009-vcrop-02.png)

Ausgangskabel ×1

![Netzanschlussleitung](assets/images/cuh.sdmc30.manual.v0.0/page-0009-vcrop-03.png)

Netzanschlussleitung ×1

---



## 1.2 Beschreibung der Anzeigen und Tasten

![Beschriftungsdiagramm des SDMC30-S-Bedienfeldes mit Anzeigen, Display und Tasten](assets/images/cuh.sdmc30.manual.v0.0/page-0010-vcrop-00.png)

### Anzeigen

- **Rückwärtsanzeige**  
  Leuchtet, wenn der Motor im Rückwärtslauf oder im Rückwärts-Standby ist.
- **Vorwärtsanzeige** (Hinweis)  
  Leuchtet, wenn der Motor im Vorwärtslauf oder im Vorwärts-Standby ist.
- **Fernsteueranzeige**  
  Leuchtet, wenn das externe Fernsteuersignal für die Drehzahl gültig ist.
- **Fotosensoranzeige**  
  Leuchtet, wenn das Signal am fotoelektrischen Anschluss gültig ist.
- **Drehzahl-A-Anzeige**  
  Leuchtet, wenn Drehzahl A gültig ist.
- **Drehzahl-B-Anzeige**  
  Leuchtet, wenn Drehzahl B gültig ist.
- **Laufanzeige**  
  Leuchtet, wenn der Laufausgang gültig ist.
- **Störungsanzeige**  
  Leuchtet, wenn der Störungsausgang gültig ist.
- **Stopp-Anzeige**  
  Leuchtet, wenn das externe Steuersignal den Motor stoppt.  
  Blinkt, wenn der Motorausgang über die Ein-/Aus-Taste oder das Not-Halt-Signal gesteuert wird.
- **Sperranzeige**  
  Leuchtet, wenn das Bedienfeld gesperrt ist.  
  Blinkt, wenn im gesperrten Zustand auf eine Tastenbetätigung nicht reagiert wird.

### Display und Tasten

- **LED-Anzeige**  
  Zeigt Symbol und Wert der Parameter an.
- **Tasten ⊕/⊖ (Erhöhen/Erniedrigen)**  
  Stellen Parameterwerte ein.  
  Kurzes Drücken: Schritt um eine Einheit.  
  Langes Drücken: beschleunigtes kontinuierliches Verstellen.
- **Tasten ▲/▼ (Auf/Ab)**  
  Wechseln zwischen verschiedenen Parametern.
- **Einstelltaste ⚙**  
  Langes Drücken: Motoreinstellungen vornehmen.  
  Zusammen mit ▲ gedrückt halten: Anschlussparameter einstellen.  
  Zusammen mit ▼ gedrückt halten: Überwachungsparameter anzeigen.
- **Ausgangs-Ein-/Aus-Taste ⏻**  
  Kurzes Drücken: Not-Halt/Wiederherstellung des Motorausgangs.  
  Langes Drücken: Bedienfeld sperren.

### Warnung am Bedienfeld

**GEFAHR**  
GEFAHRLICHE SPANNUNG! BIS ZU 5 MINUTEN NACH DEM TRENNEN VON DER STROMVERSORGUNG LIEGT GEFAHRLICHE SPANNUNG AN! SIEHE BEDIENUNGSANLEITUNG!



### Hinweis

1. Definition: Drehrichtung Vorwärts bezeichnet die Drehrichtung, die sich beim Betrachten der Welle von der Seite der Klemmenleitung aus gemäß dem Motorantrieb ergibt. IEC60034-8 legt die Drehrichtung des Motors fest.
2. Werden zwei Außenleiter vertauscht, dreht der Motor gegen den Uhrzeigersinn, d. h. Vorwärts- und Rückwärtsrichtung werden getauscht.

---



## 1.3 Beschreibung der äußeren Bauteile

> ⚠️ **GEFAHR**
>
> Beim Anschließen des Ausgangskabels die Ausrichtung des PE-Kontakts ausrichten und den Stecker einstecken; niemals ohne Bestätigung der Richtung gewaltsam einstecken.
>
> Wird der Stecker in falscher Richtung eingesteckt, verbleibt hohe Spannung am Motorgehäuse, **was zum Tod oder schweren Verletzungen führen kann.**

> ⚠️ **GEFAHR**
>
> 1. Dieses Produkt gehört zur Schutzklasse I; der dreipolige Stecker der Netzleitung dient dem Schutzerdungsanschluss. Stellen Sie sicher, dass die angeschlossene Steckdose zuverlässig geerdet ist.
> 2. Fehlt die Schutzerdung oder liegt eine fehlerhafte Verbindung vor, verbleibt hohe Spannung auf dem Reglergehäuse; die Berührung des Reglers **kann zum Tod oder zu schweren Verletzungen führen.**

![Diagramm der äußeren Bauteile: Motor-Ausgangsbuchse, Netz-Eingangsbuchse, Kontaktdefinitionen und Netzschalter.](assets/images/cuh.sdmc30.manual.v0.0/page-0011-vcrop-00.png)

**Motor-Ausgangsbuchse**

Kontaktdefinition:
- PE-PE
- 1-U
- 2-V
- 3-W
- 4-nicht belegt

**Netz-Eingangsbuchse**

Kontaktdefinition:
- 1-L
- 2-PE
- 3-N

**Netzschalter**

## 1.4 Beschreibung der Signalanschlüsse

![Diagramm der Signalanschlüsse mit den beiden Klemmenleisten und deren Kontaktbelegung.](assets/images/cuh.sdmc30.manual.v0.0/page-0011-vcrop-01.png)

| Funktion | Kontakt | Definition | Definition | Kontakt | Funktion |
|---|---|---|---|---|---|
| Fernsteuerung Drehzahl | A1 | RGND | GND | E1 | Rückwärtslauf |
| | A2 | Input | Input | E2 | |
| | A3 | 5V Out | 24V Out | E3 | |
| Fotosensor | B1 | GND | GND | G1 | Drehzahl A/B |
| | B2 | RX | Speed A | G2 | |
| | B3 | GND | GND | G3 | |
| | B4 | TX | Speed B | G4 | |
| Vorwärtslauf | C1 | GND | GND | M1 | Not-Halt |
| | C2 | Input | Input | M2 | |
| | C3 | 24V Out | 24V Out | M3 | |
| Laufausgang | D3 | GND | GND | P3 | Störungsausgang |
| | D1 | Output | Output | P1 | |
| | D2 | 24V Out | 24V Out | P2 | |

---



## 1.5 Beschreibung des Typenschilds

![Typenschild-Diagramm mit Produktmodell, Spezifikation, Hersteller und Adresse, QR-Code, Seriennummer und Herstellungsdatum.](assets/images/cuh.sdmc30.manual.v0.0/page-0012-vcrop-00.png)

**CUH® — Digitaler Drehstrom-Asynchronmotor-Regler**

- **Produktmodell**
  - Modell: SDMC30-S
- **Technische Daten**
  - Eingang: AC1PH 85~250 VAC 50/60 Hz 2,8 A
  - Ausgang: AC3PH 0~220 Vrmn 2~120 Hz 1,6 A, 0,6 kVA
  - Maximale Motorleistung: 0,2 kW
  - Nur in Höhenlagen bis 2000 m verwenden
- **Hersteller und Adresse**
  - Nanjing CUH Science & Technology Co., Ltd
  - Adresse: Building 2, Xueyan Tech Park, Tuscity, No.9 Zhineng Rd, Jiangning, Nanjing, China
- **Seriennummer**
  - INS01-202111026db6-010067032BF

**Beschreibung der Seriennummer:**

INS01-202111026db6-010067032BF

- 20211102 → Herstellungsdatum

---



## Kapitel Ⅱ Produktvorstellung

Der Hauptinhalt dieses Kapitels umfasst eine kurze Vorstellung sowie die wesentlichen Merkmale dieses Produkts.

### 2.1 Produktvorstellung

Die SDMC30-Serie digitaler Drehstrom-Asynchronmotor-Regler ist eine kompakte, geräuscharme, vollständig halbleiterbasierte, lüfterlose Umrichtersteuerung, die durch den Einsatz neuester Elektroniktechnik und sorgfältige Auslegung einzigartige Leistung bietet. Ideal für industrielle Anwendungen. Zu den Merkmalen zählen:

- Der Raumzeiger-Pulsweitenmodulations-(SVPWM-)Dreiphasen-Reinsinus-Ausgangsmodus realisiert einen hocheffizienten und leisen Motorbetrieb.
- Die V/F-Kennlinie kann angepasst werden, um unterschiedlichen Lastanwendungen des Motors gerecht zu werden.
- Der fotoelektrische Anschluss unterstützt fotoelektrische Sensoren sowie NPN- und PNP-Schaltsensoren.
- Laufausgang und Störungsausgang dienen zur Anzeige des Betriebs- und Störungszustands des Reglers.
- Der Ausgangsanschluss unterstützt NPN-, PNP- und Push-Pull-Modi.
- Die Antistall-Funktion verhindert, dass der Motor durch Überlast bei Beschleunigung, Verzögerung und Betrieb blockiert.
- Die Gleichstrombremsfunktion kann den Motor beim Herunterfahren oder bei einem Not-Halt schnell zum Stillstand bremsen.
- Umfassende Motorschutzfunktionen wie Überlast/Überstrom/Blockierung/Phasenausfall werden unterstützt.
- Die Helligkeitseinstellung des Bedienfelds unterstützt 32 Helligkeitsstufen.
- Die Rücklaufsperre kann den Motor gegen Rückwärtslauf verriegeln.
- Not-Halt-Funktion mit wählbarem sicheren Momentabschalten (Safe Torque Off), sicherer Bremssteuerung und Sicherheitsstopp der Kategorie 1.
- Bereitschaftssignalfunktion: Gibt über den intelligenten optoelektronischen Übertragungsanschluss B4 ein moduliertes oder gültiges Signal aus, um anzuzeigen, dass sich der Regler im Bereitschaftszustand befindet. Tritt beim Regler ein Fehler auf, wird das Bereitschaftssignal ungültig.
- Die Fernsteuerfunktion unterstützt die Auswahl von 1~5 V, 0~5 V, 0~10 V und 4~20 mA.
- Mit dem Fernsteuerkoeffizienten lässt sich die Wirkung der Fernsteuerspannung um den Faktor 1 verstärken oder abschwächen.
- Die Drehzahl-AB-Funktion unterstützt zwei Schaltsignale zur Steuerung von bis zu vier Motordrehzahlen.
- Vielfältige Steuersignalquellen, logische Verknüpfungen, Schaltverzögerungen und Ausgangsmodi ermöglichen komplexe Anwendungen.
- Umfassende Überwachungsfunktionen können Temperatur, Ausgangsfrequenz, Ausgangsleistung und Signalanschlussspannung überwachen.
- Vollständige Schutzfunktionen: Kurzschlussschutz des Motorausgangs, Überlastschutz des Reglers, Überhitzungs- und Unterkühlungsschutz, Unterspannungs-/Überspannungsschutz der Stromversorgung, Kurzschlussschutz von Laufausgang und Störungsausgang, Kurzschlussschutz des 24-V-Ausgangs sowie Kurzschlussschutz des 5-V-Ausgangs der Drehzahlstellung.

---



# Kapitel Ⅲ Installationsanleitung

Dieses Kapitel beschreibt die notwendigen Bedingungen für den Einsatz des Reglers sowie dessen korrekte Installation und Verdrahtung.

## 3.1 Betriebsbedingungen des Reglers

Der Regler wird mit AC 220 V gespeist; die Schutzerdung erfolgt über den Stecker der Netzleitung. Stellen Sie bitte eine normgerechte 220-V-Netzversorgung mit 50 Hz/60 Hz sowie entsprechende Verteilerinfrastruktur bereit und stellen Sie sicher, dass der Schutzerdungsleiter korrekt angeschlossen ist.

**⚠ WARNUNG** Schließen Sie den Regler niemals an 380 V AC an. Dies verursacht irreversible schwerste Schäden am Regler und kann zu Explosion, Brand und weiteren Sicherheitsvorfällen führen.

**⚠ WARNUNG** Stellen Sie sicher, dass die Netzseite zuverlässig geerdet ist. Das Metallgehäuse des Reglers ist direkt mit dem Schutzerdungsleiter verbunden. Eine mangelhafte Erdung kann dazu führen, dass das Reglergehäuse unter Spannung steht und einen Stromschlagunfall verursacht.

**HINWEIS** Der Langzeitbetrieb erzeugt Wärme und erhöht die Gehäusetemperatur. Installieren Sie den Regler in einer gut belüfteten Umgebung, befestigen Sie ihn ordnungsgemäß und halten Sie ihn von Vibrationsquellen fern.

**HINWEIS** Der Motorausgang dieses Produkts entsteht durch Gleichrichtung und Wechselrichtung des Netzes; eine galvanische Trennstufe ist nicht vorhanden. Daher darf der Ausgangspol nicht mit der Schutzerdung verbunden werden. Stellen Sie beim Anschluss des Motors sicher, dass zwischen der Motorwicklung und dem Gehäuse eine Grundisolation besteht. Andernfalls kommt es zu Ableitströmen, die einen Stromschlag sowie Schäden am Regler verursachen können.

## 3.2 Bedienung der Tasten

Dieser Regler verwendet ein 5-stelliges Digitaldisplay zur Anzeige der Parametersymbole sowie 10 rote Anzeigen, die den Zustand des Reglers bzw. der Signalanschlüsse anzeigen.

Dieser Regler wird mit 6 Tasten bedient; die Bedienung erfolgt wie folgt:

 a. Die Tastenbetätigung wird entsprechend der Druckdauer in kurzes und langes Drücken (Beschleunigung Stufe 1 bzw. Stufe 2) unterteilt.

 b. Kurzes Drücken ist als Druckdauer von mehr als 0,1 s und weniger als 2 s definiert; langes Drücken als Druckdauer von mehr als 2 s.

 c. ⊕ und ⊖ dienen zum Einstellen der Parameterwerte; ▼ und ▲ zur Auswahl verschiedener Parameter.

 d. ⏻ kurz drücken: Not-Halt des Motorausgangs; lange drücken: Bedienfeld sperren/entsperren.

 e. ⚙ lange drücken: Motoreinstellungs-Interface aufrufen/verlassen.

 f. ⚙ und ▲ lange drücken: Anschlussparameter-Interface aufrufen/verlassen.

 g. ⚙ und ▼ lange drücken: Überwachungsparameter-Interface aufrufen/verlassen. In diesem Interface kann mit ⊕ und ⊖ die Sollfrequenz vorübergehend verstellt werden.

---



## 3.3 Installation und Inbetriebnahme

### Schritt Eins:

Öffnen Sie den Umkarton und prüfen Sie den Regler und sämtliches Zubehör.

### Schritt Zwei:

Entnehmen Sie das Ausgangskabel, verbinden Sie die Klemmenleiste des Ausgangskabels mit den Anschlussklemmen des Motors und wählen Sie je nach Typenschild des Motors die Dreieck- oder Sternschaltung. Bestätigen Sie, dass der gelb-grüne Erdungsleiter zuverlässig mit dem Metallgehäuse des Motors verbunden ist.

### Dreieckschaltung

Wird der Regler mit einem Motor △230 V/Y 400 V verbunden, ist die Dreieckschaltung zu verwenden.

![Dreieckschaltung: Verdrahtungsdiagramm mit Ausgangsleitung, Motorklemmkasten und Dreieckswicklung, mit Black-U, Brown-V, Gray-W, Yellow & green-PE sowie Klemmenkennzeichnungen.](assets/images/cuh.sdmc30.manual.v0.0/page-0015-vcrop-00.png)

### Sternschaltung

Wird der Regler mit einem Motor △120 V/Y 230 V verbunden, ist die Sternschaltung zu verwenden.

![Sternschaltung: Verdrahtungsdiagramm mit Ausgangsleitung, Motorklemmkasten und Sternwicklung, mit Black-U, Brown-V, Gray-W, Yellow & green-PE sowie Klemmenkennzeichnungen.](assets/images/cuh.sdmc30.manual.v0.0/page-0015-vcrop-01.png)

### Hinweis

- Gemäß den Festlegungen der IEC60446:
  1. Für die Außenleiter des Wechselstroms werden vorzugsweise Schwarz L1, Braun L2 und Grau L3 verwendet.
  2. Der Schutzleiter PE ist mit der zweifarbigen Kombination Gelb-Grün zu kennzeichnen.
- Dieser Regler gibt dreiphasige 220-V-Leiterspannung aus und ist für 220~240-V-Motoren in Dreieckschaltung oder 220~240-V-Motoren in Sternschaltung geeignet. Wird ein 380-V-Motor angeschlossen, kommt es zu einem starken Drehmomentabfall.

### ⚠ GEFAHR

Stellen Sie unbedingt sicher, dass das Motorgehäuse zuverlässig mit dem PE-Leiter verbunden ist. Andernfalls steht das Gehäuse unter Spannung, was den Tod oder schwere Verletzungen zur Folge haben kann.

### ⚠ WARNUNG

Schließen Sie die Motorklemmen in der Reihenfolge UVW an. Bei falscher Reihenfolge kann der Motor in umgekehrter Richtung laufen und mechanische Gefahren verursachen.

---



## Schritt Drei:

Verbinden Sie den Ausgangsstecker mit der Motor-Ausgangsbuchse des Reglers und ziehen Sie die Übermutter fest.

Entnehmen Sie anschließend die Netzleitung, stecken Sie den Rundstecker der Netzleitung in die Netz-Eingangsbuchse des Reglers und ziehen Sie die Übermutter des Steckers fest.

![Verdrahtungsdiagramm: Das Ausgangskabel verbindet den Regler mit dem Motor; die Netzleitung wird zuerst auf der Reglerseite angeschlossen (zuerst die Reglerseite anschließen) und jetzt noch nicht in die Steckdose eingesteckt.](assets/images/cuh.sdmc30.manual.v0.0/page-0016-vcrop-00.png)

> ⚠ **GEFAHR**
>
> Beim Anschließen des Ausgangskabels die Ausrichtung des PE-Kontakts ausrichten und den Stecker einstecken; niemals ohne Bestätigung der Richtung gewaltsam einstecken.
>
> Wird der Stecker in falscher Richtung eingesteckt, verbleibt hohe Spannung am Motorgehäuse, **was zum Tod oder zu schweren Verletzungen führen kann.**

> ⚠ **GEFAHR**
>
> Zur Vermeidung elektrischer Schläge darf keine Verdrahtung unter Spannung vorgenommen werden. Schalten Sie die Stromversorgung der Anlage unbedingt ab und führen Sie die Verdrahtungsarbeiten erst 5 Minuten nach Erlöschen der Digitalanzeige durch. Bei unsachgemäßer Ausführung **besteht die Gefahr von Tod oder schweren Verletzungen.**

---



### Schritt Vier:

Nachdem Sie bestätigt haben, dass sich der Schalter in der Position AUS befindet, verbinden Sie den Stecker der Netzanschlussleitung mit der Netzsteckdose.

![Netzstecker der Netzanschlussleitung wird mit einer Steckdose verbunden.](assets/images/cuh.sdmc30.manual.v0.0/page-0017-vcrop-00.png)

### Schritt Fünf:

Schalten Sie den Netzschalter ein. Jetzt sollte die Sollfrequenz „F 50.0“ angezeigt werden und die Vorwärts- und Stopp-Anzeigen leuchten. Der Motor dreht sich zu diesem Zeitpunkt nicht.

F bedeutet Sollfrequenz

![SDMC30-S-Bedienfeld mit Anzeige „F 50.0“ und leuchtenden Vorwärts- und Stopp-Anzeigen; die Beschriftung kennzeichnet F als Sollfrequenz.](assets/images/cuh.sdmc30.manual.v0.0/page-0017-vcrop-01.png)

---



## Schritt Sechs:

Verbinden Sie das Vorwärts-Steuersignal oder das Rückwärts-Steuersignal mit dem Regler. Dabei erlischt die Stopp-Anzeige des Reglers, die Laufanzeige leuchtet auf und der Motor beschleunigt allmählich auf 50 Hz.

![Reglerbedienfeld zeigt „F 50.0“; Vorwärts- und Laufanzeige leuchten; Beschriftung „F bedeutet Sollfrequenz“.](assets/images/cuh.sdmc30.manual.v0.0/page-0018-vcrop-00.png)

## Schritt Sieben:

Stellen Sie mit ⊕ und ⊖ die Frequenz auf die optimale Motordrehzahl ein.

![Reglerbedienfeld zeigt „F 50.0“, ein Finger drückt die Minustaste; Beschriftung „F bedeutet Sollfrequenz“.](assets/images/cuh.sdmc30.manual.v0.0/page-0018-vcrop-01.png)

---



## Kapitel Ⅳ Beschreibung der Grundfunktionen

Dieses Kapitel beschreibt die Verwendung der Grundfunktionen dieses Produkts.

### 4.1 Sollfrequenz einstellen

Dieser Regler ermöglicht die digitale Einstellung der Ausgangsfrequenz direkt am Bedienfeld. Da er die direkte digitale Frequenzsynthese (DDS) verwendet, besitzt er eine sehr hohe Frequenzgenauigkeit und Stabilität, die sich mit Zeit und Temperatur nicht ändert.

- Netzschalter des Reglers einschalten.
- Der Regler wechselt in den Bereitschaftszustand mit dem Parameter Sollfrequenz F; die Vorwärts- und Stopp-Anzeigen am Regler leuchten und das LED-Display zeigt den Parameter F und dessen Wert an.
- ⊕ oder ⊖ drücken, um den Parameterwert einzustellen.

![Reglerbedienfeld mit Anzeige „F 50.0“, leuchtenden Vorwärts- und Stopp-Anzeigen; eine Hand zeigt auf die Minustaste; Beschriftung „F bedeutet Sollfrequenz“.](assets/images/cuh.sdmc30.manual.v0.0/page-0019-vcrop-00.png)

Der Einstellbereich der Sollfrequenz beträgt 2,0~120,0 Hz.

> - Der Bereich, in dem die Sollfrequenz F eingestellt werden kann, ist durch die Minimalfrequenz „r“ und die Maximalfrequenz „y“ begrenzt.

---



## 4.2 Vorwärts- und Rückwärtslauf

Dieser Regler verfügt über einen Vorwärtslaufanschluss C und einen Rückwärtslaufanschluss E. Ist das Anschlusssignal ungültig, läuft der Motor nicht und die Stopp-Anzeige leuchtet.

Ist das Signal am Vorwärtslaufanschluss C gültig, läuft der Motor vorwärts; die Stopp-Anzeige ist aus, die Vorwärtsanzeige und die Laufanzeige leuchten.

- ⚙ 2 Sekunden gedrückt halten, um das Motoreinstellungs-Interface aufzurufen.
- Mit ▲ und ▼ in den Einstellzustand der Vorwärts-Start/Stopp-Steuerquelle 1 „P1“ wechseln.
- ⊕ oder ⊖ drücken, um den Parameterwert einzustellen. Die Werkseinstellung dieses Parameters ist C.

![Bedienfeld bei Vorwärtslauf: P1 bedeutet Vorwärts-Start/Stopp-Steuerquelle 1; das C-Signal ist gültig. Vorwärts- und Laufanzeige leuchten.](assets/images/cuh.sdmc30.manual.v0.0/page-0020-vcrop-00.png)

Ist das Signal am Rückwärtslaufanschluss E gültig, läuft der Motor rückwärts; die Stopp-Anzeige ist aus, die Rückwärtsanzeige und die Laufanzeige leuchten.

- ⚙ 2 Sekunden gedrückt halten, um das Motoreinstellungs-Interface aufzurufen.
- Mit ▲ und ▼ in den Einstellzustand der Rückwärts-Steuerquelle 1 „Π1“ wechseln.
- ⊕ oder ⊖ drücken, um den Parameterwert einzustellen. Die Werkseinstellung dieses Parameters ist E.

![Bedienfeld bei Rückwärtslauf: Π1 bedeutet Rückwärts-Steuerquelle 1; das E-Signal ist gültig. Rückwärts- und Laufanzeige leuchten.](assets/images/cuh.sdmc30.manual.v0.0/page-0020-vcrop-01.png)

Hinweis:

1. Sind die Signale an den Vorwärts- und Rückwärtslaufanschlüssen gleichzeitig gültig, meldet der Regler den Fehler Er15 (Vorwärts-/Rückwärtskonflikt) und der Motor läuft nicht.
2. Erfolgt die Verdrahtung gemäß den Motoranschlussanweisungen, so bezeichnet gemäß IEC60034-8 die Vorwärtsdrehrichtung die im Uhrzeigersinn verlaufende Drehung, von der Antriebsseite des Motors aus betrachtet.

---



## 4.3 Not-Halt

Im Notfall kann der Regler in den Not-Halt-Zustand übergehen, um den Motorbetrieb schnell zu stoppen. Der Not-Halt-Zustand kann durch Drücken der Ein-/Aus-Taste am Bedienfeld oder durch ein gültiges Signal am Not-Haltanschluss ausgelöst werden. Dabei blinkt die Stopp-Anzeige und Ar02 (Not-Halt) wird angezeigt.

![Abbildung zum Not-Halt am Bedienfeld: Die Stopp-Anzeige blinkt; Ar02 bedeutet Not-Halt. Eine Hand drückt die Ein-/Aus-Taste des Reglers.](assets/images/cuh.sdmc30.manual.v0.0/page-0021-vcrop-00.png)

- Der durch Drücken der Ein-/Aus-Taste am Bedienfeld ausgelöste Not-Halt-Zustand kann durch erneutes Drücken der Ein-/Aus-Taste aufgehoben werden.
- Der durch ein gültiges Signal am Not-Haltanschluss ausgelöste Not-Halt-Zustand erfordert neben dem Entfernen des Not-Halt-Anschlusssignals zusätzlich das Drücken der Ein-/Aus-Taste am Bedienfeld, um den Zustand aufzuheben.

> Der Not-Halt-Modus kann über den Parameter Sq gewählt werden: sicheres Momentabschalten (Safe Torque Off), sichere Bremssteuerung und Sicherheitsstopp der Kategorie 1. Detaillierte Funktionen siehe Beschreibung der erweiterten Funktionen.

---



## 4.4 Sanftanlaufzeit

Startet dieser Regler aus dem Stopp-Zustand, kann die Motorausgangsfrequenz sanft auf die Sollfrequenz erhöht werden, um Stöße auf den Motor und die Anlage zu vermeiden.

Sanftanlaufzeit (t): Die Zeit, die die Ausgangsfrequenz des Reglers beim Start aus dem Stopp-Zustand für das sanfte Ansteigen von der Minimalfrequenz bis zur Sollfrequenz benötigt, wird als Sanftanlaufzeit bezeichnet.

- ⚙ 2 Sekunden gedrückt halten, um das Motoreinstellungs-Interface aufzurufen.
- Mit ▲ und ▼ in den Einstellzustand der Sanftanlaufzeit „t“ wechseln.
- ⊕ oder ⊖ drücken, um den Parameterwert einzustellen.

Der Bereich der Sanftanlaufzeit beträgt 0,0~99,9 Sekunden.

![Sanftanlaufzeit: t bedeutet Sanftanlaufzeit; der Regler zeigt „t 10.0“ nebst Darstellung der Tastenbedienung.](assets/images/cuh.sdmc30.manual.v0.0/page-0022-vcrop-00.png)

## 4.5 Sanftauslaufzeit/Gleichstrombremsung

Stoppt dieser Regler aus dem Laufzustand, kann die Motorausgangsfrequenz sanft auf die Minimalfrequenz abgesenkt werden, um Stöße auf den Motor und die Anlage zu vermeiden.

Sanftauslaufzeit (![Parametersymbol der Sanftauslaufzeit (annähernd spiegelverkehrtes t)](assets/images/cuh.sdmc30.manual.v0.0/page-0022-vcrop-02.png)): Die Zeit, die die Ausgangsfrequenz des Reglers beim Stopp aus dem Laufzustand für das sanfte Absenken von der Sollfrequenz bis zur Minimalfrequenz benötigt, wird als Sanftauslaufzeit bezeichnet.

- ⚙ 2 Sekunden gedrückt halten, um das Motoreinstellungs-Interface aufzurufen.
- Mit ▲ und ▼ in den Einstellzustand der Sanftauslaufzeit „[[vcrop:22:2]]“ wechseln.
- ⊕ oder ⊖ drücken, um den Parameterwert einzustellen.

Der Bereich der Sanftauslaufzeit beträgt 0,0~99,9 Sekunden.  
Der Bereich der Gleichstrombremszeit beträgt -0,0~-99,9 Sekunden.

![Sanftauslaufzeit: Erläuterung des Parametersymbols, Regleranzeige und Darstellung der Tastenbedienung.](assets/images/cuh.sdmc30.manual.v0.0/page-0022-vcrop-01.png)

---



## 4.6 Tastensperre

Sind die Parameter des Reglers eingestellt, kann die Tastensperre alle Tasten am Bedienfeld verriegeln, um Fehlbedienungen zu vermeiden.

Auch nach dem Ausschalten und erneuten Einschalten bleibt der Zustand der Tastensperre so erhalten, wie er beim letzten Ausschalten war.

- ⏻ 2 Sekunden gedrückt halten, um alle Tasten am Bedienfeld zu sperren. Die Sperranzeige leuchtet auf.
- ⏻ erneut 2 Sekunden gedrückt halten, um die Sperre aufzuheben.

![Abbildung des Reglerbedienfeldes mit Beschriftung der Sperranzeige](assets/images/cuh.sdmc30.manual.v0.0/page-0023-vcrop-00.png)

> Bei gesperrtem Regler reagieren die Tasten nicht, und die Sperranzeige blinkt.

---



## 4.7 Wiederherstellen der Werkseinstellungen

Der Anwender kann den Regler schnell in den werkseitigen Standardzustand zurückversetzen.

Aufgrund der umfangreichen Funktionalität des Reglers sind viele Parameter einstellbar. Für Einsteiger kann es nach mehreren Einstellungen und Änderungen schwierig sein, den normalen Arbeitszustand des Reglers wiederherzustellen. Mit dieser Funktion lässt sich der durcheinandergeratene Parameterzustand schnell auf die Werkseinstellungen zurücksetzen.

- ⚙ und ▲ gleichzeitig lange drücken, um das Anschlussparameter-Interface aufzurufen.

![Einstelltaste und ▲ gleichzeitig drücken.](assets/images/cuh.sdmc30.manual.v0.0/page-0024-vcrop-00.png)

- ▲ kurz drücken, um zum vollständig blinkenden LED-Display zu wechseln; dies ist der Parameter „Wiederherstellen der Werkseinstellungen“. Anschließend ⊕ drücken und halten, bis der Regler „-----“ anzeigt; dies zeigt an, dass der Regler zurückgesetzt wurde.

![Zur Wiederherstellung bereit](assets/images/cuh.sdmc30.manual.v0.0/page-0024-vcrop-01.png)

- ⊕ loslassen; nachdem der Regler „CUH“ angezeigt hat, wechselt er in das normale Bereitschafts-Interface. Damit sind alle Parameter auf die Werkseinstellungen zurückgesetzt.

![Erfolgreich wiederhergestellt](assets/images/cuh.sdmc30.manual.v0.0/page-0024-vcrop-02.png)

> Bevor der Anwender einen Werksreset durchführt, muss er ⏻ drücken, um den Regler in den Not-Halt-Zustand zu versetzen; dabei blinkt die Stopp-Anzeige.

---



## Kapitel Ⅴ Beschreibung der erweiterten Funktionen

Dieses Kapitel beschreibt vor allem die Verwendung der erweiterten Funktionen dieses Produkts.

### 5.1 Start/Stopp und Drehrichtungssteuerung des Motors

Dieser Regler ist mit einem Vorwärts- und einem Rückwärts-Start/Stopp-Signal zur Steuerung von Start/Stopp und Drehrichtung des Motors ausgestattet. Das Vorwärts-Start/Stopp-Signal verfügt über 2 Signalquellen und eine Logik-Berechnungseinheit; dasselbe gilt für das Rückwärtssignal. Mit diesen beiden Signalen können Start/Stopp sowie Vorwärts/Rückwärts des Motors gesteuert werden. Die konkreten logischen Zusammenhänge sind der folgenden Abbildung zu entnehmen.

![Logikdiagramm der Start/Stopp- und Drehrichtungssteuerung: P1 (Werkseinstellung C) und P2 (Werkseinstellung -b) speisen PN (Werkseinstellung And); N1 (Werkseinstellung E) und N2 (Werkseinstellung -b) speisen NN (Werkseinstellung And). Vorwärts- und Rückwärtsdrehung speisen Fr (Werkseinstellung 0), mit den Ausgängen Start/Stopp und Richtung.](assets/images/cuh.sdmc30.manual.v0.0/page-0025-vcrop-00.png)

Vorwärts- und Rückwärts-Start/Stopp-Steuerquellen umfassen jeweils: 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP.

Die logischen Verknüpfungen umfassen: And, Or, Xor, RS-Trigger.

Es gibt zwei Werte für die Vorwärts-/Rückwärts-Steuermodi:

- **Fr=0 bedeutet:** Das Vorwärts-Start/Stopp-Signal steuert Vorwärtsstart und -stopp; ebenso das Rückwärtssignal.
- **Fr=1 bedeutet:** Das Vorwärts-Start/Stopp-Signal steuert Start und Stopp, während das Rückwärtssignal die Drehrichtung steuert.

Hinweis: Bei Fr=0 und gleichzeitig gültigen Vorwärts- und Rückwärtssignalen wird der Fehler Er15 (Vorwärts-/Rückwärtskonflikt) ausgelöst und der Motor angehalten.

---



## 5.2 Drehrichtungswechsel und Untersagung des Rückwärtslaufs

In der Praxis kann es erforderlich sein, die Drehrichtung des Motors zu ändern oder den Lauf in eine bestimmte Richtung – etwa wegen mechanischer Systemgrenzen oder Verdrahtungsgründen – zu untersagen. Hierzu dient der Parameter Ph (Phase) für den Richtungstausch.

- **Bei Ph=Abc** ist die Standardrichtung gemeint, d. h. Vorwärtslauf ist im Uhrzeigersinn, von der Antriebsseite des Motors aus betrachtet.
- **Bei Ph=Acb** ist die getauschte Richtung gemeint, d. h. Vorwärtslauf ist gegen den Uhrzeigersinn, von der Antriebsseite des Motors aus betrachtet.
- **Bei Ph=A.b.c.** ist der Rückwärtslauf bei Standardrichtung untersagt, d. h. der Motor kann nur im Uhrzeigersinn laufen; bei einem Rückwärtslaufbefehl reagiert er nicht und zeigt die Warnung Ar08 (Rückwärtslauf untersagt) an.
- **Bei Ph=A.c.b.** ist der Vorwärtslauf bei getauschter Richtung untersagt, d. h. der Motor kann nur gegen den Uhrzeigersinn laufen; bei einem Vorwärtslaufbefehl reagiert er nicht und zeigt die Warnung Ar08 an.

Die folgende Abbildung zeigt einen Motor im Uhrzeigersinn, dessen Welle von der Antriebsseite aus im Uhrzeigersinn dreht; die Betrachtungsrichtung verläuft von der Antriebs- zur Nicht-Antriebsseite.

![Motor mit Pfeil, der die im Uhrzeigersinn verlaufende Wellendrehung (von der Antriebsseite aus betrachtet) angibt.](assets/images/cuh.sdmc30.manual.v0.0/page-0026-vcrop-00.png)

Die folgende Abbildung zeigt einen Motor gegen den Uhrzeigersinn, dessen Welle von der Antriebsseite aus gegen den Uhrzeigersinn dreht.

![Motor mit Pfeil, der die gegen den Uhrzeigersinn verlaufende Wellendrehung (von der Antriebsseite aus betrachtet) angibt.](assets/images/cuh.sdmc30.manual.v0.0/page-0026-vcrop-01.png)

---



## 5.3 Not-Halt des Motors

Dieser Regler kann den Motor per Not-Halt anhalten; diese Stoppquelle wird durch Drücken der Ein-/Aus-Taste am Bedienfeld oder durch den externen Not-Halt-Schalter wirksam aktiviert.

Die Not-Halt-Quelle kann unterschiedliche Signalquellen wählen; werkseitig ist das Signal des Not-Halt-Anschlusses eingestellt. Die Ein-/Aus-Taste am Bedienfeld ist stets eine wirksame Not-Halt-Quelle.

Abhängig vom Not-Halt-Modus wählt der Parameter Sq unterschiedliche Strategien für den Not-Halt:

- **Sq=Sto:** Der Regler schaltet die Versorgung des Motors sofort ab; der Motor läuft trieblich verzögert aus.
- **Sq=Sbc:** Der Motor wird per Gleichstrombremsung zum Stillstand gebracht; die Bremszeit wird durch die Sanftauslaufzeit bestimmt. Der Störungsausgang gibt den Not-Halt-Zustand aus und wird nicht von der Signalquelle gesteuert; es muss ein Sicherheitsbremsrelais verwendet werden.
- **Sq=SS1:** Der Motor verzögert oder bremst gemäß der durch die Sanftauslaufzeit definierten Funktion bis zum Stillstand.

### Anschlussart des Not-Halt-Schalters

![Anschlussdiagramm des Not-Halt-Schalters: Der Not-Halt-Schalter ist an die Klemmen M1 und M2 angeschlossen.](assets/images/cuh.sdmc30.manual.v0.0/page-0027-vcrop-00.png)

---



### Sto: Sicheres Momentabschalten (Safe Torque Off)

![Sto-Kurve des sicheren Momentabschaltens: Speed V, t, STO, Select Sto sowie die Beschriftung „Motor torque is switched off“.](assets/images/cuh.sdmc30.manual.v0.0/page-0028-vcrop-00.png)

### Sbc: Sicherheitsbremssteuerung

![Sbc-Kurve der Sicherheitsbremssteuerung nebst Schema des Bremskreises: Speed V, t, STO, Select Sbc; die Schaltung ist mit P1, P2, P3 und M beschriftet.](assets/images/cuh.sdmc30.manual.v0.0/page-0028-vcrop-01.png)

### SS1: Sicherheitsstopp der Kategorie 1

![SS1-Kurve des Sicherheitsstopps der Kategorie 1: Safe Stop 1, Delay Time, Speed V, Speed Limit, STO, t und Select SS1.](assets/images/cuh.sdmc30.manual.v0.0/page-0028-vcrop-02.png)

---



## 5.4 Einstellung der Motor-V/F-Kennlinie

Dieser Regler ermöglicht die Anpassung der V/F-Kennlinie, um unterschiedliche Motorlasten abzudecken.

Sie wird definiert durch die Maximalfrequenz y, die Nennfrequenz b, die Nennspannung h, die Zwischenfrequenz n, die Zwischenspannung o, die Minimalfrequenz r und die Minimalspannung u.

![Motor-V/F-Kennlinie: Mittelspannung/V über Frequenz/Hz, mit den Punkten (r, u), (n, o), (b, h) sowie einem horizontalen Abschnitt von b bis y auf dem Spannungsniveau h.](assets/images/cuh.sdmc30.manual.v0.0/page-0029-vcrop-00.png)

**Hinweis:** Aufgrund des induktiven Charakters der Motorlast sind die Ausgangs-Leiterspannungen auf den gleichgerichteten Mittelwert Vrmn kalibriert, um den Strom im linearen Abschnitt der V/F-Kennlinie zu halten. Im Allgemeinen ist der Effektivwert Vrms der Standard-Sinuswelle 1,11-mal so groß wie der gleichgerichtete Mittelwert Vrmn.

---



![Diagramm des Schutzes bei Überschreitung der oberen Motorleistungsgrenze: elektrische Motorleistung/kW und elektronischer Überhitzungsintegrator/s über der Zeit/s, mit den Schwellen Po*rc, Po, Po*rL und oL, der Echtzeit-Leistungskurve des Motors sowie der Integratorsättigung bei Überschreitung der Leistungsgrenze.](assets/images/cuh.sdmc30.manual.v0.0/page-0031-vcrop-00.png)

**Diagramm des Schutzes bei Überschreitung der oberen Motorleistungsgrenze**

Der Regler überwacht die elektrische Leistung des Motors in Echtzeit. Überschreitet die Leistung das Produkt aus der elektrischen Nennleistung Po des Motors und dem Leistungsüberschreitungsfaktor rc, löst dies den Schutz Er02P (Motorleistung über Grenze) aus. Der elektronische Überhitzungsintegrator des Motors geht unmittelbar in Sättigung. Der Regler reduziert die Ausgangsfrequenz, bis die Ausgangsleistung auf die durch den Leistungsdämpfungsfaktor rL definierte Leistung abgesunken ist. Dabei wird der Integrator zurückgesetzt. Nach abgeschlossenem Reset kehrt der Regler zur Sollfrequenz zurück und beginnt einen neuen Schutzzyklus.

---



## 5.6 Fernsteuerung der Motordrehzahl

Neben der Frequenzeinstellung über das Bedienfeld kann dieser Regler die Ausgangsfrequenz auch über externe analoge Signale steuern. Das Analogsignal unterstützt Potenziometer, 1~5 V, 4~20 mA, 0~5 V und 0~10 V; die Auswahl erfolgt über den Parameter Fernsteuerquelle A.

- **A=PAd:** Die Sollfrequenz wird ausschließlich über die Bedienfeldtasten gesteuert.
- **A=1-5V:** Die externe Eingabe 1-5 V stellt die Sollfrequenz zwischen der Minimalfrequenz r und der Maximalfrequenz y ein. Liegt die Spannung zwischen 0 und 0,5 V, ist die Fernsteuerung ungültig und die Sollfrequenz wird über das Bedienfeld gesteuert. Zwischen 0,5 und 1 V ist die Fernsteuerung gültig, jedoch läuft der Regler nicht.
- **A=0-5V:** Externe Eingabe 0-5 V; die Sollfrequenz liegt zwischen der Minimalfrequenz r und der Maximalfrequenz y.
- **A=0-10:** Externe Eingabe 0-10 V; die Sollfrequenz liegt zwischen der Minimalfrequenz r und der Maximalfrequenz y.

Dieser Regler verfügt zudem über den Parameter Fernsteuerkoeffizient c, um die Wirkung der Fernsteuerspannung zu verstärken oder abzuschwächen; er ist im Bereich 0,5~2,0 einstellbar. Bei 0,5 ist die Wirkung der Fernsteuerung auf die Sollfrequenz halbiert, d. h. ferngesteuert lässt sich nur die halbe Maximalfrequenz y erreichen. Bei 2,0 ist die Wirkung der Fernsteuerspannung auf die Ausgangsspannung verdoppelt, d. h. die Sollfrequenz erreicht y bereits bei der halben Fernsteuerspannung. Wird die Fernsteuerspannung weiter erhöht, kann die Ausgangsspannung nicht weiter ansteigen.

### Anschlussart der Potenziometersteuerung

![Potenziometer-Anschlussdiagramm mit Klemmenbezeichnungen, Fernsteuer-Stromversorgung +5 V, Eingang und Widerstandsbezug (resistive ground). Empfehlung: Bitte verwenden Sie ein lineares 1-kΩ-Potenziometer.](assets/images/cuh.sdmc30.manual.v0.0/page-0032-vcrop-00.png)

Ist das Potenziometer angeschlossen, leuchtet die Fernsteueranzeige; die Frequenzeinstellung über das Bedienfeld ist zu diesem Zeitpunkt ungültig.

---



## Anschlussart der 1~5-V-Spannungssteuerung

![Anschlussdiagramm der 1~5-V-Spannungssteuerung, einschließlich Spannungsquelle, Polarität, Klemmenbezeichnungen und Verbindungen.](assets/images/cuh.sdmc30.manual.v0.0/page-0033-vcrop-00.png)

## Anschlussart der 4~20-mA-Stromsteuerung

![Anschlussdiagramm der 4~20-mA-Stromsteuerung, einschließlich Stromquelle, Richtungspfeil, Klemmenbezeichnungen und Verbindungen.](assets/images/cuh.sdmc30.manual.v0.0/page-0033-vcrop-01.png)

1. Wählen Sie A=1-5V; unterstützt werden Potenziometer-, 1~5-V- und 4~20-mA-Eingänge.
2. Bei Auswahl von 0~5 V oder 0~10 V entspricht die Anschlussart der von 1-5 V.

---



## 5.7 Digitale Drehzahlvoreinstellung des Motors

Die Drehzahlvoreinstellung ist eine Funktion, mit der über externe oder interne Steuersignale direkt eine vorbestimmte Drehzahl ausgewählt wird. Sie bildet ein Steuersystem mit bis zu vier Drehzahlen.

![Anschlussdiagramm von Speed Switch A und Speed Switch B mit den Speed-A/B-Anschlüssen des Reglers, mit GND-, Speed-A- und Speed-B-Beschriftungen sowie vollständiger Klemmenleiste.](assets/images/cuh.sdmc30.manual.v0.0/page-0034-vcrop-00.png)

Werkseitig wählt die Drehzahlvoreinstellungsquelle 1 den externen Drehzahl-A-Anschluss SA und die Drehzahlvoreinstellungsquelle 2 den externen Drehzahl-B-Anschluss Sb. Je nach Anwendungsszenario kann die Signalquelle geändert werden, um zwischen verschiedenen Drehzahlen zu wechseln.

Jede Drehzahlvoreinstellungsquelle verfügt über eine entsprechende Anzeige am Bedienfeld, die leuchtet, wenn die Quelle aktiv ist. Die Kombination der beiden Anzeigezustände ergibt 4 Zustände (A und B aus, A an/B aus, A aus/B an, A und B an).

Durch die Kombination der Signale wechselt der Regler in den entsprechenden Drehzahlvoreinstellungs-Zustand; die Sollfrequenz des Reglers kann mit ⊕ und ⊖ verstellt werden. Diese Frequenz wird automatisch gespeichert; das Drehzahlvoreinstellungs-Steuersignal stellt den Regler bei jedem erneuten Eintritt in diesen Zustand unmittelbar auf den gespeicherten Sollfrequenzwert ein.

![SDMC30-S-Bedienfeld mit Kennzeichnung der Drehzahl-A-Anzeige und der Drehzahl-B-Anzeige.](assets/images/cuh.sdmc30.manual.v0.0/page-0034-vcrop-01.png)

---



## 5.8 Schaltsensor

Der Regler ist mit vier schaltenden Sensoranschlüssen ausgestattet: Vorwärts- und Rückwärtslauf, Drehzahl AB sowie Not-Halt. Diese Anschlüsse unterstützen die Modi NPN, PNP, Ut1 und Ut0 und können über den Parameter Schaltsensortyp ΓA eingestellt werden.

- **Der Ut1-Modus ist eine Einzelabtastung:** Vor dem Ungültigwerden des Sensorsignals werden hoher und niedriger Pegel gewechselt, um zu erkennen, ob der Anschluss gültig ist. Nach dem Auffinden eines gültigen Signals wird der Sensortyp des Anschlusses bestimmt und nicht weiter abgetastet.
- **Der Ut0-Modus ist eine Dauerabtastung:** Unabhängig vom Sensortyp wird stets durch Wechseln zwischen hohem und niedrigem Pegel erkannt, ob am Anschluss ein gültiges Signal anliegt.

Die Schaltverzögerung jedes Schaltwerts kann ebenfalls über die entsprechenden Parameter eingestellt werden; Einzelheiten siehe Parametertabelle.

### Anschlussart des Schaltsensors

![Anschlussart des Schaltsensors: Braun+ an +24V Output, Schwarz OUT an Signal und Blau- an GND, mit der Verdrahtung der Reglerklemmen.](assets/images/cuh.sdmc30.manual.v0.0/page-0035-vcrop-00.png)

---



## 5.9 Intelligenter fotoelektrischer Sensoranschluss

Der intelligente fotoelektrische Anschluss dieses Reglers unterstützt Durchlicht- oder Reflexions-Lichtschranken aus Leuchtdioden und Fototrioden; über den Parameter P (Empfindlichkeit des intelligenten fotoelektrischen Anschlusses) kann zudem die Unterstützung von NPN- oder PNP-Schaltsensoren eingestellt werden.

### Anschlussart des fotoelektrischen Sensors

![Anschlussdiagramm des fotoelektrischen Sensors: B1 GND, B2 RX, B3 GND, B4 TX; Anschlüsse der Receive- und Send-Sensoren mit weißer, roter und Kupferleitung.](assets/images/cuh.sdmc30.manual.v0.0/page-0036-vcrop-00.png)

Der Arbeitsabstand des Sensors kann durch Einstellen des Parameters P angepasst werden; je kleiner der Parameter, desto empfindlicher ist der Sensor.

### Anschlussart des Schaltsensors

Wahl des NPN- oder PNP-Typs über den Parameter P.

![Anschlussdiagramm des Schaltsensors mit Braun+, Blau-, Schwarz OUT, +24V Output, Signal- und GND-Verbindungen zu den Klemmenleisten des Reglers.](assets/images/cuh.sdmc30.manual.v0.0/page-0036-vcrop-01.png)

**Hinweis:**

Bei einem P-Wert von nPn oder PnP gibt B4 ein gültiges Signal von 10 mA aus.

Im Bereich von 2 bis 1000 gibt B4 ein moduliertes Signal von 10 mA mit einer Frequenz von etwa 200 Hz aus.

Tritt beim Regler ein Fehler auf, gibt B4 nichts aus. Dies ist die Bereitschaftssignalfunktion.

---



## 5.10 Laufausgang/Störungsausgang

Die Laufaus- und Störungsausgänge können NPN-Ausgang, PNP-Ausgang und Push-Pull-Ausgang unterstützen. Dabei gilt:

- Der NPN-Ausgang ist bei niedrigem Pegel (Low) gültig und im ungültigen Zustand hochohmig.
- Der PNP-Ausgang ist bei hohem Pegel (High) gültig und im ungültigen Zustand hochohmig.
- Der Push-Pull-Ausgang ist bei hohem Pegel (High) gültig und bei niedrigem Pegel (Low) ungültig.

### 5.10.1 Verdrahtung von Laufausgang/Störungsausgang

**Anschlussart des NPN-Ausgangs**

![Anschlussart des NPN-Ausgangs: Verdrahtungsdiagramm von Relais und Reglerklemmen](assets/images/cuh.sdmc30.manual.v0.0/page-0037-vcrop-00.png)

**Anschlussart des PNP- oder Push-Pull-Ausgangs**

![Anschlussart des PNP- oder Push-Pull-Ausgangs: Verdrahtungsdiagramm von Relais und Reglerklemmen](assets/images/cuh.sdmc30.manual.v0.0/page-0037-vcrop-01.png)

> Beim Anschluss eines 24-V-Relais unbedingt die Polarität der Spule prüfen und einen korrekten Anschluss sicherstellen. Da die Ausgangsstromfähigkeit dieses Anschlusses 350 mA beträgt, würde die interne Schutzdiode des Relais bei verpoltem Anschluss den Anschluss dieses Reglers kurzschließen und den Kurzschlussschutz Er07d/P auslösen.

---



## 5.10.2 Signalquelle und Logikdiagramm von Laufausgang/Störungsausgang

Die Steuerung von Laufausgang/Störungsausgang ist das Ergebnis der logischen Verknüpfung zweier Quellen; aus der folgenden Quellenliste kann gewählt werden.

Bedeutungsliste der Signalquellen:

| Signalquelle | Bedeutung |
|---|---|
| 0 | Ungültiges Signal |
| 1 | Gültiges Signal |
| b | Signal des intelligenten fotoelektrischen Anschlusses |
| -b | Invertiertes Signal des intelligenten fotoelektrischen Anschlusses |
| C | Signal des Vorwärtslaufanschlusses |
| -C | Invertiertes Signal des Vorwärtslaufanschlusses |
| E | Signal des Rückwärtslaufanschlusses |
| -E | Invertiertes Signal des Rückwärtslaufanschlusses |
| SA | Signal des Drehzahl-A-Anschlusses |
| -SA | Invertiertes Signal des Drehzahl-A-Anschlusses |
| Sb | Signal des Drehzahl-B-Anschlusses |
| -Sb | Invertiertes Signal des Drehzahl-B-Anschlusses |
| ES | Signal des Not-Halt-Anschlusses |
| -ES | Invertiertes Signal des Not-Halt-Anschlusses |
| od | Signal des Laufausgangsanschlusses |
| -od | Invertiertes Signal des Laufausgangsanschlusses |
| oP | Signal des Störungsausgangsanschlusses |
| -oP | Invertiertes Signal des Störungsausgangsanschlusses |
| oq | Motorausgangssignal |
| -oq | Invertiertes Motorausgangssignal |
| Er | Beliebiges Fehlersignal |
| -Er | Invertiertes beliebiges Fehlersignal |
| Ar | Beliebiges Warnsignal |
| -Ar | Invertiertes beliebiges Warnsignal |

---



## Logikdiagramm von Laufausgang/Störungsausgang:

![Logikdiagramm von Laufausgang/Störungsausgang: Zwei Laufausgangs-Signalquellen speisen And-, Or-, Xor- und RS-Logik, gefolgt von Einschaltverzögerung, Ausschaltverzögerung, Modus und Ausgangstyp.](assets/images/cuh.sdmc30.manual.v0.0/page-0039-vcrop-00.png)

Hinweis: Das Logikdiagramm des Störungsausgangs entspricht dem Logikdiagramm des Laufausgangs.

---



## 5.10.3 Modusbeschreibung von Laufausgang/Störungsausgang

Für Laufausgang/Störungsausgang stehen 2 Modi zur Verfügung: Verzögerungsmodus (delay) und Haltemodus (hold).

**Verzögerungsmodus (delay):** Nachdem das den Laufausgang/Störungsausgang treibende Signal von gültig auf ungültig gewechselt ist, schaltet der Laufausgang/Störungsausgang nach Ablauf der Ausschaltverzögerungszeit ab.

**Haltemodus (hold):** Nachdem das den Laufausgang/Störungsausgang treibende Signal gültig geworden ist, bleibt der Laufausgang/Störungsausgang während der Ausschaltverzögerungszeit eingeschaltet und schaltet erst nach Überschreiten der Ausschaltverzögerungszeit ab.

Der Unterschied zwischen beiden Modi ist nachfolgend als Zeitdiagramm dargestellt; das Eingangssignal ist das nach dem Logikauswahl-Schalter ausgegebene Signal.

![Zeitdiagramm-Vergleich zwischen Haltemodus-Ausgang und Verzögerungsmodus-Ausgang mit dem nach dem Logik-Selektor ausgegebenen Signal. T1: Verzögerung der steigenden Flanke des Ausgangssignals. T2: Verzögerung der fallenden Flanke des Ausgangssignals.](assets/images/cuh.sdmc30.manual.v0.0/page-0040-vcrop-00.png)

---



## 5.11 Einschalt- und Betriebszustand

Die Einstellfunktion des Einschalt-Betriebszustands erlaubt es, den Zustand der Ein-/Aus-Taste nach dem Einschalten festzulegen. Die Einstellung erfolgt über den Betriebszustandsparameter PS.

- **PS=run:** Die Ein-/Aus-Taste des Reglers befindet sich nach dem Einschalten im Zustand Lauf.
- **PS=stP:** Die Ein-/Aus-Taste des Reglers befindet sich nach dem Einschalten im Zustand Stopp.
- **PS=FoL:** Die Ein-/Aus-Taste des Reglers befindet sich nach dem Einschalten im Zustand des letzten Ausschaltens.

![Reglerbedienfeld mit der Anzeige „PS FoL“ und den Beschriftungen „PS bezeichnet den Einschalt-Betriebszustand“ und „FoL – folgt dem vorherigen Zustand“.](assets/images/cuh.sdmc30.manual.v0.0/page-0041-vcrop-00.png)

> FoL bezeichnet den Zustand, in dem sich der Regler vor dem Ausschalten befand.
>
> Befand sich der Regler vor dem Ausschalten im Not-Halt-Zustand mit blinkender Stopp-Anzeige, verbleibt er beim erneuten Einschalten in diesem Zustand.

---



## 5.12 Helligkeitseinstellung des Bedienfeldes

Dieser Regler verwendet einen neuen digitalen Anzeigetreiberbaustein, der es Anwendern ermöglicht, den Anzeigehelligkeitswert über den Parameter LED zwischen 1 und 32 einzustellen.

![Reglerbedienfeld mit der Anzeige „LEd32“ und den Beschriftungen „LEd bezeichnet die Helligkeit“ und „Bedienfeldhelligkeit auf 32 eingestellt“.](assets/images/cuh.sdmc30.manual.v0.0/page-0042-vcrop-00.png)



# Kapitel Ⅵ Technische Daten

## 6.1 Abmessungen　(Einheit: mm)

![Abmessungszeichnungen des Reglers, Seiten- und Frontansicht, mit den Maßen der Befestigungsbohrungen (Einheit: mm).](assets/images/cuh.sdmc30.manual.v0.0/page-0044-vcrop-00.png)

| Größenbereich | Toleranz |
|---|---|
| 0~3 | ±0,05 |
| 3~10 | ±0,1 |
| 10~30 | ±0,15 |
| 30~80 | ±0,2 |
| 80~180 | ±0,3 |
| >180 | ±0,5 |

> **! ZWINGEND**
>
> Befestigen Sie das Produkt unbedingt auf einer stabilen Plattform und nutzen Sie dazu die oberen und unteren Befestigungsbohrungen des Reglers. Installieren Sie das Gerät fern von der Aufstellung schwingungsbehafteter Geräte.

Diese Toleranztabelle gilt für alle Produkte dieser Serie.

---



## 6.2 Technische Daten

| Position | Min | Typ | Max | Einheit | Hinweis |
|---|---|---|---|---|---|
| Eingangsspannung | 85 | 220 | 250 | V | 50/60 Hz AC RMS |
| Ausgangs-Leiterspannung | 0 | 200 | 220 | Vrmn | Gleichgerichteter Mittelwert |
| Effektiver Eingangsstrom | —— | —— | 2,8 | A | |
| Eingangsstrom-Spitzenwert | —— | —— | 8,0 | A | |
| Einstellbereich des Ausgangsstroms | 0 | —— | 1,6 | A | Gleichgerichteter Mittelwert |
| Ausgangsleistung | 0 | —— | 600 | VA | |
| Ausgangsfrequenz | 2,0 | —— | 120,0 | Hz | |
| Frequenzeinstellgenauigkeit | | 0,1 | | Hz | |
| Ausgangswellenform | | Vektor-Sinus | | | |
| Zulässige Motorleistung | —— | —— | 0,2 | kW | 1/4 HP |
| Auslösetemperatur des Überhitzungsschutzes | —— | 65 | —— | ℃ | Rückkehr bei 60 ℃ |
| DC-Steuerausgangsstrom | 0 | —— | 350 | mA | |
| 24-V-Ausgangsstrom | —— | —— | 700 | mA | |
| DC-Steuerausgangsspannung | 22 | 24 | 26 | V | |
| Analogen Steuersignaleingang | | 4~20 / 1~5、0~5、0~10 | | mA / V | Über Parameter A gesteuert |
| Digitales Steuersignal | | 24 | | V | Schaltsignal |
| Einstellmethode | | 6 | | Taste | |
| Leistungsaufnahme im Bereitschaftszustand | —— | 3 | —— | W | |
| Anzeigeart | | 5 | | Stelle | LED |
| Gewicht | | 830 | | g | ohne Zubehör |
| Abmessungen | | 190\*61.8\*94.5 (L\*B\*H) | | mm | |
| Schutzart | | IP20 | | | |
| Umgebungstemperatur | -10 | 25 | 40 | ℃ | keine Kondensation |
| Umgebungsluftfeuchte | 10 | 60 | 85 | % | keine Kondensation |
| Lagerumgebungstemperatur | -20 | 25 | 85 | ℃ | keine Kondensation |
| Zulässige Höhenlage | | <2000 | | m | |



# Kapitel Ⅶ Anhang

## 7.1 Parametertabelle

| Parameter | Definition | Symbol | Anzeigesymbol | Bereich | Werkseinstellung |
|---|---|---|---|---|---|
| Bereitschaftsparameter | Sollfrequenz | F | ![Anzeigesymbol Sollfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-00.png) | 2,0~120,0 (Hz) (begrenzt durch r und y) | 50,0 |
| Motorparameter — ⚙ lange drücken | Vorwärts-Start/Stopp-Steuerquelle 1 | F1 | ![Anzeigesymbol Vorwärts-Start/Stopp-Steuerquelle 1](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-01.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | C |
| Motorparameter | Vorwärts-Start/Stopp-Steuerquelle 2 | F2 | ![Anzeigesymbol Vorwärts-Start/Stopp-Steuerquelle 2](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-02.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | -b |
| Motorparameter | Logische Verknüpfung Vorwärts-Start/Stopp | FA | ![Anzeigesymbol Logische Verknüpfung Vorwärts-Start/Stopp](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-03.png) | And, or, Xor, rS | And |
| Motorparameter | Rückwärts-Steuerquelle 1 | A1 | ![Anzeigesymbol Rückwärts-Steuerquelle 1](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-04.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | E |
| Motorparameter | Rückwärts-Steuerquelle 2 | A2 | ![Anzeigesymbol Rückwärts-Steuerquelle 2](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-05.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | -b |
| Motorparameter | Logische Verknüpfung Rückwärts | AA | ![Anzeigesymbol Logische Verknüpfung Rückwärts](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-06.png) | And, or, Xor, rS | And |
| Motorparameter | Vorwärts-/Rückwärts-Steuermodus | Fr | ![Anzeigesymbol Vorwärts-/Rückwärts-Steuermodus](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-07.png) | 0 (Die Vorwärts-Steuerquelle dient zum Starten und Stoppen des Vorwärtslaufs, die Rückwärts-Steuerquelle zum Starten und Stoppen des Rückwärtslaufs)<br>1 (Die Vorwärts-Steuerquelle dient zum Steuern von Start und Stopp, die Rückwärts-Steuerquelle zur Steuerung von Vorwärts und Rückwärts) | 0 |
| Motorparameter | Not-Halt-Quelle | Eq | ![Anzeigesymbol Not-Halt-Quelle](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-08.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | ES |
| Motorparameter | Not-Halt-Typ | Sq | ![Anzeigesymbol Not-Halt-Typ](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-09.png) | Sto: sicheres Momentabschalten, Sbc: Sicherheitsbremssteuerung,<br>SS1: Sicherheitsstopp Kategorie 1　(Hinweis 1) | Sto |
| Motorparameter | Sanftanlaufzeit | t | ![Anzeigesymbol Sanftanlaufzeit](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-10.png) | 0,0~99,9 (s) | 10,0 |
| Motorparameter | Sanftauslaufzeit | d | ![Anzeigesymbol Sanftauslaufzeit](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-11.png) | Gleichstrombremszeit: -0,0~-99,9 (s)<br>Sanftauslaufzeit: 0,0~99,9 (s) | 10,0 |
| Motorparameter | Maximalfrequenz | y | ![Anzeigesymbol Maximalfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-12.png) | 2,0~120,0 (Hz) | 50,0 |
| Motorparameter | Nennfrequenz | b | ![Anzeigesymbol Nennfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-13.png) | 45,0~65,0 (Hz) | 50,0 |
| Motorparameter | Nennspannung | h | ![Anzeigesymbol Nennspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-14.png) | 70~220 (Vrmn) | 200 |
| Motorparameter | Zwischenfrequenz | n | ![Anzeigesymbol Zwischenfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-15.png) | r~b (Hz) | 10,0 |
| Motorparameter | Zwischenspannung | o | ![Anzeigesymbol Zwischenspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-16.png) | u~h (Vrmn) | 40 |
| Motorparameter | Minimalfrequenz | r | ![Anzeigesymbol Minimalfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-17.png) | 2,0~n (Hz) | 2,0 |
| Motorparameter | Minimalspannung | u | ![Anzeigesymbol Minimalspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-18.png) | 0~o (Vrmn) | 8 |
| Motorparameter | Elektrische Nennleistung des Motors | Pn | ![Anzeigesymbol Elektrische Nennleistung des Motors](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-19.png) | 0,01~0,20 (kW) | 0,20 |
| Motorparameter | Leistungsüberschreitungsfaktor | rc | ![Anzeigesymbol Leistungsüberschreitungsfaktor](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-20.png) | 100~150 (%) | 150 |
| Motorparameter | Bremsstromkoeffizient | cb | ![Anzeigesymbol Bremsstromkoeffizient](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-21.png) | 10~150 (%) | 100 |
| Motorparameter | Überhitzungsschwelle der elektrischen Leistung | oL | ![Anzeigesymbol Überhitzungsschwelle der elektrischen Leistung](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-22.png) | 0~90 (Mal*Sekunden)<br>Anmerkung: Wird die elektrische Nennleistung des Motors überschritten, ohne die obere Motorleistungsgrenze zu überschreiten, und übersteigt das Integral pro Sekunden diese Einstellung, wird der elektronische Überhitzungsschutz aktiviert. | 30 |
| Motorparameter | Leistungsdämpfungsfaktor | rL | ![Anzeigesymbol Leistungsdämpfungsfaktor](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-23.png) | 0~90 (%)<br>0 bedeutet Abschaltung,<br>90 bedeutet Reduzierung auf 90 % der Nennleistung. | 0 |
| Motorparameter | Drehrichtungswechsel (Hinweis 2) | Ph | ![Anzeigesymbol Drehrichtungswechsel](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-24.png) | Abc: Standardrichtung, Acb: Richtungstausch,<br>A.b.c.: Rückwärtslauf bei Standardrichtung untersagt (nur Vorwärtslauf),<br>A.c.b.: Richtungstausch, Vorwärtslauf untersagt (nur Rückwärtslauf) | AbC |
| Motorparameter | Einschalt-Betriebszustand | PS | ![Anzeigesymbol Einschalt-Betriebszustand](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-25.png) | run: Lauf, stp: Stopp, FoL: letzten Zustand speichern | FoL |



**Anschlussparameter**  
⚙ und ▲ lange drücken

| Definition | Symbol | Anzeigesymbol | Bereich | Werkseinstellung |
|---|---|---|---|---|
| Empfindlichkeit des intelligenten fotoelektrischen Anschlusses | P | ![Anzeigesymbol Empfindlichkeit des intelligenten fotoelektrischen Anschlusses](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-00.png) | nPn, PnP, 2~1000 | nPn |
| Einschaltverzögerung des intelligenten fotoelektrischen Anschlusses | J | ![Anzeigesymbol Einschaltverzögerung des intelligenten fotoelektrischen Anschlusses](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-01.png) | 0,0~99,9 (s) | 0,2 |
| Ausschaltverzögerung des intelligenten fotoelektrischen Anschlusses | L | ![Anzeigesymbol Ausschaltverzögerung des intelligenten fotoelektrischen Anschlusses](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-02.png) | 0,0~99,9 (s) | 0,2 |
| Schaltsensortyp | rA | ![Anzeigesymbol Schaltsensortyp](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-03.png) | nPn, PnP, Ut1: Einzelabtastung, Ut0: Dauerabtastung | Ut0 |
| Einschaltverzögerung Vorwärtslauf | JC | ![Anzeigesymbol Einschaltverzögerung Vorwärtslauf](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-04.png) | 0,0~99,9 (s) | 0,2 |
| Ausschaltverzögerung Vorwärtslauf | LC | ![Anzeigesymbol Ausschaltverzögerung Vorwärtslauf](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-05.png) | 0,0~99,9 (s) | 0,2 |
| Einschaltverzögerung Rückwärtslauf | JE | ![Anzeigesymbol Einschaltverzögerung Rückwärtslauf](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-06.png) | 0,0~99,9 (s) | 0,2 |
| Ausschaltverzögerung Rückwärtslauf | LE | ![Anzeigesymbol Ausschaltverzögerung Rückwärtslauf](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-07.png) | 0,0~99,9 (s) | 0,2 |
| Einschaltverzögerung Drehzahl A/B | JG | ![Anzeigesymbol Einschaltverzögerung Drehzahl A/B](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-08.png) | 0,0~99,9 (s) | 0,2 |
| Ausschaltverzögerung Drehzahl A/B | LG | ![Anzeigesymbol Ausschaltverzögerung Drehzahl A/B](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-09.png) | 0,0~99,9 (s) | 0,2 |
| Einschaltverzögerung Not-Halt | JJ | ![Anzeigesymbol Einschaltverzögerung Not-Halt](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-10.png) | 0,0~99,9 (s) | 0,2 |
| Ausschaltverzögerung Not-Halt | LL | ![Anzeigesymbol Ausschaltverzögerung Not-Halt](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-11.png) | 0,0~99,9 (s) | 0,2 |
| Drehzahlvoreinstellungsquelle 1 | S1 | ![Anzeigesymbol Drehzahlvoreinstellungsquelle 1](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-12.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | SA |
| Drehzahlvoreinstellungsquelle 2 | S2 | ![Anzeigesymbol Drehzahlvoreinstellungsquelle 2](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-13.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | Sb |
| Laufausgangs-Signalquelle 1 | Ed | ![Anzeigesymbol Laufausgangs-Signalquelle 1](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-14.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | oq |
| Laufausgangs-Signalquelle 2 | td | ![Anzeigesymbol Laufausgangs-Signalquelle 2](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-15.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | 0 |
| Logische Verknüpfung Laufausgang | Ad | ![Anzeigesymbol Logische Verknüpfung Laufausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-16.png) | And, or, Xor, rS | or |
| Einschaltverzögerung Laufausgang | Jd | ![Anzeigesymbol Einschaltverzögerung Laufausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-17.png) | 0,0~99,9 (s) | 0,0 |
| Ausschaltverzögerung Laufausgang | Ld | ![Anzeigesymbol Ausschaltverzögerung Laufausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-18.png) | 0,0~99,9 (s) | 0,0 |
| Laufausgangsmodus | Fd | ![Anzeigesymbol Laufausgangsmodus](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-19.png) | dLy (Verzögerungsmodus), HLd (Haltemodus) | dLy |
| Logikrichtung Laufausgang | Sd | ![Anzeigesymbol Logikrichtung Laufausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-20.png) | `---` gleichphasig, `-﹉-` invertiert,<br>on (Öffner), oFF (Schließer) | `---` |
| Laufausgangstyp | rd | ![Anzeigesymbol Laufausgangstyp](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-21.png) | nPn, PnP, PSP (Push-Pull) | nPn |
| Störungsausgangs-Signalquelle 1 | EP | ![Anzeigesymbol Störungsausgangs-Signalquelle 1](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-22.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | Er<br>(Fehlersignal) |
| Störungsausgangs-Signalquelle 2 | 2P | ![Anzeigesymbol Störungsausgangs-Signalquelle 2](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-23.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | Ar<br>(Warnsignal) |
| Logische Verknüpfung Störungsausgang | AP | ![Anzeigesymbol Logische Verknüpfung Störungsausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-24.png) | And, or, Xor, rS | or |
| Einschaltverzögerung Störungsausgang | JP | ![Anzeigesymbol Einschaltverzögerung Störungsausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-25.png) | 0,0~99,9 (s) | 0,0 |
| Ausschaltverzögerung Störungsausgang | LP | ![Anzeigesymbol Ausschaltverzögerung Störungsausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-26.png) | 0,0~99,9 (s) | 0,0 |
| Störungsausgangsmodus | FP | ![Anzeigesymbol Störungsausgangsmodus](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-27.png) | dLy (Verzögerungsmodus), HLd (Haltemodus) | dLy |
| Logikrichtung Störungsausgang | SP | ![Anzeigesymbol Logikrichtung Störungsausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-28.png) | `---` gleichphasig, `-﹉-` invertiert,<br>on (Öffner), oFF (Schließer) | `---` |
| Störungsausgangstyp | rP | ![Anzeigesymbol Störungsausgangstyp](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-29.png) | nPn, PnP, PSP (Push-Pull) | nPn |

Anzeigesymbole der Logikrichtung: ![Anzeigesymbole für gleichphasig und invertiert](assets/images/cuh.sdmc30.manual.v0.0/page-0048-vcrop-30.png)



| | Definition | Symbol | Anzeigesymbol | Bereich | Werkseinstellung |
|---|---|---|---|---|---|
| Anschlussparameter | Fernsteuerquelle | A | ![Anzeigesymbol Fernsteuerquelle](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-00.png) | Pad (Tastensteuerung), 1-5V, 0-5V, 0-10 | 1-5V |
| Anschlussparameter | Fernsteuerkoeffizient | r | ![Anzeigesymbol Fernsteuerkoeffizient](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-01.png) | 0,50~2,00 | 1,00 |
| Anschlussparameter | Bedienfeldhelligkeit | LEd | ![Anzeigesymbol Bedienfeldhelligkeit](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-02.png) | 1~32 | 16 |
| Anschlussparameter | Wiederherstellen der Werkseinstellungen | 8.8.8.8.8. | ![Anzeigesymbol Wiederherstellen der Werkseinstellungen](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-03.png) | —— | —— |
| Überwachungsparameter<br>⚙ und ▼ lange drücken | Reglertemperatur | C | ![Anzeigesymbol Reglertemperatur](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-04.png) | -20,0~85,0 (℃) | —— |
| Überwachungsparameter | Ausgangsfrequenz | E | ![Anzeigesymbol Ausgangsfrequenz](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-05.png) | 2,0~120,0 (Hz) | —— |
| Überwachungsparameter | System-Wirkleistung<br>(Regler + Motor) | qP | ![Anzeigesymbol System-Wirkleistung](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-06.png) | 0,00~0,40 (kW) | —— |
| Überwachungsparameter | Busstrom | AC | ![Anzeigesymbol Busstrom](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-07.png) | 0,00~3,50 (A) | —— |
| Überwachungsparameter | Ausgangsspannung | dU | ![Anzeigesymbol Ausgangsspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-08.png) | 0~250 (V) | —— |
| Überwachungsparameter | Busspannung | PU | ![Anzeigesymbol Busspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-09.png) | 0~400 (V) | —— |
| Überwachungsparameter | 24-V-Ausgangsspannung | nU | ![Anzeigesymbol 24-V-Ausgangsspannung](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-10.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Fernsteueranschluss | AU | ![Anzeigesymbol Spannung am Fernsteueranschluss](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-11.png) | 0,0~10,0 (V) | —— |
| Überwachungsparameter | Signalspannung am intelligenten fotoelektrischen Anschluss | bU | ![Anzeigesymbol Signalspannung am intelligenten fotoelektrischen Anschluss](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-12.png) | 0~999 | —— |
| Überwachungsparameter | Spannung am Vorwärtssignal | tU | ![Anzeigesymbol Spannung am Vorwärtssignal](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-13.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Laufausgang | dU | ![Anzeigesymbol Spannung am Laufausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-14.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Rückwärtssignal | EU | ![Anzeigesymbol Spannung am Rückwärtssignal](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-15.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Drehzahl-A-Anschluss | SA | ![Anzeigesymbol Spannung am Drehzahl-A-Anschluss](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-16.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Drehzahl-B-Anschluss | Sb | ![Anzeigesymbol Spannung am Drehzahl-B-Anschluss](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-17.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Not-Halt-Anschluss | SU | ![Anzeigesymbol Spannung am Not-Halt-Anschluss](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-18.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Spannung am Störungsausgang | FU | ![Anzeigesymbol Spannung am Störungsausgang](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-19.png) | 0,0~28,0 (V) | —— |
| Überwachungsparameter | Version der Steuerplatine | uc | ![Anzeigesymbol Version der Steuerplatine](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-20.png) | —— | —— |
| Überwachungsparameter | Version der Leistungsplatine | uq | ![Anzeigesymbol Version der Leistungsplatine](assets/images/cuh.sdmc30.manual.v0.0/page-0049-vcrop-21.png) | —— | —— |

Hinweis 1: Bei Sto schaltet der Regler die Versorgung des Motors sofort ab; der Motor läuft trieblich verzögert aus.

Bei Sbc wird der Motor per Gleichstrombremsung zum Stillstand gebracht; die Bremszeit wird durch die Sanftauslaufzeit bestimmt. Der Störungsausgang gibt den Not-Halt-Zustand aus, wird nicht von der Signalquelle gesteuert, und es muss ein Sicherheitsbremsrelais verwendet werden.

Bei SS1 verzögert oder bremst der Motor gemäß der durch die Sanftauslaufzeit definierten Funktion bis zum Stillstand.

Hinweis 2: Gemäß IEC60034-8 ist die Standardrichtung wie folgt definiert: die im Uhrzeigersinn verlaufende Drehrichtung, von der Antriebsseite des Motors aus betrachtet; dieser Parameter beeinflusst nicht den Zustand der Vorwärts- und Rückwärtsanzeigen.

---



## 7.2 Ein- und Ausgangs-Schaltbilder

![Schaltbild des Fernsteuer-Drehzahlanschlusses A: A3 +5V, A2 Input, A1 RGND; 5V Output, 10KΩ, 100KΩ, 10uF und 249Ω.](assets/images/cuh.sdmc30.manual.v0.0/page-0050-vcrop-00.png)

**Fernsteuer-Drehzahlanschluss A**

![Schaltbild des intelligenten Fotosensor-Anschlusses B: B4 TX, B3 GND, B2 RX, B1 GND; P 24V/2,4kΩ, 300Ω, zwei 10KΩ-Widerstände; Fotosensor oder NPN: +5 V, PNP: 0 V.](assets/images/cuh.sdmc30.manual.v0.0/page-0050-vcrop-01.png)

**Intelligenter Fotosensor-Anschluss B**

![Schaltbild von Laufausgang D/Störungsausgang P: D2/P2 24V Output, D1/P1 Output, D3/P3 GND; 24 V, zwei 28-V-Beschriftungen und Überstromschutzschaltung.](assets/images/cuh.sdmc30.manual.v0.0/page-0050-vcrop-02.png)

**Laufausgang D/Störungsausgang P**

---



![Schaltbild von Vorwärtslaufanschluss C/Rückwärtslaufanschluss E/Not-Haltanschluss M/Drehzahlvoreinstellungsanschluss G. Beschriftungen umfassen 24 V, 2.4KΩ und automatische Sensor-Typerkennung.](assets/images/cuh.sdmc30.manual.v0.0/page-0051-vcrop-00.png)

| Anschluss | Funktion |
|---|---|
| C3/E3/M3 | 24V-Ausgang |
| C2/E2/M2/G2/G4 | Eingang |
| C1/E1/M1/G1/G3 | GND |

**Vorwärtslaufanschluss C/Rückwärtslaufanschluss E/**  
**Not-Haltanschluss M/Drehzahlvoreinstellungsanschluss G**

---



## 7.3 Fehlercodes

| Fehlercode | Bedeutung | Eintrittsbedingungen | Reaktion des Reglers | Störungsbeseitigung |
|---|---|---|---|---|
| Er01 | Kurzschluss des Hauptausgangs | Kurzschluss der Ausgangsphasen untereinander oder gegen PE | Hauptausgang stoppen; mit kurzem Druck auf die Ein-/Aus-Taste quittieren. | ◆ Den Ausgang kurzschließen oder den Ausgangsschalter zweimal ausschalten und anschließend wieder einschalten. |
| Er02H | Elektronik-Überhitzung des Motors | Motor überschreitet die Überhitzungsschwelle der elektrischen Leistung | Stopp und automatischer Neustart oder Betrieb mit verminderter Leistung je nach Einstellung des Dämpfungsfaktors. | ◆ Die eingestellte Motorbetriebsfrequenz ggf. angemessen reduzieren. |
| Er02P | Motorleistung über Grenze | Die Ausgangsleistung überschreitet den Leistungsüberschreitungsfaktor | Stopp und automatischer Neustart oder Betrieb mit verminderter Leistung je nach Einstellung des Dämpfungsfaktors. | ◆ Die eingestellte Motorbetriebsfrequenz ggf. angemessen reduzieren. |
| Er03L | Unterkühlung | Die Reglertemperatur liegt unter -20 ℃ | Hauptausgang stoppen.<br>Bei Rückkehr der Temperatur auf den Normalbereich wird der Ausgang automatisch wieder gestartet. | ◆ Aktivierung des Reglers bei extremen Kälte-Temperaturen vermeiden. |
| Er03H | Überhitzung | Die Reglertemperatur liegt über 65 ℃ | Hauptausgang stoppen.<br>Bei Rückkehr der Temperatur auf den Normalbereich wird der Ausgang automatisch wieder gestartet. | ◆ Installieren Sie den Regler in einer gut belüfteten Umgebung. |
| Er04L | Unterspannung | Die mittlere Busspannung liegt unter 77 V | Hauptausgang stoppen.<br>Bei normaler Versorgungsspannung wird der Ausgang automatisch wiederhergestellt. | ◆ Sicherstellen, dass die Eingangsspannung zwischen 85 V und 250 V liegt. |
| Er04H | Überspannung | Die mittlere Busspannung liegt über 390 V | Hauptausgang stoppen.<br>Bei normaler Versorgungsspannung wird der Ausgang automatisch wiederhergestellt. | ◆ Sicherstellen, dass die Eingangsspannung zwischen 85 V und 250 V liegt. |
| Er05 | Interne Kommunikationsstörung | 2 Sekunden in Folge keine Antwort der Leistungsplatine | Hauptausgang stoppen.<br>Wird bei Wiederherstellung der Kommunikation automatisch beseitigt. | ◆ Sicherstellen, dass am 24-V-Stromanschluss keine externe Spannung anliegt, oder unseren technischen Support kontaktieren. |
| Er06 | Störung des Temperatursensors | Temperatur nicht lesbar | Hauptausgang stoppen und 2 Sekunden lang erneut versuchen, die Temperatur zu lesen. | ◆ Kontaktieren Sie unseren technischen Support. |
| Er07d/P | Kurzschluss Lauf-/Störungsausgang | Ausgangsstrom überschreitet 350 mA oder Kurzschluss | Lauf-/Störungsausgang innerhalb von 5 ms abschalten,<br>2 Sekunden später Ausgangs-Neustart versuchen. | ◆ Sicherstellen, dass die Last nicht kurzgeschlossen ist und der Strom 350 mA nicht überschreitet. |
| Er10 | Kurzschluss des 24-V-Ausgangs | Der 24-V-Ausgang ist kurzgeschlossen oder der Strom überschreitet 700 mA | 24-V-Ausgang stoppen; durch erneutes Einschalten wird der Ausgang wieder gestartet. | ◆ Sicherstellen, dass der 24-V-Ausgang nicht kurzgeschlossen ist oder den Strom von 700 mA überschreitet. |
| Er11 | Störung des 5-V-Ausgangs | 5-V-Ausgang verlässt den Bereich von ±10 % | Die Fernsteuerung der Drehzahl fällt aus; automatisch wiederherstellbar | ◆ Sicherstellen, dass der 5-V-Ausgang nicht kurzgeschlossen oder mit externer Spannung verbunden wurde. |
| Er12 | 24-V-Spannungsstörung | Prüfung, ob die interne 24-V-Spannung zwischen 22~26 V liegt | Steuerausgangsanschluss geht in hochohmigen Zustand; automatisch wiederherstellbar | ◆ Sicherstellen, dass am 24-V-Stromausgangs- oder Steuerausgangsanschluss keine externe Stromversorgung angeschlossen ist. |
| Er13 | Eingangsphasenausfall<br>(nur bei Dreiphasen-Eingangsmodellen) | Phasenausfall der Dreiphasen-Stromeingabe | Hauptausgang stoppen | ◆ Spannung abschalten, den Phasenausfall am Eingang beseitigen und wieder einschalten. |
| Er14 | Ausgangsphasenausfall | Unsymmetrie der Ausgangsphasenströme von mehr als 50 % | Hauptausgang stoppen | ◆ Spannung abschalten, den Phasenausfall am Ausgang beseitigen und wieder einschalten. |
| Er15 | Vorwärts-/Rückwärtskonflikt | Vorwärts- und Rückwärtssignale liegen gleichzeitig an | Hauptausgang stoppen; nach Beseitigung des Konflikts automatisch wiederherstellbar | ◆ Sicherstellen, dass Vorwärts- und Rückwärtssignale nicht gleichzeitig anliegen. |



## Kapitel Ⅷ Produktgarantie

### 8.1 Garantiezeitraum

Die von der Firma für dieses Produkt gewährte Garantiezeit beträgt 3 Jahre ab Auslieferung des Produkts an den vom Käufer bestimmten Ort.

### 8.2 Garantieumfang

(1) Tritt innerhalb der oben genannten Garantiezeit ein von unserem Unternehmen verursachter Fehler auf, reparieren wir das Produkt kostenlos. Die folgenden Situationen sind jedoch nicht von der Garantie abgedeckt:

a. Nichteinhaltung der in der Kurzanleitung, im Benutzerhandbuch oder in den speziell zwischen Käufer und Firma vereinbarten technischen Anforderungen festgelegten Bedingungen, unsachgemäße Bedienung oder Fehler durch unsachgemäße Verwendung.

b. Fehler, die nicht auf einen Produktmangel, sondern auf die Gerätetechnik oder Softwareauslegung des Käufers zurückzuführen sind.

c. Störungen, die durch Änderungen oder Reparaturen verursacht wurden, die nicht vom Personal der Firma durchgeführt wurden.

d. Fehler, die durch korrekte Wartung oder den Austausch von Verschleißteilen gemäß Kurzanleitung oder Benutzerhandbuch vollständig vermeidbar gewesen wären.

e. Fehler, die nach dem Versand des Produkts aus unserem Unternehmen durch unvorhersehbare Fortschritte der Wissenschaft und Technik entstehen.

f. Fehler durch Naturkatastrophen wie Feuer, Erdbeben, Hochwasser oder durch externe Faktoren wie abnormale Spannung; hierfür besteht keine Garantiehaftung.

(2) Der Garantieumfang beschränkt sich auf die in (1) geregelten Situationen. Für Folgeschäden (z. B. Geräteschäden, entgangene Gelegenheiten, Gewinnausfälle) oder sonstige Verluste übernimmt die Firma keinerlei Verantwortung.

### 8.3 Produkteignung

Die Regler unserer Firma sind für die allgemeine Verwendung in der Motorsteuerungsbranche konzipiert und gefertigt. Daher darf dieser Regler nicht für die folgenden Anwendungen verwendet werden und eignet sich hierfür nicht:

(1) Einrichtungen mit schwerwiegenden Auswirkungen auf Leben und Eigentum, z. B. Kernkraftwerke, Flughäfen, Bahnanlagen, Schiffe, motorisierte Vorrichtungen und medizinische Geräte.

(2) Öffentliche Versorgungseinrichtungen, einschließlich Strom, Gas, Wasserversorgung usw.

(3) Verwendung im Freien unter ähnlichen Bedingungen oder Umgebungen.

---



![CUH-QR-Code](assets/images/cuh.sdmc30.manual.v0.0/page-0056-vcrop-00.png)

Nanjing CUH Science & Technology Co.,Ltd  
https://en.cuhnj.com  
Tel.:+86-25-84730411 / 84730415 / 84730416  
Fax:+86-25-84730426  
E-mail:sales@cuhnj.com  
Add.:Building 2, Xueyan Tech Park, Tuscity,  
No.9 Zhineng Rd, Jiangning, Nanjing, China

Dokumentnr.: IDP1000330


