# Formular-Templates für OpenProject

---

## Projektübersicht

Dieses GitHub-Projekt stellt eine Sammlung **anpassbarer HTML-Formularvorlagen** bereit. Sie wurden speziell dafür entwickelt, die Informationserfassung für verschiedene **Projektmanagement-Typen in OpenProject** zu optimieren. Da OpenProject aus Sicherheitsgründen die direkte Einbettung von HTML-Dateien mit JavaScript nicht unterstützt, dienen diese Vorlagen als Basis für eine **externe Datenerfassungslösung**. Die gesammelten Daten können anschließend über die OpenProject REST API in entsprechende **benutzerdefinierte Felder** von OpenProject übertragen werden.

Die Vorlagen sind darauf ausgelegt, die wichtigsten Informationen für folgende Projekttypen zu erfassen:

* **Prozessmanagement-Projekte**
* **Projektmanagement-Projekte**
* **Programmmanagement-Projekte**

Jedes Formular ist **einfach zu ändern** und kann bei Bedarf als **PDF** abgelegt werden, um eine statische Archivierung oder Verteilung zu ermöglichen.

---

## Warum dieses Projekt?

OpenProject ist ein mächtiges Tool für das Projektmanagement. Standardmäßig bietet es umfangreiche Anpassungsmöglichkeiten über **benutzerdefinierte Felder** und die **Formularkonfiguration**. Manchmal sind jedoch **komplexere Formularlogiken**, dynamische Inhalte oder spezifische Frontend-Designs erforderlich, die über die nativen Funktionen hinausgehen.

Dieses Projekt bietet eine Lösung für genau solche Szenarien, indem es:

* Eine **flexible HTML/CSS/JS-Basis** für anspruchsvolle Formularanforderungen bereitstellt.
* Den Weg für die **Integration mit der OpenProject API** ebnet, um externe Daten nahtlos in OpenProject zu überführen.
* Das Konzept der **dedizierten Formulare pro Projekttyp** fördert, um die Datenerfassung zu straffen.

---

## Features

* **Vorkonfigurierte HTML-Vorlagen** für Prozess-, Projekt- und Programmmanagement.
* **Klare Strukturierung** der Formularfelder für wichtige Informationen.
* **Einfache Anpassbarkeit** des HTML- und CSS-Codes für individuelle Anforderungen.
* **Inkludierte JavaScript-Strukturen** für potenzielle Validierungen oder dynamische Felder (müssen bei API-Anbindung angepasst werden).
* **Dokumentierte Vorgehensweise** für die Integration mit OpenProject (Konzept).

---

## Verwendung

### 1. Klonen des Repositorys

```bash
git clone https://github.com/FJReichert/TestWebsite.git
cd TestWebsite
