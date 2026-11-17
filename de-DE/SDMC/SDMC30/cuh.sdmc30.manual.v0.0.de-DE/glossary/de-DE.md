# Terminkandidaten (cuh.sdmc30.manual.v0.0.de-DE)

- **Erstellt am**: 2026-09-17 03:30:00
- **Quelle**: Übersetzung der englischen Vorlage `en-US/SDMC/SDMC30/cuh.sdmc30.manual.v0.0.zh-CN/doc.md` (Quell-PDF: SDMC30_SMS-EN_1_01)
- **Hinweis**: Die maschinenlesbare Kandidatenliste `glossary/terms.yaml` entstammt der Konvertierung des englischen Quell-PDFs und wurde aus der Vorlage übernommen. Die folgende Liste ordnet die wichtigsten Fachtermini der deutschen Fassung mit englischem Original und chinesischer Referenz gegenüber; nach Freigabe sind sie in das firmenweite `glossary/` zu übernehmen.

## 1. Kapitel- und Gliederungstermini

| term_id | Deutsche Fassung | Englisches Original | Erste Seite |
| --- | --- | --- | ---: |
| `auto-0001` | Urheberrechtshinweis & Haftungsausschluss | Copyright Statement & Disclaimer | 2 |
| `auto-0002` | Vorwort | Preface | 3 |
| `auto-0003` | Sicherheitshinweise und Vorsichtsmaßnahmen | Safety and Precautions | 4 |
| `auto-0004` | Betriebs- und Lagerumgebung | Operating and Storage Environment | 5 |
| `auto-0005` | Inhaltsverzeichnis | Contents | 7 |
| `auto-0007` | Kapitel Ⅰ Vor der Inbetriebnahme | Chapter Ⅰ Before Use | 9 |
| `auto-0008` | Prüfen des Lieferumfangs | Check the Package Contents | 9 |
| `auto-0009` | Beschreibung der Anzeigen und Tasten | Indicators and Buttons Description | 10 |
| `auto-0010` | Beschreibung der äußeren Bauteile | External Parts Description | 11 |
| `auto-0011` | Beschreibung der Signalanschlüsse | Signal Ports Description | 11 |
| `auto-0012` | Beschreibung des Typenschilds | Nameplate Description | 12 |
| `auto-0013` | Kapitel Ⅱ Produktvorstellung | Chapter Ⅱ Product Introduction | 13 |
| `auto-0015` | Kapitel Ⅲ Installationsanleitung | Chapter Ⅲ Installation Guide | 14 |
| `auto-0016` | Betriebsbedingungen des Reglers | Controller Usage Conditions | 14 |
| `auto-0017` | Bedienung der Tasten | Operation Method of Buttons | 14 |
| `auto-0018` | Installation und Inbetriebnahme | Install and Use | 15 |
| `auto-0019` | Kapitel Ⅳ Beschreibung der Grundfunktionen | Chapter Ⅳ Basic Function Description | 19 |
| `auto-0028` | Kapitel Ⅴ Beschreibung der erweiterten Funktionen | Chapter Ⅴ Advanced Function Description | 25 |
| `auto-0048` | Kapitel Ⅵ Technische Daten | Chapter Ⅵ Technical Specifications | 44 |
| `auto-0052` | Kapitel Ⅶ Anhang | Chapter Ⅶ Appendix | 47 |
| `auto-0057` | Kapitel Ⅷ Produktgarantie | Chapter Ⅷ Product Warranty Information | 54 |

## 2. Funktions- und Parametertermini

| Deutscher Begriff | Englisches Original | Symbol/Parameter |
| --- | --- | --- |
| Sollfrequenz | Set Frequency | F |
| Vorwärts- und Rückwärtslauf | Forward and Reverse Running | — |
| Not-Halt | Emergency Stop | Ar02 (Anzeige) |
| Sanftanlaufzeit | Soft Start Time | t |
| Sanftauslaufzeit | Soft Closing Time | d |
| Gleichstrombremsung | DC Braking | d (negativer Bereich) |
| Tastensperre | Keyboard Lock | ⏻ lang |
| Wiederherstellen der Werkseinstellungen | Restore Default Settings | 8.8.8.8.8. |
| Start/Stopp- und Drehrichtungssteuerung | Motor Start/Stop and Direction Control | Fr |
| Drehrichtungswechsel | Rotation Direction Exchange | Ph |
| Rücklaufsperre / Untersagung des Rückwärtslaufs | Prohibition of Reverse Rotation | Ph=A.b.c. |
| Motor-V/F-Kennlinie | Motor V/F Curve Setting | y, b, h, n, o, r, u |
| Leistungsschutz des Motors (obere Leistungsgrenze) | Motor Overpower Protection | Po, rc, rL, oL |
| Fernsteuerung der Motordrehzahl | Motor Speed Remote Control | A |
| Fernsteuerkoeffizient | Remote Control Coefficient | c |
| Digitale Drehzahlvoreinstellung | Motor Speed Digital Preset | S1, S2 |
| Schaltsensor | Switch Sensor | rA |
| Intelligenter fotoelektrischer Sensoranschluss | Intelligent Photoelectric Sensor Port | P |
| Laufausgang | Running Output | D / od |
| Störungsausgang | Fault Output | P / oP |
| Einschalt- und Betriebszustand | Power On and Running Status | PS |
| Bedienfeldhelligkeit | Panel Brightness | LEd |
| Ausgangsüberwachungsparameter | Output Monitoring Parameters | ⚙+▼ |
| Maximalfrequenz | Maximum Frequency | y |
| Nennfrequenz | Rated Frequency | b |
| Nennspannung | Rated Voltage | h |
| Elektrische Nennleistung des Motors | Motor Rated Electrical Power | Pn |
| Not-Halt-Typ (Modus) | Emergency Stop Type | Sq (Sto/Sbc/SS1) |

## 3. Sicherheitskennzeichnung (Signalwörter)

| Deutsch | Englisch | Bedeutung |
| --- | --- | --- |
| GEFAHR | Danger | Nichtbeachtung führt zu Personenschaden oder Tod |
| WARNUNG | Warn | Nichtbeachtung kann zu Personenschaden oder Tod führen |
| VORSICHT | Careful | Nichtbeachtung kann zu mittleren/leichten Personenschäden führen |
| HINWEIS | Notice | Nichtbeachtung führt zu Produkt- und Sachschäden |
| ZWINGEND | Essential | Zwingend zu beachtende Vorsichtsmaßnahmen und Einsatzbeschränkungen |

## 4. Konventionsentscheidungen der Übersetzung

- **Regler** als durchgängige Bezeichnung für „Controller"（控制器）； alternativ „Steuergerät" wurde verworfen, um die Assoziation zur Leistungsregelung zu erhalten.
- **Sollfrequenz** für „Set Frequency"（设定频率）; entspricht der Normsprache der Antriebstechnik.
- **Not-Halt** durchgängig für „Emergency Stop"（急停）, auch in Komposita (Not-Halt-Anschluss, Not-Halt-Quelle).
- Signalwörter der Sicherheitskennzeichnung in Großbuchstaben (GEFAHR/WARNUNG/VORSICHT/HINWEIS/ZWINGEND) entsprechend EN-82079-Konventionen; die im Quell-PDF vorhandenen chinesischsprachigen Warnhinweise (危险) wurden im Original belassen und in der Struktur der Vorlage beibehalten.
- Zahlenformate: Dezimaltrennzeichen Komma (z. B. 0,2 kW), physikalische Einheiten mit geschütztem Leerzeichen.
- Produktspezifische Kürzel (F, P1, Π1, Er01…Er15, Ar02/Ar08, nPn/PnP/PSP, dLy/HLd usw.) bleiben unverändert, da sie Anzeigen des Geräts sind.
