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

# Aufgaben   
Sicherheitsmassnahmen im KMU IT-Umfeld analysieren & implementieren

---

# 1.1 BSI-Bausteingruppen (3 Punkte)

Aus welchen Bausteingruppen sind Bausteine für die Bewertung der Mailserverumgebung zu entnehmen?

[x] APP – Anwendungen  
[x] NET – Netze und Kommunikation  
[x] SYS – IT-Systeme  
[ ] INF  
[ ] ISMS  
[ ] ORP  
[ ] IND  
[ ] ANW  

*Begründung:*  
Mailserver = Anwendung (APP), läuft auf Servern (SYS) und hängt von Policies, Firewall und Netzwerkzonen (NET) ab.

---

# 1.2 Auditvergleich Mailsecurity

## 1.2.1 Auditpunkte → BSI APP-Zuordnung (12 Punkte)

**Verwendeter Baustein:**  
👉 **APP.5.3 – Allgemeiner E-Mail-Client und -Server**

| Auditpunkt | BSI APP-Baustein | Begründung |
|-----------|------------------|------------|
| 002 – Unsichere Protokolle | APP.5.3.A2 | Sichere Transportverschlüsselung für SMTP/IMAP/POP zwingend |
| 003 – Externer Zugriff ungefiltert | APP.5.3.A2 | Erlaubte Protokolle und Dienste müssen festgelegt werden |
| 005 – Fehlende Backupberichte | APP.5.3.A3 | Regelmässiges Backup und dokumentierte Wiederherstellungsprüfung |
| 008 – Kein Logging | APP.5.3.A2 / OPS.1.1.5 | Mailserver müssen sicher konfiguriert und Ereignisse protokolliert werden |
| 009 – Keine Spamrichtlinie | APP.5.3.A6 | Institution muss Richtlinie für Spam-/Mail-Security definieren |
| 011 – Passwortpolitik schwach | SYS.1.1.A7 | Server-Passwortregeln müssen definiert & umgesetzt werden |
| 012 – PW-Policy wird nicht erzwungen | SYS.1.1.A7 | Passwortanforderungen müssen technisch enforceable sein |
| 018 – Fehlende NTP-Einstellungen | SYS.1.1.A12 | Server benötigen korrekte Zeitquelle für Logs & Auth |

---

# 1.2.2 Risikoanalyse ungelöster Auditpunkte (6 Punkte)

## Punkt 1  
**Unsichere Protokolle (002)**  
Ohne Verschlüsselung können Angreifer E-Mails abfangen oder manipulieren. Das führt zu Datenverlust, Leaks oder Social-Engineering-Angriffen.

## Punkt 2  
**Keine Passwort-Policy / nicht erzwungen (011/012)**  
Schwache Passwörter ermöglichen Kontoübernahmen, was direkten Zugriff auf Postfächer und interne Kommunikation erlaubt.

---

# 1.3 Statusabgleich Mailumgebung (17 Punkte)

### 1.3.1 Statusvergleich (X = behoben)

Basierend auf Betriebshandbuch (neue Mailzonen, Spamfilter, Backup, Logging, DNS, Richtlinien):

| Audit | Status | Audit | Status | Audit | Status |
|-------|--------|--------|--------|--------|--------|
| 001 | [ ] | 013 | [x] | 025 | [x] |
| 002 | [x] | 014 | [x] | 026 | [x] |
| 003 | [x] | 015 | [x] | 027 | [ ] |
| 004 | [x] | 016 | [ ] | 028 | [ ] |
| 005 | [x] | 017 | [x] | 029 | [x] |
| 006 | [ ] | 018 | [x] | 030 | [ ] |
| 007 | [ ] | 019 | [x] | 023 | [ ] |
| 008 | [x] | 021 | [x] | 024 | [x] |
| 009 | [x] | 022 | [ ] |     |     |
| 010 | [x] |     |      |     |     |
| 011 | [x] |     |      |     |     |
| 012 | [x] |     |      |     |     |

---

korrekt:

| Audit Nr. | Status | Begründung |
|-----------|--------|------------|
| 001 | [ ] | Betriebshandbuch sagt nichts über veraltete User im Hotel-Druid → nicht Mailserver |
| 002 | [x] | Neue DMZ-Zonierung + Mailgateway + verschlüsselte SMTP-Verbindungen |
| 003 | [x] | Neue Paketfilter-Regeln + nur Mailgateway darf SMTP/IMAP → behoben |
| 004 | [x] | Halbjährliche Firewall-Protokolle wurden im neuen Konzept berücksichtigt |
| 005 | [x] | Backup täglich 02:00 + extern im Banktresor → NEU und klar definiert |
| 006 | [ ] | Interne Schwachstellenscans werden im Handbuch NICHT erwähnt |
| 007 | [ ] | Betrifft interne Zone + Datenbanken → kein Bezug zur Mailumgebung |
| 008 | [x] | Logging neu vorhanden: Mailgateway prüft & loggt Verbindungen |
| 009 | [x] | Spam-Umgang neu definiert + Mitarbeiterschulung alle 6 Monate |
| 010 | [x] | PW-Policy: SSO über ADS → starke Passwortregeln automatisch übernommen |
| 011 | [x] | PW-Policy wird durch ADS erzwungen → behoben |
| 012 | [x] | PW-Policy erzwingbar → durch AD-Integration behoben |
| 013 | [x] | ESXi NTP etc. → laut Handbuch Teil des neuen Betriebsprozesses |
| 014 | [x] | Unnötige Dienste deaktiviert → Mailserver nur SMTP/IMAP |
| 015 | [x] | Unnötige Software wurde deaktiviert → sauberer Server |
| 016 | [ ] | Anti-Virus auf Windows-Servern wird NICHT erwähnt im Handbuch |
| 017 | [x] | NTP neu geprüft und korrigiert (im Handbuch: neue Zeitquelle) |
| 018 | [x] | Cronjob / ntpdate laut Betriebshandbuch angepasst |
| 019 | [x] | Alerts im Monitoring neu definiert und verbessert |
| 021 | [x] | Monitoring neu definiert (unabhängig, klare Regeln) |
| 022 | [ ] | Prüfung Hotel-Druid – nichts im Handbuch |
| 023 | [ ] | Mailbox-Limits → Handbuch sagt nur: 500 MB *intern* (nur Mitarbeiter). Aber Audit sagt: bestimmte Mailboxen müssen limitiert werden. → nicht vollständig behoben |
| 024 | [x] | Mailfilter blockiert gefährliche Anhänge (pdf, exe, .docm) |
| 025 | [x] | Open Relay verhindert (Mailgateway prüft Absender, DNS, Reputation) |
| 026 | [x] | Schlüsselwechsel wird im Handbuch erwähnt (Zonentransfer etc.) |
| 027 | [ ] | Tür RZ – physische Sicherheit nicht im Handbuch erwähnt |
| 028 | [ ] | Externe Vulnerability Scans fehlen noch |
| 029 | [x] | WLAN-Scans → im neuen Wireless-Formular & Instruktion ergänzt |
| 030 | [ ] | Incident Response Plan: jährlicher Test fehlt noch |

---

# 1.3.2 BSI-Grundschutzkompendium (2 Punkte)

Name der BSI-Best-Practice-Serie:

**„BSI IT-Grundschutz – Praxisempfehlungen“**

---

# 1.3.3 Zusätzliche Empfehlungen Email-Authentisierung (3 Punkte)

[x] DKIM  
[x] SPF  
[x] DMARC  
[ ] Sender ID  
[ ] SURBL  
[ ] Statistische Inhaltsanalyse  

---

# 1.4 Sicherheitsbewertung Betrieb & Unterhalt (8 Punkte)

## 1.4.1 Maildatensicherung (4 Punkte)

Wurde bemängelt?  
[x] Ja

Beurteilung:  
[x] Datensicherung vorhanden  
[x] Regelmässige Restore-Tests (jährlich)  
[x] Backup extern in Bankschliessfach  
[ ] Keine Sicherung vorhanden

---

## 1.4.2 Schwachstellenscans (2 Punkte)

Wurde bemängelt?  
[x] Ja

Beurteilung:  
[x] Regelmässige externe Scans  
[x] Regelmässige interne Scans  
[x] Ergebnisse bewertet & Massnahmen umgesetzt  
[ ] Scans fehlen

---

## 1.4.3 Systemaktualisierungen (2 Punkte)

Wurde bemängelt?  
[x] Ja

Beurteilung:  
[x] OS wird automatisch aktualisiert  
[x] Updates werden zuerst in Testumgebung geprüft  
[ ] Updates sind deaktiviert  
[ ] Updates erfolgen unkontrolliert

---
