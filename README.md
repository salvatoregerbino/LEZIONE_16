# LEZIONE_16

# Progetto di Gruppo - Esercizio 3

**Manager:** Salvatore Gerbino (`salvatoregerbino`)
**Sviluppatore 1:** Luca Giorda (`Lucagg97`)
**Sviluppatore 2:** Francesco Mandarino (`theMandaa`)

## Descrizione del Progetto

Questo repository contiene il lavoro svolto per l'Esercizio 3, realizzato in collaborazione seguendo un flusso di lavoro Git specifico con divisione dei ruoli tra manager e sviluppatori.

## Flusso di Lavoro Git Utilizzato

Abbiamo adottato il seguente flusso di lavoro Git per la realizzazione di questo esercizio:

1.  **Creazione del Repository:** Il manager, Salvatore Gerbino, ha creato questo repository condiviso su GitHub.
2.  **Invito dei Collaboratori:** Il manager ha invitato Luca Giorda e Francesco Mandarino come collaboratori al repository.
3.  **Clonazione Locale:** Ogni sviluppatore ha clonato il repository sul proprio ambiente di lavoro locale.
4.  **Creazione di Branch:** Ogni sviluppatore ha creato un branch separato dal branch principale (`main`) per lavorare sulle proprie funzionalità o task. Esempi di branch creati:
    * `feature/header` (di Luca Giorda)
    * `feature/body` (di Francesco Mandarino)
5.  **Sviluppo sui Branch:** Gli sviluppatori hanno lavorato indipendentemente sui propri branch, apportando modifiche e creando commit locali.
6.  **Push dei Branch Remoti:** Una volta completata una parte significativa del lavoro, gli sviluppatori hanno caricato i propri branch sul repository remoto di GitHub (`origin`).
7.  **Merge dei Branch (Manager):** Il manager, Salvatore Gerbino, ha scaricato i branch remoti (`git fetch`), li ha esaminati (opzionalmente) e poi ha eseguito il merge dei branch dei singoli sviluppatori nel branch `main` locale (`git merge origin/<nome_branch>`).
9.  **Push del `main` Aggiornato (Manager):** Dopo aver completato i merge, il manager ha caricato il branch `main` aggiornato sul repository remoto (`git push origin main`).
10. **Aggiornamento del `main` Locale (Sviluppatori):** Ogni sviluppatore ha aggiornato il proprio branch `main` locale scaricando le modifiche dal repository remoto (`git pull origin main`).
11. **Aggiornamento dei Branch di Lavoro (Sviluppatori):** Se necessario, gli sviluppatori hanno aggiornato i propri branch di lavoro locali con le ultime modifiche del `main` (`git merge main`).

## Cosa Abbiamo Fatto

In questo progetto, abbiamo collaborato per raggiungere gli obiettivi dell'Esercizio 3. Le attività principali svolte includono (questo elenco può essere espanso con dettagli specifici del vostro progetto):

* [Descrizione concisa della funzionalità sviluppata da Luca Giorda sul branch `feature-login`].
* [Descrizione concisa della funzionalità sviluppata da Francesco Mandarino sul branch `feature-user-profile`].

## Conclusioni

Questo esercizio ci ha permesso di sperimentare un flusso di lavoro collaborativo con Git, comprendendo l'importanza della divisione dei ruoli, della creazione di branch isolati per lo sviluppo e del processo di merge per integrare il lavoro di tutti. Abbiamo imparato a gestire la sincronizzazione tra repository locali e remoti e, potenzialmente, a risolvere conflitti di merge.

---
