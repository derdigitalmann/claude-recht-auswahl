# claude-recht-auswahl

Claude-Plugin-Marketplace mit einer Auswahl von Plugins aus [Klotzkette/claude-fuer-deutsches-recht](https://github.com/Klotzkette/claude-fuer-deutsches-recht), automatisch gespiegelt. Schwerpunkt: IT-Recht, gewerblicher Rechtsschutz, Urheber- und Medienrecht, E-Commerce, Datenschutz, Verträge.

Das Original-Repository ist für die Marketplace-Funktion in claude.ai zu groß (Download-Grenze 512 MB). Dieses Repository enthält deshalb nur die in `plugins.txt` gelisteten Plugins und gleicht sie täglich mit dem Original ab.

**Kein offizielles Projekt von Klotzkette.** Urheber der Plugin-Inhalte ist Klotzkette (siehe `NOTICE`). Dieses Repository spiegelt die Inhalte unverändert; geändert wird nur das Marketplace-Manifest `.claude-plugin/marketplace.json` (Name, Beschreibung, Auswahl und Pfade der Plugins).

## Enthaltene Plugins

| Bereich | Plugins |
|---|---|
| Kernset | `fachanwalt-it-recht`, `fachanwalt-gewerblicher-rechtsschutz`, `fachanwalt-urheber-medienrecht`, `ecommerce-recht`, `datenschutzrecht`, `agb-recht-pruefer`, `softwarerecht-de-eu-us`, `zitierweise-deutsches-recht`, `methodenlehre-buergerliches-recht` |
| Shop und Marktplatz | `produktrecht`, `verbraucherschutzrecht-pruefer`, `dsa-dma-digitalregulierung`, `barrierefreiheit-web-checker` |
| Gewerblicher Rechtsschutz | `markenamt-assistent`, `urheberrecht-de-eu`, `lizenzvertragsersteller`, `meinungspruefer` |
| KI und IT-Compliance | `ki-vo-ai-act-pruefer`, `nis2-cybersecurity-compliance` |
| Verträge und Durchsetzung | `vertragsrecht`, `nda-verschwiegenheit-generator-checker`, `prozessrecht` |

## Installation

**claude.ai und Claude Desktop:** Anpassen > Plugins > Hinzufügen > Marketplace hinzufügen > Aus einem Repository hinzufügen > `derdigitalmann/claude-recht-auswahl` > Synchronisieren. Danach die gewünschten Plugins einzeln hinzufügen.

**Claude Code:**

```
claude plugin marketplace add derdigitalmann/claude-recht-auswahl
claude plugin install fachanwalt-it-recht@mehmet-recht-auswahl
```

## Aktualisierung

Ein GitHub-Workflow gleicht täglich mit dem Original ab und öffnet bei Änderungen einen Pull Request. Nach dem Merge übernehmen Marketplaces mit aktivierter automatischer Synchronisierung die neue Fassung.

## Lizenz

Die gespiegelten Inhalte stehen unter `Apache-2.0 OR MIT` (Wahl des Nutzers, siehe `NOTICE`, `LICENSE-MIT`, `LICENSE-APACHE`). Dieses Repository nutzt sie unter der **MIT-Lizenz**. Skripte und Workflow dieses Repositorys stehen ebenfalls unter der MIT-Lizenz.

## Hinweis

Die Inhalte sind keine Rechtsberatung und ersetzen keine Prüfung im Einzelfall. Normen, Rechtsprechung und Fristen vor jeder Verwendung am Original prüfen. Bereitstellung unentgeltlich und ohne Gewähr.

Anbieter dieses Repositorys: Mehmet Aydoğdu, digitalmann. [Impressum](https://digitalmann.de/impressum)
