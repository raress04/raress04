# Tema 2 - Unix Timestamp

###### Pentru task-urile 2-5 vom folosi un vector in care vom salva numarul de zile din fiecare luna 
###### Urmand ca la task-ul 6 sa folosim un vector asemanator de tip char, in care vom stoca numele fiecarui luni din an

### Task 1
- Impartim timestamp-ul primit ca parametru la numarul de secunde dintr o ora, respectiv la numarul de minute dintr-o ora
- Valoarea ramasa in timestamp reprezinta numarul de secunde
- Se returneaza rezultatul sub forma [ ora , minute, secunde ]

### Task 2
- Calculam intai anul, asemanator ca in taskul anterior
- Apoi scadem din timestamp numarul de secunde intr-o zi inmultite cu numarul de zile de pe pozitia respectiva, folosind vectorul de zile
- Ulterior pentru a afla ziua din data, impartim timestamp-ul la secundele dintr-o zi

### Task 3
- Asemantor algoritmului de la taskului anterior, vom calcula data din timestamp, tinand cont de existenta anilor bisecti

### Task 4
- In plus, fata de taskul 3, vom calcula si ora exacta aferenta timestamp-ului (asemanator ca in taskul 1)

### Task 5
- La acest task, facem procedeul invers fata de taskul aneterior, tinand cont de anii bisecti si actualizand vectorul cu zilele din an, in functie de valoarea anului
- Vom avea nevoie de 2 for-uri, unul pentru a aduna secundele din fiecare an complet pana la cel dat si unul pentru a aduna secundele din toate lunile complete pana la cea data, urmand sa adunam si zilele, orele, minutele, secundele, scazand in final diferenta de fus orar 

### Task 6
- Vom afisa data si ora in formatul cerut, tinand cont de padding
