# Zusammenfassung der behandelten Begriffe

## ISO/IEC 27001

- **Typ:** Norm, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** International Organization for Standardization / International Electrotechnical Commission  
- **Erklärung:** ISO/IEC 27001 ist eine internationale Norm für Informationssicherheits-Managementsysteme (ISMS). Sie beschreibt Anforderungen, mit denen Organisationen die Informationssicherheit systematisch aufbauen und verbessern können.  
- **Hinweise:**  
  - Eher für Management  
  - Sicherheitsniveau kann beurteilt werden  

---

## BSI IT-Grundschutz

- **Typ:** Standard, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** Bundesamt für Sicherheit in der Informationstechnik  
- **Erklärung:** Der IT-Grundschutz ist ein vom BSI entwickelter Standard zur Informationssicherheit in Deutschland. Er liefert praxisnahe Vorgehensweisen und Maßnahmenkataloge für den Aufbau eines Sicherheitsmanagements.  
- **Hinweise:**  
  - Grundschutz-Bausteine zeigen die Anforderungen  
  - IT-Si-Reihe zeigt die praktische Beschreibung  

---

## OSSTMM

- **Typ:** Standard, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** Open-Source Security Testing Methodology Manual  
- **Erklärung:** OSSTMM ist ein international verbreiteter Standard für Sicherheitstests. Er definiert eine systematische Methode zur Prüfung von Netzwerken, Systemen und Prozessen auf Sicherheitslücken.  
- **Hinweise:**  
  - Eher für technische Security-Analysen interessant  
  - Strukturierte Schwachstellenanalyse  

---

## IKT-Minimalstandard (CH)

- **Typ:** Standard, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** Informations- und Kommunikationstechnologien (IKT)  
- **Erklärung:** Der IKT-Minimalstandard ist ein Standard der Schweizer Bundesverwaltung. Er legt verbindliche Mindestanforderungen an die Informations- und Cybersicherheit für Behörden fest.  

---

## Österreichisches Sicherheitshandbuch

- **Typ:** Standard, IT-relevant, sicherheitsrelevant  
- **Erklärung:** Das Österreichische Sicherheitshandbuch ist ein nationaler Standard, der Vorgaben und Empfehlungen zur Informationssicherheit für Organisationen in Österreich bereitstellt.  

---

## ISO/IEC 9001

- **Typ:** Norm  
- **Bedeutung:** International Organization for Standardization / International Electrotechnical Commission  
- **Erklärung:** ISO/IEC 9001 ist eine internationale Norm für Qualitätsmanagementsysteme. Sie dient der Sicherstellung von gleichbleibender Qualität in Unternehmen, ist aber nicht speziell auf IT oder Sicherheit ausgerichtet.  

---

## DSGVO

- **Typ:** Norm, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** Datenschutz-Grundverordnung (EU)  
- **Erklärung:** Die DSGVO ist eine Rechtsnorm der Europäischen Union, die den Schutz personenbezogener Daten regelt. Sie betrifft stark die IT, da Unternehmen technische und organisatorische Maßnahmen zum Datenschutz umsetzen müssen.  

---

## OWASP Top Ten

- **Typ:** Standard, IT-relevant, sicherheitsrelevant  
- **Bedeutung:** Open Web Application Security Project  
- **Erklärung:** Die OWASP Top Ten ist ein anerkannter Standard, der die zehn wichtigsten Sicherheitsrisiken für Webanwendungen beschreibt. Sie dient Entwicklern und Sicherheitsteams als Orientierung für sichere Softwareentwicklung.  
- **Top 3 Angriffe (Beispiele):**  
  - Broken Access Control  
  - Cryptographic Failures  
  - Injection  

---

## ITIL

- **Typ:** Standard, IT-relevant  
- **Bedeutung:** Information Technology Infrastructure Library  
- **Erklärung:** ITIL ist ein international anerkannter Standard für Best Practices im IT-Service-Management. Er beschreibt Prozesse und Vorgehensweisen, um IT-Services effizient und kundenorientiert bereitzustellen.  

---

## COBIT

- **Typ:** Standard, IT-relevant  
- **Bedeutung:** Control Objectives for Information and Related Technology  
- **Erklärung:** COBIT ist ein internationaler Standard für IT-Governance und Management. Er liefert ein Rahmenwerk, mit dem Unternehmen ihre IT-Prozesse steuern und kontrollieren können, um Geschäftsziele besser zu unterstützen.  

---

## Konzepte zur IT-Sicherheit

- Zonierung/Segmentierung  
- Isolation  
- Drei-Schichten-Modell  
- Minimalprinzip der Benutzerrechte (Least Privilege)  

---

## Inhalt eines Change Request

- Priorität / Risiko (gibt an, wie dringend es ist)  
- Geplante Downtime  
- Antragsteller  
- Antragsdatum  
- Problembeschreibung  
- Kosten, wenn möglich in Dauer/Aufwand  
- Projektleiter  
- Maßnahmen  
- Testing  
- Fallback-Prozedur  
- Abgrenzung  
- Anhänge / Dokumentation  
- Unterschrift des Antragstellers  

---

## HTTP-Request-Methoden

- PUT  
- PATCH  
- POST  
- DELETE  
- GET  

---

## Quellen mit Hinweisen auf Malware

- Virenscan  
- Persistenter Speicher (z. B. Laufwerk C:)  
- Prozessliste  
- Eventliste  
- ARP-Cache  
- Logs  
- Zentrales Log  

---

## Reaktion auf Sicherheitsvorfälle

- System/Host isolieren  
- Snapshot erstellen  
- Account des Täters löschen (bzw. sperren, je nach Prozess)  

---

## Drei-Schichten-Architektur

- Man trennt:  
  - Präsentation (z. B. Website, GUI)  
  - Anwendung (Business-Logik)  
  - Datenhaltung (z. B. Datenbank)  

---

## Change Request – Zweck und Entscheidung

- **Warum macht man einen Change Request?**  
  - Konfigurationsänderungen werden dokumentiert.  
  - Änderungen werden überprüft und freigegeben oder abgelehnt.  

- **Wer entscheidet?**  
  - Change Advisory Board (CAB)  

---

## Social Engineering – Beispielanalyse

### Möglicher Schaden für das Opfer

- Verlust der Kontosicherheit  
- Risiko von Identitätsdiebstahl  
- Finanzielle Schäden möglich (z. B. SIM-Swap)  
- Verletzung der Privatsphäre  

### Weiterverwendung der Informationen

- SIM-Swap / Kontrolle über Telefonnummer  
- Zugriff auf Bank-, E-Mail- oder Social-Media-Konten  
- Verkauf der Daten im Darknet  
- Weitere Phishing- / Social-Engineering-Angriffe  

### Warum erhielt die „Testerin“ die Infos?

- Mitarbeiter vertraute ihr aufgrund der emotionalen Situation  
- Darstellung einer dringenden Notlage  
- Sicherheitsprüfung ungenügend durchgeführt  
- Genutzte persönliche Informationen (z. B. Name der Frau)  

### Genutzte Faktoren beim Angriff

- Emotionale Manipulation (schreiendes Baby)  
- Glaubwürdigkeit durch persönliche Infos  
- Erzeugter Zeitdruck  
- Ausnutzung von Mitgefühl  
- Täuschung mit gefälschter AHV-Nummer  

---

## Social Engineering – Prävention und Reaktion

### Wie hätte der Fall vermieden werden können?

- Strengere Identitätsprüfung durch den Provider  
- Keine Weitergabe sensibler Daten ohne eindeutige Verifizierung  
- Schulung der Mitarbeiter im Umgang mit Social Engineering  
- Technische Zusatzsicherungen (z. B. PIN oder Passwort fürs Kundenkonto)  

### Was kann der Kunde tun?

- Starke Passwörter und zusätzliche Sicherheitsfragen einrichten  
- Zwei-Faktor-Authentifizierung aktivieren  
- Persönliche Daten nicht unnötig preisgeben  
- Bei Verdacht sofort den Provider kontaktieren  

### Wie gehe ich als Betroffener vor?

- Sofort Provider informieren und Konto sperren lassen  
- Passwörter und Sicherheitsfragen ändern  
- Verdächtige Abbuchungen oder Aktivitäten prüfen  
- Polizei oder Meldestelle für Cybercrime einschalten  
- Beobachten, ob weitere Konten betroffen sind

---


---


---


---

# Lösung – Schriftliche Prüfung Element C  
Sicherheitsmassnahmen im KMU IT-Umfeld analysieren & implementieren

---

# 1.1 BSI-Bausteingruppen (3 Punkte)

Aus welchen BSI-Bausteingruppen sind Bausteine für die Bewertung der Mailserverumgebung zu entnehmen?

[ ] ISMS  
[ ] ORP  
[x] APP – Anwendungen  
[ ] ANW  
[ ] IND  
[x] NET – Netze und Kommunikation  
[x] INF – Infrastruktur  

---

# 1.2 Auditvergleich Mailsecurity (PCI-DSS vs. BSI)

## 1.2.1 Auditpunkte → BSI APP-Zuordnung (12 Punkte)

| Auditbericht (Nr.) | Passender BSI APP-Baustein |
|--------------------|----------------------------|
| 002 – Unsichere Protokolle | APP.3.1.A6 Sichere Kommunikationsprotokolle |
| 003 – Externer Zugriff ungefiltert | APP.3.1.A1 Segmentierung / Firewall |
| 005 – Fehlende Backupberichte | APP.3.2.A1 Datensicherung |
| 008 – Kein Logging | APP.3.1.A12 Protokollierung |
| 009 – Keine Spamrichtlinie | APP.3.3.A4 Umgang mit Spam |
| 011 – Passwortpolitik schwach | APP.3.1.A7 Authentisierung |
| 012 – PW-Policy nicht erzwungen | APP.3.1.A7 Authentisierung |
| 018 – NTP auf Linux fehlt | APP.3.1.A6 Systemhärtung / Zeitdienst |

---

# 1.2.2 Risikoanalyse ungelöster Auditpunkte (6 Punkte)

## Punkt 1  
Wenn unsichere Protokolle weiter offen bleiben, können Angreifer unverschlüsselten Mailverkehr abfangen oder manipulieren.

## Punkt 2  
Fehlende Passwortregeln erhöhen das Risiko eines erfolgreichen Kontoangriffs durch schwache oder kompromittierte Passwörter.

---

# 1.3 Statusabgleich Mailumgebung (17 Punkte)

Handbuch gilt als umgesetzt → folgende Auditpunkte sind nun **behoben**.

### 1.3.1 Status (X = behoben)

| Audit Nr. | Status |
|-----------|--------|
| 001 | [ ] |
| 002 | [x] |
| 003 | [x] |
| 004 | [x] |
| 005 | [x] |
| 006 | [ ] |
| 007 | [ ] |
| 008 | [x] |
| 009 | [x] |
| 010 | [x] |
| 011 | [x] |
| 012 | [x] |
| 013 | [x] |
| 014 | [x] |
| 015 | [x] |
| 016 | [ ] |
| 017 | [x] |
| 018 | [x] |
| 019 | [x] |
| 021 | [x] |
| 022 | [ ] |
| 023 | [ ] |
| 024 | [x] |
| 025 | [x] |
| 026 | [x] |
| 027 | [ ] |
| 028 | [ ] |
| 029 | [x] |
| 030 | [ ] |

---

# 1.3.2 BSI-Grundschutzkompendium (2 Punkte)

Wie nennt das BSI seine zusätzlichen praktischen Handlungsempfehlungen?

**Antwort:**  
**BSI IT-Grundschutz – “Best Practice” Serie / “Technische Richtlinien”**

---

# 1.3.3 Zusätzliche Empfehlungen des BSI (3 Punkte)

Welche zusätzlichen Massnahmen empfiehlt BSI zur E-Mail-Authentisierung?

[x] DKIM  
[x] SPF  
[x] DMARC  
[ ] Sender ID  
[ ] SURBL  
[ ] Statistische Inhaltsanalyse  

---

# 1.4 Sicherheitsbewertung Betrieb & Unterhalt (8 Punkte)

## 1.4.1 Bewertung Maildatensicherung

Wurde dieser Punkt im Audit bemängelt?  
[x] Ja  
[ ] Nein

### Beurteilung  
[x] Es wird eine Datensicherung erstellt  
[x] Die Datensicherung wird regelmässig geprüft  
[x] Es existiert ein externes Backup (Bankschliessfach)  
[ ] Die Datensicherung erfolgt unregelmässig  

---

## 1.4.2 Bewertung Schwachstellenscans

Wurde dieser Punkt im Audit bemängelt?  
[x] Ja  
[ ] Nein

### Beurteilung  
[x] Es werden wöchentliche **externe** Scans durchgeführt  
[x] Es werden regelmässige **interne** Scans durchgeführt  
[x] Resultate werden bewertet und Massnahmen definiert  
[ ] Scans finden nur selten statt  

---

## 1.4.3 Bewertung Systemupdates

Wurde dieser Punkt im Audit bemängelt?  
[x] Ja  
[ ] Nein

### Beurteilung  
[x] Das OS des Mailservers wird regelmässig aktualisiert  
[x] Updates werden zuerst in einer Testumgebung ausprobiert  
[ ] Updates werden komplett deaktiviert  
[ ] Updates erfolgen unstrukturiert  

---


