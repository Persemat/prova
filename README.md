# Risk Game

![Version](https://img.shields.io/badge/version-4.0.0-success)
![License](https://img.shields.io/github/license/UnimibSoftEngCourse2022/progetto-monopoly-1-gangoffour2)
![Stars](https://img.shields.io/github/stars/UnimibSoftEngCourse2022/progetto-monopoly-1-gangoffour2)

![RiskLogo.png](Monopoly.png?raw=true)

## Come eseguire il progetto

### Prerequisiti

- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/install.html) (3.1 or >)
- [Git](https://git-scm.com/downloads)

### Import e installazione 

- `git clone https://github.com/UnimibSoftEngCourse2022/riskgame-malnati-negro-persico-romano-radaelli-mvc-guru-1.git`: per eseguire la clone del repository localmente.

*I seguenti comandi sono da eseguire all'interno della root del repository*

- `mvn package`: Esegue la build del server e i relativi test. 
Se hanno successo, esegue anche la build del client all'interno di `src/main/app` e copia i file generati
in `target/static`, dove `target/` è la cartella in cui risiedono i file compilati del server.
Infine, crea il pacchetto .jar completo.

- `java -jar target/monopoly-VERSION.jar`: Esegue il file .jar generato in precedenza.
`VERSION` è il numero di versione presente nel file `pom.xml` alla path `project.version`.
Attualmente è `4.0.0`.

- Il server è ora accessibile all'indirizzo `localhost:8080`.

Una volta aperto il server troverai questa schermata e avrai due possibilità:
	- registrarti, loggarti
	- entrare come ospite 
In entrambi i casi potrai passare alla pagina successiva cliccando su cliccando 'Play Game'

![home_page.png](Monopoly.png?raw=true)
- 
- Una volta , questa sarà visibile dalla scheda a destra. Cliccando sull'id, apparirà una schermata tramite la quale sarà possibile avviare la partita.
- Se vi sono più giocatori selezionati, la partita non inizierà fino a che non verrà raggiunto il numero prestabilito.

*made by MVC-GURU*
