# IT-Recht Semester 4

# Inhaltsverzeichnis

# 1 ISO Voraussetzungn, Policies, Organisation, Governance Model
:question: Ist ISO eine IT Rolle?
> der ISO sollte innerhalb der IT-Abtielung positioniert sein. So ist eine effektive Zusammenarbeit mit der IT-Abteilung möglich

:question: Was ist die Verbindung zwischen ISO und der Gesetzgebung?
> Der ISO hat die Aufgabe, rechtliche Rahmenbedingungen der Datenverarbeitung zu kontrollieren.

## Klassifizierung von Sicherheitsrisiken 

1. Niedrig: wenige Angriffe, keine Indikatoren für Eindringlinge oder Attacken
2. Gesichert: normales Risiko. Keine Indikatoren für Eindringlinge oder Attacken
3. Erhöht: Signifikantes Risiko: Mäßige Anzahl an Angriffen. Keine Anzeichen für Eindringlinge oder direkte Attacken
4. Hoch: hohes Risiko: hohe Anzahl an gemeldeten Angriffen. Keine Anzeichen für Eindringlinge oder direkte Attacken
5. Schwer: schweres Risiko. Anzeichen oder starker Verdacht für Eindringlinge

---

## Schwachstellen

### ISMS 
1. Fehlende oder unklare Anforderungen an InfoSec
2. Unklares InfoSec Vorgehensmodel
3. Fehlende Produkt- oder Service Lifecycle Orientierung :arrow_right: veraltete produkte und Services
4. Fokus nur auf technische Umsetzung :arrow_right: Prozesse hinter Technologien benötigt
5. Fehlende Standardisierung :arrow_right: führt zu unsicheren Architekturen, Lösungen und Software
6. Fehlende Notfall Planung :arrow_right: nicht zu bewältigendes Risiko

### Cyber Security
1. Schwachstellen in Software :arrow_right: nicht angemessen sicher genug für Gefahrenlage
2. Unangemessener Schutz gegen Maleware :arrow_right: geringe Erkennungsrate
3. Identifikation und Authentifizierung fehlend :arrow_right: Passwörter alleine sind nicht sicher genug
4. Unsichere Webseiten
5. Mobilgeräte Nutzung :arrow_right: Generierung zusätzlicher Angriffsvektoren (immer an, fehlende Updates, Nutzung unsicherer Netze)
6. E-Mail ist wie Postkarte :arrow_right: Phishing, Werbung, Viren, Social Engineering
7. Bezahlen mit persönlichen Daten :arrow_right: hohes Risiko für Privatsphäre
8. Fehlende Internet Kompetenz
9. Manipulierte Technologien
10. Fake News

---

## Operational Excellence (OPEX)
- Mindset der gewisse Prinzipien und Tools umfasst, um eine *Culture of Excellence* im Unternehmen einzuführen.
- Jeder Mitarbeiter kann den Wertefluss zum Kunden einsehen, dazu beitragen und ihn verbessern

Zielsetzung:

:arrow_right: Kernprozesse in der Wertschöpfungskette ständig im Hinblick auf Effektivität und Effizienz optimieren. Unterstützt durch die richtige Kombination der Verbesserungsmethoden den kontinuierlichen Verbesserungsprozess.

---

## COBIT (Control Objectives for Information and Related Technology)

International anerkanntes Framework zur IT-Governance und gliedert IT Aufgaben in Prozesse und Kontrollziele.

:arrow_right: Es wird definiert was umzusetzen ist, nicht wie es umzusetzen ist.

---

## ISMS / Policies

Schritte zur Einführung von ISO 27001:
1. Management Überzeugen
2. Verstehen wer in welcher Form betroffen ist. Prozesse und Dokumentationen benötigt
3. Vorbereitung von z.B. Risiko Analysen, Notfallplänen, Trainings
4. Implementierung des ISMS inklusive Prozesse und handhabung von Risiken
5. Überwachen und Überprüfen der Prozesse, Aktivitäten. Stage 1 Audit, Management Review und kontinuierliche Verbesserung/Anpassung
6. Zertifizierung. Stage 2 Audit, Management Überprüfung, kontinuierliche Verbesserung

### Einführung eines ISMS

:::mermaid
flowchart LR
    id1[Anforderungen \n und \n Standards \n definieren]--> id2[Beteiligte \n ermitteln]--> id3[ISMS Scope \n festlegen] --> id4[GAP Analyse \n durchführen]--> id5[Kosten \n und \n Aufwand \n Schätzung]--> id6[Management \n Erlaubnis \n erhalten] --> id7[Projekt Start]
:::

---

## Standards

| Standard | Icon | Beschreibung |
| --- | --- | --- | 
| ISO 27001 | <img src="https://wp.alohi.com/wp-content/uploads/2022/01/ISO-27001.svg" alt="drawing" width="100"/> | Internationale Norm für Einrichtung, Umsetzung, Aufrechterhaltung und fortlaufende Verbesserung eines dokumentierten Informationssicherheits-Managementsystems |
| TISAX | <img src="https://portal.enx.com/tisaxlogo" alt="drawing" width="100"/> | TISAX ist Kfz-Branchen-spezifisch. Der Standard betrifft die sichere Verarbeitung von Informationen von Geschäftspartnern, den Schutz von Prototypen und den Datenschutz gemäß Datenschutz-Grundverordnung (DSGVO) für mögliche Geschäfte zwischen Autoherstellern und ihren Dienstleistern oder Lieferanten |
| BSI Standard 200 | <img src="https://www.bsi.bund.de/_config/richsnippets/logo.jpg?__blob=normal&v=2" alt="drawing" width="100"/> | Erläutert den Aufbau eines Informationssicherheitsmanagementsystems (ISMS). Kompatibel zum ISO -Standard 27001 und berücksichtigt die Empfehlungen der anderen ISO -Standards wie ISO 27002 |
| KRITIS | <img src="https://www.bsi.bund.de/SharedDocs/Bilder/DE/BSI/Themen/KRITIS/UPK/upk-logo.png?__blob=normal&v=2" alt="drawing" width="100"/> | Standard gültig für Betreiber kritischer Infrastrukturen. Umfasst 9 Sektoren der Kritischen Infrastruktur welche wichtige Bedeutung für das staatliche Gemeinwesen haben und  deren Ausfall oder Beeinträchtigung nachhaltig wirkende Versorgungsengpässe, erhebliche Störungen der öffentlichen Sicherheit oder andere dramatische Folgen haben würde. |
| IT Sicherheitsgesetz | <img src="https://www.bsi.bund.de/SharedDocs/Bilder/DE/BSI/Themen/KRITIS/UPK/upk-logo.png?__blob=normal&v=2" alt="drawing" width="100"/> | Verbesserung der Sicherheit informationstechnischer Systeme (IT-Sicherheit) in Deutschland und Schutz kritischer Infrastrukturen, welche für das Funktionieren des Gemeinwesens relevant sind | 

---

## ISMS Scope festlegen





# 2 Aktuelle Standards in der Informations Sicherheit

# 3 Asset Management, Risk Management

# 4 EU-GDPR, BDSG + Internationales Datenschutz Recht

# 5 Rechtliche Lage Deutschland + International + Open Source

# 6 Zero Trust