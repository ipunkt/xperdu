# xperdu
Changelog for xperdu - a website builder.

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
