# Gone Sour · Hilfe und Datenschutz

Statische Website für Gone Sour, veröffentlicht mit GitHub Pages:

- [Hilfe und Kontakt](https://brightfold-apps.github.io/gone-sour-support/)
- [Datenschutz](https://brightfold-apps.github.io/gone-sour-support/privacy.html)

Die englischen Fassungen liegen unter `en/index.html` (Help & Contact) und `en/privacy.html` (Privacy). Auf allen Seiten führt die Sprachwahl „Deutsch / English“ zur entsprechenden Fassung. Die bisherigen URLs bleiben deutsch; die Navigation innerhalb von `en/` bleibt englisch. Die Sprachwahl funktioniert ohne JavaScript, Cookies oder Browser-Speicher. Deutsche App-Schaltflächen werden in der englischen Anleitung mit ihrer englischen Bedeutung erklärt.

## Anbieter- und Supportangaben

Anbieter ist Frederik Nelles. Die mitgeteilte Postanschrift lautet:

```text
Frederik Nelles
c/o IP-Management #12563
Ludwig-Erhard-Str. 18
20459 Hamburg
Deutschland
```

Support und Datenschutz verwenden **info@brightfold-apps.de**. Das Supportpostfach wird über Microsoft 365 betrieben. Nach der vom Anbieter festgelegten Praxis werden abgeschlossene Supportanfragen nach sechs Monaten gelöscht, vorbehaltlich gesetzlicher Aufbewahrungspflichten und konkreter Rechtsansprüche. Die Website beschreibt diese Praxis; sie richtet keine automatische Löschung im Postfach ein.

Adresse, E-Mail und Werbewiderspruch stehen auf beiden Seiten. Die Datenschutzerklärung erläutert außerdem die E-Mail- und Postbearbeitung. Frühere Kontaktplatzhalter und Entwurfsmarkierungen sind entfernt.

## Inhalte aktuell halten

1. Anbieter- und Kontaktangaben in `index.html`, `privacy.html` und ihren englischen Fassungen unter `en/` gemeinsam aktualisieren.
2. Bei Änderungen am E-Mail-Dienst oder an der Bearbeitung und Aufbewahrung von Supportanfragen auch die Datenschutzerklärung anpassen. Die beschriebene Löschpraxis muss im Postfach einschließlich vorhandener Kopien und Aufbewahrungsregeln umgesetzt werden.
3. Datenschutzhinweise bei Änderungen der App-Datenverarbeitung, des Webhostings oder des Postdienstes prüfen und aktualisieren.
4. Änderungen in einem Arbeitsbranch prüfen. Erst ein ausdrücklich freigegebener Merge nach `main` veröffentlicht sie über GitHub Pages. Danach [Actions](https://github.com/brightfold-apps/gone-sour-support/actions) und beide öffentlichen Seiten prüfen.
5. Beide Sprachen gemeinsam pflegen und Sprachwechsel, Navigation und mobile Darstellung in beiden Fassungen prüfen.

Die beiden Website-Adressen bleiben bei Änderungen gleich. In App Store Connect gehört die Startseite ins Feld **Support-URL** und `privacy.html` ins Feld **Datenschutzrichtlinie**.

## Dateien und Veröffentlichung

`index.html`, `privacy.html`, `en/index.html`, `en/privacy.html`, `styles.css` und `assets/app-icon.png` bilden die Website. Beide Sprachen verwenden dieselben Styles und Assets. `.nojekyll` sorgt für die direkte Auslieferung. Es sind keine Installation, kein eigener Build und keine externen Schriften oder Skripte erforderlich. Veröffentlichungsquelle ist `main`, Verzeichnis `/`.

Das öffentliche Repository enthält nur die Website, keinen Quelltext der iOS-App. Zugangsdaten und nicht zur Veröffentlichung bestimmte Informationen gehören nicht hierher. Die Angaben ersetzen keine Prüfung besonderer Anbieterumstände; zusätzliche Register- oder Umsatzsteueridentifikationsangaben hängen von der tatsächlichen Anbieterform ab.
