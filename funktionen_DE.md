# Funktionen und Review!

## Berühmte Fragen zur Programmierung

Im Folgenden findest du **10 Übungen**, um zu üben, wie wir Funktionen in Python planen und schreiben. 
Dazu gibt es Tipps und Online-Ressourcen, die dir helfen, diese Aufgaben zu lösen.

_Spoiler-Alarm: Einige dieser Fragen werden oft in Vorstellungsgesprächen bei Google, Meta und IBM gestellt.

**Tip: Du kannst Online-Ressourcen nutzen, die dir bei der Lösung einer bestimmten Frage helfen.**

> Wenn du 5 Übungen absolvierst, bekommst du +5 Kiberonen extra. 

> Wenn du 7 Übungen absolvierst, bekommst du +10 Kiberonen extra. 

> Wenn du alle Übungen absolvierst, bekommst du +20 Kiberonen extra. 

1. Schreibe eine Funktion, die einen Namen (eine Zeichenkette) und ein Alter (eine ganze Zahl) als Eingaben annimmt und die resultierende Zeichenkette ausgibt. 

    - Erwartetes Verhalten:
    
    ```python
    # Input
    name = "José"
    age = 25
    # Output
    >> "Hi, my name is José and I'm 25 years old."
    ```

2. Schreibe eine Funktion, die zwei Zahlen nimmt, sie zusammenzählt und feststellt, ob das Ergebnis eine gerade Zahl ist. 

    - Erwartetes Verhalten:
    
    ```python
    # Input
    first_number = 1
    second_number = 11
    # Output
    >> "Sum = 12. Even? True"
    ```

3. Schreibe eine Funktion, die eine Liste von Zahlen als Eingabe annimmt und prüft, ob das erste und das letzte Element der Liste gleich sind.

    - Erwartetes Verhalten:
    
    ```python
    # Input
    input_list = [0, 10, 11, 2, 13, 0]
    # Output
    >> True
    ```

4. Schreibe eine Funktion, die die Multiplikationstabelle einer gegebenen Eingangszahl ausgibt. 

    - Erwartetes Verhalten:
    
    ```python
    # Input
    table_number = 2
    # Output
    >> 2, 4, 6, 8, 10, 12, 14, 16, 18, 20
    ```

5. Schreibe eine Funktion, die alle ungeraden Zahlen zwischen 0 und 100 ausgibt. 

    - Erwartetes Verhalten:
    
    ```python
    # Output
    >> 1, 3, 5, 7, 9, ..., 99
    ```

6. Definiere einen Würfel. Schreibe eine Funktion, die einen Würfel wirft.

    - Erwartetes Verhalten:
    
    ```python
    # Definition
    die = [1, 2, 3, 4, 5, 6]
    # Example output
    >> 4
    ```

7. Schreibe eine Funktion, die dir sagt, ob heute Samstag ist. 

    - Versuche es mit dem Befehl ``import datetime``. Lies seine Dokumentation. Unter [diesem Link](https://www.delftstack.com/howto/python/python-datetime-day-of-week/) findest du einen Hinweis.

8. Schreibe eine Funktion, die den Durchmesser annimmt und den Flächeninhalt eines Kreises zurückgibt. Zeige dann den Kreis mit Schildkröten. 

    - Denke daran, dass die Fläche eines Kreises $A = \pi r^{2}$ ist, wobei $r$ der Radius eines Kreises ist. Der Radius ist die Hälfte des Durchmessers.

9. Definiere ein Standard-Kartenspiel. Schreibe eine Funktion, die 4 Karten nach dem Zufallsprinzip zieht. 

    - Siehe [diesen Link](https://en.wikipedia.org/wiki/Standard_52-card_deck)

10. Definiere eine Funktion, die eine beliebige Anzahl von ganzzahligen Parametern annimmt und den maximalen Wert zurückgibt. 

    - Untersuche, was ``*args`` in Python ist. Siehe [diesen Link](https://realpython.com/python-kwargs-and-args/)
    
    ```python
    # Example function call
    myfunc(8, 9, 100, 20, 2, 1, ...)
    # Output
    >> 100
    ```