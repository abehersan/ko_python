# Rock, Paper, Scissors!

## (Stein, Papier, Schere)

Unser heutiges Ziel ist es, ein Programm zu planen und zu entwerfen, das es einem Spieler ermöglicht, "Stein, Papier, Schere" mit dem Computer zu spielen. 

In jeder Runde muss der Spieler entweder "Stein", "Papier" oder "Schere" wählen. 
Der Computer trifft dann eine zufällige Wahl und entscheidet über seinen Zug. 

Wir können dann die Eingabe des Spielers und die Entscheidung des Computers vergleichen, um zu entscheiden, wer gewonnen hat! 

Beachten Sie natürlich, dass ungültige Antworten nicht akzeptiert werden. 
Eine ungültige Antwort ist alles andere als Stein, Papier oder Schere. 

## Plan the program

The internal algorithm that our program must follow is:
    
1. Definieren Sie eine Liste mit Zeichenketten für die möglichen Entscheidungen der Spieler
2. Definiere eine Variable, die die Eingabe des Spielers aufnimmt (`player = input()` kann hier nützlich sein. Die Funktion `input()` wartet, bis der Spieler etwas in das Terminal getippt hat)
3. Wir überprüfen den Wert, den der Spieler eingegeben hat, mit der Liste der Auswahlmöglichkeiten und stellen fest, ob die Eingabe gültig ist. Z.B. ist die Option `steineeee` nicht gültig.
4. Definiere die "Wahl" des Computers, indem du eine zufällige Wahl aus den verfügbaren Möglichkeiten auswählst (Das `random` Modul ist in diesem Fall hilfreich)
5. Vergleiche die Spielervariable mit der Computervariable und bestimme den Gewinner.
6. Wiederholen Sie den Vorgang, bis der Spieler das Spiel aufgibt. 

## Write the program

AUFGABE: Führen Sie den obigen Algorithmus in Python aus! 

Scheuen Sie sich nicht, in Google nach Antworten oder Beispielen zu suchen. 
Programmieren ist zu 50 % Planung und zu 50 % online nachschauen, wie es geht! 

## Online resources and help

Vergessen Sie nicht, die "random"-Bibliothek in Ihr Skript zu importieren! (`import random`)
Probieren Sie [diesen Link](https://www.w3schools.com/python/ref_random_choice.asp) aus, um zu sehen, wie die Methode `random.choice()` funktioniert.


