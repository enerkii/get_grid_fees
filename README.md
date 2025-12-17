Fertiggestellte Features:
1. Formular-Felder (nach deinen Vorgaben):
Persönliche Daten: Vorname*, Nachname*, Anrede, Unternehmen
Kontaktdaten: E-Mail*, Telefon
Technische Daten: Spannungsebene* (Dropdown: Niederspannung/Mittelspannung/Hochspannung)
Adresse: Straße und Hausnummer*, PLZ*, Stadt*
2. Validierung:
Pflichtfelder mit * markiert
E-Mail Pattern-Validierung
Telefon optional mit Pattern-Validierung
PLZ: 5-stellig deutsch (Pattern: ^\d{5}$)
minLength Checks für Textfelder
Echtzeit-Fehlerbehandlung
3. Design:
Gleiche enerkii Farbpalette wie in index.html
Zentriertes, fokussiertes Formular-Layout
Responsive Design (mobile-first)
Saubere Gruppierung nach Datentypen
Shadow-Box Design
4. API Integration:
POST Request an Webhook-URL: https://enerkii.app.n8n.cloud/webhook/grid_operator_lookup
Payload mit allen Formularfeldern
15 Sekunden Timeout
Error Handling mit User-Feedback
5. Views:
Main View: Übersichtliches Formular
Success View: Grüner Checkmark + Erfolgsmeldung
Wichtige Hinweise:
Die Webhook-URL ist ein Platzhalter und kann in Zeile 60 angepasst werden
Das Formular sendet alle Daten als JSON POST Request
Alle Validierungen funktionieren clientseitig in Echtzeit
Responsive für Mobile und Desktop optimiert
Die Datei ist einsatzbereit! Du kannst sie direkt öffnen und testen.
