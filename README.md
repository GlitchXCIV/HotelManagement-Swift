# HotelManagement-Swift
Un Albergo richiede la creazione di un’applicazione per la
gestione e prenotazione delle sue camere.

L’albergo gestisce delle Stanze.
Ogni camera ha una property che la identifica
univocamente.
Esistono due tipologie di Stanza: Singola e Doppia.
La Singola può ospitare al massimo una persona ed in
più qualche singola (non tutte) può avere la possibilità di avere
un cucinino.
la Doppia può ospitare due persone, non può avere cucinino
ma qualche doppia (non tutte) potrebbe avere la possibilità di
aggiungere un terzo lettino (cosa che non può avere la stanza
singola)
Ogni camera può essere prenotata.
Una funzione dell’albergo mostra tutte le camere libere sia
singole che doppie ognuna con le sue caratteristiche
(Cucinino / Terzo lettino)
Una funzione dell’Albergo permette di prenotare una camera
che sia identificata come “libera” in base alla scelta svolta
dall’utente. (Singola, Singola con Cucinino, Doppia, Doppia
con Lettino).

Se un utente chiede di prenotare una stanza “Singola” o
“Doppia” (e con le opportuni varianti) la nostra funzione deve
essere in grado di effettuare una ricerca tra tutte le stanze in
modo da poter ritornare una stanza che non sia occupata per
poterla in seguito prenotare.
Se non ci sono stanze libere, deve mandare in Output un
messaggio all’utente :
“Ci dispiace ma non ci sono al momento stanze con le
caratteristiche da Lei richieste.”
Se esiste la Stanza e questa è libera, un’altra funzione deve
permettere all’utente di prenotarla, settando la stessa come
occupata.
