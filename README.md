# easy-pagination
Test-Webcomponente für mein Forschungsprojekt

Kompentente erstellt eine Seitennavigation. Ziel ist es, jsdoc-Kommentare im Script-Teil der Polymerkomponenten auszuwerten. 

## Verwendung

#### Einbindung

` <easy-pagination page="1" max-page="7"></easy-pagination> `

#### Attribute

* `page` **Number** Aktuelle Seite
* `max-page` **Number** Maximale Anzahl Seiten

#### Methoden

* `nextPage()` Eine Seite weiter
* `lastPage()` Eine Seite zurück

Verwendung (Beispiel):

 `<a href="" onclick="document.querySelector('easy-pagination').lastPage(); return false;">Letzte Seite</a>`


