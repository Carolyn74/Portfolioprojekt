# Profitabilitätsanalyse eines Einzelhandelsunternehmens 
Eine datengetriebene Untersuchung von Umsatzentwicklung, Profitabilität, Rabattstrategien und Produktperformance


## Projektüberblick

Ziel dieser Analyse ist die Untersuchung der Profitabilität eines Einzelhandelsunternehmens sowie die Identifikation von Faktoren, die diese beeinflussen. Im Fokus stehen der Zusammenhang zwischen Rabatten und Profitabilität sowie die Identifikation von Produktgruppen und Subkategorien mit besonders positiven oder negativen Ergebnisbeiträgen.

### Datengrundlage
Quelle: Kaggle
Datensatz: Superstore Sales Dataset
Zeitraum: 2014–2017

### Datenaufbereitung
Vor der Analyse wurden die Datensatz mit Python und Pandas geladen und aufbereitet.

Folgende Schritte wurden durchgeführt:

- Import des Datensatzes im CSV-Format
- Überprüfung der Datenqualität
- Bereinigung und Aufbereitung der Daten
- Anpassung und Konvertierung von Datentypen
- Berechnung zusätzlicher Kennzahlen:
  - Bruttoumsatz (Gross Sales)
  - Rabattbetrag (Discount Amount)
  - Gewinnmarge % (Profit Margin %)
- Erstellung und Speicherung eines bereinigten Datensatzes als Grundlage für die weiteren Analysen

### Verwendete Technologien
- Python
- Pandas
- Jupyter Notebook
- VS Code
- Git & GitHub
- Power BI

### Fragestellungen
#### Fragestellung 1
Wie haben sich Umsatz und Profitabilität zwischen 2014 und 2017 entwickelt?
#### Fragestellung 2
Welchen Einfluss hatten Rabatte auf die Profitabilität?
#### Fragestellung 3
Welche Produktgruppen tragen am wenigsten zur Profitabilität bei?
#### Fragestellung 4
Welche Subkategorien innerhalb der Kategorie Furniture beeinflussen die Profitabilität besonders stark?
#### Fragestellung 5
In welchen Regionen treten die identifizierten Profitabilitätsprobleme besonders häufig auf?
#### Fragestellung 6
Welche Bundesstaaten tragen am stärksten zu den Verlusten von Tables und Bookcases bei?
### Zentrale Erkenntnisse
- Die Analyse zeigt, dass sich Umsatz und Profitabilität zwischen 2014 und 2017 insgesamt positiv entwickelt haben. Trotz einer dauerhaft hohen Rabattbelastung konnten Umsatz und Gewinn gesteigert werden. Auf Gesamtunternehmensebene lässt sich kein eindeutiger negativer Zusammenhang zwischen Rabatten und Profitabilität feststellen.
- Detaillierte Analysen zeigen jedoch, dass die Kategorie Furniture trotz vergleichbarer Rabattquoten eine deutlich geringere Profitabilität aufweist als Technology und Office Supplies. Insbesondere die Subkategorien Tables und Bookcases tragen wesentlich zu dieser Entwicklung bei. 
- Die größten Verlustbeiträge konzentrieren sich dabei auf einzelne Bundesstaaten wie Pennsylvania, Illinois, Texas, New York und Ohio.
### Handlungsempfehlungen
- Überprüfung der Rabattstrategie für Tables und Bookcases, insbesondere bei Produkten mit negativer Profitabilität.
- Einführung von Rabattgrenzen oder Genehmigungsprozessen für hohe Rabattquoten.
- Detaillierte Analyse von Produkten mit Rabattquoten über 30 %, um sicherzustellen, dass gewahrte Rabatte durch zusätzliche Absatzmengen oder strategische Ziele gerechtfertig sind.
- Überprüfung der Kategorien Technology und Office Supplies auf Produktebene, um potenzielle Verlustbringer oder margenschwache Produkte trotz der insgesamt hohen Profitabilität der Kategorien zu identifizieren.
- Regelmäßige Überwachung von Rabattquoten, Gewinnbeiträgen und Profitabilität auf Produkt- und Subkategorieebene.
### Fazit
Die Ergebnisse verdeutlichen, dass die Profitabilität nicht allein durch gewährte Rabatte erklärt werden kann. Die Analyse zeigt vielmehr, dass neben Rabatten auch die zugrunde liegende Kostenstruktur eine wichtige Rolle spielt. Insbesondere die Subkategorien Tables und Bookcases innerhalb der Kategorie Furniture tragen maßgeblich zu den identifizierten Verlusten bei. Eine gezielte Überprüfung dieser Bereiche kann dazu beitragen, die Profitabilität nachhaltig zu verbessern. Ende