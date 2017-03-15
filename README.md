# Ausbildung-Anwendungsentwicklung
Bereiche die man als IT-Fachinformatiker Anwendungsentwicklung beherrschen muss, um eine Full-Stack - iOS App schreiben zu können.

In diesem Dokument geht es darum, was man während der Ausbildung zum IT-Fachinformatiker alles wissen sollte, um eine App in iOS mit einem PHP-Backend umsetzen zu können.

# Warum iOS und PHP? 
In meinem aktuellen Beruf arbeite ich als Team Lead iOS bei CHECK24 und meine täglichen Werkzeuge umfassen genau diesen Stack. Früher oder später kann man diesen Leitfaden gerne noch weiter auf Android, JavaScript, HTML5, CSS3, MySQL, etc. ausbauen um noch einen tieferen Einblick gewähren zu können.

# Module
Dieser Leitfaden ist in verschiedene Module aufgeteilt, die durch die 3 Jahre einer Ausbildung leiten sollen, damit man alles umfassend erklärt bekommt. Es wird bei den Grundlagen angefangen, geht über erweiterte Programmierparadigmen und hört bei High Level Themen auf.

# Beantwortung von den Fragen
Eine Frage wird direkt unter der Fragestellung beantwortet. Wenn es sich dabei um eine Frage handelt die direkt mit der Programmierung zusammenhängt sollte auch ein Code Schnipsel mit angehangen werden für Swift und PHP.

## Beispiel
### Wie deklariere ich eine Variable?
**swift**
```swift
var foo = "bar"
```
**PHP**
```php
$foo = 'bar';
```
# Grundlagen

## Programmausgaben
### Wie kann ein Programm dem Nutzer Feedback auf der Konsole geben?

## Variablen
### Deklarieren von Variablen
#### Wie deklariere ich eine Variable?

#### Wie deklariere ich eine Konstante?

#### Was ist der Unterschied zwischen einer Konstanten und einer Variablen?

### Variablen ausgeben
#### Wie gebe ich eine Variable aus?

#### Wie swappe die Werte zweier Variablen?

### Integers
#### Was ist ein Integer?

#### Was ist der unterschied zwischen einem Signed und Unsigned Integer?

#### Wie findet man die minimalen und maximalen Werte aus einem Integer raus?

### Floats
#### Was ist ein Float?

### Typensicherheit
#### Was bedeutet Typensicherheit?

#### Wie kann man die Typensicherheit in Swift umgehen?

#### Wie kann man die Typensicherheit in PHP forcieren?

### Literals
#### Was sind Literals?

#### Nenne mindestens drei verschiedene Typen von Literals.

### Typen Umwandlung
#### Warum muss man typen umwandeln?

#### Zeige anhand von einem Beispiel wie man zwei verschiedene Typen zu einem zusammen fasst.

### Type Aliases
#### Was ist ein Type Alias?

#### Wann wird im normalfall ein Type Alias benutzt?

### Booleans
#### Was sind Booleans?

### Tuples
#### Was sind Tuples?

#### In welchem Anwendungsfall sollte man ein Tuple benutzen? Warum?

#### In welchem Anwendusgsfall sollte man keinen Tuple benutzen? Warum?

### Optionals
#### Was ist ein Optional?

#### Was ist der Vorteil von Optionals?

#### Was ist optional chaining?

## Operatoren

### Unary
#### Was ist ein Unary Operator? Nenne mindestens ein Beispiel.

### Binary
#### Was ist ein Binary Operator? Nenne mindestens drei Beispiele.

### Ternary
#### Was ist ein Ternary Operator? Nenne ein Beispiel.

#### Ternary Conditional Operator

### Assignment
#### Was ist ein Assignment Operator?

#### Kann man ein Assignment Operator in einer Kontrollstruktur verwenden?

### Arithmetic
#### Was ist ein Arithmetic Operator?

#### Zeige ein Beispiel mit einem Addition Operator

#### Zeige ein Beispiel mit einem Substraction Operator

#### Zeige ein Beispiel mit einem Multiplication Operator

#### Zeige ein Beispiel mit einem Division Operator

#### Remainder 
##### Was ist ein Remainder Operator?

##### Wie wird der Remainder Operator sonst noch genannt?

### Compound Assignment Operators
#### Was ist ein Compound Assignment Operator?

#### Zeige ein Beispiel mit einem Compound Assignment Operator

### Comparison
#### Nenne alle Comparision Operators

#### Was ist der unterschied zwischen `==` und `===`?

### Nil-Coalescing (Swift only?)
#### Was ist der Nil-Coalescing Operator?
#### Zeige ein Beispiel mit einem Nil-Coalescing Operator

### Range (Swift only?)
#### Was ist ein Range Operator

#### Zeige ein Beispiel für eine Closed Range

#### Zeige ein Beispiel für eine Half-Open range

### Logic Operators
#### Für welche Typen benutzt man Logic Operators?
#### Zeige ein Beispiel für ein NOT Operator
#### Zeige ein Beispiel für ein AND Operator
#### Zeige ein Beispiel für ein OR Operator
#### Zeige ein Beispiel die alle oben genannten Operatoren miteinander verbindet.
#### Wie kann man Operatoren zusammenfassen?

## Kommentare
### Was ist ein Kommentar?
### Wie werden Kommentare ausgezeichnet?
### Wie Dokumentiert man Funktionen / Methoden richtig?
### Werden Kommentare mit in das Programm kompiliert / interpretiert?

## Kontrollstrukturen
### Conditional Statements
#### If
##### Zeige ein Beispiel für eine einfache If Bedingung
##### Zeige ein Beispiel für eine If-Else Bedingung
##### Zeige ein Beispiel für eine If-ElseIf-Else Bedingung
#### Switch
##### Was ist der Vorteil von einem Switch gegenüber einem If?
##### Wann sollte man einem Switch vorziehen?
##### Was bedeutet break?
##### Was sind Compound Cases?
##### Welche unterschiede im Switch gibt es in PHP und Swift?
### Schleifen
#### Kopfgesteuerte Schleifen
#### Fußgesteuerte Schleifen
### Assertions
### Transfer Statements
#### continue
##### Zeige ein Beispiel für ein continue statement in einer beliebigen Schleife
##### Wann setzt man ein continue ein?
#### break
##### Zeige ein Beispiel für ein break statement in einer beliebigen Schleife
##### Wann setzt man ein break in einer Schleife ein?
##### Zeige ein Beispiel für ein break statement in einem Switch
##### Wann setzt man ein break in einem Switch ein?
#### fallthrough
##### Zeige ein Beispiel für ein fallthrough statement in einem Switch
##### Wann setzt man ein fallthrough in einem Switch ein?
#### return
##### Wann wird return benutzt?
##### Was hat in Swift guard damit zu tun?
##### Zeige ein Beispiel für ein return statement
##### Zeige ein Beispiel für ein guard statement
##### Was ist early return?
##### Warum sollte man early returns benutzen?
#### throw
##### Wann benutzt man einen throw?
##### Was für ein Vorteil hat ein throw?
##### Was ist der unterschied von throw in Swift und PHP?

## Funktionen
### Was sind Funktionen?
### Wie deklariert man eine Funktion?
### Wie ruft man eine Funktion auf?
### Was sind Funktionsparameter?
### Was sind Rückgabewerte?
### Ist es möglich eine Funktion in einer Funktion zu deklarieren?
### Gibt es Funktionen ohne Rückgabewerte?
### Wie setzt man bei FUnktionsparameter Standardwerte?
### Was sind Variadic Parameters?
### Wie reicht man eine Referenz in eine Funktion?
### Kann man Funktionen als Parameter übergeben?
### Kann man Funktionen als Rückgabewert definieren?

## Closures / Lambdas
### Was sind Closures / Lambdas?
### Wie wird ein Closure definiert?
### Was sind häufige Anwendungsfälle für Closures / Lambdas?
### Was ist der unterschied zwischen escaping und noesacping?

## Klassen und Strukturen
### Klassen
#### Was ist eine Klasse?
#### Wie wird eine Klasse erzeugt?
#### Was macht eine Klasse aus?
#### Was für einen Typen hat eine Klasse in Swift?
#### Was für einen Typen hat eine Klasse in PHP?
#### Wie vererbt man eine Klasse?
#### Wie überschreibt man eine Property?
#### Wie überschreibt man eine Methode?
#### Wie ruft man die Methode, die man überschrieben hat, der Eltern Klasse auf?
### Sturkturen (swift only)
#### Was ist eine Struktur?
#### Wie wird eine Struktur erzeugt?
#### Was macht eine Struktur aus?
#### Was für einen Typen hat eine Struktur?
### Allgemeine Fragen
#### Was ist der Unterschied zwischen einer Klasse und einer Struktur?
#### Was haben Strukturen und Klassen gemeinsam?
#### Was ist eine Property?
#### Was ist eine Methode?
#### Wann entscheidet man sich für eine Klasse und wann für eine Struktur?
#### Was ist eine Computed Property?

## Methoden 
### Was ist eine Methode?
### Was ist der Unterschied von Instanz und Typen Methoden?
### Zeige ein Beispiel einer Instanz Methode
### Zeige ein Beispiel für eine Typen Methode
### Was bedeutet self / $this?
### Was bedeutet mutating? (swift only)
### Was ist der unterschied zwischen static und class Methoden?

## Enumerations (swift only)
### Was ist eine Enumeration?
### Wann benutzt man eine Enumeration?
### Zeige ein Beispiel für eine Enumeration
### Zeige ein Beispiel mit einer Enumeration und einem Switch Statement
### Was sind Associated Values?
### Was ist ein Raw Value?
### Was sind implizit gesetzte Raw Values?
### Wie kann man ein Enum mit einem Rae Value erzeugen?
### Wie zeichnet man eine Rekursive Enumeration aus?
### Was hat das für Vorteile?

## Collection Types
### Was ist ein Array?
### Was ist ein Set?
### Was ist ein Dictonary?
### Gibt es die oben genannten Collectiontypes auch in PHP?
### Was für Vor- und Nachteile hat ein Array?
### Was für Vor- und Nachteile hat ein Set?
### Was für Vor- und Nachteile hat ein Dictonary?
### Was sind Mehrdimensionale Collection Types?
### Wann benutzt man diese?
### Zeige ein Beispiel wie man dies benutzt und wofür man es benötigt.
### Was sind Subscripts?
### Kann man Subcripts selbst erstellen? Wenn ja, wie?

## Interfaces
### Was ist ein Interface?
### Können Interfaces voneinander erben?
### Was sind die Vorteile von einem Interface zu einer Klasse mit Vererbung?
### Welches Design Pattern wird oft mit Interfaces in der Cocoa (Touch) Welt benutzt?
### Ist es möglich ein Interface nur auf Klassen zu beschränken? Wenn ja welche vorteile hat dies?
### 

## Error Handling

## Generics

## Intepretiert vs. Kompiliert

# Algorithmen

# UIKit (iOS only)

# Design Patterns

## Architektur Patterns
### MVC - Model View Controler
### MVP - Model View Presenter
### MVVM - Model View View Model

# Testing

# Reguläre Ausdrücke

# Datenbanken
## Relational
## Nicht-Relational

# GIT
## Unterstützende Software
### Server
### Client

# Sauberen Code schreiben

# Deployment

# Server Architektur

# Caching

# Performance

# Sorts

# Threading

# Promises 

# Runloops

# Continous Integration

# IDE

# Programmierkonzepte
## Prozedural
## OOP
## POP
## FP
## FRP 

# Zahlensysteme

# Datenformate
## XML
### HTML
## JSON
## CSV
## YAML
## RDF
## Roher Text [.txt]

# Modelierungssprachen
## PAP
## UML
## ERM
## Wahrheitstabelle

# Vorgehensmodelle
## Wasserfall
## SCRUM
## KANBAN
## SCRUMBAN
## Extreme Programming
## Behaviour Driven Development
## Feature Driven Development
## RAD - Rapid Application Development


# THEMENSPEICHER
# iOS - Lernreihenfolge
## Xcode 8 - Navigieren und Interface
## Labels
## Textfields
## Buttons
## Images [Bilder]
## Übungs-App erstellen: Hundejahre berechnen [Textfeld-Abfrage * Jahre, per Klick auf Button, Ausgabe in einem Label]
## Variablen
## Arrays
## Dictionaries
## If - Abfrage / Verzweigung
## Select Case - Verzweigungen
## While - Schleife
## For - Schleife
## Klassen
## Objekte
## Optionals
## Auto Layout
## Navigation Bars
## TableViews
## Daten speichern
## View Controllers
## Keyboard bei iOS
## Inhalte aus dem Internet laden
# Sonstige iOS - Themen
## Animationen
## Apple Karten integrieren
## Audio 
## Wischgesten 
## CoreData [schwer für Anfänger!]
## APIs
## SpriteKit
