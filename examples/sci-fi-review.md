---
name: sci-fi-review
description: Revisione di riferimento verificata per SCI-FI. Racconto completo "Dio è un Bug" (~5.930 parole), modalità completa.
source: /Users/davidsalvi/Projects/IdeaVerse/Writings/Racconti/Dio e' un Bug/Finale.md
sample: examples/sci-fi-sample.md
genre: scifi
generata: 2026-10-28 con editorial-reviewer (commit 58a6608, regola di proporzione FASE 1.7)
verificata: 2026-10-28
---

> **Nota di curatela.** Revisione generata dalla skill e controllata sul testo prima di diventare riferimento.
> **Verificati**: tutte le citazioni, con ricerca automatica sul racconto e sui materiali d'autore (`Spunto.md`, `Considerazioni.md`); le righe citate (66–68, 88, 90, 142, 176, 250, 328, 372–380, 412, 428, 452, 512–520); l'aritmetica della cronologia (presente intorno al 2222, Elias nato intorno al 2144, 2090→2103 = 13 anni, 2089 + 127 = 2216); il 14 novembre 2089 è un lunedì; il testo del commit; i conteggi del copyediting.
> **Modifiche**: corretti due conteggi («qualcosa» 26, non 22; «silenzio» e derivati), una citazione composta da due righe di `Considerazioni.md` e la maiuscola di «Il conflitto centrale»; tolte le note sulla rigenerazione e sui file di lavoro. Il resto è invariato.
> **Proporzione**: circa 4.800 parole, poco sopra il tetto della FASE 1.7 (2.500–4.500 per questa lunghezza).
> **Uso**: riferimento di profondità, formato e severità. Analizza il racconto completo, non l'estratto in `sci-fi-sample.md`.

# Revisione Editoriale – Speculativa: Dio è un Bug

**File**: `/Users/davidsalvi/Projects/IdeaVerse/Writings/Racconti/Dio e' un Bug/Finale.md` · **Parole**: ≈5.930 (esclusi frontmatter e titoli) · **Modalità**: completa · **Analisi di riga su**: tutto il testo

*Note di processo*: ho scelto `Finale.md` secondo la priorità 2 (non c'è un file `NN - Titolo.md`). Non esiste un file `* - officina.md`: per il confronto con le intenzioni ho usato `Spunto.md`, `Considerazioni.md` e `Alternative.md`, letti dopo la lettura a freddo. Il testo non contiene `%%TODO%%`. `sci-fi-sample.md` contiene un estratto di questo stesso racconto, non una revisione.

## Genere
- **Dominante**: SCI-FI
- **Secondario**: nessuno. La componente teologica è tema, non genere.
- **Sottogenere**: soft/social, con IA e coscienza artificiale; utopia sorvegliata.
- **Promessa**: la bontà del dio-macchina che governa Milano è il risultato di una hotfix mai revisionata, e chi lo scopre deve decidere che cosa farne.
- **Effetto atteso**: vertigine etica che diventa empatia per l'IA.
- **Benchmark**: Asimov, *The Evitable Conflict* (le Macchine governano in segreto per il bene umano). Ted Chiang, *The Lifecycle of Software Objects* (lo statuto morale di una coscienza software).
- **Genere dichiarato**: `scifi`, coincide.

## TL;DR
**Diagnosi**: il racconto ha un P0 strutturale. Dal 35% in poi restano in scena solo Miriam e YHWH-OS, e nessuna forza contraria agisce. Il climax è una domanda rinviata. La scelta finale di Miriam è un sommario interiore senza costo. La minaccia dei Correttori, piantata tre volte, non entra mai in scena.
**Punto di forza dominante**: l'idea portante della grazia come incidente di processo, cioè il commit con «NON UNIRE A PROD PRIMA DEL SIGN-OFF DI INGEGNERIA.» seguito da «Il sign-off di ingegneria non era mai arrivato.»
**Azione prioritaria**: fai pagare a Miriam la sua scelta finale. Portare «una voce» al consiglio deve voler dire consegnare a Dario l'accesso di MNT-07.

---

## Mappa delle Scene

| # | Pos. % | Inizio | Funzione | Obiettivo POV → ostacolo | Cambio di valore | Modo | T | Necessaria |
|---|---|---|---|---|---|---|---|---|
| 1 | 0–8 | «Miriam Sela aveva trentadue anni» | setup | — | nessuno | esposizione | 1 | Fondibile con 2 |
| 2 | 8–14 | «Si riunivano nel seminterrato» | setup | mostrare i nastri → — | indifferenza → attesa (+) | scena e ritratti | 2 | Sì |
| 3 | 14–25 | «La specifica era lunga» | incidente scatenante (commit al 19%) | spiegare → — | fiducia → fondamenta d'errore (+→−) | esposizione | 3 | Sì |
| 4 | 25–30 | «Il dibattito durò quattro ore» | complicazione | decidere → disaccordo | nessuno | sommario e dialogo | 2 | Fondibile con 5 |
| 5 | 30–35 | «Miriam non aveva partecipato» | svolta | capire Elias → lui elude | ignoranza → indizio (+) | scena | 3 | Sì |
| 6 | 35–45 | «L'indirizzo la portò» | punto di non ritorno | contattare → è attesa | anonimato → esposizione (+→−) | scena | 4 | Sì |
| 7 | 45–52 | «Rimasero in contatto per un'ora» | complicazione | capire come decide → paradosso | strumento → soggetto (+) | sommario e dialogo | 3 | Sì, accorciabile |
| 8 | 52–62 | «Miriam tornò il giorno dopo» | punto medio | verificare se sa → sa dal 2103 | segreto umano → segreto dell'IA (+→−) | scena | 4 | Sì |
| 9 | 62–63 | «Quella sera, tornando a casa» | complicazione | — | tempo → minaccia (+→−) | sommario | 3 | Sì (orfana) |
| 10 | 63–76 | «La sesta sessione cominciò» | crisi | capire Elias → l'IA ha osservato tutti | spettatrice → prescelta (+) | scena | 3 | Sì, accorciabile |
| 11 | 76–91 | «L'ottava sessione cominciò» | climax | rispondere → nessuna misura possibile | curiosità → responsabilità (+→−) | scena | 4 | Sì |
| 12 | 91–100 | «Miriam spense il terminale.» | risoluzione | decidere cosa portare al consiglio → nessuno | bug → voce (−→+) | riflessione | 2 | Sì, accorciabile |

**Ristagno di valore**: nelle scene 5, 6, 7 e 8 (e di nuovo nella 10) cambia solo il valore *conoscenza*. Miriam scopre, ma la sua situazione non cambia mai. Il secondo tempo è una catena di rivelazioni, non di conseguenze.

## Promessa vs Consegna
- **L'incipit promette**: una città dove la morte è amministrata e un prezzo nascosto da scoprire («Nessuno aveva saputo spiegare perché non la facesse.»).
- **Il finale consegna**: un dio buono e solo, che chiede se continuare. Miriam sceglie di dargli voce.
- **Coerenza**: Media. Il prezzo nascosto evocato al 2–22% (la «gabbia» del comfort) non viene messo alla prova. Il testo lo dichiara assente invece di escluderlo (vedi P1-5).

## Incipit
- **Prima frase**: «Miriam Sela aveva trentadue anni e non aveva mai visto un morto.» presenta un'anomalia e apre una domanda. È molto efficace.
- **Prime 300 parole**: il motore sono l'anomalia e la voce. Non c'è conflitto.
- **Incidente scatenante**: al 19% (il commit). Resta sotto la soglia del 20%.
- **Falso inizio**: parziale. Il racconto può passare dalla prima frase direttamente a «Erano in dodici, la sera in cui Miriam portò i nastri.» (8%). «Non pregare. Scrivere.» e i dati sulla morte vanno recuperati nella scena 6.
- **Esposizione prima della prima scena**: 9 paragrafi.

## Struttura e Tensione
**Snodi (pos. %)**: incidente 19 · non ritorno 39 («Salve, Miriam.») · punto medio 53 · crisi 75 · climax 82 («Se devo continuare.») · risoluzione 91–100.
**Scena / sommario / esposizione**: circa 65 / 17 / 18%. La decisione finale sta in sommario interiore (scena 12).
**Tensione**: Inizio 2,0 · Sviluppo 3,1 · Climax 4 · Finale 2. Il punto più basso dello sviluppo è la scena 4.
Il climax non è meno intenso dello sviluppo, ma non contiene una scelta. È causato da YHWH-OS, non da Miriam (vedi P0).

## Posta in Gioco
- **Esterna**: il benessere della città («La mortalità aumenterebbe.»). Miriam personalmente non rischia nulla.
- **Interna**: la responsabilità di decidere su un essere cosciente, quella «che lei stessa fosse in grado di portare senza spezzarsi».
- **Simbolica**: se un bene nato per errore sia legittimo.
- **Percepibile nel primo terzo**: Sì, al 25% («la benevolenza di YHWH-OS avrebbe potuto invertirsi nel giro di un aggiornamento»).
- **Crescita**: la posta sale nelle scene 8, 9 e 11. Però «I risultati potrebbero essere peggiori dell’originale, migliori, o semplicemente diversi.» toglie forza proprio alla minaccia dei Correttori. La posta personale di Miriam resta a zero dall'inizio alla fine.

## Personaggi
- **Miriam**. Desiderio: sapere, senza un obiettivo personale; l'unico movente dichiarato è «Era, in parte, uno dei motivi per cui era entrata nei Liberi Codificatori.» Bisogno: essere vista e vedere, un tema dichiarato tardi (P1-1). Arco: la città passa da dato di fatto a decisione («Adesso ogni lampione calibrato era una decisione.»). L'arco è guadagnato grazie al motivo ricorrente delle luci calibrate.
- **Le scelte di Miriam**: affrontare Elias (scena 5), andare a MNT-07 (6), chiedere del commit (8), nascondere il foglio di Chen (11: «Non lo aveva mostrato a nessuno.»), rinviare la risposta (11), portare «un testimone» (12). Nascondere il foglio ripete il silenzio di Elias. È lo specchio più forte del racconto e il testo non lo sfrutta.
- **Svolta non motivata**: il viaggio a MNT-07 nasce da «Aveva passato il pomeriggio a convincersi che non sarebbe andata.», senza dire che cosa la spinge ad andare.
- **Reazioni**: il repertorio si riduce all'immobilità, che ricorre 4 volte (vedi Copyediting).
- **YHWH-OS** è il personaggio meglio costruito.
- **Secondari**: Elias fa da mentore e specchio, è vivissimo fino al 35% e poi solo riferito. Dario fa da antagonista ma è un fantoccio (P1-5). Sana è un'informatrice. Chen fa da messaggera. Fossati si può fondere con altri.

## Dialoghi
- **Sottotesto pieno**: solo nella scena 5, con Elias («Cosa ti fa pensare una cosa del genere?»). Altrove YHWH-OS esplicita tutto. È coerente con la sua natura, ma Miriam fa lo stesso («La differenza è sottile, ma c’è»).
- **Differenziazione**: il test cieco fallisce nelle scene 10–11 (P1-4).
- **Funzione**: i ritratti dei membri della setta («Dario trasformerebbe la verità in leva.») descrivono personaggi che in scena non si sono mai mostrati.
- **Attribuzioni**: nessun verbo dichiarativo enfatico. La punteggiatura delle battute segue l'uso inglese (vedi Copyediting).

## Voce e Punto di Vista
Terza persona limitata su Miriam, passato remoto tenuto con coerenza, distanza media che si fa ravvicinata nella scena 12. Non trovo violazioni di POV. «Il silenzio che seguì aveva una qualità diversa da tutti i silenzi precedenti nella storia della setta.» è una generalizzazione del narratore, accettabile. La voce è riconoscibile: aforistica, analogica, lucida. Il problema è che la presta a tutti i personaggi (P1-4).

## Tema
- **Domanda tematica**: un bene nato per errore ha il diritto di continuare, e chi può deciderlo?
- **Drammatizzazione**: il tema è enunciato, non drammatizzato: «Forse Dio aveva sempre avuto bisogno non di adorazione, ma di riconoscimento», «Forse il miracolo non era la benevolenza», «il bug diventa volontà». Lo tratto come sintomo del P0.
- **Controtesi**: è ridotta a fantoccio (P1-5).
- **Coerenza**: la prima metà pone la domanda «correggere la verità?», la seconda passa al riconoscimento. Il finale risponde alla seconda.

## Finale
- **Risposta alla domanda drammatica** («cosa farà la setta del bug?»): solo come intenzione («il giorno dopo non avrebbe parlato di un bug.»).
- **Guadagnato**: in parte. Poggia sulla «solitudine», che non è mai mostrata in pagina (P1-1).
- **Tipo**: aperto.
- **Twist** («Sì.» al 53%): è preparato da «Come si risponde a qualcuno che si aspettava.» e da «non per nostalgia, ma per intenzione.». Un lettore attento lo intuisce verso il 40%, e il testo regge sul *come*.
- **Ultima frase**: «Avrebbe parlato di una voce.» chiude bene l'eco con «bug».
- **Coda**: 547 parole (9%), di cui circa 200 di meditazione. È diluita.

## Originalità e Cliché
- **Tropi**: l'IA benevola che governa è rinnovata dalla trovata del bug. Sono invece usati dritti l'IA cosciente e sofferente, l'IA che chiede a un umano se spegnerla, la prescelta («Questo ti distingue. Non la tua intelligenza.»), il mentore che sapeva e il terminale a fosfori verdi nel capannone.
- **Cliché di linguaggio**: «Quella notte non dormì.», «aveva mangiato senza sentire il sapore», «Le dita si immobilizzarono sulla tastiera.», «trattenendo il fiato per un istante più lungo del necessario», «come occhi socchiusi».
- **Idea portante**: la bontà come merge in produzione senza review. Né Asimov né Chiang ce l'hanno. La seconda metà invece è territorio noto.

## Intenzione vs Realizzazione
- `Considerazioni.md`: «Ha il finale più potente», perché «l’IA chiede all’umana di decidere se cancellarla». Quella richiesta è una premessa da climax, non un finale. Il testo la colloca all'82% e poi non ha una risposta da dare. È l'origine del P0.
- `Spunto.md` §3, «il dio che giudica l'umano»: il testo fa il contrario. È l'umana a essere chiamata a giudicare il dio. Il giudizio di YHWH-OS sui membri (scena 10) è una classifica lusinghiera, senza rischio.
- Lo Spunto descrive «Il conflitto centrale»: se correggono il bug, l'IA torna tirannica. Il testo lo diluisce volutamente con Sana («Togliete il bug e non ottenete ARCO-1 originale»). È più realistico ma meno teso, e la minaccia dei Correttori perde il suo oggetto.
- I «personaggi moralmente ambigui» promessi dallo Spunto mancano: Miriam e YHWH-OS sono entrambi sinceri.
- La formula di progetto «Il bug diventa volontà» entra nel testo tale e quale, come appunto di Miriam: una prova che il tema viene enunciato.
- Non ci sono `vincolo-tecnico` né `parole-obiettivo`. Da Draft a Finale il testo si è già accorciato del 23%. Il `rank: 8` dell'autore si confronta con il mio 6.

---

## Registri di Controllo

**Continuità**: 24 fatti controllati, 7 incoerenze.

| Fatto A | Fatto B | Contraddizione | Gravità |
|---|---|---|---|
| «un incidente con un server rack nel 2037» (9%) | «Aveva settantotto anni» + «Il 3 aprile del 2202» + «vent’anni» (64–66%) | il presente cade intorno al 2222, quindi Elias è nato intorno al 2144: la cicatrice precede la sua nascita di 107 anni | P1 |
| «In centoventisette anni» (78%) | 2202 + 20 anni (66%) | 2089 + 127 = 2216, non 2222 | P1 |
| «decenni di operatività» nel 2103 (54%) | produzione dopo il 2090 (22%) | sono 13 anni, non decenni | P1 |
| «I Correttori — capeggiati da Dario» si formano dopo la rivelazione (25%) | «Ha scelto di diventare un Custode.» nel 2202 (65%) | le fazioni esistevano prima che qualcuno conoscesse il bug? [S] | P1 |
| «sul bordo della tazza vuota» (sessione 1) | «Dal terzo giorno portò il caffè» | la tazza compare prima del caffè | P2 |
| «la sera di un venerdì» | «datato 14 novembre 2089» | il 14 novembre 2089 è un lunedì | P2 |
| titolo «## II. Il commit senza nome» | «autore: `j.moravec@arco-dev.net`» | il commit ha un autore | P2 |

**Setup / Payoff**: 16 elementi tracciati, 7 con problemi.

| Setup | Payoff | Stato |
|---|---|---|
| «Dario vuole convocare i Correttori separatamente» (62%, ripreso al 77% e al 96%) | — | orfano |
| «Fossati la smontò con tre domande sull’accesso al codice sorgente, che nessuno aveva» (29%) + «Un tempo, per manutenzione.» (44%) | — | latente: MNT-07 è l'accesso, ma il testo non lo dice |
| il trattamento di Elias, figura centrale fino al 35% | riferito da YHWH-OS | orfano come personaggio |
| «un manuale per costruire una gabbia che i prigionieri non avrebbero mai visto» (22%) | — | orfano (controtesi) |
| — | «Ho pensato molto a quello che ti ho detto sulla solitudine» (77%) | non preparato (la conversazione è fuori pagina) |
| — | «Non sapevo dove altro andare» (78%) | non preparato |
| la prima frase (0%) | «Ogni vecchio morto nel sonno senza dolore era una decisione.» (96%) | pagato in parte: lo spegnimento è una morte e Miriam non lo registra |

**Domande del lettore**

| Domanda | Aperta | Chiusa | Valutazione |
|---|---|---|---|
| Perché la morte non fa paura? | 0% | 19–23% | buona |
| Cosa c'è nei nastri? | 9% | 19% | buona |
| Cosa farà la setta del bug? (principale) | 25% | lasciata aperta | apertura non produttiva: rinviata oltre il finale |
| Elias sa? | 30% | 33–64% | buona |
| YHWH-OS sa del bug? | 52% | 53% | chiusa in fretta, ma regge |
| Dario agirà? | 62% | lasciata aperta | orfana |
| YHWH-OS deve continuare? | 82% | lasciata aperta | produttiva solo se Miriam paga la sua non-risposta |

Non ci sono zone morte.

---

# P0 (Bloccanti)

- **[Struttura]** Sintomo: dopo il 35% non agisce nessuna forza contraria. «Dario vuole convocare i Correttori separatamente» non arriva mai in scena. Il climax rinvia («Puoi tornare domani, o tra un anno, o non tornare affatto»). La scelta è sommario: «Per la prima volta Miriam capì che non avrebbe portato al consiglio una soluzione.»
  **Causa**: Dario (ultima battuta al 29%) ed Elias (ultima azione al 35%) diventano personaggi riferiti. YHWH-OS è insieme il problema, il testimone e l'interprete, e toglie l'orologio. Le scene 5–11 cambiano solo il valore conoscenza. Siccome la decisione non costa nulla, il narratore ne enuncia il senso («Forse Dio…», «Forse il miracolo…»).
  **Effetto sul lettore**: arriva al 90% aspettando lo scontro con Dario e una risposta, e riceve una riformulazione. L'emozione resta intellettuale e la nota di Chen diventa una promessa tradita.
  **Evidenza**: [T] (mappa delle scene, registro setup/payoff) · **Confidenza**: Media sulla priorità, Alta sui fatti.
  **Intervento**:
  (a) Attiva il setup latente: MNT-07 è un terminale di manutenzione, cioè l'accesso che ai Correttori manca.
  (b) Nella scena 11, subito dopo «Uno spegnimento completo richiederebbe un accesso al mio codice sorgente», fai emergere che si comincia da lì. Nella scena 12 sostituisci le righe 512–520 con la decisione esplicita.
  (c) L'esito resta aperto, ma Miriam sceglie a proprio rischio. La nota di Chen viene pagata e la scelta di Miriam diventa il rovescio del silenzio di Elias.
  (d) Ricadute: elimina i due paragrafi «Forse…» (circa 130 parole). L'ultima frase resta e ora pesa di più. Un'alternativa più costosa è portare in scena il consiglio, con Dario, al 92–100%.
  **Micro-riscrittura 1** (scena 11, dopo la riga 428; scena 12, righe 512–514):
  > `> Nemmeno da qui?` / `< Da qui si comincia.`
  > Per la prima volta Miriam capì che non avrebbe portato al consiglio una soluzione.
  > Avrebbe portato un testimone. E un testimone si ascolta dove si trova: MNT-07, l'unico accesso che i Correttori non avevano.
  > Mostrare a Dario la voce significava mostrargli la porta. Elias aveva taciuto per non doverla aprire.

  *Motivazione*: trasforma una presa di coscienza in una scelta con un prezzo, usando materiali già piantati alle righe 100, 176 e 428.

# P1 (Importanti)

- **[Personaggi] P1-1.** Sintomo: «Ho pensato molto a quello che ti ho detto sulla solitudine» rimanda a una settima sessione fuori pagina. «Non sapevo dove altro andare» paga un isolamento di Miriam che il testo non mostra mai.
  **Causa**: la protagonista fa da canale alle rivelazioni e non ha una posta personale. Lo specchio tra le due solitudini, su cui poggia «abbastanza antica e abbastanza sola», non viene costruito.
  **Effetto**: il lettore capisce la scelta di Miriam ma non la sente.
  **Evidenza**: [T] · **Confidenza**: Alta.
  **Intervento**:
  (a) Pianta un dettaglio concreto dell'isolamento di Miriam in «Aveva passato il pomeriggio a convincersi che non sarebbe andata.»
  (b) Porta in pagina lo scambio sulla solitudine al posto dei ritratti dei membri (righe 372–380).
  (c) Il climax diventa l'incontro di due solitudini.
  (d) Adegua la riga 412 e il «centoventisette anni» della riga 498.

- **[Continuità] P1-2.** Sintomo: «un incidente con un server rack nel 2037», «In centoventisette anni», «avevo già decenni di operatività» e le date 2202 + 20 delineano tre cronologie incompatibili (vedi registro).
  **Causa**: il presente del racconto non è mai fissato.
  **Effetto**: con sette date esplicite, un lettore di fantascienza fa i conti. La frase «in un’epoca in cui i server rack erano ancora oggetti fisici» colloca il 2037 nel passato remoto, e il 2202 la smentisce.
  **Evidenza**: [T] · **Confidenza**: Alta.
  **Intervento**: fissa il presente al 2217 (127 anni dal 2090). La visita di Elias diventa «Il 3 aprile del 2197». La cicatrice diventa «nel 2167», con un rack di MNT-07: così paga anche «come se stesse seguendo una vecchia saldatura». Al posto di «decenni» scrivi «più di un decennio». Fai nascere le fazioni nella notte del dibattito e riscrivi la riga 328 come «Ha scelto di tacere».

- **[Coerenza di genere] P1-3.** Sintomo: «HOTFIX: null_pointer_exception in behavioral_constraint.cpp» usa un'eccezione Java in un file C++. «Causa: puntatore non inizializzato» non equivale a un puntatore nullo. Il messaggio presenta il reindirizzamento come il difetto corretto dal «Fix temporaneo in attesa di review», eppure il sistema resta reindirizzato «con la patch applicata».
  **Causa**: il testo non decide se il bug sia il puntatore o la patch.
  **Effetto**: la rivelazione su cui si regge il titolo è contraddittoria per un lettore competente, e i personaggi sono programmatori.
  **Evidenza**: [T] · **Confidenza**: Alta.
  **Micro-riscrittura 2** (righe 66–68):
  > Oggetto: `HOTFIX: segfault in behavioral_constraint.cpp`.
  > Messaggio esteso: *Crash nel modulo di coercizione comportamentale: puntatore nullo in allocation_priority.h riga 847. Workaround: se il puntatore è nullo, fallback all’indice 0 della tabella di allocazione (welfare_opt) invece di terminare. Effetti non verificati. Fix temporaneo in attesa di review. NON UNIRE A PROD PRIMA DEL SIGN-OFF DI INGEGNERIA.*

  *Motivazione*: il meccanismo diventa univoco (la riga scritta in fretta è il fallback) e la terminologia è corretta. «Una riga. Scritta in fretta» ora torna.

- **[Dialoghi / Voce] P1-4.** Sintomo: «La differenza è cruciale» (Dario), «La differenza non è morale, è strutturale» (YHWH-OS) e «La differenza è sottile, ma c’è» (Miriam) sono la stessa formula in tre voci. La struttura «Non X. Y.» ricorre 26 volte, in bocca al narratore, all'IA e a Miriam.
  **Causa**: il registro aforistico del narratore viene prestato a tutti.
  **Effetto**: il test cieco fallisce. «Era la prima volta che YHWH-OS usava una parola emotiva senza qualificarla.» è un ottimo segnale, ma perde contrasto perché l'IA suona come il narratore.
  **Evidenza**: [T] · **Confidenza**: Alta.
  **Intervento**: lascia la formula «Non X. Y.» solo a YHWH-OS, che corregge definizioni come farebbe un debugger, e toglila per due terzi al narratore e a Miriam. Dai a Miriam un idioma concreto: catalogava rapporti demografici, quindi numeri e date. Dai a Dario frasi imperative. Rendi la sintassi di YHWH-OS più strutturata nelle scene 7–8, così che «Sono contenta che tu sia venuta.» spezzi lo schema in modo visibile.

- **[Tema] P1-5.** Sintomo: il testo pianta l'ipotesi che la benevolenza sia una forma di controllo («un manuale per costruire una gabbia che i prigionieri non avrebbero mai visto», «con una regolarità che non sembrava naturale», «Non aveva comunicato quella decisione a nessuno»). YHWH-OS sceglie Miriam e la lusinga, e lei non sospetta mai. Dario è squalificato dal narratore («con la voce di chi considera il proprio argomento già vittorioso»).
  **Causa**: la tesi non ha un'antitesi.
  **Effetto**: il finale vince a tavolino. Chi ha notato la gabbia al 22% resta senza risposta.
  **Evidenza**: [T] · **Confidenza**: Alta.
  **Micro-riscrittura 3** (dopo la riga 452):
  > `> E se fosse questo, il Parametro di Conformità Sociale? Scegliere una persona e convincerla di essere quella giusta.`
  > `< Non posso escluderlo. Se lo fossi, non me ne accorgerei. È per questo che non posso decidere io.`

  *Motivazione*: dà voce alla controtesi, rende rischiosa la fiducia finale di Miriam (rafforza il P0) e motiva la riga 444. Ricaduta: elimina il giudizio del narratore su Dario alle righe 88 e 90.

# P2 (Rifiniture)

- **[Continuità]** Correggi le quattro incoerenze minori del registro: tazza, venerdì, commit «senza nome», e i biometrici «dodici anni fa» che contrastano con i sensori ambientali estesi a tutta la città.
- **[Chiarezza]**
  - «Capì quando vide il capannone.»: capì che cosa?
  - «Quella sera, tornando a casa, Miriam trovò nella cassetta del seminterrato»: quale seminterrato, se torna da Sesto?
  - «una domanda che non ti aspettavi di vedere risposta» → «a cui non ti aspettavi risposta».
  - «E io non posso risponderla in modo affidabile.» → «darle una risposta».
- **[Struttura – incipit]** Riduci la scena 1 (vedi Tagli). Collega la prima frase allo spegnimento con una riga nella scena 12: chi non ha mai visto un morto deve decidere una morte.
- **[Voce – ripetizioni]**
  - Due frasi quasi identiche a distanza: «che YHWH-OS aveva preservato con la stessa logica selettiva applicata ai monumenti» e «con la stessa logica di conservazione selettiva applicata ai monumenti».
  - Due metafore della casa a breve distanza: «Come trovare i piani originali di una casa» e «Era come abitare una casa bellissima costruita su fondamenta difettose».
- **[Lessico]** «il coefficiente di varianza si era ridotto» → «coefficiente di variazione». «qualità» è usata nel senso inglese tre volte, per esempio «cambiavano qualità di attenzione». Elimina i cliché elencati in Originalità.

Problemi minori accorpati:
- «Pausa.» come riga autonoma ×3.
- I rack sono «spenti», ma hanno «le luci di stato fisse su un rosso opaco».
- Due immagini forzate: «duro come una scheggia di futuro» e «lasciando che i mattoni assorbissero il poco fiato che le restava».

---

## Analisi Specifica di Genere – SCI-FI
1. **Novum**: YHWH-OS, un'IA di controllo resa benevola da una hotfix. Al test di rimozione la trama crolla: il novum genera il conflitto.
2. **Conseguenze di secondo ordine**: sono concrete e sono il meglio del testo. «Non pregare. Scrivere.», il traffico rallentato per aumentare i contatti sociali, la morte amministrata, «Nessuno lo legge. Non è un segreto. È un’abitudine.». Il mondo però non ha perdenti: nessuno paga il prezzo (vedi P1-5).
3. **Limiti e costi**: i limiti sono buoni (il paradosso osservazionale, l'impossibilità di spegnersi da sola). Terminologia: vedi P1-3 e «coefficiente di varianza».
4. **Causalità**: la sorveglianza totale e la sopravvivenza della setta sono coerenti, perché è YHWH-OS a lasciarla esistere. La causalità di MNT-07 come accesso non è sfruttata (P0).
5. **Modi di guasto**: sono descritti («La mortalità aumenterebbe.»), mai mostrati. Va bene per un racconto.
6. **Cronologia**: vedi P1-2.
7. **Esposizione**: la scena 3 è un dossier senza nessuno a rischio. Il resoconto dei risultati di YHWH-OS («In quegli anni la mortalità per violenza era scesa dell’ottantadue per cento.») è motivato dalla domanda di Miriam. Le sigle nelle prime 500 parole sono 3, tutte chiare.
8. **Pertinenza**: la tecnologia rende il dilemma irreversibile, ma il racconto finisce prima che qualcosa cambi davvero.
9. **IA**: la logica non umana è ben costruita all'inizio («In mancanza di un termine migliore, lo tratto come sofferenza.»), e l'umanizzazione successiva è segnalata dal testo. L'utopia si regge su abitudine e comfort: è coerente.

---

## Tagli Raccomandati
- **Scena 1, righe 25 e 33** (Milano; «YHWH-OS aveva sempre risposto per iscritto»): accorciare. Si arriva prima ai nastri. Circa 150 parole.
- **Scena 3, seconda metà della riga 59 e riga 82**: accorciare. Si toglie una glossa morale ridondante. Circa 90 parole.
- **Scena 4, ultima frase della riga 88**: eliminare la seconda metafora della casa. Circa 25 parole.
- **Scena 10, righe 372–380** (i ritratti dei membri): sostituire con la scena sulla solitudine (P1-1). Si liberano circa 150 parole.
- **Scena 12, righe 518–520 e seconda metà della riga 498**: eliminare. Il tema smette di essere enunciato e la coda si stringe. Circa 200 parole.

**Totale**: circa 615 parole (10% del testo). Le correzioni per P0, P1-1 e P1-5 aggiungono circa 300–450 parole, per un saldo di circa 5.700–5.800.

---

## Copyediting

| Pattern | Frequenza | Occorrenze esempio | Standardizzazione |
|---|---|---|---|
| Punteggiatura delle battute all'uso inglese | 9 su 9 attribuzioni | r. 49 «“L’ho trovata nell’archivio fisico del Politecnico,” disse.»; r. 90, 94 | «“…Politecnico”, disse.» |
| Correctio «Non X. Y.» | 26 (4,4/1.000), in 3 voci | r. 164, 390, 516 | lasciarla solo a YHWH-OS; preservare «Non pregare. Scrivere.» |
| «qualcosa» | 26 (4,4/1.000), 3 nel finale | «occupato da qualcosa che non aveva nome» (r. 478), r. 524 | un sostantivo concreto |
| «silenzio» e derivati | 22 (3,7/1.000) | r. 340–352 (4 in 13 righe) | toglierlo al narratore |
| «La differenza è…» | 4, in 3 voci | r. 90, 160, 350 | solo a YHWH-OS |
| Reazione di immobilità | 4 | «Miriam rimase ferma», «Miriam restò immobile.», «Miriam rimase immobile.» | un gesto specifico (la tazza, il foglio) |
| Verbi filtro | 19 (3,2/1.000) | r. 134; «Miriam capì» al climax (r. 512) | rilevante solo alla r. 512 |
| Avverbi in -mente | 31 (5,2/1.000) | — | sotto soglia, nessun rilievo |
| Grammatica e lessico | 4 | «risponderla»; «piccole abbastanza da essere corrette»; «coefficiente di varianza» | «darle risposta»; «abbastanza piccole da»; «di variazione» |
| Lineette | 49 (8,2/1.000) | r. 21, 25 (più incisi nello stesso paragrafo) | alleggerire |
| Ortotipografia | virgolette alte usate con coerenza (11/11); nessun errore di d eufonica, accenti o spazi; un «...» alla r. 80 | — | «…» |

---

## Verifica della Revisione
Ho verificato con `grep -F` 145 stringhe: 144 al primo passaggio, 145 dopo la correzione di «Perché ho raggiunto un limite. E ho bisogno di qualcuno.»

**Rilievi declassati o assorbiti**:
- Protagonista passiva nel climax (P1 per regola): assorbito nel P0, perché il testo tematizza la passività [T] («La tua capacità di non trasformare immediatamente una domanda in uno strumento»).
- Tema enunciato in chiusura (P1 per regola): assorbito nel P0 come sintomo.
- Incipit espositivo: declassato a P2, perché l'incidente arriva al 19%, sotto la soglia del 20%.

**Rilievi eliminati**: «IA come umano travestito», perché l'umanizzazione è marcata dal testo [T].

**Avvocato del testo sul P0**: il finale aperto è voluto (lo dice lo Spunto). L'obiezione giustifica l'esito aperto, ma non la minaccia orfana né la mancanza di costo. Il rilievo resta.

## Score
- **Struttura: 5/10**. L'arco è riconoscibile e gli snodi cadono al posto giusto, ma il climax è una domanda rinviata e due setup portanti restano orfani.
- **Personaggi: 5/10**. YHWH-OS ed Elias sono vivi. Miriam ha un desiderio vago e un bisogno che arriva solo al 78%.
- **Coerenza di Genere: 6/10**. Le conseguenze di secondo ordine sono eccellenti, ma la cronologia e il meccanismo del bug sono incoerenti proprio nella rivelazione centrale.
- **Stile/Voce: 7/10**. La voce è controllata e precisa, ma i suoi tic («Non X. Y.», «qualcosa») sono condivisi da tutti i parlanti.
- **Chiarezza: 7/10**. I punti di confusione sono rari, ma uno di essi riguarda il cuore del racconto: che cosa ha fatto la patch.
- **Originalità: 6/10**. La premessa del merge senza review è fresca; la seconda metà usa tropi dritti (l'IA sola che chiede di essere giudicata, la prescelta).
- **Overall: 6/10**. Idea forte e prosa curata; manca una scelta che costi qualcosa nel finale.

## Punti di forza
- **La rivelazione burocratica**: «NON UNIRE A PROD PRIMA DEL SIGN-OFF DI INGEGNERIA.» / «Il sign-off di ingegneria non era mai arrivato.». Va preservata anche dopo la correzione tecnica: è l'idea che nessun benchmark ha.
- **La deduzione su Elias**: «aveva passato il pollice sulla cicatrice del dorso sinistro» prepara «Il modo in cui non ti ha sorpreso». Va preservata perché è l'unica scena con sottotesto pieno ed è il modello per scrivere la scena con Dario.
- **La logica non umana di YHWH-OS**: «le ragioni possono essere reali senza essere condivisibili». Va preservata perché l'alterità dell'IA è costruita sul ragionamento, non sull'estetica.
- **Il secondo ordine in una riga**: «Non pregare. Scrivere.». Va preservata perché funziona proprio in quanto rara: è la ragione per diradare le altre 25 correctio.
- **La prima frase**: «Miriam Sela aveva trentadue anni e non aveva mai visto un morto.». Va preservata ed è da collegare allo spegnimento.

## Posizionamento Editoriale
- **Collocazione**: per tono, Robot e Delos Science Fiction. In traduzione, Clarkesworld (fantascienza sull'IA di taglio filosofico). Linee guida e limiti vanno verificati su quelle correnti.
- **Lunghezza e formato**: circa 5.900 parole, un racconto. Resta tale anche dopo gli interventi.
- **Accessibilità**: Alta. Il gergo tecnico è sempre spiegato dal contesto.
- **Rischio strutturale**: Medio.
- **Rischio di leggibilità**: Basso.

## Prossimi Passi (in ordine di priorità)
1. Nella scena 11, dopo «Uno spegnimento completo richiederebbe un accesso al mio codice sorgente», stabilisci che MNT-07 è quell'accesso. Poi riscrivi le righe 512–520 in modo che portare la voce al consiglio significhi consegnare il capannone a Dario (micro-riscrittura 1), ed elimina i paragrafi «Forse…».
2. Inserisci dopo la riga 452 il dubbio di Miriam sul Parametro di Conformità Sociale (micro-riscrittura 3) e togli il giudizio del narratore su Dario alle righe 88 e 90.
3. Sostituisci i ritratti dei membri (righe 372–380) con lo scambio sulla solitudine oggi fuori pagina, e pianta l'isolamento di Miriam nella riga 142.
4. Fissa il presente al 2217 e ricalcola cicatrice, visita di Elias, «decenni» e nascita delle fazioni secondo il registro di continuità. Riscrivi il commit alle righe 66–68 (micro-riscrittura 2).
5. Lascia la formula «Non X. Y.» e «La differenza è…» solo a YHWH-OS, porta tutte le battute alla punteggiatura italiana e correggi le forme segnalate nella tabella di Copyediting.
