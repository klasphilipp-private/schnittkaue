# Schnittkaue – Website-Vorschau

Statische Webseite mit lokal ausgelieferten Bildern und Schriftarten. Die HTML-, CSS- und JavaScript-Dateien liegen direkt im Repository-Hauptverzeichnis.

## GitHub Pages

Veröffentlichung über `main`, Ordner `/` (root). Kein Build erforderlich; `.nojekyll` deaktiviert Jekyll.

Vorschau: https://klasphilipp-private.github.io/schnittkaue/

## Vor dem regulären Betrieb ergänzen

Impressum und Datenschutz sind sichtbar als Entwürfe gekennzeichnet. Offen sind:

- Rechtlicher Betreiber, Firmierung, Rechtsform und Vertretungsberechtigte anhand der Gewerbeanmeldung bestätigen. Ein Branchenverzeichnis führt den Salon unter [Nicole Devic](https://branchenbuch.meinestadt.de/recklinghausen/company/500194887). Zwei bereitgestellte Salonartikel nennen Nicole und Nedjo Devic als Salonleitung. Die rechtliche Betreiberrolle ergibt sich daraus nicht eindeutig.
- Münsterstraße 20, 45657 Recklinghausen und 02361 9386622 sind im [Branchenverzeichnis](https://web2.cylex.de/firma-home/schnittkaue-15395294.html) belegt. Die [Salonwebsite](https://schnittkaue.de/) nennt auch info@schnittkaue.de.
- Die [Handwerkskammer Münster](https://www.hwk-muenster.de/de/service-center/handwerksrolle) ist für Recklinghausen örtlich zuständig. Eintragung und Betriebsdaten aus der Handwerkskarte abgleichen. Nicole wird im bereitgestellten Salonporträt als Friseurmeisterin bezeichnet. Titel, Verleihungsstaat und ggf. die verleihende Stelle anhand der Urkunde bestätigen. Die [Handwerksordnung führt Friseure unter Anlage A Nr. 38](https://www.gesetze-im-internet.de/hwo/anlage_a.html).
- Register- und Umsatzsteuer-/Wirtschafts-ID-Angaben, soweit vorhanden/erforderlich.
- Angaben zur Verbraucherschlichtung, soweit erforderlich.
- Fotografenangaben und erforderliche Urhebervermerke.
- Betriebliche Email-/Telefon-/Terminverwaltung, Löschfristen und gegebenenfalls Datenschutzbeauftragter.
- Hosting-Vereinbarungen, internationale Datenverarbeitung und konkrete Protokollspeicherdauer.

Die Vorschau ist mit `noindex,follow,max-image-preview:large` gekennzeichnet. Dies verhindert keinen Zugriff; Repository und Pages-Vorschau sind öffentlich.

## Datenschutz und Cookie-Hinweis

Keine eigenen Analyse- oder Werbedienste; keine extern geladenen Schriften oder eingebetteten Social-Media-Inhalte. Der Hinweis speichert nach Klick auf „Verstanden“ ausschließlich `schnittkaue-privacy-notice=dismissed` im Session Storage. Über den Footer kann der Hinweis erneut geöffnet werden. Wenn zusätzliche Dienste hinzukommen, sind Hinweis und Datenschutzerklärung entsprechend anzupassen.

GitHub Pages protokolliert IP-Adressen zu Sicherheitszwecken. Informationen: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages und https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

Rechtliche Quellen: § 5 DDG https://www.gesetze-im-internet.de/ddg/__5.html und § 25 TDDDG https://www.gesetze-im-internet.de/ttdsg/__25.html

## Bearbeitung

`index.html`: Startseite · `style.css`: Layout · `app.js`: Menü, Galerie, Header und Hinweis · `impressum.html` und `datenschutz.html`: Rechtstextentwürfe · `assets/`: Bilder und Schriften.

## SEO-Vorbereitung

Seitentitel und Beschreibung für Friseur/Schnittkaue/Recklinghausen, Canonical, Open Graph, Twitter Card und strukturierte Daten (WebSite, WebPage, HairSalon) sind enthalten. Das Headerfoto ist als JPEG unter `assets/schnittkaue-eigentuemer-vorschau.jpg` mit absoluter URL als Vorschau- und bevorzugtes Seitenbild hinterlegt. Keine erfundenen Öffnungszeiten, Bewertungen, Preise oder Betreiberangaben.

Die Arbeitsvorschau bleibt `noindex`. Beim regulären Livegang: absolute URLs in Canonical, Open Graph, strukturierten Daten und Sitemap auf die finale Domain umstellen; Startseite mit `index,follow,max-image-preview:large` freigeben; Sitemap in robots.txt referenzieren und in Google Search Console einreichen. Rechtstextseiten können `noindex` behalten. Google entscheidet selbst über das letztlich angezeigte Bild und Snippet.

Quellen: https://developers.google.com/search/docs/appearance/google-images und https://developers.google.com/search/docs/appearance/structured-data/local-business
