# Python Starter Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FoehrsWorks/PythonJupyter/blob/main/Programmieren_Einstieg_Python.ipynb)

## Willkommen in der Programmieren-Starterumgebung

Dieses Notebook hilft dir, die Grundlagen von Python zu lernen. Du kannst Code direkt hier ausführen und ändern.

## Dein erster Python-Code: Hello, World!

Willkommen in der Programmieren-Starterumgebung! 😊  
Um mit Python zu starten, ist es immer eine gute Idee, etwas Einfaches auszuprobieren.  

### Was macht dieses Programm?

Es zeigt eine einfache Nachricht auf dem Bildschirm an. Das ist ein erster Schritt, um zu lernen, wie man Python-Code schreibt und ausführt.

### Warum ist das wichtig?

- Du lernst, wie ein Python-Programm aufgebaut ist.  
- Es zeigt dir sofort, dass dein Code funktioniert.

Drücke jetzt einfach den **Play-Button** (▶️) unter dem folgenden Code, um dein erstes Programm auszuführen:

```python
# Dein erster Python-Code
print("Hello, World!")
```

### 1. Hello World Aufgaben

#### Aufgabe 1: Variablen nutzen
Ändere das Programm so, dass es eine Nachricht in einer Variablen speichert und diese dann ausgibt.

#### Aufgabe 2: Benutzername einfügen
Passe das Programm so an, dass es den Namen des Benutzers in die Nachricht einfügt.

## Dein erster Python-Taschenrechner 🧮

Jetzt, da du deinen ersten Python-Code ausgeführt hast, schauen wir uns etwas Spannenderes an: einen **einfachen Taschenrechner**!  

### Was macht dieses Programm?

Dieser Taschenrechner kann zwei Zahlen nehmen und die Grundrechenarten ausführen:  
- **Addition (+)**  
- **Subtraktion (-)**  
- **Multiplikation (*)**  
- **Division (/)**  

Du gibst zwei Zahlen ein, wählst eine Rechenoperation, und der Taschenrechner zeigt dir das Ergebnis an.

### Warum ist das wichtig?

- Du lernst, wie man Eingaben von Nutzern verarbeitet.  
- Du siehst, wie **Verzweigungen** (if/else) funktionieren, um unterschiedliche Aktionen auszuführen.  
- Es ist ein praktisches Beispiel, das du direkt ausprobieren und erweitern kannst.

```python
# Einfacher Taschenrechner
num1 = float(input("Gib die erste Zahl ein: "))
num2 = float(input("Gib die zweite Zahl ein: "))
operation = input("Wähle eine Operation (+, -, *, /): ")

if operation == "+":
    print("Ergebnis:", num1 + num2)
elif operation == "-":
    print("Ergebnis:", num1 - num2)
elif operation == "*":
    print("Ergebnis:", num1 * num2)
elif operation == "/":
    if num2 != 0:
        print("Ergebnis:", num1 / num2)
    else:
        print("Fehler: Division durch null!")
else:
    print("Ungültige Operation!")
```


### Aufgaben für den Taschenrechner

#### Aufgabe 1: Berechne die Summe von drei Zahlen
Ergänze den Code, um die Summe von drei Zahlen zu berechnen!

#### Aufgabe 2: Erweiterung um Modulo
Füge die Berechnung des Restwerts (Modulo, `%`) hinzu.

#### Aufgabe 3: Fehler abfangen
Sorge dafür, dass das Programm einen Fehler abfängt, wenn der Benutzer keine Zahl eingibt.

#### Aufgabe 4: Mehrere Berechnungen hintereinander
Lass den Benutzer mehrere Berechnungen hintereinander durchführen, bis er „exit“ eingibt.

## Kreative Aufgaben

### Aufgabe 1: Benutzerdefinierte Begrüßung
Schreibe ein Programm, das den Benutzer fragt, wie er begrüßt werden möchte.

### Aufgabe 2: Zufällige Begrüßung
Das Programm soll aus einer Liste von Begrüßungen zufällig eine auswählen.

## Aufgaben zur Förderung von Logik

### Aufgabe 1: Zahlen vergleichen
Schreibe ein Programm, das zwei Zahlen vergleicht und sagt, welche größer ist.

### Aufgabe 2: Gerade oder ungerade?
Schreibe ein Programm, das überprüft, ob eine eingegebene Zahl gerade oder ungerade ist.

## Erweiterte Herausforderungen

### Aufgabe 1: Mini-Spiel – Zahlenraten
Der Benutzer soll eine Zahl zwischen 1 und 10 erraten, die das Programm zufällig auswählt.
