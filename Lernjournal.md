# D1 Verbesserung
1) [Ein Konstante ist immer global definiert im Code.] ist falsch ➞ Warum?  
   Die Aussage ist falsch, weil Konstanten dort definiert werden, welche normale Variablen auch definiert werden, also in Funktionen. (sie können lokal oder global definiert werden, je nachdem, wo du sie brauchst.)

2) [Wird eine Variable verwendet, bevor sie deklariert ist, meldet der Kompiler eine Fehlermeldung.] ist richtig ➞ Warum?  
   Richtig, weil der Compiler beim übersetzen den Datentypen und Speicherplatz der Variable kennen muss.  
   z.B.: Zeige mir die Zahl x.  
   Aber du hast vorher nicht gesagt, wie groß x ist oder dass es x überhaupt gibt.

4) Wann spricht man von einer **lokalen** Variable? Wo muss die Deklaration erstellt werden?  
   Wenn eine Variable nur innerhalb einer bestimmten Funktion sichtbar ist. Die Deklaration muss innerhalb der Funktion sein, damit sie verwendet werden. (bestimmten Ort)

5) Wann spricht man von einer **globalen** Variable? Wo muss die Deklaration erstellt werden?  
   Globale sind im ganzen Programm sichtbar. Diese müssen ausserhalb der Funktionen deklariert werden. (ganz Programm)

6) [Bestimme geeigneter Datentyp zum Speicher von 2'200'500'000] ➞ Welche Datentypen sind möglich?  
   Die primitiven Datentypen long, double und float sind geeignet.  
   int: reicht nicht aus, da er kann kleinere Zahlen speichern

7) [Die Anzahl Bits in Java für den Datentyp char ist 8]  ist falsch ➞ Warum?  
   Die Anzahl Bits für char ist 16.

8) Welche Wertebereich hat der float Datentyp?  
   gut geeignet für z.B. Kommazahlen:  
   sehr kleine: ±1.4…×10^-38 (ungefähr 0.000000000000000000000000000000000000014)  
   sehr grosse: ±3.4…×10^+38 (ungefähr 340000000000000000000000000000000000000)
