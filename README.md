**Caratteristiche Tecniche:**
* **Modellazione OOP (Object-Oriented):** Ho utilizzato la classe `DigitalTwinAgricolo` per incapsulare i dati e i metodi, rendendo il codice scalabile. Se in futuro l'azienda volesse aggiungere un nuovo raccolto (es. Mais), basterebbe aggiungere un record al dizionario senza toccare la logica algoritmica.
* **Motore Stocastico:** La funzione `genera_scenario_climatico()` simula l'interferenza dell'ambiente esterno, restituendo moltiplicatori matematici che alterano le variabili di produzione (Simulazione Monte Carlo-like).
* **Motore Stocastico:** La funzione `genera_scenario_climatico()` simula l'interferenza dell'ambiente esterno, restituendo moltiplicatori matematici che alterano le variabili di produzione.
* **Elaborazione sicura dei dati:** Ho evitato l'uso di liste mutabili per i parametri operativi, preferendo le *Tuple* e i metodi `.get()`, per prevenire bug e conflitti durante l'iterazione dei calcoli sui lead-time.

##  CLI Dashboard & Output Direzionale
