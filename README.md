# CERT-Bund-2022020828000531

Dieses Repository enthält deutschsprachige Writeups einer Reihe von Sicherheitslücken in [EuroCommand CommandX](https://www.eurocommand.com/).

Die gefundenen Schwachstellen wurden im Januar 2022 erstmalig an den Hersteller, sowie im Februar 2022 an das CERT-Bund des Bundesamtes für Sicherheit in der Informationstechnik (BSI) gemeldet. Das BSI hat der Meldung folgende ID zugeteilt: *CERT-Bund-2022020828000531*. 

Folgende Schwachstellen wurden gefunden:

1. Remote Code Execution in der Standardinstallation
2. Exfiltration und Manipulation vertraulicher (Patienten-)Daten *i.V.m. 1*
3. Sniffing/MitM durch fehlerhafte Validierung von TLS Zertifikaten
4. SQL Injektion im Loginformular der Anwendung

**Derzeit nicht veröffentlicht, da sich der Hersteller weigert Patches zur Verfügung zu stellen (Stand: 2022-06-30).**

## English

This repository contains write-ups (in german) of various major security flaws found in [CommandX by EuroCommand](https://www.eurocommand.com/).

The vulnerabilities have been reported to the software vendor in January 2022 and to the German Federal Office for Information Security (BSI) in February 2022, which assigned ID *CERT-Bund-2022020828000531* to the findings.

The following weaknesses were found:

1. Remote code execution in default installation
2. Exfiltration and manipulation of patient data
3. Improper TLS certificate validation allowing sniffing/MitM attacks
4. SQL injection in login form of desktop application

**Currently undisclosed, because vendor refuses to provide patches as of today (2022-06-22).**
