📝 _Draft_

# Citizen Science Projekt - Connectivity Layer

Dieses Dokument enthält einen Entwurf für einen Connectivity-Layer für ein Citizen Science Projekt.

## Hintergrund

Zum Hintergrund des Gesamtprojektes kannst du [hier mehr lesen](./Hintergrund.md).

## Welche Daten werden erhoben?

Das Citizen Science Projekt zur Überwachung des Ökosystems des Flusses Oker konzentriert sich auf die Erhebung verschiedener Arten von Umweltdaten. Die Schlüsseldatenarten, die erhoben werden, sind:

1. **Sedimentproben** \
   Diese Proben werden von autorisierten Personen entnommen und analysiert, um die Konzentration von Schwermetallen im Flussbett zu bestimmen. Diese Daten sind besonders wichtig, um die Verschmutzungsquellen und die Auswirkungen auf das Ökosystem zu verstehen.

2. **Wasserqualitätsparameter** \
   Automatisierte Sensorik erfasst wichtige Wasserqualitätsparameter wie pH-Wert, Sauerstoffgehalt und Temperatur des Wassers. Diese Daten geben fortlaufend Aufschluss über den Gesundheitszustand des Flusses und helfen bei der Identifikation von Umweltveränderungen und potenziellen Gefahrenquellen.

3. **GPS-Daten** \
   Die entnommenen Proben werden mit Hilfe von GPS georeferenziert, was bedeutet, dass die genauen Standorte der Probenentnahme dokumentiert werden. Diese räumlichen Daten sind entscheidend für die Visualisierung der Daten auf einer Open Source Karte, um räumliche Muster der Verschmutzung und ihre Verbreitung im Flussbett zu erkennen.

4. **Bürgerbeteiligungsdaten** \
   Daten zur Beteiligung der Bürger, etwa wie viele Personen an der Probenentnahme beteiligt sind oder an Bildungsveranstaltungen teilnehmen, können ebenfalls erfasst werden. Diese Daten sind wichtig, um das Engagement und die Wirksamkeit des Projekts in der lokalen Gemeinschaft zu bewerten.

Durch die Kombination dieser Daten und die Bildung von Zeitreihen kann das Projekt umfassende Einblicke in die Umweltbedingungen des Flusses Oker gewinnen und gleichzeitig das öffentliche Bewusstsein und Engagement für Umweltthemen fördern.

## Wie werden die Daten erhoben?

Elemente für eine Citizen Science App mit Datenplattform – "Oker Explorer"

### 1. Mobile Web-Anwendung für manuelle Probenentnahme

Erfassung von Daten zu Sedimentproben durch Nutzer.

- Eingabefelder für Ort (GPS-gestützt), Datum, Zeit, Nummer Probenentnahme.
- Möglichkeit zur Angabe der beteiligten Personen.
- Einfaches und intuitives Design für schnelle Dateneingabe.
- Upload-Funktion für Fotos oder zusätzliche Notizen.

### 2. Integration automatisierter Sensorik

Kontinuierliche Erfassung und Übertragung von Wasserqualitätsdaten in eine zentrale Datenbank.

- Sensorintegration für Parameter wie pH-Wert, Sauerstoffgehalt, Temperatur.
- Echtzeit-Datenübertragung in die Cloud-Datenbank.
- System zur Wartung und Überwachung der Sensorik – [siehe Fernwartung](/Fernwartung.md)

### 3. Interaktive Webseite zur Datenpräsentation und Community-Bildung

Visualisierung der gesammelten Daten und Förderung der Nutzerbeteiligung.

- Kartenansicht zur Darstellung der Datenpunkte.
- Registrierungsoption und Benutzerkonten.
- Diskussionsbereich zur Förderung des Community-Austausches.
- Informations- und Lernbereiche über Flussökologie und Umweltschutz.

### 4. Gamifizierungselemente zur Steigerung der Nutzerbeteiligung

Motivation der Nutzer durch spielerische Elemente.

- Belohnungssystem für regelmäßige Beiträge (z.B. Badges, Punkte).
- Herausforderungen und Wettbewerbe mit Leaderboards.
- Interaktive Tutorials und Quizze zur Wissensvermittlung.

## Technische Anforderungen und Integration:

- Sichere und skalierbare Cloud-Infrastruktur zur Datenspeicherung.
- Responsive Design für die Web-Anwendung, kompatibel mit verschiedenen Geräten.
- Datenschutzkonforme Verarbeitung der Nutzerdaten.
- Schnittstellen (APIs) für die Integration von Sensordaten und externe Tools wie openSenseMap.
