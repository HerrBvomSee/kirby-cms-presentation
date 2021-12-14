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
- seit der Jugend mit Computern (C64) und Programmieren beschäftigt
- 2001 an den wunderschönen Bodensee umgezogen
- Tagsüber festangestellter Software-Entwickler
- Abends Vater und Ehemann
- und im Rest der Zeit Selbständig im Bereich Applikations- und Webentwicklung

::right::
<img src="/logo.png" class="m-auto max-h-3/4 content-center" />


---

# Begriffe

Was ist ein Content-Management-System (CMS)?

Ein CMS ist eine Software zur gemeinschaftlichen Erstellung, Bearbeitung, Organisation und Darstellung digitaler Inhalte (Content) zumeist zur Verwendung in Webseiten, aber auch in anderen Medienformen. 
(Quelle: Wikipedia)

<img src="/cms_schema.jpeg" class="m-auto max-h-3/4 content-center" />


---

# Welche Systeme/Typen gibt es

Enterprise CMS: Der Begriff Enterprise CMS bezeichnet eigentlich einen übergeordneten Software-Typ, wird in der Praxis jedoch von vielen Anbietern verwendet, um sich gegenüber weniger komplexen CMS wie beispielsweise WordPress abzugrenzen. Enterprise CMS zeichnen sich durch ihren Feature-Reichtum und die Integrationsmöglichkeit in anspruchsvolle Systemlandschaften aus, wie sie üblicherweise in großen Unternehmen und Konzernen vorzufinden sind.
Beispiele: Adobe Experience Manager (AEM), Drupal, Magnolia, uvm

Headless CMS sind Content Management Systeme, die eine Verwaltung von Inhalten anbieten, jedoch keine Generierung von Webseiten innerhalb des CMS ermöglichen. Stattdessen werden die Inhalte über eine Programmierschnittstelle (API) ausgeliefert. Die Schnittstellen können von Entwicklern genutzt werden, um Inhalte abzurufen und daraus andere Content-Anwendungen (wie zum Beispiel eine Webseite) zu erstellen. Headless CMS gehören derzeit zu den großen Trends im CMS-Markt, eigenen sich aber längst nicht in jedem Anwendungsfall.
Beispiele: Strapi, Directus, Contentful, Cockpit, uvm

---

# Welche Systeme/Typen gibt es

Web-Baukästen sind nur für einfache Webseiten im privaten Umfeld geeignet, in manchen Fällen auch für Freelancer oder Klein-Unternehmen. Über die Baukästen lassen sich ohne technische Kenntnisse Webseiten mit beschränkten Funktionalitäten erstellen. Allerdings wird der Arbeitsaufwand für die Erstellung der Webseite in Eigen-Regie oft unterschätzt. 
Beispiele: WiX, Jimdo, Squarespace, Domainfactory, uvm.

Static Site Generatoren sind keine Content Management Systeme, sondern technische Hilfsmittel zur Generierung statischer HTML-Auftritte. Bekannte Beispiele sind Jekyll oder Hugo. Für normale Anwender sind Static Site Generatoren keine Option, da die technischen Hürden zu groß sind. In der Technik-Szene haben Static Site Generatoren die klassischen Content Management Systeme jedoch fast vollständig abgelöst. Sie werden sowohl für Dokumentationen, als auch für kleine Webseiten oder Blogs eingesetzt.
Beispiele: Hugo, Nuxt/Next, Gatsby, Sphinx, uvm.

---

# Welche Systeme/Typen gibt es

Proprietär oder Open Source: Die Unterscheidung zwischen proprietär und Open Source ist zwar sehr gängig, macht als Auswahl-Kriterium jedoch nur selten Sinn, auch wenn darüber oft emotionale Diskussionen geführt werden. Open Source bedeutet, dass die Software über Lizenzen wie MIT oder GPL frei verbreitet werden kann. Proprietäre System werden dagegen über eine kostenpflichtige Lizenz vertrieben und dürfen nicht frei weitergegeben werden. Über die Qualität der Systeme sagt Open Source und proprietär nichts aus, und natürlich entstehen auch beim Einsatz von Open Source CMS Kosten.
Beispiele: Wordpress, Typo3, Contao, Redaxo, Joomla, uvm.

Flat-File-CMS sind spezielle CMS ohne eine Datenbank. Statt einer Datenbank nutzen die Systeme einfache Text-Dateien, um die Inhalte auf dem Server abzuspeichern. In der Regel gehören Flat-File-Systeme eher zu den leichtgewichtigen CMS, die für Blogs oder kleine Webseiten geeignet sind. Es gibt aber auch hier komplexere Systeme, die sehr gut für den kleineren Mittelstand eingesetzt werden können. 
Beispiel: Grav, Statamic, Bludit, KirbyCMS, uvm.

---

# Marktverteilung

<img src="/anteile_cms.png" class="m-auto max-h-3/4 content-center" />
Quelle: https://www.domaintechnik.at/cms-vergleich.html

---

# Kirby CMS

Was macht es besonders

---

# Aufbau

Wie ist eine Seite aufgebaut

---

# Vorteile/Nachteile

Liste mit Vor- und Nachteilen

---

# Live-Demo

---

# und was sonst noch damit gemacht wird

https://outdoor-cinema.net/de

https://richtiggut.bauhaus.info/

https://fishermansfriend.com/de-de