# Grundsätze der OO-Programmierung
DIes ist das ReadMe zu den gemachten Aufträgen am 05.09.2023 im Auftrag A13.

## Geschaute Videos
Wir hatten als Auftrag folgende Videos zu schauen:
- [Beliebteste Programmiersprachen 1970 - Heute (Programmierer reagiert)
](https://www.youtube.com/watch?v=qLWb94Exc-o)
- [Programming Paradigms --- Procedural vs. Object-Oriented Programming (OOP)
](https://www.youtube.com/watch?v=4DDSUYhJIFc)
- [Chapter 10.1: Procedural v.s. Object-oriented - PRG105](https://www.youtube.com/watch?v=ese5Udwgwzc)

Ebenfalls haben wir verschiedene Arikel zu lesen bekommen:
- [How to explain object-oriented programming concepts to a 6-year-old](https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/)
- [OOPs Concepts in Java With Examples](https://beginnersbook.com/2013/04/oops-concepts/)

## Auftrag: 4 Konzepte von OOP in eigenen Worten beschreiben
In diesem Kapitel werden wir folgende Konzepte von OOP in eigenen Worten beschreiben:
- [Objects](#objects)
- [Classes](#classes)
- [Abstraction](#abstraction)
- [Encapsulation](#encapsulation)
- [Inheritance](#inheritance)

### Objects
Objekte ist alles, dem man verschiedene weitere Eigenschaften zuordnen kann. Ein Beispiel für ein Objekt wäre ein Velo. 
Einem Velo verschiedenes zuordnen. Beispiele dafür wäre: Geschwindigkeit, Farbe, Grösse, Alter oder Marke. 

### Classes
Klassen kann man gut als "Bauplan" bezeichnen. Mit einer Klasse kann man definieren, wie genau ein bestimmtes Objekt aussehen könnte. 
Mit der Klasse kann man sagen, welche verschiedenen Eigenschaften bei einem Objekt vorhanden sein sollten. Diese Eigenschaften kann man dann ganz einfach im Objekt definieren und umändern. 

### Abstraction
Dies ist der Prozess, bei dem man nur relevante Eigenschaften preisgibt.
Ein einfaches Beispiel: Bei einer Schule muss der Hausmeister nicht unbedingt wissen, wie viel alle anderen Lehrer verdienen. 
Bei der Abstraktion benutzt man private und öffentliche Methoden und Attribute, um die Informationen möglichst sicher bearbeiten zu können. 

### Encapsulation
Verkapselung ist der Prozess indem verschidene Daten mithilfe von verschiedenen Methoden gesichert werden. Das Ziel, wie ähnlich bei der Abstraction, ist Daten von zu sichern. Man will mit dem Sicherstellen, dass nicht alles Code auf alle Daten zugreifen kann.

### Inheritance
Mithilfe der Vererbung kann man übergeordnete Klassen definieren. 
Hier vererben die Child Classes bestimmte Attribute und Methoden von der Parent Klasse. 
Ein Beispiel: <br>
Wir haben eine Velo, Auto und Autobus Klasse.
Nun wollen wir allen drei Klassen nicht die Attribute 'Anzahl Räder', 'Max. Geschwindigkeit' oder Gewicht geben. <br>
Also erstellen wir eine übergeordnete Klasse mit dem Namen 'Fahrzeug'. Hier müssen wir diese Attribute nur einmal definieren und dann können die verschiedenen Klassen (Velo, Auto und Autobus) diese Attribute einfach von der 'Fahrzeug' Klasse erben.