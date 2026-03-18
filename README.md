# Proiect Baze de Date: Platformă de E-Learning

Acest proiect modelează o platformă educațională online (tip Udemy/Coursera), realizat pentru cursul de Baze de Date.

## 1. Descrierea modelului real
Scopul aplicației este de a facilita interacțiunea dintre instructori și studenți prin intermediul cursurilor digitale.
* **Instructorii** pot crea cursuri, care sunt împărțite în module și lecții. De asemenea, pot crea teste de evaluare.
* **Studenții** se pot înscrie la cursuri (generând o tranzacție financiară/plată), pot parcurge lecțiile, pot susține teste și pot lăsa recenzii. 
* La finalizare, studentul primește un certificat de absolvire.

## 2. Constrângeri și Reguli de funcționare
* Un utilizator se identifică unic prin adresa de email.
* Prețul unui curs și valoarea unei plăți trebuie să fie strict pozitive (> 0).
* Un student nu poate lăsa o recenzie pentru un curs la care nu are o înscriere activă.
* O recenzie poate avea un rating doar între 1 și 5.
* Un curs trebuie să aparțină obligatoriu unei categorii.
* Un test de evaluare este promovat doar dacă scorul obținut este mai mare sau egal cu scorul minim setat.

## 3. Diagrama ERD (Entity-Relationship Diagram)
*Notă: Diagrama conține 13 entități pentru a respecta standardul de proiect complex.*

![Diagrama ERD](out/diagrama_erd/diagrama_erd.png)

## 4. Diagrama Conceptuală
Această diagramă detaliază structura logică a bazei de date, incluzând atributele, tipurile de date, Cheile Primare (PK) și Cheile Străine (FK), precum și tabelul asociativ "Inscriere".

![Diagrama Conceptuala](out/diagrama_conceptuala/diagrama_conceptuala.png)