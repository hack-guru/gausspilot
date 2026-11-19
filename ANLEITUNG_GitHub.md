# GaussPilot-Webseite bei GitHub Pages veröffentlichen

## 1. Platzhalter ausfüllen
In `index.html`, `impressum.html` und `datenschutz.html` alle Stellen in eckigen Klammern ersetzen:
`[VORNAME NACHNAME]`, `[STRASSE HAUSNUMMER]`, `[PLZ ORT]`, `[E-MAIL-ADRESSE]`, `[TELEFON – optional]`.
Das Impressum braucht eine ladungsfähige Anschrift (kein Postfach).

## 2. Hochladen (ohne Programmierkenntnisse)
1. Auf https://github.com ein Konto anlegen bzw. anmelden.
2. Oben rechts **„+“ → „New repository“**. Name z. B. `gausspilot`, **Public**, „Create repository“.
3. Auf der leeren Seite **„uploading an existing file“** anklicken und diese Dateien hineinziehen:
   `index.html`, `impressum.html`, `datenschutz.html`, `style.css`, `.nojekyll`
   (diese Anleitung muss nicht mit). „Commit changes“.
   Tipp: `.nojekyll` ist unter Windows evtl. ausgeblendet – die Seite funktioniert auch ohne.
4. Im Repository **Settings → Pages**: bei „Source“ **„Deploy from a branch“**, Branch **main**, Ordner **/(root)**, „Save“.
5. Nach 1–2 Minuten ist die Seite erreichbar unter `https://<IHR-GITHUB-NAME>.github.io/gausspilot/`
   – diese Adresse bei ELSTER als „Webseite“ eintragen.

**Wichtig:** Das Repository ist öffentlich. Nur die Webseiten-Dateien hochladen – **niemals** den Programmcode,
die `Daten`, `Sicherungen` oder `Steuer`-Ordner.

## 3. Später: eigene Adresse
Wenn `gausspilot.de` registriert ist: Settings → Pages → „Custom domain“ eintragen und beim Domain-Anbieter
einen CNAME-Eintrag auf `<IHR-GITHUB-NAME>.github.io` setzen. Dann „Enforce HTTPS“ anhaken.
