# Klausurfragen

Nennen Sie 4 Schwachstellen im Bereich der Informationssicherheit (4)
```
**Folie 20**

- unklare Sicherheitsprozesse
- fehlende Notfallplanung
- insecure Websites
- fehlendes Patch Management
```

Welche Probleme können sich ergeben, wenn man sich aktiv gegen Geheimdienste schützt? (10)

```
- Sanktionen gegen die Firma, ggf Entzug der Geschäftslizenz (z.B. China)
- Verwenden für IT-Angriffe oft Zero-Day Exploits
-
```

Welche Phasen hat der Deming Circle? Bitte beschreiben Sie diese. (8)

```
- Plan : Plane deine Implementation/Vorhaben etc. 
- Do : Setze den Plan um
- Check: Wirksamkeitskontrolle -Pentest oder andere Tests zum Identifizieren von Gaps
- Daten sammeln für Act Phase
- Act: Verbessere die Implementierung/Vorhaben durch Eliminierung der erkannten Gaps
```

Welche Vorteile ergeben sich durch den Einsatz des InfoSec Wheels? Beschreiben Sie dazu beispielhaft ein Primärfarben- und ein Sekundärfarbenteam (10)

```
Primärfarbenteams:
- Rot ("Angreifer"): offensive Security (PenTest, Blackbox Tests)
- Blau ("Verteidiger"): Operatives Verteidigungsteam. Erkennt Angriffe auf das System, leitet Gegenmaßnahmen ein
- Gelb ("Architekten"): Programmierer, Ersteller des Systems

Sekundärfarbenteams:
- purple (Blau+Rot): Das Team steigert die Erfolgschance des Red Teams und ermöglicht bessere Ergebnisse des blauen Teams durch Insiderwissen der jeweils anderen Gruppen. --> Erlaubt eine Verteidigung anhand des Angreifervorgehens 
- green (blue + yellow): Verbesserung der Verteidigungenfähigkeiten zur Erkennung und Reaktion auf Vorfälle durch Verbesserung des Designs
- orange (red + yellow): inspire yellow to be more security conscious, increase security awareness, educate people, benefit the software code and design implementation --> develop offensive critical thinking 
```

Bei der Risikoanalyse stellen Sie das Risiko eines Ransomware Angriffs fest, das gemäß der definierten Risikomatrix nicht akzeptiert werden kann.
Welche Optionen haben Sie und warum? (12)

```
- Akzeptieren fällt raus, nach Aufgabenstellung (außer Top-management will Risiko trotzdem eingehen?) aber Modifizieren bis Akzeptieren
- Risk modification (modifikation bis es akzeptiert werden kann), durch risikosenkende Maßnahmen
-  Risk Avoidance (Abschalten):
    Non Business-critical systems können abgeschaltet werden. Damit ist de factop die gesamte IT betroffen. Vermeiden ist schwierig, weil das de facto bedeuten würde, keine IT-Systeme einzusetzen
- Risk sharing (Abgeben der Verantwortung durch Versicherung des Risikos)
```

Was ist der Unterschied zwischen Eintrittswahrscheinlichkeit und Schadenshäufigkeit? (4)

```info
- Die Schadenshäufigkeit ist ein statistischer Wert, der angibt, wie oft ein gegebenes Risiko in der Vergangenheit eingetreten ist
- Die Eintrittswahrscheinlichkeit ist eine Schätzung für die Zukunft, der aus verschiedenen Quellen
```

Nennen Sie 2 Beispiele für besondere Kategorien personenbezogener Daten gem. Art 9 EU-GDPR und erläutern Sie die besonderen Einschränkungen, die bei der
Verarbeitung dieser beachtet werden müssen. (12)

``` info

```

4 V 10
Der Produktionsleiter möchte die Kontakte der relevanten Ansprechpartner inkl. biometrischem Foto aushängen, (z.B. Schichtleiter, Sicherheitsbeauftragte). Unter welchen
Voraussetzungen ist das möglich? Bitte beachten Sie besonders Art. 6, 9, 32 EU-GDPR 15
5 W 6 Was ist der Kern-Regelungsgegenstand des TKG? Und des TMG? 6
5 V 10 Würden Sie Open Source Software in Ihrem Unternehmen einsetzen? Bitte begründen Sie Ihre Position. 15
6 V 10 Warum ist Zero Trust notwendig? 15
6 M 5 Was ist lateral movement? Und warum ist es so gefährlich? 10
7 W 6 Was bedeutet CERT and wie ist seine Funktionsweise? 6
7 V 6 Was ist ein Low Interaction Honeypot und was sind seine Vor-/Nachteile? 12
8 W 6 Nennen Sie eine Secure Coding Guideline und erklären deren Ansatz kurz. 4
8 W 8 Welche verschiedenen Arten der Kundenseparierung gibt es in Datenbanken? Welche Vor- und Nachteile haben diese? 8
9 V 10 Was bedeutet der Begriff Cybercrime as a Service? Wie funktionieren diese "Firmen", und was macht sie so gefährlich? 15
9 V 8 Wie funktioniert eine DDOS Attacke? 10
Total 136 189
W 7 41 40
M 5 41 67
V 6 54 82


Klausur Aufbau:
8Wissen: Keine Pragraphen aus deutschen Geetzen zitieren lassen
4Methode
3Verständnis

- Sollten wissen was ISO Norm Ist
- NIST ist Framework
- CISO
- Implementierung der Frameworks (ITIL, Cobit)

## Mögliche Fragen

- Was ist der grobe Inhalt hinter BSI-200?
- Was ist OWASP
- Nennen Sie 4 Grundprinzipien des Zero Trust
- Nennen und beschreiben Sie kurz die sechs Schritte zur Implementation eines ISMS nach ISO27001
- Wie ist ein ISMS aufgebaut?
- Nennen Sie das CIA Triad
- Wie läuft der Zertifizierungsprozess nach ISO 27001 ab?
- Was ist ein CMMI (oder Spice) und nennen Sie die Phasen
- Welche Simulationen und Awareness Tests können genutzt werden, um die Awareness eines Unternehmens zu überprüfen
- Was ist IAAA?
- Was ist das Problem an gängigen Classification Level Einstufungen von beispielsweise Word dokumenten?
- Was sind die 4 Risk Treatment Optionen? Wann werden diese Angewendet? -> Zeichnen Sie dies in ein Risiko Analyse Diagramm ein
- Geben die Art 4-7 DGSVO wieder
- Was ist der Unterschied zw. Data Processor und Controller?
- Wann wird ein Data Protection Officer benötigt und was für Aufgaben und Besonderheiten stehen ihm bei?
- Nennen Sie wesentliche Unterschiede der Data Security Law von China und Deutschland

Du bist ein unternehmen in Deutschland. du arbeitest mit einem anderen unternehmen aus z.B. China zusammen. Während der Zusammenarbeit stellt sich heraus das persönliche Daten gebraucht werden.
a) darf ich diese Daten überhaupt übetragen? und
b) muss dann nicht die GDPR/DSGVO nicht auch für das Unternehmen in China gelten? oder liegt da dann das Risiko sozusagen alleinig bei mir (Bearbeitet) ALSO GEHT NOCHMAL UM DEN SCOPE VON DSGVO außerhalb von EU

- Wie würdest du als CISO eine Business Impact Analyse angehen? was gilt es dabei zu beachten und vor welchen möglichen Herausforderungen stehst du?

- stell dir vor du möchtest innerhalb des Unternehmens einen höheren Grad an Awareness erreichen - beschreibe dein vorhaben & wie überzeugst du den Betriebsrat und das Management von deiner Idee

- vor einigen Jahren wurde die Störerhaftung verändert - jetzt fragt dich dein Management wie du dem ganzen entgegen stehst - was würdest du antworten?

- welche 5 Phasen befolgt das NIST Framework
- was sind die verschiedenen Development Strategien
- was sind Möglichkeiten zum Outsourcen