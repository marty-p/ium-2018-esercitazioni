# Domanda 1
Si supponga di dover valutare un sistema di risposta vocale interattiva (IVR), che permetta agli utenti di una compagnia telefonica mobile di ottenere informazioni sui servizi attivati e attivabili e sui relativi costi.  Lo studente descriva per sommi capi come organizzerebbe la sessione di valutazione, quali siano le metriche importanti da considerare e come eseguire l'analisi dei dati. 

# Risposta 1 (tutor)
1. Utenti poco pratici
2. Fare una comparazione fra questa applicazione e una versione precedente del sistema con un operatore
3. Un metodo di test è trovare l'efficienza tra un operatore e un assistente vocale (tramite tempo di completazione (completition rate))

    L'utente è riuscito a completare il task? dati binari
    
    In quanto tempo è riuscito a completare il task? dati numerici
    
    Altrimenti si divide la popolazione in due e alla prima metà prova l'operatore e la seconda l'assistente vocale (between subjects)
    
    Altrimenti la popolazione prova sia l'operatore e l'assistente vocale (within subjects) se è riuscito a completare il task in 1min
    
    Ci sono 4 risposte possibili. Altrimenti si da un questionario di tipo SuS

4. Se la differenza è minima, è un successo. Criterio di successo la % delle persone che sono riuscite a completare il task.

# Risposta 1 (personale)
L'obbiettivo è quello di ottenere feedback sui servizi attivati e attivabili e sui relativi costi.

Chiederei ai propri clienti di compilare dei questionari online il cui link è passato tramite sms.

Si tratta di sessioni di valutazione brevi da 2 minuti circa.
Gli verranno fatte solo 10 domande inerenti all'obbiettivo in cui bisogna specificare.
Per la risposta si avrà un range di score da 1 a 5 a forma di stella.

Per l'analisi dei dati, separo le domande positive con quelle complementari negative, dopodiché calcolo la loro media prestando attenzione ad invertire il risultato di quelle negative.

Se la differenza fra positive e complementari negative è minima, allora è un successo.

# Domanda 2
Si supponga di essere il gestore del sito web della Galleria degli Uffizi e di voler pubblicizzare un nuovo biglietto integrato per i più famosi monumenti della città di Firenze. Non essendo il contenuto principale da mostrare nella homepage del sito, vi rimane come opzione quella di mostrare l’avviso vicino nell’header della pagine, oppure nella barra laterale destra, accanto ai link agli altri siti dei musei.  Lo studente descriva per sommi capi come organizzerebbe una sessione di valutazione di supporto a questa decisione, quali siano le metriche importanti da considerare e come eseguire l'analisi dei dati. 

# Risposta 2 (tutor)
between subjects tramite a/b testing
ad un gruppo di utenti mostro l'homepage con il link nell'header, negli altri quelli nella barra laterale (75 utenti A, 75 utenti B)
calcolare il numero di click per test (30 click utenti A, 20 click utenti B)

# Risposta 2 (personale)

# Ci devono essere per ogni risposta
1. L'individualizzazione della categoria degli utenti
2. Quali test, compiti sono richiesti, perché, motivandoli
3. Le metriche da considerare con la loro rilevanza
4. Come condurre l'analisi dei dati con criteri di successo (se p < 0.05 allora "ho vinto"; oppure se entrambe le opzioni hanno la stessa importanza)
