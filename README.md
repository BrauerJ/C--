C++
===

Exercises



Hallo liebe 913er hier gibts einige C++ Übungen:



	 Vector Class

Erstelle eine eigene Vector3 Klasse und/oder eine Vector2 Klasse. Versuche dabei an die Performance zu denken.
Mache dir Gedanken welche Operatoren implementiert werden sollten.

Implementiere mindestens! 5 Operatoren sinnvoll.
Stelle für den Benutzer nützliche Konstruktoren zur Verfügung.

Nehme dir die Rule of Three zu Herzen und übe diese in dieser Übung:
http://en.wikipedia.org/wiki/Rule_of_three_(C%2B%2B_programming)



	 Binary Tree Structure

Erstelle eine eigene Datenstruktur! Ein binärer Baum wird sehr häufig in der Spieleentwicklung benötigt.
Implementiere eine generische BinaryTree Klasse die folgende Funktionen mindestens zur Verfügung stellt:

Dequeue()
Enqueue()
Peek()
Search()

Achte darauf das so ein Baum schon sehr viele Member haben kann und du solltest auf den Speicherverbrauch und Performance achten. 
Auch hier nehm dir die Rule of Three zu Herzen.
Wenn die Klasse erfolgreich implementiert ist mache einige Unit und Performance Tests, mal sehen wer die schnellste Datenstruktur programmiert ;)



	Dynamic Array

In dieser Übung wird ein generisches dynamisch vergrößerebares Array erstellt das vielseitig nutzbar ist und sich selber verwaltet.
Erstelle eine Template Klasse das die standard Funktionen eines Arrays aufweist und seine Speicherverwaltung selbst in die Hand nimmt.
Ablaufbeschreibung:
- Erstelle eine C++ Konsolenanwendung
- Erstelle eine Template Klasse
- Sorge dafür das nur der wirklich benötigte Speicher allokiert wird
- Sorge dafür das das Array beim befüllen automatisch wächst
- Sorge dafür das das Array automatisch kleiner wird beim removen
- Überlade den “[]” Operator angemessen



	MyPtr<>
	
Erstelle eine Template Klasse die einen optimierten Pointer repräsentiert. Diese soll eine Template Klasse sein und ihren Speicher selbst verwalten. 
- Überlade die boolischen Operatoren (<=, !=, usw)
- Denke an die Rule of Three
- Erstelle eine Delete() Funktion
- Erstelle eine getValue() Funktion






	OpenGL Basics Übung

Erstelle ein OpenGL Projekt und inistialisiere ein Fenster in der Größe von 800x600. Gehe dabei Objektorientiert vor!

Das Finale Ergebnis soll so aussehen:  http://postimg.org/image/6v53fry5z/

- Inistialisiere eine passende Kamera
- Erstelle eine abstrakte Primitive Klasse mit der abstrakten Funktion draw()
- Erstelle eine Quad und eine Circle Klasse die die draw() Methode implementieren und im Konstruktur folgendes übergeben bekommen:
- Quad(int x, int y, int sizeX, int sizeY)
- Circle(int x, int y, int radius)

- Vergiss nicht aufzuräumen!


	
