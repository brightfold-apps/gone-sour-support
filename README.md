# Gone Sour · Hilfe und Datenschutz

Statische Website für Gone Sour, veröffentlicht mit GitHub Pages:

- [Hilfe und Kontakt](https://brightfold-apps.github.io/opened-support/)
- [Datenschutz](https://brightfold-apps.github.io/opened-support/privacy.html)

## Eigene Angaben ergänzen

Die Website ist ein öffentlich sichtbarer Entwurf. Vor Verwendung für die App-Prüfung müssen die Anbieter-/Kontaktangaben und der tatsächliche Umgang mit Supportanfragen ergänzt werden.

1. [Supportseite bearbeiten](https://github.com/brightfold-apps/opened-support/edit/main/index.html): Unter „Kontakt & Support“ den bereits eingetragenen Namen prüfen sowie Postanschrift und Support-E-Mail ergänzen. Den markierten Block `pending-contact` durch echte Angaben ersetzen; die E-Mail als `mailto:`-Link eintragen.
2. [Datenschutzseite bearbeiten](https://github.com/brightfold-apps/opened-support/edit/main/privacy.html): Unter „Wer verantwortlich ist“ denselben vollständigen Namen, dieselbe Postanschrift und eine E-Mail für Datenschutzanfragen angeben. Dafür kann dieselbe Supportadresse verwendet werden.
3. In derselben Datei im Abschnitt „Wenn du den Support kontaktierst“ den tatsächlichen E-Mail-Anbieter, einen Link zu seinen Datenschutzhinweisen, gegebenenfalls internationale Verarbeitung und die tatsächlich praktizierte Löschfrist oder konkrete Löschkriterien ergänzen. Diese Angaben sind noch unbekannt und wurden nicht erfunden. Auch Kopien und Backups des verwendeten Postfachs berücksichtigen.
4. Die übrigen Beschreibungen mit der tatsächlichen Nutzung abgleichen. In beiden Dateien den Hinweis mit `class="draft-note"` und die Zeile `<meta name="robots" content="noindex,nofollow">` entfernen, sobald alle Angaben vollständig sind. Bei ausgefüllten Blöcken auch die Klasse `pending-contact` entfernen.
5. Änderungen speichern. GitHub Pages aktualisiert die Website automatisch. Den Erfolg unter [Actions](https://github.com/brightfold-apps/opened-support/actions) prüfen und anschließend beide Seiten ohne Anmeldung öffnen.

### Welche eigenen Angaben gehören hinein?

- Vollständiger Vor- und Nachname des tatsächlichen Anbieters, bei einem Unternehmen dessen vollständiger Name und gegebenenfalls Rechtsform und Vertretung.
- Zustellfähige Postanschrift: Straße, Hausnummer, Postleitzahl, Ort und Land. Ein bloßes Postfach ersetzt diese Anschrift nicht.
- Öffentliche, tatsächlich erreichbare E-Mail-Adresse für Support und Datenschutz. Eine gemeinsame Adresse genügt; sie muss nicht die private Alltagsadresse sein.
- Falls tatsächlich ein Datenschutzbeauftragter benannt ist: dessen Kontaktdaten zusätzlich angeben. Keinen solchen Ansprechpartner erfinden.

„brightfold-apps“ ist der GitHub-Organisationsname und ersetzt die Identität des tatsächlichen Verantwortlichen nicht. Die Pflicht zu weiteren Anbieterangaben, etwa vorhandenen Register- oder Umsatzsteueridentifikationsdaten, ist von der Datenschutzerklärung zu unterscheiden und hängt von der tatsächlichen Anbieterform ab. Eine persönliche Steuer-ID, ein Geburtsdatum, Bankdaten oder Ausweisdokumente gehören nicht in diese Datenschutzseite.

Die ergänzten Texte beschreiben die derzeitigen App-Funktionen und dienen als Entwurf. Die Rechtsgrundlagen sind den konkreten Zwecken zugeordnet; sie ersetzen keinen tatsächlichen Umgang mit den Daten und keine Prüfung besonderer Anbieterumstände.

Die beiden Website-Adressen bleiben bei Änderungen gleich. In App Store Connect gehört die Startseite ins Feld **Support-URL** und `privacy.html` ins Feld **Datenschutzrichtlinie**. Eine eigene Domain ist nicht nötig.

## Dateien und Veröffentlichung

`index.html`, `privacy.html`, `styles.css` und `assets/app-icon.png` bilden die Website. `.nojekyll` sorgt für die direkte Auslieferung. Es sind keine Installation, kein eigener Build und keine externen Schriften oder Skripte erforderlich. Veröffentlichungsquelle ist `main`, Verzeichnis `/`.

Das Repository enthält nur die Website, keinen Quelltext der iOS-App. Da es öffentlich ist, dürfen hier keine Zugangsdaten oder nicht zur Veröffentlichung bestimmten Informationen abgelegt werden. Die Entwurfsmarkierung und `noindex` sind kein Zugriffsschutz.
