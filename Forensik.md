# IT-Forensik: Wo findet man Spuren eines Angriffs?

## Mögliche Orte für digitale Spuren

- **Dateisysteme:**  
  Dateien, Ordner, temporäre Dateien, gelöschte Dateien, geänderte Zeitstempel.

- **Logdateien:**  
  System-Logs, Anwendungs-Logs, Sicherheitsprotokolle, Authentifizierungs-Logs (z.B. Login-Versuche).

- **Netzwerkdaten:**  
  Netzwerkverkehrsprotokolle, Verbindungslogs, Firewall- und Router-Logs, IDS/IPS-Meldungen.

- **Speicherinhalte:**  
  RAM-Speicher (flüchtige Daten), das heißt aktive Prozesse und temporäre Daten.

- **Registry (Windows):**  
  Konfigurationsänderungen, gestartete Programme, Malware-Hinterlassenschaften.

- **Malware-Spuren:**  
  Schadcode, versteckte Dateien, verdächtige Registry-Einträge, manipulierte Systemdateien.

- **Benutzerspuren:**  
  Benutzerprotokolle, geöffnete Dateien, zuletzt verwendete Programme, USB-Anschluss-Logs.

- **Backup- und Archivsysteme:**  
  Frühere Zustände von Dateien und Systemen zur Vergleichsanalyse.

- **Peripheriegeräte:**  
  USB-Sticks, externe Festplatten oder andere Speichergeräte, die zum Datenabfluss genutzt werden könnten.

- **Cloud- und virtuelle Umgebungen:**  
  Zugriffsdaten, Logs von Cloud-Diensten und virtuellen Maschinen.

  **ARP**

  Arp Table


Inhalt CR: Zusätzliche dokumentation
Änderungsbeschreibung
Problembeschreibung
Masnahmen
Aufwand kosten
Prio/Risiken
Downtime
Pointofnoreturn
Testing
Nach/namen

## Wichtige Aspekte zur Spurensicherung

- **Integrität:**  
  Beweisführung durch manipulationssichere Datensicherung, z.B. forensische Images mit Write-Blockern.

- **Dokumentation:**  
  Lückenlose und nachvollziehbare Protokollierung aller Untersuchungsschritte.

- **Zeitanalyse:**  
  Timeline-Analysen zur Rekonstruktion des Angriffsablaufs.

Diese Orte und Methoden helfen dabei, Spuren eines Angriffs zu entdecken, zu sichern und gerichtsverwertbar auszuwerten.

##  Sofort Massnamen

Netzwerk trennen

Snapshots erstellen
