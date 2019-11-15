# Aufgabe: Klasse `Car`

Erstellen Sie eine Klasse namens `Car` (Auto) mit den nachstehenden Eigenschaften. Jedes Auto soll

 - ein Model `model`
 - eine Tankkapazität `fuelCap` in Litern,
 - den Tankinhalt `fuel` in Litern,
 - den Spritverbrauch (Liter pro 100km)  `fuelConsum`, 
 - eine Seriennummer `serialId` haben.   
 
Ein Modell kann zum Beispiel ein `OLDTIMER` sein.

## Konstruktor und Methoden

Der Konstruktor soll ein Model `model`, die Tankkapazität `fuelCap` und den Spritverbrauch (Liter pro 100km)  `fuelConsum` annehmen. Bei Konstruktion soll der Tankinhalt leer sein.

Die `serialId` soll immer 1 höher sein als die, vom letzten Auto. Die Zählung beginnt für das erste Auto mit der Nummer 1. Außerdem soll diese später nichtmehr verändert werden können.

Außerdem soll jedes Auto die Methode `drive(km)` kennen und sinnvoll ausführen. Die Methode soll außerdem die tatsächlich gefahrenen Kilometer zurückgeben, falls der Tank leer geht.

Die Methode `refuel()` soll den Tank aufüllen und die getankten Liter zurückgeben.

Um an die Informationen des Auto zu kommen nutzen wir `get`-Methoden. 

Die `toString()` methode soll etwas wie das Auto mit Seriennummer zurück geben.
Außerdem soll es auch den Weg ausgeben, der mit der momentanen Tankfüllung zurücklegen kann.

Außerdem sollen die Autos per `equals()` anhand der Seriennummer `serialId` verglichen werden können.

## Szenario 

Erstelle drei _verschiedene_ Autos drei verschiedener Modelle.   
Auto 1 ist ein Oldtimer mit einer Tankkapazität von 30 litern und einem Spritverbrauch von 12,8 l/100km.    
Auto 2 ist ein Oldtimer mit einer Tankkapazität von 20 litern  und einem Spritverbrauch von 3,4 l/100km.    
Auto 3 ist ein Youngtimer mit einer Tankkapazität von 60 litern  und einem Spritverbrauch von 5,9 l/100km.    
Das Auto mit der Seriennummer 1 fährt 3200 km, Auto Nr. 2 2170,7 km,3 und Auto Nr. 3 4920,69 km.

Schreibe eine Methode, welche ein Auto solange fahren und tanken lässt, bis es die gewünschte Anzahl an Kilometern gefahren ist.
