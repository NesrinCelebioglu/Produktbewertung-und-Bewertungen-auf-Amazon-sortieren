# Amazon Produktbewertung Analyse & Sortierung

Dieses Projekt analysiert Amazon-Produktbewertungen, berechnet gewichtete Durchschnittsbewertungen und sortiert die Bewertungen, um die zuverlässigsten und hilfreichsten Rezensionen hervorzuheben.

## Geschäftszweck

### Auf E-Commerce-Plattformen ist es entscheidend, die Produktbewertungen korrekt zu berechnen und Kommentare effektiv zu sortieren:

- Erhöht die Kundenzufriedenheit
- Hilft Verkäufern, ihre Produkte hervorzuheben
- Verbessert das Einkaufserlebnis der Nutzer

### Probleme bei falscher oder irreführender Sortierung:

- Negativer Einfluss auf den Produktverkauf
- Finanzielle Verluste
- Verlust von Kunden

### Ziel des Projekts:

- Berechnung gewichteter Bewertungen auf Basis aktueller Rezensionen
- Effektive Rangfolge der Kommentare für verlässliche Darstellung

## Datensatz

Der Datensatz enthält Produktbewertungen für Elektronikprodukte.
| Spalte           | Beschreibung                                        |
| ---------------- | --------------------------------------------------- |
| `reviewerID`     | Benutzer-ID                                         |
| `asin`           | Produkt-ID                                          |
| `reviewerName`   | Name des Rezensenten                                |
| `helpful`        | Hilfreichkeitsbewertung `[helpful_yes, total_vote]` |
| `reviewText`     | Text der Bewertung                                  |
| `overall`        | Bewertung des Produkts (Rating)                     |
| `summary`        | Zusammenfassung der Bewertung                       |
| `unixReviewTime` | Zeitstempel der Bewertung (Unix)                    |
| `reviewTime`     | Zeitstempel der Bewertung (lesbares Datum)          |
| `day_diff`       | Tage seit der Bewertung                             |
| `helpful_yes`    | Anzahl der hilfreichen Stimmen                      |
| `total_vote`     | Gesamtanzahl der Stimmen                            |

## Fazit

- Gewichtete Bewertungen zeigen die aktuelle Wahrnehmung des Produkts.

- Wilson Lower Bound sorgt für zuverlässige Top-Bewertungen.

- Die Methode kann auf andere E-Commerce-Plattformen übertragen werden, um die Kundenzufriedenheit zu steigern.
