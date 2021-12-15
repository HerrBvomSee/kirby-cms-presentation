---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1457305237443-44c3d5a30b89
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# KirbyCMS
## Die kleine, aber feine Alternative zu Wordpress 
#### (und anderen)

---
layout: two-cols
---

# Wer bin ich?

- geboren in den frühen 70ern
- Kind des Ruhrgebiets, dass in den Stollen der Bergwerke groß geworden ist ... naja, nicht wirklich
- seit der Jugend mit Computern und Programmieren beschäftigt
- 2001 an den wunderschönen Bodensee umgezogen
- Tagsüber festangestellter Software-Entwickler
- Abends Vater und Ehemann
- ... und im Rest der Zeit Selbständig im Bereich Applikations- und Webentwicklung

::right::
<img src="/logo.png" class="m-auto max-h-3/4 content-center" />


---

# Begriffe

Was ist ein Content-Management-System (CMS)?

Ein CMS ist eine Software zur gemeinschaftlichen Erstellung, Bearbeitung, Organisation und Darstellung digitaler Inhalte (Content) zumeist zur Verwendung in Webseiten, aber auch in anderen Medienformen. 
(Quelle: Wikipedia)

<img src="/cms_schema.jpeg" class="m-auto max-h-1/2 content-center" />


---

# Welche Arten von CMS gibt es?

## Enterprise CMS
- bezeichnet einen übergeordneten Software-Typ
- zeichnen sich durch ihren Feature-Reichtum und die Integrationsmöglichkeit in anspruchsvolle Systemlandschaften aus
- Beispiele: Adobe Experience Manager (AEM), Drupal, Magnolia, uvm

## Headless CMS
-  bieten eine Verwaltung von Inhalten, jedoch keine Generierung von Webseiten
-  Inhalte werden über eine API bereitgestellt
-  Beliebige Dritt-Systeme oder Anwendungen können die Inhalte abzurufen und daraus Webseiten erstellen.
-  Beispiele: Strapi, Directus, Contentful, Cockpit, uvm

<!-- 
Enterprise: 
- wird in der Praxis jedoch von vielen Anbietern verwendet, um sich gegenüber weniger komplexen CMS wie beispielsweise WordPress abzugrenzen. 
- wie sie üblicherweise in großen Unternehmen und Konzernen vorzufinden sind.

 Headless
 - gehören derzeit zu den großen Trends im CMS-Markt, eigenen sich aber längst nicht in jedem Anwendungsfall.
-->

---

# Welche Arten von CMS gibt es?

## Static Site Generatoren
- sind technisches Hilfsmittel zur Generierung statischer HTML-Auftritte.
- in der Technik-Szene haben Static Site Generatoren die klassischen Content Management Systeme fast vollständig abgelöst
- Einsatz für Dokumentationen, als auch für kleine Webseiten oder Blogs
- Beispiele: Hugo, Nuxt/Next, Gatsby, Sphinx, uvm.

## Web-Baukästen
- in erster Linie für einfache Webseiten im privaten Umfeld geeignet
- in manchen Fällen auch für Freelancer oder Klein-Unternehmen
- niederschwellige technische Hürde, kann von Laien benutzt werden
- Arbeitsaufwand für die Erstellung der Webseite in Eigen-Regie wird oft unterschätzt
- Beispiele: WiX, Jimdo, Squarespace, Domainfactory, uvm.

<!-- 
Site generator: 
- sind zu "technisch", nicht für den einfachen Anwender nutzbar
- know-how benötigt

Baukasten:
- Erweiterungen und Sonderwünsche schwer möglich
- Seiten sehen sich ähnlich

-->

---

# Welche Systeme/Typen gibt es

## "Klassische" CMS
- System bietet alle Voraussetzungen nach der Definition CMS
- In verschiedenen Ausprägungen für unterschiedliche Anwendungsfälle
- Beispiele: Wordpress, Typo3, Contao, Redaxo, Joomla, uvm.

## Flat-File-CMS
- Arbeiten wie ein klassisches CMS, jedoch ohne eine Datenbank
- Um Inhalte abzuspeichern werden einfache Text-Dateien auf dem Server abgelegt 
- Durch Verzicht auf Datenbank geringere Anforderungen an Server
- Einsatzfelder reichen von kleinen Blogs bis hin zu komplexen mittelständischen Unternehmensseiten
- Beispiel: Grav, Statamic, Bludit, KirbyCMS, uvm.

---

# Marktverteilung

<img src="/anteile_cms.png" class="mx-auto max-h-11/12 content-center" />
[Quelle]: https://www.domaintechnik.at/cms-vergleich.html

---

# Kirby CMS

Was macht es besonders

---

# Aufbau

Wie ist eine Seite aufgebaut

<div class="flex justify-items-auto ">
<img src="/ansicht_ordner.png" class="max-h-80  content-center" />
<img src="/ansicht_content.png" class="max-h-80  content-center" />
<img src="/ansicht_site.png" class="max-h-80  content-center" />
</div>


---
layout: two-cols
---

# Vorteile
- schlankes System
- schnelle Ladezeiten der Seite
- einfache Bedienung im Backend
- geringe Hardware-Anforderungen
- Upload/Migration schnell möglich
- Anpassungen an Kundenwünsche extrem einfach 
- Reichhaltige Plug-In Liste (inkl. Shopsystem)
- 

::right::
# Nachteile
- Programmierkenntnisse für Erstellung von Vorteil
- schneller Theme-Wechsel nicht möglich
- Kosten => 99€ / Server


<!-- 
Plugins definitv nicht so zahlreich wie für Wordpress

Das Theme ist stark mit dem Inhalt/System verknüpft
Wordpress Installation mit Plugins kann schnell teurer werden (Kosten je Plugin)
-->
---

# Live-Demo

---

# und was sonst noch damit gemacht wird

https://outdoor-cinema.net/de

https://richtiggut.bauhaus.info/

https://fishermansfriend.com/de-de