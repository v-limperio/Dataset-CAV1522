# CAV_1522

La nota metodologica fornita dall’ISTAT (ISTAT-1) riferisce che le informazioni fornite durante la telefonata vengono registrate su una piattaforma informatizzata di cui si dispongono i dati a partire dal gennaio 2018. L’analisi del fenomeno della violenza e dello stalking che emerge dalla lettura dei dati del 1522 restituisce uno spaccato utile a comprenderne le dinamiche e le caratteristiche, che si avvicina sorprendentemente al profilo già rilevato dalle indagini campionarie condotte dall’Istat sulla stessa tematica. 
La registrazione avviene a seguito di domande poste dalle operatrici del numero verde secondo un percorso standardizzato il cui filtro è rappresentato dal motivo della chiamata. A seconda dei diversi motivi della chiamata l’operatrice inserisce informazioni e dati, riportando quanto dichiarato dagli utenti del 1522.
A seconda della motivazione le chiamate sono state classificate in due macro-raggruppamenti: 

* Chiamate valide che provengono da interlocutori che chiamano per avere informazioni o chiedere supporto per sé stessi, per altre persone facenti parte della propria rete amicale e/o parentale;
* Chiamate non valide in quanto provenienti da utenti il cui scopo non è quello di chiedere aiuto ma di scherzare o denigrare lo stesso e chiamate fatte per errori non intenzionali.

All’interno delle chiamate valide le informazioni riportate sono state ulteriormente suddivide per le macrocategorie “utenti” e “vittime”. Le vittime sono coloro che hanno subito qualche forma di violenza e/o stalking, e di cui si dispongono dettagli socio-anagrafici che negli utenti sono molto meno indagati. 
Una importante considerazione va effettuata sul processo di standardizzazione operato sul data base. I dati sono stati resi confrontabili per i vari anni dal momento che nelle diverse annualità sono state utilizzate modalità di risposta non omogenee. Questo lavoro di normalizzazione è stato condotto soprattutto per rendere fruibili i dati raccolti che sono disponibili nel dataware house accessibile attraverso ISTAT “violenza sulle donne” https://www.istat.it/it/violenza-sulle-donne.

Un’attenzione specifica va fatta sulla numerosità dei casi: trattandosi di chiamate (telefoniche e via chat) e non di persone, i numeri e i commenti sono sempre riferiti a questa unità di rilevazione e non alla utente/vittima che si rivolge al servizio. È infatti possibile che la stessa persona possa chiamare diverse volte il numero verde, sia per sé stessa sia per altri. Il sistema ad oggi, anche per motivi di privacy, non controlla queste informazioni se non attraverso una domanda che viene rivolta a colui che chiama, con la quale si chiede se sia la prima volta o meno che l’utente si sia rivolto al numero verde. Allo stesso modo, giacché è impossibile controllare le informazioni raccolte durante la chiamata o il messaggio inviato, è possibile che la chiamata sia registrata a nome di un possibile interlocutore (diverso dalla vittima) ma che si tratti, in realtà della stessa vittima che non voglia riportare informazioni riferite a sé stessa. In tale caso il database, acquisendo tutte le informazioni di natura socio-anagrafica, viene segnata come vittima.

Un’ultima considerazione va necessariamente fatta al fine di guidare nella corretta lettura delle informazioni riportate che è strettamente connessa a quanto appena indicato: il fatto che il database sia costituito da chiamate (via telefono o chat) comporta un numero di dati “non disponibili’ (N.D. nelle tabelle) molto elevato e variabile. Spesso le chiamate si interrompono prima della conclusione del colloquio e in molti casi non si riescono ad imputare tali missing alla volontà di non rispondere o all’interruzione della telefonata. Laddove è stato possibile ricostruire il dato del “non risposto” intenzionale, da quello non intenzionale di non rispondere, si è proceduto con questa codifica.

Il dataset utilizzato è stato ricavato da un insieme di ventuno tavole fornite da Il numero verde 1522 durante la pandemia (dati trimestrali al I trimestre 2021) (istat.it) pubblicato il 24 Giugno 2021, di cui si dispone della nota metodologica appena citata per descrivere le impostazione dei dati, indice delle tavole che ne descrive le informazioni di ciascuna e il riferimento per poter accedere a queste ultime. Al fine di ottenere un dataset utilizzabile, sono state effettuate delle modifiche, al fine di esportare un insieme di tabelle appropriato.




## Indice Tavole

* Cartella Tavola 1 (Contatti effettuati al 1522):
    * Tavola 1 - Totali: Totali dei contatti per tipologia di utenza.  
    * Tavola 1 - Contatti: Motivi dei contatti. 
* Cartella Tavola 2 (Contatti effettuati al 1522 per canale di comunicazione):
    * Tavola 2 - Totali: Totali dei contatti per tipologia di utenza e per canale di comunicazione. 
    * Tavola 2 - Motivi: Motivi dei contatti per canale di comunicazione.
* Cartella Tavola 4 (Contatti effettuati per fascia oraria):
    * Tavola 4 - Fascia oraria (Vittime): Contatti effettuati secondo la fascia oraria per le vittime.
    * Tavola 4 - Fascia oraria (Utenti): Contatti effettuati secondo la fascia oraria per gli utenti.
* Cartella Tavola 5 (Contatti effettuati per fascia giornaliera):
    *  Tavola 5 - Fascia giornaliera (Vittime): Contatti effettuati secondo la fascia giornaliera per le vittime.
    *  Tavola 5 - Fascia giornaliera (Utenti): Contatti effettuati secondo la fascia giornaliera per gli utenti.
* Tavola 6 - Chiamate effettaute da utenti dal 1°gennaio 2018 al 31 dicembre 2021. 
* Tavola 9 - Modalità di conoscenza del 1522 riportato da tutti gli utenti del numero verde e trimestre. 
* Tavola 10 - Primo contatto effettuato al servizio 1522.
* Cartella Tavola 12 (Variabili socioanagrafiche delle vittime): 
    * Tavola 12 - Genere: Numero di vittime che contattano il 1522 suddivise per genere.
    * Tavola 12 - Condizione occupazionale: Numero di vittime che contattano il 1522 suddivise per condizione occupazionale.
    * Tavola 12 - Classe di età: Numero di vittime che contattano il 1522 suddivise per fascia d'età.
    * Tavola 12 - Stato civile: Numero di vittime che contattano il 1522 suddivise per stato civile.
    * Tavola 12 - Nazionalità: Numero di vittime che contattano il 1522 suddivise per nazionalità.
* Cartella Tavola 13 (Violenze subite):
    * Tavola 13 - Violenza principale: Numero di vittime per violenza subita.
    * Tavola 13 - Altre violenze subite: Numero di vittime per altre violenze subite, raccolta per tipologia.
    * Tavola 13 - Numero di violenze subite: Numero di vittime per numero di violenze subite.
* Tavola 14 -  Frequenza dell'atto violento riportato dalle vittime.
* Tavola 15 - Modifica dei comportamenti delle vittime a seguito dell'atto violento.
* Tavola 16 - Luogo dell'atto violento riportato dalle vittime.
* Cartella Tavola 17 (Denunce effettuate):
    *  Tavola 17 - Denunce: Denunce effettuate e assenti. 
    *  Tavola 17 - Motivo assenza denuncia: Motivazione dell'assenza della denuncia.
* Tavola 18 - Vittime per tipo di rapporto con l'autore della violenza.
 * Cartella Tavola  19 (Violenza assistita, vittime e figli):
    *  Tavola 19 - Vittime: Vittime per presenza di figli.
    *  Tavola 19 - Figli: Violenza assistita o subita da parte dei figli.
*  Tavola 20 - Violenza assistita. Tipo di reazione dei figli delle vittime.
*  Cartella Tavola 21: Numero di vittime secondo le variabili socioanagrafiche dell'autore:
   *  Tavola 21 - Genere: Vittime per genere degli autori.
   *  Tavola 21 - Età: Vittime per classe di età degli autori. 
   *  Tavola 21 - Condizione occupazionale: Vittime per condizione occupazionale degli autori.
   *  Tavola 21 - Titolo di studio: Vittime per titolo di studio degli autori.
   *  Tavola 21 - Stato civile: Vittime per stato civile degli autori.
   *  Tavola 21 - Nazionalità: Vittime per nazionalità degli autori

