# Esame-De-Cristofaro-Andrea
## Corso: Abilità Informatiche e telematiche

Sono riportati gli scripts della risoluzione degli esercizi 3, 4, 5 e 8 di Bash, e dell'esercizio di Python. 

Istruzioni:

Per verificare gli esercizi di Bash copiare ed eseguire i codici nella SHELL.

L'esercizio 5 di Bash produrrà nella directory corrente un file.txt al cui interno vi saranno i primi 10 numeri interi (da 1 a 10) in colonna. 

Per verificare l'esercizio 8 Bash, nell'ultima riga di codice inserire al posto di '/filepath', il percorso file di una directory di cui si vogliono elencare i file. Ad esempio: '/Users/andreadecristofaro/Desktop/Trieste'.

Per verificare l'esercizio Python copiare il file: 'file2.txt' nella cartella in cui lavora l'interprete Python, quindi eseguire il codice con l'interprete Python.

Il codice Python genererà i plot di ogni 'task' dell'esercizio (6 in totale).

Commenti:

Task 1: Dopo aver sovrapposto il fit lineare ai dati, si mostrano questi ultimi anche in un grafico in scala log-log. Il grafico in scala log-log sembra permettere una maggiore leggibilità dei dati. È stato anche fatto un tentativo di fit lineare dei dati in scala logaritmica, tuttavia il fit lineare non sembra rispecchiare accuratamente l'andamento dei punti sperimentali.

Task 2: Il grafico in scala log-log ha reso più leggibili i dati sperimentali.

Task 3: Per ottenere un istogramma leggibile, gli intervalli dei bin dell'asse x dell'istogramma sono stati distribuiti in scala logaritmica, quindi anche l'asse x del grafico è stato visualizzato in scala logaritmica.

Task 4: Per rendere la 'colormap' leggibile, i dati relativi alla 'Gas_mass' sono stati convertiti in scala logaritmica; lo stesso è stato fatto per 'Stellar_mass' che rappresenta la dimensione dei punti sperimentali. In entrambi i casi sono anche state anche utilizzate due costanti, 'riscale1' e 'riscale2', per rendere apprezzabili il colore e la dimensione dei punti nel grafico.

Task 5: I dati sperimentali sono stati prima converititi in scala logaritmica, poi fittati e plottati. In questo modo il fit lineare sembra riprodurre bene l'andamento dei dati.

Task 6: Anche per questo punto gli intervalli dei bin dell'asse x degli istogrammi sono stati distribuiti in scala logaritmica, quindi l'asse x dell'istogramma comulativo finale, che rappresenta le masse delle strutture, è stato visualizzato in scala logaritmica.
