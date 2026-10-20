# opened · Hilfe und Datenschutz

Statische Website für opened, veröffentlicht mit GitHub Pages:

- [Hilfe und Kontakt](https://brightfold-apps.github.io/opened-support/)
- [Datenschutz](https://brightfold-apps.github.io/opened-support/privacy.html)

## Eigene Angaben ergänzen

Die Website ist ein öffentlich sichtbarer Entwurf. Vor Verwendung für die App-Prüfung müssen die Anbieter-/Kontaktangaben und der tatsächliche Umgang mit Supportanfragen ergänzt werden.

1. [Supportseite bearbeiten](https://github.com/brightfold-apps/opened-support/edit/main/index.html): Im Abschnitt „Kontakt & Support“ den markierten Absatz `pending-contact` durch die eigenen öffentlichen Angaben ersetzen. Für eine anklickbare E-Mail-Adresse einen `mailto:`-Link verwenden.
2. [Datenschutzseite bearbeiten](https://github.com/brightfold-apps/opened-support/edit/main/privacy.html): Die markierten Absätze bei „Wer verantwortlich ist“ und „Wenn du den Support kontaktierst“ vervollständigen. Kontaktweg und tatsächliche E-Mail-Verarbeitung angeben.
3. In beiden Dateien den sichtbaren Hinweis mit `class="draft-note"` und die Zeile `<meta name="robots" content="noindex,nofollow">` entfernen, sobald alle Angaben vollständig sind.
4. Änderungen speichern. GitHub Pages aktualisiert die Website automatisch. Den Erfolg unter [Actions](https://github.com/brightfold-apps/opened-support/actions) prüfen und anschließend beide Seiten ohne Anmeldung öffnen.

Die beiden Website-Adressen bleiben bei Änderungen gleich. In App Store Connect gehört die Startseite ins Feld **Support-URL** und `privacy.html` ins Feld **Datenschutzrichtlinie**. Eine eigene Domain ist nicht nötig.

## Dateien und Veröffentlichung

`index.html`, `privacy.html`, `styles.css` und `assets/app-icon.png` bilden die Website. `.nojekyll` sorgt für die direkte Auslieferung. Es sind keine Installation, kein eigener Build und keine externen Schriften oder Skripte erforderlich. Veröffentlichungsquelle ist `main`, Verzeichnis `/`.

Das Repository enthält nur die Website, keinen Quelltext der iOS-App. Da es öffentlich ist, dürfen hier keine Zugangsdaten oder nicht zur Veröffentlichung bestimmten Informationen abgelegt werden. Die Entwurfsmarkierung und `noindex` sind kein Zugriffsschutz.
