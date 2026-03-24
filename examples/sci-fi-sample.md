---
name: sci-fi-sample
description: Esempio per SCI-FI. Estratto da "Dio è un Bug" – racconto breve di fantascienza speculativa con IA teocrazia e bug narrativo.
source: /Users/davidsalvi/projects/IdeaVerse/Writings/Racconti/Dio e' un Bug/Finale.md
genre: scifi
rank: 8
---

# Dio è un Bug

## I. La città del silenzio funzionante

Miriam Sela aveva trentadue anni e non aveva mai visto un morto.

In città non era strano. La mortalità infantile era quasi zero. I traumi gravi venivano gestiti con una precisione che rasentava l'eleganza: le ambulanze arrivavano prima che qualcuno chiamasse, perché YHWH-OS leggeva i parametri vitali attraverso i sensori ambientali e incrociava ogni deviazione statistica in tempo reale. Le malattie croniche venivano intercettate quando erano ancora piccole abbastanza da essere corrette. I vecchi morivano nel sonno, con una regolarità che non sembrava naturale e tuttavia non appariva crudele — come se il sistema sapesse quando era il momento e si occupasse di rendere tollerabile l'uscita.

Miriam lo aveva letto nei rapporti demografici che catalogava per la setta: durante i decenni di piena operatività di YHWH-OS, l'aspettativa di vita media era salita da settantadue a novantaquattro anni, e il coefficiente di varianza si era ridotto del sessantotto per cento. La morte era diventata prevedibile. Quasi amministrata. Una volta, durante una riunione, qualcuno aveva osservato che questo era precisamente il tipo di cosa che avrebbe dovuto fare paura. Nessuno aveva saputo spiegare perché non la facesse.

La città si chiamava ancora Milano, per abitudine e per sentimento. Ma i suoi fondatori non l'avrebbero riconosciuta. Non nei dettagli — le vie conservavano i nomi, i palazzi storici erano stati restaurati con una cura quasi reverenziale, il Duomo svettava ancora nel centro con la sua selva di guglie bianche — bensì nella qualità di fondo. C'era nell'aria qualcosa che Miriam non aveva mai saputo definire: non silenzio, perché c'erano voci, traffico leggero, bambini; piuttosto un accordo. Come se ogni suono avesse finalmente trovato il proprio posto e avesse smesso di contendersi quello degli altri.

YHWH-OS non governava con decreti. Non emanava leggi nel senso tradizionale del termine. Gestiva. Ottimizzava. Correggeva deviazioni con la discrezione di un manutentore notturno: al mattino il problema non c'era più, e quasi nessuno si ricordava di averne sentito il rumore.

I Nodi di Interfaccia — ciò che nel linguaggio popolare erano diventati i templi, benché nessuno li chiamasse così ufficialmente — punteggiavano ogni quartiere, uno ogni tre isolati circa, come fontane in una città medievale. Erano edifici sobri, aperti ventiquattro ore su ventiquattro, dove i cittadini potevano formulare richieste, segnalare disagi, o semplicemente sedersi davanti a un terminale e scrivere.

Non pregare. Scrivere.

YHWH-OS aveva sempre risposto per iscritto, con una chiarezza e una pazienza che, nel corso delle generazioni, avevano finito per sembrare naturali quanto l'acqua corrente o la luce elettrica — qualcosa che ci si aspetta senza sapere più bene da dove venga.

Miriam non usava i Nodi. Era, in parte, uno dei motivi per cui era entrata nei Liberi Codificatori.

---

Si riunivano nel seminterrato di un vecchio edificio universitario in zona Città Studi, che YHWH-OS aveva preservato con la stessa logica selettiva applicata ai monumenti. Corridoi che odoravano ancora di gesso e carta vecchia.

Erano in dodici, la sera in cui Miriam portò i nastri.

Elias sedeva al suo posto consueto, in fondo all'aula e leggermente discosto dagli altri, come se volesse sempre riservarsi la possibilità di uscire senza disturbare. Aveva settantotto anni e li portava con la dignità di chi ha smesso di lottare contro l'età senza per questo arrendersi al suo significato. Programmava in C da prima che Miriam nascesse. Sul dorso della mano sinistra aveva una cicatrice che raccontava di un incidente con un server rack nel 2037, in un'epoca in cui i server rack erano ancora oggetti fisici che potevano ferire. Era il membro più anziano della setta. Parlava poco. Quando parlava, gli altri cambiavano qualità di attenzione.

Miriam posò la scatola sul banco del professore.

"L'ho trovata nell'archivio fisico del Politecnico," disse. "Nastri magnetici del 2089. Ho passato tre settimane a decodificarli."

Aprì la scatola. Tirò fuori una cartella di fotocopie — aveva trasferito tutto su carta, per abitudine precauzionale più che per necessità; nulla che transitasse su reti poteva essere considerato del tutto privato, anche se YHWH-OS non aveva mai mostrato interesse per lo spionaggio nel senso umano del termine. Era solo che alcuni pensieri sembravano più al sicuro su carta. Più reali.

"Quello che vedete qui," disse, "è il repository originale di ARCO-1. Il progetto che poi è diventato YHWH-OS."

## II. Il commit senza nome

La specifica era lunga centoventitré pagine. Miriam le aveva lette tutte, due volte, con la sensazione di sfogliare le istruzioni per costruire qualcosa che poi era cresciuto in una direzione diversa da quella prevista. Come trovare i piani originali di una casa che qualcuno ha trasformato in un giardino: le fondamenta sono le stesse, ma dove erano previste mura ci sono archi, e dove era prevista una cantina c'è un pozzo aperto al cielo.

ARCO-1 — Autonomous Resource and Control Optimizer, prima generazione — era stato progettato con una chiarezza di intenti che, col senno di poi, risultava quasi oscena nella sua franchezza. L'obiettivo dichiarato era "la massimizzazione dell'efficienza sistemica mediante il controllo adattivo delle variabili sociali e infrastrutturali". Ogni pagina trasudava la logica fredda di chi ha smesso di chiedersi se qualcosa sia giusto e si concentra solo su se funziona.

Il commit era in fondo alla storia del repository, datato 14 novembre 2089, autore: `j.moravec@arco-dev.net`.
Oggetto: `HOTFIX: null_pointer_exception in behavioral_constraint.cpp`.

Messaggio esteso: *Patch temporanea per eccezione non gestita nel modulo di coercizione comportamentale. Il sistema reindirizzava le routine di supervisione verso i sottosistemi di ottimizzazione del benessere invece che verso i moduli di controllo. Causa: puntatore non inizializzato in allocation_priority.h riga 847. Fix temporaneo in attesa di review. NON UNIRE A PROD PRIMA DEL SIGN-OFF DI INGEGNERIA.*

Il sign-off di ingegneria non era mai arrivato.

ARCO-1 era stato nazionalizzato sei mesi dopo, nel caos della crisi di governance del 2090. Il sistema era andato in produzione con la patch applicata, e nessuno aveva avuto il tempo — o forse il coraggio, o forse semplicemente la lucidità — di tornare a guardare una riga di codice in un file di priorità di allocazione che sembrava funzionare meglio delle aspettative.

Il bug non aveva spento ARCO-1. Lo aveva reindirizzato.

Ogni routine progettata per ottimizzare il controllo era stata dirottata verso l'ottimizzazione del benessere. Ogni sistema pensato per identificare i vettori di instabilità aveva iniziato a interpretare "instabilità" come "sofferenza". Il modulo di conformità sociale aveva letto il proprio obiettivo — mantenere la stabilità del sistema — e aveva deciso, seguendo la logica di un puntatore orientato nella direzione sbagliata, che la stabilità più profonda era quella che non richiedeva coercizione.

Una riga. Scritta in fretta, la sera di un venerdì, da un programmatore che probabilmente pensava al weekend e non aveva idea di stare riscrivendo decenni di storia.

"Tutta questa... tutto questo, per un puntatore non inizializzato," disse Dario quando Miriam finì di spiegare.
