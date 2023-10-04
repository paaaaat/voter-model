# Voter Model
Il "Voter Model" è una rappresentazione dell'evoluzione delle opinioni in una popolazione. Il modello consiste di N agenti (o votanti) che fungono da vertici di un grafo semplice non orientato. Ogni agente può assumere uno di due stati (od opinioni). Il sistema evolve in tempo discreto, seguendo queste semplici regole: ad ogni time-step

* un individuo viene selezionato casualmente in modo uniforme (agente i);
* uno dei vicini dell'agente i viene selezionato casualmente in modo uniforme (agente j);
* se gli stati dei due agenti sono differenti, l'agente i adotta lo stato dell'agente j, altrimenti gli stati rimangono inalterati.

Osserviamo che ogni individuo viene influenzato solo dai suoi diretti vicini; non esiste il concetto di opinione giusta/sbagliata e non ci sono influenze esterne o altri tipi di interazione.
Cominciando da una qualsiasi condizione iniziale, queste semplici regole di aggiornamento tendono ad aumentare l'ordine del sistema; questa dinamica porta necessariamente al consenso di uno dei due stati (lo stato finale viene detto absorbing state). Il tempo impiegato per raggiungere il consenso dipende dal numero dei vertici N e dalla dimensione d del sistema.
