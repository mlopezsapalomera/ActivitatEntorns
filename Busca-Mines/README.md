### 1. Resum estès de cada document Java:

#### `Controlador.java`:
Aquest fitxer conté la classe `Controlador`, que és responsable de gestionar les interaccions de l'usuari i coordinar les accions amb el model del joc de Buscamines. La seva funció principal és iniciar el joc, rebre les accions de l'usuari (com ara col·locar una bandera, destapar una casella o abandonar el joc) i coordinar l'execució d'aquestes accions amb el model del joc.

#### `Model.java`:
En aquest fitxer es troba la classe `Model`, que representa el model del joc de Buscamines. Conté funcions per inicialitzar el joc, gestionar el seu estat i verificar-ne la finalització. A més, s'encarrega de posicionar les bombes aleatòriament, comptar el nombre de bombes al voltant de cada casella i destapar caselles segons les accions de l'usuari. També proporciona mètodes per verificar si el jugador ha guanyat i mostrar el resultat del joc.

#### `Vista.java`:

#### `MinesMLM.java`:


### 2. Funcionament del projecte:

El projecte de Buscamines en Java segueix una estructura MVC (Model-Vista-Controlador), on cada component compleix un paper específic:

- **Controlador**: Representat per la classe `Controlador`, actua com a intermediari entre el model i la vista. Gestiona les interaccions de l'usuari, com ara col·locar banderes, destapar caselles o abandonar el joc, i coordina aquestes accions amb el model.

- **Model**: Representat per la classe `Model`, gestiona la lògica del joc, incloent la inicialització del camp de mines, el posicionament de les bombes, el recompte del nombre de bombes adjacents, el destapament de caselles i la verificació de l'estat del joc.

- **Vista**: 