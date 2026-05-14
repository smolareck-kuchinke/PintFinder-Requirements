
# Analyse: PintFinder

## 1. Einleitung

PintFinder ist eine Plattform zur Bewertung von Guinness-Bieren in Berliner Bars, Pubs und Kneipen. User können Bars suchen, Bewertungen abgeben, Bilder hochladen und andere Erfahrungen kommentieren.

Das Ziel des Projekts ist die Entwicklung einer spezialisierten Community-Plattform für Guinness-Fans. Im Mittelpunkt stehen Nutzerbewertungen, Kartenfunktionen und die Vernetzung von Berliner Pubs mit interessierten Besuchern.


---

## 2. Methodik und verwendete Werkzeuge

Für die Analyse und Planung des Projekts habe ich unterschiedliche Werkzeuge eingesetzt.

### Trello
Trello habe ich als einfaches Tool verwendet. Dort wurden erste Ideen, Anforderungen und Statusinformationen gesammelt und strukturiert.

### Jira
Jira habe ich als professionelles Projektmanagementwerkzeug verwendet. Dort wurden Requirements mit verschiedenen Attributen wie Priorität, Stakeholder, Akzeptanzkriterien und Status dokumentiert.

### GitHub
GitHub habe ich für die Versionsverwaltung und Dokumentation des Projekts genutzt. Zusätzlich wurden dort Screenshots, technische Dokumentationen und Analyseergebnisse abgelegt.

### Vorgehensmodell
Für das Projekt wurde ein agiles Vorgehensmodell gewählt. Anforderungen werden schrittweise entwickelt, validiert und erweitert.

---

## 3. Stakeholder-Analyse

Für PintFinder existieren unterschiedliche Stakeholder mit verschiedenen Interessen.

### Endnutzer
Die Hauptzielgruppe sind Guinness-Fans und Besucher von Berliner Bars. Nutzer möchten hochwertige Empfehlungen, ehrliche Bewertungen und eine einfache Navigation erhalten.

### Pub- und Barbetreiber
Barbetreiber profitieren von positiven Bewertungen und höherer Sichtbarkeit auf der Plattform. Gleichzeitig besteht Interesse an fairen und transparenten Bewertungen.

### Plattformbetreiber
Die Betreiber der Plattform sind verantwortlich für Wartung, Moderation, Datenschutz und technische Weiterentwicklung.

### Entwicklerteam
Das Entwicklerteam ist verantwortlich für Architektur, Sicherheit, Qualitätssicherung und Weiterentwicklung der Plattform.

---

## 4. Datenanalyse

Im Projekt werden unterschiedliche Arten von Daten verarbeitet.

### Benutzerdaten
- Benutzername
- E-Mail-Adresse
- Login-Daten

Diese Daten unterliegen datenschutzrechtlichen Anforderungen.

### Bewertungsdaten
Nutzer können Guinness-Biere bewerten und Kommentare verfassen. Diese Daten bilden das Kernfeature der Plattform.

### Bilddaten
Benutzer können Bilder von Guinness-Bieren oder Bars hochladen. Dabei müssen Dateitypen, Speichergrößen und Sicherheitsaspekte berücksichtigt werden.

### Standortdaten
Die Plattform verarbeitet Standortinformationen von Bars sowie optionale Geolokationsdaten von Nutzern.

### Metadaten
Zusätzlich entstehen technische Metadaten wie Zeitstempel, Logdaten und API-Anfragen.


## 5. Anforderungsebene

Für PintFinder wurden funktionale und nichtfunktionale Anforderungen definiert.

### Funktionale Anforderungen
- Benutzerregistrierung
- Guinness-Bewertungssystem
- Bild-Upload
- Kartenansicht Berliner Pubs
- Google-Maps-Navigation
- Suchfunktion
- Kommentar-System

### Nichtfunktionale Anforderungen
- hohe Benutzerfreundlichkeit
- schnelle Ladezeiten
- sichere Authentifizierung
- Datenschutzkonformität
- Skalierbarkeit der Plattform

- ## 6. Rechtlich-regulatorische Ebene

Das Projekt verarbeitet personenbezogene Daten und muss daher rechtliche Anforderungen berücksichtigen.

### Datenschutz
Die Speicherung von Benutzerkonten, Bewertungen und Standortdaten unterliegt den Anforderungen der DSGVO.

### Bildrechte
Beim Hochladen von Bildern müssen Urheberrechte sowie Persönlichkeitsrechte berücksichtigt werden.

### Moderation
Kommentare und Bewertungen müssen moderiert werden, um rechtswidrige oder beleidigende Inhalte zu vermeiden.

### API-Nutzung
Die Nutzung externer Dienste wie Google Maps unterliegt zusätzlichen Nutzungsbedingungen und möglichen Kostenmodellen.

---

## 7. Ethics & Trustworthy AI

Im Projekt sollen KI-Funktionen verantwortungsvoll eingesetzt werden.

### Transparenz
Empfehlungen und KI-generierte Inhalte sollen nachvollziehbar bleiben und den Nutzern transparent dargestellt werden.

### Vermeidung von Bias
Bewertungssysteme und KI-Empfehlungen dürfen einzelne Bars oder Nutzer nicht unfair bevorzugen oder benachteiligen.

### Vertrauenswürdigkeit
Die Plattform soll ehrliche Bewertungen fördern und Manipulationen durch Fake-Accounts verhindern.

### Datenschutz
KI-Systeme dürfen personenbezogene Daten nur im notwendigen Umfang verarbeiten.

---

### Priorisierung
Die wichtigsten Kernfunktionen wurden zunächst als MVP (Minimum Viable Product) priorisiert. Dazu gehören Registrierung, Bewertungen und Kartenfunktionen.

---

## 8. Sicherheitsebene

Für PintFinder bestehen verschiedene sicherheitsrelevante Anforderungen.

### Authentifizierung
Benutzerkonten müssen gegen unbefugte Zugriffe geschützt werden. Passwörter sollen sicher gespeichert und gehasht werden.

### Schutz vor Missbrauch
Die Plattform muss gegen Spam, Fake-Bewertungen und automatisierte Bot-Angriffe abgesichert werden.

### Sichere Bild-Uploads
Beim Upload von Bildern müssen schädliche Dateien und unsichere Dateiformate erkannt und blockiert werden.

### API-Sicherheit
Externe APIs wie Google Maps müssen sicher eingebunden und API-Schlüssel geschützt gespeichert werden.

### Datenschutz und Zugriffskontrolle
Nur berechtigte Benutzer dürfen auf bestimmte Daten oder Verwaltungsfunktionen zugreifen.

---

## 9. Qualitätssicherungsebene

Zur Sicherung der Softwarequalität werden unterschiedliche Maßnahmen eingesetzt.

### Reviews
Requirements und Anforderungen werden regelmäßig überprüft und aktualisiert.

### Akzeptanzkriterien
Für zentrale Funktionen wurden Akzeptanzkriterien definiert, um Anforderungen messbar zu machen.

### Tests
Wichtige Funktionen wie Login, Bewertungen und Uploads sollen getestet werden.

### Versionsverwaltung
Git und GitHub ermöglichen die Nachvollziehbarkeit von Änderungen und unterstützen die Zusammenarbeit.

### Iterative Verbesserung
Durch agile Entwicklung und Feedback können Anforderungen schrittweise verbessert werden.

---

## 10. Prozess- und Lifecycle-Ebene

Für PintFinder wurde ein iteratives Vorgehensmodell gewählt. Anforderungen werden schrittweise entwickelt, getestet und erweitert.

### MVP-Ansatz
Zunächst soll ein funktionsfähiges Minimalprodukt entwickelt werden. Der Fokus liegt dabei auf Registrierung, Bewertungen und Kartenfunktionen.

### Iterative Weiterentwicklung
Neue Funktionen wie Bild-Uploads, Kommentare oder KI-Empfehlungen werden in späteren Iterationen ergänzt.

### Agile Entwicklung
Das Projekt orientiert sich an agilen Methoden mit kurzen Entwicklungszyklen und regelmäßiger Überprüfung der Anforderungen.

### Wartbarkeit
Durch modulare Komponenten und Versionsverwaltung soll die Plattform langfristig erweiterbar und wartbar bleiben.

---

## 11. Wirtschaftlich-strategische Ebene

PintFinder verfolgt die Idee einer spezialisierten Plattform für Guinness- und Pub-Kultur in Berlin.

### Zielgruppe
Die Plattform richtet sich insbesondere an Guinness-Fans, Touristen und Besucher von Berliner Pubs.

### Wettbewerb
Indirekte Konkurrenz besteht durch Plattformen wie Google Maps oder Untappd. PintFinder konzentriert sich jedoch gezielt auf Guinness-Bewertungen und Berliner Pubs.

### Skalierungsmöglichkeiten
Langfristig könnte die Plattform auf andere Städte oder weitere Getränkekategorien erweitert werden.

### Monetarisierung
Mögliche Geschäftsmodelle wären:
- Werbung
- Premium-Funktionen
- Kooperationen mit Bars
- Event-Partnerschaften

### Kosten
Zu den wichtigsten Kostenfaktoren zählen:
- Hosting
- API-Nutzung
- Bildspeicherung
- Moderation
- Weiterentwicklung

---

## 12. AI-Erweiterung des Projekts

Im Rahmen der Analyse wurde das Projekt um mögliche KI-Funktionen erweitert.

### KI-basierte Empfehlungen
Die Plattform könnte Nutzern auf Basis bisheriger Bewertungen passende Bars oder Guinness-Sorten empfehlen.

### Bilderkennung
Eine KI könnte hochgeladene Bilder analysieren und automatisch erkennen, ob Guinness-Biere oder bestimmte Bars dargestellt werden.

### Kommentar-Moderation
KI-Systeme könnten beleidigende oder unangemessene Kommentare automatisch erkennen und markieren.

### Analyse von Bewertungen
Durch KI könnten häufig genannte Probleme oder besonders positiv bewertete Bars automatisch identifiziert werden.

### Risiken von KI
Der Einsatz von KI bringt zusätzliche Risiken mit sich:
- Bias in Empfehlungen
- fehlerhafte Moderation
- Datenschutzprobleme
- mangelnde Transparenz von Entscheidungen

---


## 13. Fazit

Die Analyse von PintFinder zeigt, dass bereits in frühen Projektphasen unterschiedliche technische, organisatorische, rechtliche und sicherheitsrelevante Aspekte berücksichtigt werden müssen.

Durch den Einsatz von Jira, Trello und GitHub konnten Anforderungen strukturiert dokumentiert und analysiert werden. Besonders wichtig waren dabei Datenschutz, Sicherheit, Benutzerfreundlichkeit und Skalierbarkeit der Plattform.

Die Erweiterung um KI-Funktionen zeigt mir zusätzlich, dass moderne Softwareprojekte zunehmend Anforderungen im Bereich AI berücksichtigen müssen.

----

U.a. verwendete AI-Prompts von ChatGPT


- „Erstelle funktionale Anforderungen für eine Guinness-Bewertungsplattform.“
- „Welche Sicherheitsrisiken existieren bei Bild-Uploads aus IT-Sicherheitssicht?“
- „Erstelle Akzeptanzkriterien für eine Kartenansicht.“
- „Welche KI-Funktionen wären für eine Community-Plattform sinnvoll?“
- „Wie könnte eine Startup-Roadmap für PintFinder aussehen?“

