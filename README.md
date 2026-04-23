SUPSI 2026  
Corso d’interaction design, CV429.01  
Docenti: A. Gysin, G. Profeta  

Progetto 1: La conquista dello spazio

# NASA - Perseverance Rover
Autore: Nahele Belli \
[NASA - Perseverance Rover](https://naheleee.github.io/NaheleBelli_IXD_2026/Progetto1_PerseveranceRover/)


## Introduzione e tema
Il progetto consiste in un sitoweb interattivo dedicato all'esplorazione del Rover "Perseverance" e la missione NASA Mars 2020. L'obiettivo è colmare il divario tra la complessità dell'ingegneria aerospaziale e la divulgazione scientifica, offrendo un'esperienza immersiva che permette di analizzare da vicino uno dei veicoli più avanzati mai inviati su un altro pianeta.


## Riferimenti progettuali
Lo sviluppo si è basato sull'analisi del sito originale della Nasa (nasa.gov/mission/mars-2020-perseverance).



## Design dell’interfaccia e modalità di interazione
L'interfaccia è stata progettata seguendo i principi del Minimalist Design, con un approccio "Game-like" per massimizzare il coinvolgimento. Invece di menu complessi, l'utente interagisce direttamente con il modello tramite controlli orbitali (zoom, rotazione, pan), rendendo l'esplorazione naturale sia per esperti che per neofiti.

[<img src="README_img/cards.gif" width="500" alt="Magic trick">]()


## Tecnologia usata
Three.js: Utilizzato per il rendering in tempo reale del modello 3D (.GLTF), gestendo geometrie complesse e texture ad alta risoluzione senza l'ausilio di plugin esterni. La libreria permette anche una gestione fluida di luci, ombre e materiali fisici.<br>
Rigging e Articolazi in Blender: Per rendere il Rover dinamico e non solo una mesh statica, è stato eseguito il rigging all'interno di Blender. È stata creata un'armatura (skeleton), con una gerarchia di "ossa" che rispecchia la meccanica reale del veicolo (braccio robotico, torretta e sistema di sterzo).




```JavaScript
CODICE DI ESEMPIO
```

## Target e contesto d’uso
Giovani, adulti, e curiosi. Il progetto si rivolge a un pubblico eterogeneo, che spazia dagli studenti agli appassionati di tecnologia.

[<img src="README_img/munari.jpg" width="300" alt="Supplemento al dizionario italiano">]()
