# Sorting-Algorithms-Project

Proiectul contine:
- fisier cu sursa codului (python)
- fisier cu cateva teste (mai multe au fost rulate in prezentare)
- fisier cu prezentarea proiectului (compararea algoritmilor de sortare)

> Observatie importanta! 

La Counting Sort am utilizat **metoda python .count**. Aceasta afecteaza timpul de 
rulare al algoritmului intrucat parcurge iar vectorul pentru fiecare 
element pentru a-l contoriza.

Pentru a observa corect cum functioneaza Counting Sort numaram aparitiile
printr-o singura parcurgere a vectorului dupa cum urmeaza:
```sh
for i in range(len(v)):
	if v[i] = element:
		contor_element += 1
```

Aceasta modificare afecteaza clasamentul sortarilor si timpii de rulare, 
punand Counting Sort pe o pozitie mai buna in clasament. 

In sursa main.py este modificat acest lucru, in prezentare nu. 
