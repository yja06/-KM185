# Element C – Schriftliche Prüfung KM185  
Sicherheitsmassnahmen im KMU IT-Umfeld analysieren & implementieren

---

# 1.1 BSI-Bausteingruppen (3 Punkte)

Für die Bewertung einer Mailserver-Infrastruktur müssen Bausteine aus folgenden Bereichen herangezogen werden:

[x] APP – Anwendungen  
[x] NET – Netz- und Kommunikationsstrukturen  
[x] SYS – IT-Systeme  

Diese drei Gruppen decken alle sicherheitsrelevanten Aspekte rund um Betrieb, Netzwerkzugang und Anwendungsebene des Mailservers ab.

---

# 1.2 Auditvergleich Mailsecurity

## 1.2.1 Zuordnung Auditpunkte → BSI APP-Bausteine (12 Punkte)

Verwendeter BSI-Baustein für Mailserver: **APP.5.3 (Allgemeiner E-Mail-Client und -Server)**  
+ ergänzend SYS.1.1 dort, wo es um Serverbasisfunktionen geht.

| Auditpunkt | BSI-Baustein | Kurzbegründung |
|-----------|--------------|----------------|
| 002 – Unsichere Protokolle | APP.5.3.A2 | Mailserver müssen verschlüsselte Verbindungen anbieten |
| 003 – Unkontrollierter Zugriff von extern | APP.5.3.A2 | Protokolle und Dienste müssen klar definiert und beschränkt werden |
| 005 – Keine Dokumentation zu Backups | APP.5.3.A3 | E-Mail-Bestände müssen regelmässig gesichert und Wiederherstellung getestet werden |
| 008 – Fehlende Protokollierung | APP.5.3.A2 + OPS.1.1.5 | Ereignisse müssen auf dem Mailserver nachvollziehbar protokolliert werden |
| 009 – Fehlende Spamrichtlinie | APP.5.3.A6 | Es braucht institutionelle Vorgaben zum Umgang mit Spam |
| 011 – Passwortanforderungen ungenügend | SYS.1.1.A7 | Server benötigen definierte Passwortstandards |
| 012 – Passwortregeln werden nicht durchgesetzt | SYS.1.1.A7 | Die Passwortanforderungen müssen technisch erzwungen werden |
| 018 – NTP-Einstellungen fehlen | SYS.1.1.A12 | Ein korrekter Zeitdienst ist für Logging und Authentisierung unverzichtbar |

---

# 1.2.2 Risikoanalyse (6 Punkte)

## Risiko zu Punkt 1 – Unsichere Protokolle  
Werden E-Mails ohne Verschlüsselung übertragen, können Angreifer Nachrichten mitschneiden oder verändern. Dies birgt ein erhebliches Risiko für Datenverlust oder Manipulation.

## Risiko zu Punkt 2 – Fehlende Passwortdurchsetzung  
Wenn keine starken Passwörter verlangt und kontrolliert werden, steigt die Gefahr, dass Konten kompromittiert und sensible E-Mail-Inhalte ausgelesen werden.

---

# 1.3 Statusabgleich Mailumgebung (neu formuliert)

### Einordnung:
Der Audit beschreibt den alten Stand –  
das Betriebshandbuch zeigt die neue, überarbeitete Mailserver-Umgebung.  
Entsprechend wird bewertet, welche Punkte inzwischen tatsächlich gelöst wurden.

---

## 1.3.1 Überprüfung der Auditpunkte (X = gelöst)

| Nr. | Status | Neue Begründung |
|-----|--------|-----------------|
| 001 | [ ] | Der Punkt bezieht sich nicht auf die Mailumgebung und wird im Handbuch nicht behandelt |
| 002 | [x] | Durch die neue DMZ-Struktur und Filterregeln ist der Zugriff nun sauber geregelt |
| 003 | [x] | Der Datenfluss läuft neu ausschliesslich über das Mailgateway → Problem beseitigt |
| 004 | [x] | Firewall-Logging und -Konzept wurden in der neuen Architektur klar definiert |
| 005 | [x] | Backups sind nun mit festen Zeiten und Offsite-Speicherung dokumentiert |
| 006 | [ ] | Interne Schwachstellenscans werden weiterhin nicht erwähnt |
| 007 | [ ] | Keine Relevanz zum Mailsystem und im Handbuch nicht adressiert |
| 008 | [x] | Mailgateway und Mailserver verfügen über zentrale Protokollierung |
| 009 | [x] | Spam-Behandlung ist neu im Dokument festgehalten und Bestandteil der Schulung |
| 010 | [x] | Mit ADS-Integration gelten automatisch stärkere Passwortregeln |
| 011 | [x] | Durch ADS werden Passwortvorgaben technisch erzwungen |
| 012 | [x] | Ebenfalls über ADS vollständig behoben |
| 013 | [x] | Themen wie NTP und ESXi-Standards wurden bei der Neuerstellung berücksichtigt |
| 014 | [x] | Nur benötigte Dienste sind aktiv, Rest wurde entfernt |
| 015 | [x] | Nicht benötigte Software wurde deaktiviert bzw. bereinigt |
| 016 | [ ] | Antivirenbetrieb wird im Dokument nicht beschrieben |
| 017 | [x] | Zeitsynchronisation wurde neu implementiert |
| 018 | [x] | NTP-Aufgaben werden nun automatisiert abgearbeitet |
| 019 | [x] | Alarmierung ist neu strukturiert und dokumentiert |
| 021 | [x] | Monitoring wurde neu definiert und ist jetzt unabhängig |
| 022 | [ ] | Keine Informationen zu Hotel-Druid im Handbuch |
| 023 | [ ] | Limitierung der Mailboxen ist nicht für alle Rollen klar umgesetzt |
| 024 | [x] | Mailfilter blockiert problematische Anhänge zuverlässig |
| 025 | [x] | Das System kann nicht mehr als offenes Relay missbraucht werden |
| 026 | [x] | Schlüssel und Zertifikate werden im neuen Design berücksichtigt |
| 027 | [ ] | Physische Risiken (Türproblem) werden nicht angesprochen |
| 028 | [ ] | Externe Schwachstellenscans weiterhin nicht dokumentiert |
| 029 | [x] | WLAN-Scan-Prozess wurde aktualisiert |
| 030 | [ ] | Der jährliche Notfalltest fehlt noch |

---

# 1.3.2 BSI-Grundschutzkompendium – Best Practice Serie (2 Punkte)

Das BSI veröffentlicht ergänzend eine praxisnahe Sammlung von Handlungsempfehlungen unter dem Titel:

**„BSI IT-Grundschutz – Praxisempfehlungen“**

---

# 1.3.3 Zusätzliche Empfehlungen zur E-Mail-Authentisierung (3 Punkte)

[x] DKIM  
[x] SPF  
[x] DMARC  
[ ] Sender ID  
[ ] SURBL  
[ ] Statistische Inhaltsanalyse

Diese drei Mechanismen gelten als Standard zur Sicherstellung der Absenderintegrität.

---

# 1.4 Bewertung zur Sicherheit im Betrieb

## 1.4.1 Mail-Backup und Wiederherstellbarkeit

Audit bemängelte diesen Punkt?  
[x] Ja

Beurteilung:

[x] Backups werden täglich erstellt  
[x] Wiederherstellung wird regelmässig getestet  
[x] Externe Sicherungen sind vorhanden  
[ ] Kein Backup-Prozess dokumentiert

---

## 1.4.2 Schwachstellenscans

Audit bemängelte diesen Punkt?  
[x] Ja  

Bewertung:

[x] Externe Prüfungen finden statt  
[x] Interne Scans werden regelmässig durchgeführt  
[x] Resultate we
