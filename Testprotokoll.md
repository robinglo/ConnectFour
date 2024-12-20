# Erkenntnisse

## Programmabstürze

- Wenn man versucht, mehr als 6 Eingaben auf eine einzelne Reihe zu tätigen.  
  z.B. Eingabe auf bereits volle Reihe =>  
  _(System.IndexOutOfRangeException: Index was outside the bounds of the array.)_

- Wenn man versucht, Zahlen ausserhalb der Range von 0-7 einzugeben.  
  z.B. Eingabe 8 =>  
  _(System.IndexOutOfRangeException: Index was outside the bounds of the array.)_

- Wenn man versucht, andere Dattentypen als int einzugeben.  
  z.B. Eingabe "xyz"  
  _(System.FormatException: The input string 'xyz' was not in a correct format.)_

- Wenn man versucht, gar nichts einzugeben.
  z.B. Eingabe = ""  
  _(System.FormatException: The input string '' was not in a correct format.)_
