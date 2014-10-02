
TUD-KOMA-Script
===============

TUD-KOMA-Script 2014/10/xx v2.02
Copyright (c) Falk Hanisch <tudscr[at]gmail.com>, 2012-2014

This material is subject to the LaTeX Project Public License.
See http://www.latex-project.org/lppl.txt for the details of that license.

English text below

-------------------------------------------------------------------------------

Zusammenfassung
---------------

Das TUD-KOMA-Script-Bundle stellt sowohl Klassen als auch Pakete bereit, um 
LaTeX-Dokumente im Corporate Design der Technischen Universität Dresden zu 
erstellen. Es basiert auf dem KOMA-Script-Bundle, welches zwingend vorhanden 
sein muss. Außerdem sind die PostScript-Schriftfamilien Univers und DIN-Bold 
erforderlich. Mitarbeiter und Studenten der Technischen Universität Dresden 
können diese unter https://tu-dresden.de/service/publizieren/cd/4_latex vom 
Universitätsmarketing  mit dem Hinweis auf die Verwendung von LaTeX anfordern.

Für die Installation der PostScript-Schriften sei auf den entsprechenden 
Release unter https://github.com/tud-cd/tudscr/releases/tag/fonts und das 
LaTeX-Forum der Technischen Universität Dresden verwiesen: 
http://latex.wcms-file3.tu-dresden.de/phpBB3/index.php


Klassen und Pakete
------------------

Das Bundle beinhaltet:

+ die drei Dokumentklassen `tudscrartcl`, `tudscrreprt`, `tudscrbook` als
  Wrapper-Klassen von `scrartcl`, `scrreprt` and `scrbook`,
+ das Paket `tudscrsupervisor`, welches Umgebungen und Befehle für die
  Erstellung von Aufgabenstellungen, Gutachten und Aushängen bereitstellt,
+ das Paket `tudscrfonts`, das die Schriften des Corporate Designs der
  Technischen Universität Dresden für die LaTeX-Standard-Klassen und die 
  KOMA-Script-Klassen nutzbar macht,
+ das Paket `mathswap` für das Austauschen mathematischer Trennzeichen 
  innerhalb von Zahlen (ähnlich zu `ionumbers`),
+ das Paket `twocolfix` zur Fehlerbefehbung der Position von Überschriften im
  zweispaltigen Layout und
+ eine umfassende Anwenderdokumentation sowie mehrere Tutorials.

Versionen
---------

**v2.02** (2014/10/xx)
+ Paket `tudscrfonts`
+ Probleme mit der Klasse `standalone` behoben
+ Laden der Schriften des Corporate Designs im OpenType-Format mit `fontspec`
  ermöglicht
+ verbesserte Installationsroutine der PostScript-Schriften
+ Seiten im Stil des Corporate Designs werden mithilfe des Paketes
  `scrlayer-scrpage` erzeugt
+ verschiedene Optionen und Befehle zur individuellen Gestaltung dieser Seiten
+ Unterstützung der KOMA-Script-Schriftelemente für Titel und Umschlagseite
+ Befehle und Umgebungen für Zusammenfassung, Selbstständigkeitserklärung und
  Sperrvermerk wurden verbessert
+ Fussnoten in Überschriften können per Option mit Symbolen gesetzt werden
+ einige Befehle wurden für Kompatibilität zu anderen Paketen umbenannt
+ Funktionalität des Paketes `mathswap` im Dokument umschaltbar

**v2.01b** (2014/06/04)
+ Bug bei Aufgabenstellung behoben (tudscrsupervisor)

**v2.01a** (2014/06/03)
+ Bug bei der Verwendung des Untertitels behoben

**v2.01** (2014/04/24)
+ Fehlerkorrekturen beim Kerning der Ziffern und bei der Schriftstärke auf der 
  Titelseite

**v2.00** (2014/04/22)
+ Das TUD-KOMA-Script-Bundle wurde von Grund auf überarbeitet und mittels 
  `docstrip` erzeugt. Viele Fehler wurden entfernt und die Robustheit der 
  Befehle und Optionen wurde erhöht. Die Verwendung der Schriften, insbesondere 
  für den mathematischen Satz, wurde entscheidend verbessert. Weiterhin erfuhr 
  das Handbuch des Bundles eine komplette Überarbeitung, wurde erweitert und um 
  mehrere Indexe ergänzt.

**v1.0** (2012/10/31)
+ erste Version des TUD-KOMA-Script-Bundles

-------------------------------------------------------------------------------

Summary
-------

The TUD-KOMA-Script bundle provides both classes and packages in order to 
create LaTeX documents in the corporate design of the Technische Universität 
Dresden. It bases on the KOMA-Script bundle, which must necessarily be present.
In addition, the PostScript font families Univers and DIN-Bold are required. 
Employees and students of the Technische Universität Dresden can request these
fonts via  https://tu-dresden.de/service/publizieren/cd/4_latex from the 
university marketing university marketing with regard to the use of LaTeX.

To install the PostScript fonts, please refer to the corresponding release 
under https://github.com/tud-cd/tudscr/releases/tag/fonts and the LaTeX forum 
of the Technische Universität Dresden: 
http://latex.wcms-file3.tu-dresden.de/phpBB3/index.php

Classes and Packages
--------------------

The bundle offers:

+ the three document classes `tudscrartcl`, `tudscrreprt`, `tudscrbook` as
  wrapper classes for `scrartcl`, `scrreprt` and `scrbook`,
+ the package `tudscrsupervisor` providing environments and macros to create
  tasks, evaluations and notices for scientific theses,
+ the package `tudscrfonts`, which makes the corporate design fonts of the
  Technische Universität Dresden available for LaTeX standard classes and 
  KOMA-Script classes,
+ the package `mathswap` for swapping math delimiters within numbers (similiar
  to `ionumbers`),
+ the package `twocolfix` for fixing the positioning bug of headings in
  twocolumn layout and
+ an comprehensive user documentation as well as several tutorials.

Versions
--------

**v2.02** (2014/10/xx)
+ package `tudscrfonts`
+ fixed bug with class `standalone`
+ loading the corporate design fonts in OpenType format with `fontspec` is
  possible
+ improved installation routine of PostScript fonts
+ pages in the style of the corporate design are generated using the package 
  `scrlayer-scrpage`
+ various options and commands to customize these pages
+ support of the KOMA-Script font elements for title and cover
+ commands and environments for abstract, statement of authorship and
  restriction note have been improved
+ footnotes in headings can be set as symbols per option `footnotes`
+ some commands have been renamed for compatibility with other packages
+ functionality of the package `mathswap` can be switched within the document

**v2.01b** (2014/06/04)
+ Fixed bug when using task (tudscrsupervisor)

**v2.01a** (2014/06/03)
+ Fixed bug when using the subtitle.

**v2.01** (2014/04/24)
+ Fixes the kerning of the digits and the font weight at the title page.

**v2.00** (2014/04/22)
+ The TUD-KOMA-Script bundle has been redesigned from the ground up and is 
  generated by using `docstrip`. Many bugs have been removed and the robustness 
  of the commands and options has been increased. The use of the fonts, 
  especially for the mathematical set, was significantly improved. The manual 
  of the bundle underwent a complete overhaul, has been extended and 
  supplemented by several indexes.

**v1.0** (2012/10/31)
+ first version of the TUD-KOMA-Script bundle
