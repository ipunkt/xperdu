# xperdu
Changelog for xperdu - a website builder.

## 2.8.1
Features:
- Richtext Checkbox im Formular ergänzt

## 2.8.0
Features:
- Eigentümer auf N3W geändert
- Korrektur der Update-URLs diverser Plugins
- HTML Block für Seiteninhalte ergänzt

## 2.7.3
Features:
- RSS Feed des Blogs kann mittels Kategorie Parameter gefiltert werden

## 2.7.2
Features:
- Geänderte [Avalex API](https://www.avalex.de/222.html) integriert
- Neue Formularfeldkomponente für E-Mail Adressen
- Fehlerbehandlung für Twig-Templates erweitert
  - wenn Variablen im Template nicht ersetzt werden können wird der Seitenbetreiber per E-Mail darüber informiert

Bugfix:
- Vimeo Videos werden nicht in voller Breite/Höhe begonnen

## 2.7.1
Bugfix:
- PHP7 Support für Less-Kompilierung

## 2.7.0
Features:
- Einbindung von [Avalex.de](https://www.avalex.de/222.html) für Rechtstexte

## 2.6.1
Features:
- "Gruppierung" für Dienstleistungsblöcke ermöglichen
  - Dienstleistungsblöcke die die Option `Mit anderen Elementen gruppieren` aktiv haben, werden miteinander verbunden, als wären sie ein einzelnes Dienstleistungselement.

## 2.6.0
Features:
- Formular-Handling erweitert um Twig-Templates
  - Versand-E-Mail Body lässt sich per Twig-Template setzen
  - Versandbestätigung an Formularausfüller einstellbar
  - Versandbestätigung per Twig-Template möglich
  - Berechnung und Datum automatisch möglich

## 2.5.5
Features:
- Cookie Consent Farben aus CSS werden angewendet
- Blogbeitrag kann Hintergrundbild hochkant ergänzen
- Download-Links in Dienstleistungen sind als Download gekennzeichnet
- Position der Social Midea Bar immer fixed (TOP)
- Lat/Lng als String Eingabefelder für Karte und Pins geändert (Map-Script kann alle Eingaben fehlertolerant nutzen)
- Hintergrundfarbe für Bildelement ermöglicht
- Höhe der Megamenüpunkte über Variable steuerbar
- Stilvorlagen für WYSIWYG Elemente ergänzt

## 2.5.4
Features:
- Google Tag Manager hinzugefügt

## 2.5.3
Bugfix:
- RSS Feed mit absoluten URLs für Images unterstützen

## 2.5.2
Bugfix:
- Page-Navigation Element in Blogübersichtseite als `section` markiert, Styling angepasst
- Fehler in NoCache-Plugin behoben durch Aktualisierung auf letzten Stand

## 2.5.1
Bugfix:
- Diverse Whitespace-Fixes aus dem letzten Release nachgebessert
- Abstände für Vollflächenelemente als erstes/letztes Element angepasst
- Kategorien in Blogübersichtseite als `section` markiert, Styling angepasst

## 2.5.0
Features:
- Anpassung Layouts/Strukturen der Komponenten auf klare HTML Struktur und Whitespace Verhalten
- Parallax Effekt für Bildelement schaltbar
- Schriftschnitt kann per CSS Config festgelegt werden
- Whitespace vereinheitlicht
- Übersetzung für Cookiebanner / DSGVO-Banner

Bugfix:
- deaktivierte Suche blendet Suchbuttons aus
- Map-Einbindung
- Diverse Paddings/Margins angepasst
- Footer `z-index` für Popover

## 2.3.8
Bugfix:
- Margin bei Icons im Diensleistungselement

## 2.3.6
Features:
- Update Cookiebanner: Ist der neue Cookiebanner aktiv, muss in diesem zunächst die Zustimmung für die Analytics-Tools erteilt werden,
  bevor diese geladen werden. (#268)

## 2.3.5
Bugfix:
- Bilder in Dienstleistungselementen/Kacheln sind nicht zentriert, wenn Layout auf zentriert steht (#275)

## 2.3.4
Bugfix:
- Absender bei E-Mail-Formularen nicht korrekt gesetzt

Features:
- Neues Element "Kacheln" (#266)
    - Layout identisch mit Dienstleistungen
    - WYSIWYG-Text (vollständig freie Gestaltung)
    - Kacheln haben keine direkten Links

## 2.3.3
Bugfix:
- Go-Live Button führt Aktion nicht aus (#272)

## 2.3.2
Bugfix:
- Go-Live lädt bei Erfolg die Seite nicht richtig neu (#272)

## 2.3.1
Features:
- Sortierung und Ausrichtung der Inhalt in Dienstleistungsblöcken (#252)
- Craft Update Button vollständig verstecken (#267)

## 2.3.0
Features:
- "Go-Live" Button in Einstellungen
- Craft Auto-Updates deaktiviert (#267)
- Deprecated Elemente entfernt (#269)

## 2.2.24
Updates:
- Craft-Version 2.7.6

Bugfix:
- Hintergrundfarbe für Instagram ergänzt (#261)
- Fehlende Verknüpfung für Instagram im Footer (#261)
- Zeilenabstand für Listen (`ul`/`ol`) in WYSIWYG-Einträgen angepasst (#262)

## 2.2.23
Features:
- Anpassungen an Sentryplugin um Fehler auch außerhalb übergeben zu können

## 2.2.22
Features:
- Art des Claims in einem Bildelementslide kann jetzt frei bestimmt werden (Auswahl zw. H1-H6 und "Schmuckelement"bzw. Div) (#251)

## 2.2.21
Bugfix:
- Darstellungsfehler beim Hovern im Megamenu (#250)

## 2.2.20
Features:
- Environment-Variable für `TRAILING_SLASH` hinzfügen (#257)

## 2.2.19
Bugfix:
- Mailversand aus Formular zeigt keine Inhalte (#254)

Features:
- Verzögerung beim ein-/ausblenden der Dropdown-Navigation (#250)

## 2.2.18
Bugfix:
- Vorgegebene Felder "Absender" werden nicht im E-Mail-Inhalt gezeigt (#246)
- Google Maps nur dann laden, wenn es auch im Backend gesetzt ist (#241)

Features:
- Socialmedia-Icons im Footer immer in Footer-Link-Farben (`@color-link-footer` und `@color-link-footer-hover`) (#247)

## 2.2.17
Bugfix:
- Datumfelder in älteren Browsern funktionieren nicht (#245, Polyfill für date inputs)

Features:
- reCAPTCHA für alle Formulare automatisch aktiv, sofern key im Backend gesetzt.

## 2.2.16
Bugfix:
- Linkfarbe in Megafooter anpassen

## 2.2.15
Features:
- Verlinkung für Titel im Bildelement (#238)

Bugfixes:
- Darstellung Navigation in ie11 (#239)

## 2.2.14
Features:
- Healthcheck für Dockercontainer

## 2.2.13
Features:
- Sentry-Plugin um Fehlermeldungen an einen zentralen Sentryserver zu schicken

## 2.2.12
Features:
- Disabled-Styling für Buttons (`.button.disabled`) mit entsprechenden Variablen

## 2.2.11
Neues Plugin:
- Shopify (ermöglicht die Einbindung eines Shopify-Webshops durch Templates)

Features:
- Geringfühgige Stylingverbesserungen für Formularfelder
- Fehlerstyles für flexible Forms

xperdu Extensions:
- Sections (Es lassen sich ab jetzt auch Sections/Einträge über Extensions installieren)

## 2.2.10
Neues Plugin:
- No-Cache (ermöglicht Caching in Teiltemplates zu deaktivieren)

## 2.2.9
Updates:
- Craft-Version 2.7.4

Bugfixes:
- nginx-Konfiguration für aktuelles Rancherize

Features:
- xperdu Extensions
    - xperdu bietet jetzt die Möglichkeit von anderen Plugins an bestimmten Core-Funktionen einzuhaken, wie z.B.
      die xperdu-Komponenten.
    - Damit lassen sich jetzt spezifische Plugins entwickeln, welche den Funktionsumfang von xperdu sinnvoll erweitern.
    - Dokumentaton hierzu befindet sich angehangen an die README.md
- Globale Einstellung: Metanavi
    - Zusätzliches frei konfigurierbares Navigationselement oberhalb der Standardnavigation
    - Wird mobil an die bestehende Navigations angehangen
- Globale Einstellung: Megafooter
    - Zusätzliches frei konifgurierbares Footerlement (4-spaltig)
    - Bietet eine Freitextfläche in der Kontaktspalten
    - Wenn aktiv, schrumpft der Standardfooter
- Bootstrap-Grid in CSS

## 2.2.8
Bugfix:
- Fehler bei der Formatierung der Media Queries für Bildelement aus 2.2.7 (siehe #219)

## 2.2.7
Updates:
- Craft-Version 2.7.2

Bugfix:
- Breakpoints für Menü sind wieder vorhanden (#215)
- Verhalten der Farbe für "Individueller Link" in Social-Media-Bar korrigiert (#216)
- Link-Hover-Farbe wird jetzt wieder korrekt verwendet (#218)
- Text/Label für Formulare verwenden, wenn Wert nicht festgelegt (#220)

Features:
- Zusätzliche Bildquelle "Hochkant" für das Bildelement um die Darstellung für mobile Geräte zu optimieren (#219)

## 2.2.6
Features:
- Weitere Gestaltungsmöglichkeiten für das Menü
    - Hintergrundfarbe für Dropdown/Megamenü: `@background-dropdown-opacity` und `@color-background-dropdown`
    - Hovereffekt für Verlinkungen: `@background-link-navigation-hover`
- Padding für Megamenü/Dropdown angepasst

## 2.2.5
Bugfix:
- Formatierung innerhalb WYSIWYG-Elementen zerstört umliegendes Raster (#206)

Features:
- Social-Media-Bar kann jetzt um eigene Einträge ("Individueller Link") ergänzt werden (#208)
- Google reCAPTCHA für Formulare aktivierbar (#209)

## 2.2.4
Bugfix:
- Störer mobil nicht scrollbar (#205)

## 2.2.3
Updates:
- Craft-Version 2.7.0

Bugfix:
- Margin zu "Weiterlesen"-Button in Listing nicht vorhanden
- Portrait in Bildelement wird nicht korrekt positioniert

Features:
- Listing-Einträge mit dem Style "Liste" können jetzt wieder wie zuvor nebeneinander gezeigt werden (Option: "Elemente pro Reihe")

## 2.2.2
Bugfix:
- Testlabel entfernt (sorgte unter Umständen für eine fehlgeschlagene Installation)

## 2.2.1
Bugfix:
- Install/Update schlägt durch doppelte Bennenung des Feldes "Zitat" fehl
- Submenu-Indicator ist auch dann sichtbar, wenn Unterseiten alle "versteckt" sind

### BREAKING CHANGE:
Die Startseite ist durch ein neues Element "Seiteninhalt anzeigen" ersetzt. Künftig wird die Startseite unter
"Strukturen > Seiten" angelegt und über das neue Element referenziert.
**Dadurch geht beim Update der bestehende Inhalt der Startseite komplett verloren!**

## 2.2.0
Updates:
- Craft auf 2.6.3019 updaten

Features:
- Navigation komplett überarbeitet
    - Sauberer Aufbau
    - Bessere mobile Darstellung
    - Darstellung der Suche verändert (Fährt über gesamte Breite aus)
    - Language Switcher verbessert
- Autoren und Popover als Strukturen abspeichern (statt Kanäle)
- "Cloaking"-Element (Seite zeigt Inhalte von anderer Seite)
- Umbennung der "Flexiblen Seiten" zu "Seiten"
- Neuer Seitentyp "Umleitung"
    - leitet auf Inhalte oder externe Seiten um
    - wird im Menu korrekt dargestellt
- Zitat und Testimonials zu neuem Element "Zitate" verbinden
- Bildvollfläche, Videohintergrund und Header/Slider zu neuem Element "Bildelement" verbinden
- Neues Element: Listing
    - Ersetzt Verhalten von "neueste Blogbeiträge"
    - Auswahl von diversen Quellen (Blog, Referenzen, Seiten)
    - Auswahl von diversen Layouts (Liste, Grid, Links-Rechts)

Bugfixes:
- "Call To Action"-Element wird nicht länger über gesamte Bildschirmbreite angezeigt

Deprecated (Diese Elemente dürfen nicht länger verwendet werden, sie werden in einem künftigen Update entfernt):
- Zitate
- Testimonials
- Bildvollfläche
- Videohintergrund
- neueste Blogbeiträge
- Referenzindex

## 2.1.33
Bugfix:
- Padding für Footer angepasst, damit Inhalte immer sichtbar sind
- Portrait-Modus des Seitenlogos für mobile Ansicht optimiert
- Anpassungen an Skalierung der Unterzeile im Vollflächenbild für mobile Ansicht

Features:
- Download von bestimmten Dateien nicht länger erzwingen
- "Seitensuche deaktiviewren?" als Option in den globalen Seiteneinstellungen ergänzt
- "In Navigation anzeigen?" standardmäßig ausschalten

## 2.1.32

Bugfix:
- "Bild zentrieren?" wird jetzt korrekt dargestellt

Features:
- Responsive Nutzung der Bilder
- Neue Bildtransformationen
- Breakpoints festgelegt
- Flaggen für das Sprachmenü

## 1.1.31

Updates:
- Retour Plugin macht keinen Redirect nach der Installation mehr
- Craft auf 2.6.3012

## 1.1.30

Bugfixes:
- Margin / Padding in "Neueste Blogbeiträge" stimmen nicht
- Mobile Ansicht der "Neuesten Blogbeiträge" fehlerhaft

## 1.1.29

Bugfixes:
- Leere Kategorien bei "Neueste Blogbeiträge" führt zu leeren Ergebnislisten

## 1.1.28

Updates:
- Craft auf 2.6.3009

Bugfixes:
- Text für Schlagworte wird nicht ausgegeben
- Diverse Abstände angepasst

Features:
- Neues Element "Neueste Blogbeiträge"
- Geschwindigkeit der Links/Rechts-Slider steuerbar

Verbesserungen:
- Teaser in Blogauflistung automatisch auf Basis des Volltextes generieren

## 1.1.27

Bugfixes:
- Fehlerhafte Darstellung der Beitragsbilder in der Blogübersicht

Verbesserungen:
- Headerhöhe in mobiler Darstellung via Variable anpassbar machen

## 1.1.26

Updates:
- Craft auf 2.6.3008

Bugfixes:
- Javascript für Edge/Safari

Verbesserungen:
- UglifyJS in Webpack

## 1.1.25

Updates:
- Craft auf 2.6.3007

Bugfixes:
- Footer nicht immer am unteren Bildschirmrand
- Referenzen nicht sortierbar (wurde von Channel zu Struktur umgewandelt)
- Weißer Balken unterhalb des Menüs
- Videobackground wird nicht über gesamte Bildschirmfläche gefüllt
- Fehlerhafte Darstellungen im Footer in mobiler Ansicht
- Fehlerhaftes Verhalten des Popovers in mobiler Ansicht
- Fehlerhafte Darstellung der "+"-Buttons in der mobilen Navigation
- Fehlerhafte Darstellung der Parallax-Hintergrundbilder

Features:
- BASE_URL über xperdu CP überschreibbar
- Geschwindigkeit für Autoplay-funktion des Sliders regelbar (in Header und Testimonials)
- Neue Breakpoints für die Navigation ergänzen (`@breakpoint-navi-smaller` und `@breakpoint-navi-mobile`)
- Javascriptberechnung der Breakpoints aus dem CSS abfragen (benötigt beim Menü)

Verbesserungen:
- Darstellung der Header/Slider-Elemente in Verbindung mit einem Portrait optimiert

## 1.1.24

Updates:
- Craft auf 2.6.3004

Bugfixes:
- Mobiles Menü nicht scrollbar
- Bilder in Linksrechts nicht sichtbar
- Cache wird bei neuen Blogbeiträgen nicht invalidiert
- MimeType für Video dynamisch setzen

## 1.1.23

Updates:
- Craft auf 2.6.3003

Bugfixes:
- Port für die Datenbankverbindung ergänzt in der Konfiguration

Features:
- Anbindung an xperdu Deployment

## 1.1.22

Bugfixes:
- responsives Verhalten für 2-Spalter Element verbessert
- Icon für Störer Darstellung mit mehr Abstand
- Darstellung der Störer auf mobilen Endgeräten optimiert
- Schlagwörter Buttons haben mehr Abstand auch nach unten (wichtig bei vielen Tags)
- Verknüpfung von Schlagwortsuchen optimiert
- Überschriften erhalten mehr Abstand

Features:
- Kategorie wird für den Schlagwort-Buttons ausgegeben
- Kategorie-Buttons haben eigene CSS-Klasse
- Versionshash an CSS und JS Links, damit die Scripte aktualisiert geladen werden vom Browser
- Videohintergrund kann nun auch mit Titel, Untertitel umgehen

## 1.1.21

Bugfixes:
- Socialmediabar rechtsbündig

Update:
- Supertables auf 1.0.6

## 1.1.20

Bugfixes:
- Fehlende Feldbeschreibungen ergänzt
- Aktuelle Unterpunkte in Seitennavigation auch einfärben
- Überarbeitung der Headernavigation in der mobilen Ansicht (Bessere Sichtbarkeit)
- SEO: Hierarchie der Titel-Tags wird jetzt korrekt eingehalten
- Hovereffekt für Dienstleistungsblöcke ohne Link deaktiviert
- Maximalbreite der Testimonials/Zitate angepasst (Verhindert Überschneiden der Anführungszeichen)

Updates:
- Craft auf 2.6.3000 aktualisiert

Neue Plugins:
- Retour Plugin integriert (Redirects von alten URLs auf neue URLs)
- SimpleSitemap Plugin integriert (Generiert die sitemap.xml)

Neue Features:
- Generator-Metatag ergänzt
- HTML lang-Attribute ergänzt
- HTML-Ausgabe komprimiert
- Überschriften mit Ankerpunkten versehen
- Blogeinträge sind jetzt auch per Klick auf das jeweilige Bild erreichbar
- Blogtags: Jedem Blogeintrag können jetzt auch Tags hinzugewiesen werden
- Bilder in Links/Rechts können jetzt auch zentriert dargestellt werden
- SEO: Seitentitel ergänzt
- Seiteninhaberschaft in den Plugineinstellungen ergänzt

## 1.1.19
- Farben zwischen Zitat und Testimonial sind jetzt unterscheidbar
- Der Störer im "Randleiste"-Modus sitzt wieder richtig

## 1.1.18
- Konfiguration über Environment und .env.php optimiert für Installer
- Craft auf 2.6.2994 aktualisiert

## 1.1.17
- Konfiguration über Environment und .env.php

## 1.1.16
- Meta-Tags verbessern
  - Twitter, Facebook, usw
- Craftversion auf 2.6.2992 updaten

## 1.1.15
- Fix: Cookiconsent Banner für mobil
- Videobackground
  - reagiert jetzt auf mobile Geräte
  - standardmäßig gemutet
  - looping läuft sauber durch

## 1.1.14

Bugfixes:
- Breite für iframes ist nicht länger auf die Gesamtbreite des Layouts erzwungen (Videos in Blogeinträgen)
- Fehlendes ThemeColor-Feld ergänzen

Neue Features:
- "Read More" Button für Blogübersicht
- Cookiehinweis-Banner (cookieconsent)
- Verhalten "Randleiste" für Störer
- Copyright im Footer

Sonstiges:
- Caching für die meisten Inhalte wieder deaktivert, wegen Performanceproblemen

## 1.1.13
- Lokalisierungen für statische Texte
- Lokalisierung für alle Felder aktivieren
- "Hauptnavigation ausblenden" für flexible Seiten (Landing Pages)
- Grafiken sind nicht länger Pflichtfelder in Dienstleistungsblöcken
- Labels für die Social Media Bar
- Favicon über Admin festlegbar (Unter Globale Inhalte -> Favicon.png)
- Theme Color über Admin festlegbar (Unter Globale Inhalte -> Theme Color)
- Caching für Inhalte aktivieren

## 1.1.12
- update.php löscht sich selbst am Ende
- "Kunde" bekommt mehr Berechtigungen

## 1.1.11
- Update Craft auf 2.6.2990
- Lineheight für Menü konfigurierbar
- CSS-Config Kommentierung/Dokumentation auf Github

## 1.1.10

Bugfixes:
- Doppelte WYSIWYG-Felder bei 2-reihigem Layout haben komisches padding
- Hintergrundfarbe für Textfelder nicht weiß

Features:
- SEO-Keywords für Unterseiten
- Zwei neue Portrait-Positionen für den Header/Slider
- Aktive Seite im Menü farblich hervorheben

Sonstiges:
- Kleiner Rand für die Slider-Bullets ergänzen
- Pfeile für Referenz-Blöcke ergänzen
- Update für interne Rancherize-Struktur
- Mehr CSS-Einstellungen über die Config ermöglichen

## 1.1.9
- CSS-Stylesheet aufräumen (10kB eingespart!)
- Bilderskalierung für Slider und Bildvollfläche auf maximale Bildschirmbreite

## 1.1.8

Bugfixes:
- Bilder verschwinden manchmal
- Popover-Instanzen (Störer) werden nicht immer richtig geladen
- Bildgröße für WYSIWYG-Editor begrenzen
- Default CSS-Config wird nicht eingelesen

Features:
- Swiper autoplay und Paginierung
- Button "Zur Homepage" für Fehlerseiten
- Standardsortierung in der Navigation überarbeitet
- Neues Element: Referenz-Grid

Sonstiges:
- Stylesheets aufgeräumt

## 1.1.7
- Bugfix: Dynamische Lokalisierung gibt falschen Pfad zurück

## 1.1.6
- Redactor-Config um 2 Schriftgrößen (small, xs) erweitert
- Anpassungen an Vollflächentexte werden jetzt vernünftig gespeichert (Bildgrößen, Positionierung, usw.)
- devMode automatisch aktivieren, wenn in xperdu-Einstellungen gesetzt
- Refactoring
- "Call To Action"-Element
- Störer-Element
  - Störer auf jeder Seite frei wählbar
  - Verhalten festlegbar (Immer sichtbar, Nach X Sekunden sichtbar)
  - Positionierung frei wählbar (4 Bildschirmecken)
  - Größe/Höhe regulierbar
  - Diverse Inhalte über eine Matrix verwalten (Titel, Text, Formular, Call To Action)

## 1.1.5
- Lokalisierung dynamisch generieren (aus aktiven Craft-Einstellungen)
- xperdu wird bei einem Editionswechsel (Personal, Client, Pro ) automatisch neu installiert

## 1.1.4
- Fehlerseiten im xperdu-Styling

## 1.1.3
- Benennung für Blog angepasst (Blog Index -> Blog)

## 1.1.2
- Bugfix: Translateable für Flexible Element wieder aktivieren
- Localizierung über Ordnerstruktur

## 1.1.1
- Darstellung der Map-Einstellungen optimiert

## 1.1.0
- Map Pins
- Analytics (Facebook, Piwik)
