La struttura del grafo viene utilizzata per rappresentare una mappa su griglia rettangolare suddivisa in righe e colonne. 
Il Grafo utilizza come identificativo una stringa composta da 4 cifre organizzate come ccrr, dove cc indica la colonna formattata in due cifre e rr indica la riga formattata in due cifre, potendo coprire quindi mappe fino a 100x100 di dimensione.
I nodi del grafo contengono l'id come identificativo, e due valori interi riga e colonna che rappresentano la loro posizione.
Al grafo è possibile aggiungere un nodo indicando l'id o riga e colonna, e un arco indicando l'id di sorgente e destinazione. Ogni arco viene aggiunto bidirezionalmente (quindi andata e ritorno).
I metodi BellmanFord e Dijikstra prendono in input sorgente e destinazione come id e poi restituiscono un array di id che rappresenta lo shortest path.
