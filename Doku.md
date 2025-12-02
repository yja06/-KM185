# Inhalt

## Begriffe

- [translate:Broadcast Domain]  
  Ein Netzwerkbereich, in dem eine Nachricht an alle Geräte geschickt wird.

- [translate:Segmentierung]  
  Die Aufteilung eines Netzwerks oder Marktes in kleinere Abschnitte oder Gruppen, um besser zu steuern oder zu analysieren.

- [translate:Subnetz] & [translate:Routing]  
  [translate:Subnetz] bedeutet, ein großes Netzwerk in kleinere Teile zu zerlegen. [translate:Routing] ist der Weg, wie Datenpakete im Netzwerk von einem Teilnetz zum anderen gelangen.

- [translate:NAT] / Masquerading  
  Techniken, um private IP-Adressen in öffentliche zu übersetzen, damit Geräte im Internet kommunizieren können.

- [translate:Verschlüsselungsverfahren]  
  Methoden, um Daten so zu verändern, dass sie nur für berechtigte Personen lesbar sind.

- 2FA / MFA  
  Zwei- oder Mehrfaktor-Authentifizierung; zusätzliche Sicherheitsschritte beim Einloggen, z. B. neben Passwort auch einen Code eingeben.

- IT Schutzziel: [translate:Verfügbarkeit], [translate:Integrität], [translate:Vertraulichkeit]  
  Die Ziele in der IT-Sicherheit: Systeme sollen immer verfügbar sein, Daten sollen unverändert bleiben und nur berechtigte Personen darauf zugreifen.

- [translate:Sicherheitslücke] (Vulnerability) / CVE / Zero-Day  
  Schwachstellen in Software, die von Angreifern genutzt werden können; CVE ist eine Liste solcher Schwachstellen; Zero-Day bedeutet, dass die Schwachstelle noch unbekannt oder nicht behoben ist.

- [translate:Ransomware]  
  Schadsoftware, die Daten verschlüsselt und Geld fordert, um sie wieder freizugeben.

## Normen und Standards

- [translate:ISO/IEC 27001]  
  Internationale Norm für Informationssicherheits-Managementsysteme. Sie hilft Unternehmen, ihre IT und Daten systematisch vor Gefahren zu schützen und Sicherheitsmaßnahmen zu planen.

- BSI IT-Grundschutz  
  Deutscher Standard für Informationssicherheit. Enthält Vorgaben und Empfehlungen, wie Organisationen und Behörden ihre IT und Daten gegen Bedrohungen absichern.

- OSSTMM  
  Open Source Security Testing Methodology Manual. Ein offenes Handbuch für professionelle und systematische Sicherheitstests (z. B. Penetrationstests) an IT-Systemen.

- IKT-Minimalstandard (CH)  
  Schweizer Standard für minimale Anforderungen an IT-Sicherheit in Behörden und öffentlichen Einrichtungen, damit eine sichere Infrastruktur gewährleistet ist.

- Österreichisches Sicherheitshandbuch  
  Leitfaden für IT-Sicherheit in Österreich. Gibt Empfehlungen, wie Sicherheitsmaßnahmen geplant und umgesetzt werden, speziell für Organisationen und Behörden.

- [translate:ISO/IEC 9001]  
  Internationale Norm und Standard für Qualitätsmanagement. Sorgt dafür, dass Abläufe in Unternehmen verbessert werden und Produkte/Dienstleistungen zuverlässig sind.

- DSGVO  
  Datenschutz-Grundverordnung: EU-Gesetz, das regelt, wie personenbezogene Daten verarbeitet, gespeichert und geschützt werden müssen. Ziel ist der Schutz der Privatsphäre.

- OWASP Top Ten  
  Liste der zehn häufigsten und gefährlichsten Sicherheitsrisiken bei Webanwendungen, von der Organisation OWASP veröffentlicht. Dient als Orientierung für Entwickler und IT-Sicherheitsleute.

- ITIL  
  Information Technology Infrastructure Library: Framework für IT-Service-Management. Gibt Empfehlungen, wie IT-Abteilungen ihre Dienstleistungen professionell und effizient anbieten können.

- COBIT  
  Control Objectives for Information and Related Technologies. International anerkanntes Framework für IT-Management und -Steuerung, mit Fokus auf Prozesse, Risiken und Unternehmensziele.

## IT-Forensik - Zusammenfassung / Spickzettel

1. Grundlagen IT-Forensik  
   100% Sicherheit gibt es nicht - besonders in der IT. Sofortmaßnahmen & passende Unterstützung kennen ist wichtiger als Konzepte der Brandbekämpfung. Gebot der Stunde: Brand- und Ursachenermittlung (System-Entwurf mit IT-Forensik-Readiness).  
   Einleitung: BSI Baustein DLR 2.2 (Kapitel 1.1)

2. Ziele & Aufgaben der IT-Forensik  
   IT-Forensiker = Tatortermittler im digitalen Raum. Die IT-Forensik versucht nach einer Tat folgende Fragen zu beantworten:  
   - Was ist geschehen?  
   - Wo ist es passiert?  
   - Wann ist es passiert?  
   - Wie ist es passiert?

3. Motivation & Zielveränderung  
   Sobald eine Strafuntersuchung oder Sicherheitsbewertung läuft, ändern sich die Fragen zu:  
   - Wer hat es getan?  
   - Was kann gegen eine Wiederholung getan werden?

4. Hauptproblem der IT-Forensik  
   ❌ "Das ist ein Hack" - ist eine Hackerattacke und kein Bedienungsfehler?  
   Problem im Zentrum: Eine Störung, Auffälligkeit, etwas was nicht dahin gehört.  
   "Das ist ein Hack" handelt sich mit großer Wahrscheinlichkeit eher um einen Witz, eine Hollywood-Produktion, und hoffentlich nicht um echte Ransomware.  
   Wichtig: Vorsicht, Aufmerksamkeit und Zurückhaltung mit Anschuldigungen sind keine schlechten Gebote für diesen Moment.

5. Terminologie & Vorgehen bei IT-Forensischer Analyse  
   Aus dem BSI-Leitfaden:  
   Vorfall systematisch beschreiben durch Einsatz der CERT-Taxonomie (bewährt, ständig erweitert bzw. angepasst). Sie adressiert vorsätzliche Handlungen im Rahmen eines Vorfalls. Zufällige Betriebsstörungen und der Ausfall bzw. das Fehlverhalten von Hard- und Software sind nicht Teil der Taxonomie. Ziel: Ein Minimum an abstrakt zu beschreibenden Begriffen zu finden, um Sicherheitsvorfälle präzise zu klassifizieren.

6. Erste praktische Aufgabe  
   Szenario: Mitarbeiter kopiert unberechtigt schützenswerte Dateien auf Speichermedium. Wie und in welcher Form könnten digitale Spuren von Missetaten entstehen und gefunden werden? Mindestens 5 mögliche Fundorte schriftlich festhalten.

7. Weitere Denkansätze  
   Überlegen, was Systeme wo installieren müssten, damit an mindestens 5 unterschiedlichen Orten Spuren eines solchen Diebstahls entstehen würden.

8. IT-Forensik-Readiness  
   System-Design-Sicht: Systeme so entwerfen und betreiben, dass forensisch verwertbare Spuren entstehen. Ein kompetenter Angreifer wird versuchen, Spuren zu verwischen.  
   Überlege Gegenmaßnahmen gegen Spurenbeseitigung oder deren Erschwerung (mindestens 3).

9. IT-Forensik: Der Krux mit dem Beweis  
   Zentrale Frage: Wie kann eine Tat einer Person nachgewiesen werden? Mindestens 3 Möglichkeiten festhalten, wie eine Verbindung zwischen Beweisen und tatverdächtiger Person hergestellt werden kann.

10. Ausblick: Weitere Leitfragen  
    - Wo hinterlassen Manipulationen Spuren?  
    - Wo könnten sich mögliche Spuren finden lassen?  
    - Wie kann deren Verlust vermieden werden?  
    - Was kann ich selbst sichern?  
    - Was vermeide ich? Wovon lasse ich lieber die Finger?
