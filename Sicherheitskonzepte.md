# Sicherheitskonzepte: Segmentierung & Isolation

## [translate:Netzwerksegmentierung]
**Definition:** Aufteilung eines Netzwerks in kleinere Segmente/Subnetze zur Begrenzung von Broadcast-Domains und Kontrolle des Datenverkehrs [web:6].

**Sicherheitsvorteile:**
- Eindämmung von Lateral Movement bei Angriffen
- Segment-spezifische Sicherheitsrichtlinien
- Reduzierung der Angriffsfläche
- Bessere Überwachung und Troubleshooting

**Umsetzung:**
- VLANs (Layer 2 Segmentierung)
- Subnetting / IP-Segmentierung (Layer 3)
- Firewalls zwischen Segmenten
- Micro-Segmentation (Zero Trust)

## [translate:Isolation]
**Definition:** Vollständige Trennung kritischer von unkritischen Systemen.

**Isolationstypen:**
- **Physische Isolation (Air-Gapping):** Keine Netzwerkverbindung
- **Logische Isolation:** VLANs, MPLS, SD-WAN
- **Workload-Isolation:** Container-Security, VM-Sandboxing
- **Netzwerk-Isolation:** DMZ, Guest-Netzwerke

## [translate:Zero Trust]
**Prinzip:** "Never trust, always verify" - Kein implizites Vertrauen innerhalb des Netzwerks.

**Kernprinzipien:**
- Identity-basierte Zugriffe
- Least Privilege Principle
- Micro-Segmentation
- Kontinuierliche Überwachung

## [translate:Defense in Depth]
**Konzept:** Mehrschichtiger Schutz durch mehrere unabhängige Sicherheitsmaßnahmen.

**Schichten:**
