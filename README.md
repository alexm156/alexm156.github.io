# Family Hub – öffentliche Informationsseiten

Statische Projekt-, Datenschutz- und Nutzungsinformationen für den privaten Family Hub. Dieser öffentliche Quellstand enthält ausschließlich die Informationsseiten. Keine Anwendung, Zugangsdaten, privaten Kontaktdaten oder internen Serveradressen.

## GitHub Pages

Im Repository unter **Settings → Pages → Build and deployment** die Quelle **Deploy from a branch**, den Branch **main** und den Ordner **/ (root)** wählen und speichern. HTTPS aktivieren, sobald verfügbar.

Vorgesehene Adressen nach erfolgreicher Veröffentlichung:

- Startseite: https://alexm156.github.io/
- Datenschutz: https://alexm156.github.io/datenschutz.html
- Nutzung: https://alexm156.github.io/nutzung.html

Eine `.nojekyll`-Datei stellt die direkte statische Bereitstellung sicher. Keine Abhängigkeiten, Skripte, externen Schriftarten oder Analysewerkzeuge.

## Google-Konfiguration

Erst nach erfolgreicher Erreichbarkeitsprüfung die Adressen im Branding des bestehenden Google-Projekts eintragen. `alexm156.github.io` als autorisierte Domain ergänzen; bei geforderter Eigentumsbestätigung die URL-Präfix-Property `https://alexm156.github.io/` in der Google Search Console mit dem gleichen Google-Konto bestätigen. Die bereitgestellte Verifizierungsdatei unverändert im Repository-Wurzelverzeichnis ergänzen oder den konkret bereitgestellten Verifizierungs-Metatag in `index.html` einsetzen. Keinen Verifizierungscode erfinden.

Bestehenden OAuth-Client und Rückleitungsadressen des privaten Hub beibehalten. Eine öffentlich erreichbare Informationsseite allein bestätigt weder die Domain noch die Google-App. Die weitere Annahme von Branding, Domain und privaten Rückleitungsadressen muss in der Console geprüft werden. Das Projekt befindet sich bis zur dort erfolgreich bestätigten Umstellung weiterhin im Testmodus.

## Datenhinweise

Die Beschreibung wurde anhand des Funktionsstands v0.9.6 erstellt. Sie beschreibt insbesondere die mögliche Weitergabe angefragter Kontaktfelder und aktivierter Kalenderkontexte an Modellanbieter. Bei Änderungen an Datenflüssen, Modellanschlüssen, Speicherung oder Freigaben müssen die Angaben angepasst werden. Diese Veröffentlichung ist keine rechtliche oder Google-seitige Zertifizierung.

Als Kontaktweg dient die Supportadresse im Google-Zustimmungsbildschirm beziehungsweise der bestehende private Kontakt der Familienmitglieder; eine private E-Mail-Adresse wird hier nicht zusätzlich veröffentlicht.
