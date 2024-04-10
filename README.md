Backend Test (Shopware)
===========================

* **Zeiteinsatz**: Nicht limitiert. Abgabedatum
* **Umzusetzen in**: HTML (Twig), (S)CSS, php, ES6, TypeScript und MySQL / MariaDB.

Es soll ein Shopware 6 Plugin zur Verwaltung von Aufpreisen erstellt werden.
Dazu müssen die typischen, von Shopware 6 implementierten Technologien verwendet werden.

Der Test unterteilt sich in einzelne, aufeinander aufbauende Teilaufgaben.
Je mehr Aufgaben erfüllt werden, desto besser.

**Aufgabe 1**
1. Das Plugin muss die Möglichkeit bieten, für bestimmte Produkte automatisch einen Aufpreis in den Warenkorb hinzuzufügen. 
2. Es müssen folgende Informationen konfigurierbar sein.
    * Welche Produkte lösen das Verhalten aus bzw. sind dafür freigegeben.
    * Um welche Art von Aufpreis handelt es sich (absolut, prozentual).
    * Wie hoch ist der Aufpreis.
3. Der Aufpreis muss als eigene Position im Warenkorb dargestellt werden.
    * Es soll ersichtlich sein, dass es sich um einen Aufpreis handelt.
    * Es soll ersichtlich sein, welches Produkt den Aufpreis ausgelöst hat.
    * Es soll ein Aufpreis je Anzahl Produkt hinzugefügt werden.

**Aufgabe 2**
1. Auf Detailseiten von betroffenen Produkten muss ein Hinweis auf den Aufpreis dargestellt werden.
    * Der Hinweis muss den Wert und die Art des Aufpreises beinhalten.

**Aufgabe 3**
1. Im Hinweis aus Aufgabe 2 muss ein Link hinzugefügt werden.
    * Der Link muss auf eine vom Plugin implementierte Seite führen.
    * Auf der Seite müssen folgende Inhalte dargestellt werden.
        * Ein beschreibender Text für eine Erklärung der Aufpreise. Dieser Text muss im Plugin konfigurierbar sein.
        * Eine Liste der Produkte, die einen Aufpreis auslösen. Die Produkte sollen auf die entsprechende Detailseite verlinken.
    * Diese Seite stellt eine Übersicht für Kunden dar.

**Aufgabe 4**
1. Das Plugin soll um eine Version erhöht werden.
2. Mit der neuen Version muss eine neue Funktionalität implementiert werden.
   * Es muss eine eigene Datenbank-Tabelle angelegt werden.
   * In dieser Tabelle muss eine Referenz auf eine abgeschlossene Bestellung und die Summe aller Aufpreise dieser hinterlegt sein.
3. Die Seite aus Aufgabe 3 muss um folgende Informationen erweitert werden.
   * Anzahl Aufpreise des Kunden
   * Anzahl Aufpreise aller Kunden
   * Summe aller Aufpreise des Kunden
   * Summe aller Aufpreise aller Kunden

**Sonstige Anmerkungen**
* Das Plugin muss den Prefix "Webnetz" tragen.
* Das Plugin muss in custom/static-plugins abgelegt werden und via "composer require" installierbar sein.
* Symfony autoconfigure und autowire sind auszuschalten.
* Die optische Darstellung (Frontend) ist nicht kritischer Bestandteil der Aufgabe.
Sie kann aber als Bonus in der Auswertung berücksichtigt werden.

Einreichung
-----------
Zur Abgabe muss das Plugin und eine `README.md` mit deinem Namen, dem Abgabedatum, und ein paar Gedanken zu deiner Arbeit als ZIP-Archiv zur Verfügung gestellt werden.

Wir empfehlen vorab zu prüfen, ob das Plugin so wie abgegeben lauffähig ist.

Über Feedback zu dem Test freuen wir uns natürlich auch.

Terminologie
------------
Die in diesem Dokument verwendeten Begriffe “MUSS”, “DARF NICHT”, “ERFORDERLICH”, “KANN”, “MUSS NICHT”, “SOLL”, “SOLL NICHT”, “EMPFOHLEN”, “NICHT EMPFOHLEN”, “KÖNNTE”, “OBLIGATORISCH” und “OPTIONAL” müssen gemäß [BCP 14](https://tools.ietf.org/html/bcp14), [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119) interpretiert werden.

Autor / Lizenz
--------------
Copyright © 2023, [web-netz GmbH](https://www.web-netz.de/)

Proprietäre Lizenz
