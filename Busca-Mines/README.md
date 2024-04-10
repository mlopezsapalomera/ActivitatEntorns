### 1. Resum estès de cada document Java:

#### `Controlador.java`:
Aquest fitxer conté la classe `Controlador`, que és responsable de gestionar les interaccions de l'usuari i coordinar les accions amb el model del joc de Buscamines. La seva funció principal és iniciar el joc, rebre les accions de l'usuari (com ara col·locar una bandera, destapar una casella o abandonar el joc) i coordinar l'execució d'aquestes accions amb el model del joc.

#### `Model.java`:
En aquest fitxer es troba la classe `Model`, que representa el model del joc de Buscamines. Conté funcions per inicialitzar el joc, gestionar el seu estat i verificar-ne la finalització. A més, s'encarrega de posicionar les bombes aleatòriament, comptar el nombre de bombes al voltant de cada casella i destapar caselles segons les accions de l'usuari. També proporciona mètodes per verificar si el jugador ha guanyat i mostrar el resultat del joc.

#### `Vista.java`:
La classe `Vista` en aquest fitxer s'encarrega de mostrar la informació del camp de mines a l'usuari. Conté una funció per mostrar el camp de mines a la consola, amb les caselles ocultes i visibles, així com les lletres de les files i els números de les columnes per facilitar la referència a l'usuari.

#### `MinesMLM.java`:
Aquest fitxer conté la classe principal `MinesMLM`, que inclou el mètode `main` per iniciar el joc de Buscamines. Simplement crida al mètode `jugar()` de la classe `Controlador` per iniciar l'execució del joc.


### 2. Funcionament del projecte:

El projecte de Buscamines en Java segueix una estructura MVC (Model-Vista-Controlador), on cada component compleix un paper específic:

- **Controlador**: Representat per la classe `Controlador`, actua com a intermediari entre el model i la vista. Gestiona les interaccions de l'usuari, com ara col·locar banderes, destapar caselles o abandonar el joc, i coordina aquestes accions amb el model.

- **Model**: Representat per la classe `Model`, gestiona la lògica del joc, incloent la inicialització del camp de mines, el posicionament de les bombes, el recompte del nombre de bombes adjacents, el destapament de caselles i la verificació de l'estat del joc.

- **Vista**: Representat per la classe `Vista`, s'encarrega de mostrar la informació del camp de mines a l'usuari a la consola, facilitant la interacció visual.

Quan s'executa el programa (`MinesMLM.java`), el mètode `main` inicia el joc cridant al mètode `jugar()` del controlador. A partir d'aquí, el controlador gestiona les interaccions de l'usuari, que es reflecteixen en el model a través de les accions realitzades pel jugador. El model actualitza el seu estat en conseqüència i notifica a la vista perquè actualitzi la visualització del camp de mines a la consola. El cicle continua fins que el joc finalitza, ja sigui perquè el jugador guanya, perd o decideix abandonar.