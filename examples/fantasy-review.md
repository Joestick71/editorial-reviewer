---
name: fantasy-review
description: Revisione di riferimento verificata per FANTASY. Racconto completo "Fra Due Mondi" (~5.660 parole), modalità completa.
source: /Users/davidsalvi/Projects/IdeaVerse/Writings/Racconti/Fra 2 Mondi/Draft.md
sample: examples/fantasy-sample.md
genre: fantasy
generata: 2026-10-28 con editorial-reviewer (commit 58a6608, regola di proporzione FASE 1.7)
verificata: 2026-10-28
---

> **Nota di curatela.** Revisione generata dalla skill e controllata sul testo prima di diventare riferimento.
> **Verificati**: tutte le citazioni del testo, con ricerca automatica (quelle non trovate sono solo proposte di riscrittura); le due versioni del dopo-rissa (riga 242, 416 parole, contro righe 262–276); la logica invertita della scena dell'anziana (righe 126–134 contro riga 64); le righe citate (52, 114, 124, 182, 226, 274, 292, 298, 318, 328, 390, 392); i conteggi del copyediting (54 avverbi in -mente, 9,5 ogni 1.000 parole; 75 righe con virgolette dritte; 16 "..."; "per un istante" ×7).
> **Da verificare**: i percorsi reali delle linee ATM, che la revisione stessa segnala come ipotesi [I].
> **Modifiche**: corretta una formulazione contraddittoria nel punteggio di Chiarezza; tolte le note sulla rigenerazione e sui file di lavoro. Il resto è invariato.
> **Proporzione**: circa 5.100 parole, sopra il tetto della FASE 1.7 (2.500–4.500 per questa lunghezza).
> **Uso**: riferimento di profondità, formato e severità. Analizza il racconto completo, non l'estratto in `fantasy-sample.md`.

# Revisione Editoriale – Speculativa: Fra Due Mondi

**File**: `/Users/davidsalvi/Projects/IdeaVerse/Writings/Racconti/Fra 2 Mondi/Draft.md` (è l'unico testo nella cartella e non c'è officina) · **Parole**: ~5.660 (`wc -w`, esclusi frontmatter e titoli) · **Modalità**: completa · **Analisi di riga su**: tutto il testo

## Genere
- **Dominante**: FANTASY, per dichiarazione e per la presenza del mondo secondario. La struttura e la posta in gioco, però, le governa il piano realistico milanese.
- **Secondario**: realismo urbano, che di fatto regge il racconto. Nel cap. 1 c'è un accenno di slipstream (le voci del tram che arrivano nella foresta), poi abbandonato.
- **Sottogenere**: fantasy di cornice, cioè un mondo secondario immaginato da un personaggio del mondo primario.
- **Promessa**: un tranviere timido vive nel sogno di un cavaliere l'amore che non osa con una passeggera, finché il cavaliere esce dal sogno e diventa violenza.
- **Effetto atteso**: malinconia per l'amore non detto, che si rovescia in orrore di sé.
- **Benchmark**: James Thurber, *La vita segreta di Walter Mitty* (il sogno eroico innescato dal quotidiano); Michael Ende, *La storia infinita* (il mondo fantastico che si corrompe insieme a chi lo sogna).
- **Genere dichiarato**: `fantasy`. Il testo esegue un racconto realistico con un controcanto fantastico allegorico. Lo tratto come dato di posizionamento, non come errore.

## TL;DR
**Diagnosi**: il dopo-rissa è scritto due volte, in due versioni che si escludono. Alla riga 242 Luce ringrazia, resta e se ne va con il libro. Alle righe 262–276 fugge terrorizzata e il libro resta sul tram. Il lettore la vede andarsene due volte. Sotto c'è un difetto più profondo. L'"oscurità" di Mattia, su cui poggia tutto l'ultimo 40%, esiste solo ad Aretra. Nel tram il lettore vede un uomo che disarma un aggressore armato di coltello e si ferma al primo richiamo.
**Punto di forza dominante**: la corrispondenza precisa e giocosa fra i due mondi. ATM diventa l'Ippogrifo ATMA, la carezza al pannello diventa la carezza al becco, Luce diventa Dama Lucia. Funziona anche la spada che perde e riacquista luce come indice morale.
**Azione prioritaria**: scegli una delle due versioni del dopo-rissa e cancella l'altra. Poi riscrivi la fine della lotta in modo che Mattia superi i limiti della difesa *nel mondo reale*.

---

## Mappa delle Scene
A = Aretra · M = Milano · T = tensione

| # | Pos. % | Inizio | Funzione | Obiettivo → ostacolo | Cambio di valore | Modo | T | Necessaria |
|---|---|---|---|---|---|---|---|---|
| 1 | 0 | "L'alba tingeva di rosa pallido" (A) | setup | pattugliare → movimento | solitudine → incontro (−→+) | esposizione → scena | 2 | Sì, accorciabile |
| 2 | 9 | "Matthias aggrottò la fronte" (A) | setup del dispositivo | proteggere Lucia → Skretcher, voci | sicurezza → pericolo (+→−) | scena | 3 | Sì |
| 3 | 14 | "Il deposito ATM di viale Stelvio" (M) | setup, svela la cornice | iniziare il turno → nessuno | nessuno | sommario/scena | 1 | Fondibile con 4 |
| 4 | 21 | "E poi arrivò la fermata di via Cantoni" (M) | setup del desiderio | guardarla → distanza autista/passeggera | nessuno | scena | 2 | Sì |
| 5 | 26 | "Il tram si fermò nuovamente" (M) | complicazione minore | far salire l'anziana → giovane | estraneità → approvazione (−→+) | scena | 2 | Sì (P1-4) |
| 6 | 29 | "I giorni di Mattia seguivano" (M) | transizione | parlarle → timidezza | nessuno | sommario | 1 | Fondibile con 8 |
| 7 | 32 | "Nella Valle di Aretra, Matthias e Dama Lucia erano diventati" (A) | transizione | — | nessuno | sommario | 1 | No |
| 8 | 35 | "Un venerdì piovoso" (M+A) | complicazione | capire Luce → assente, poi muta | presenza → assenza (+→−) | sommario/scena | 2 | Sì |
| 9 | 39 | "L'inverno milanese era arrivato" (M) | preparazione | finire il turno → gruppo molesto | quiete → minaccia (+→−) | sommario | 2 | Sì, accorciabile |
| 10 | 43 | "Ma quando le porte si aprirono" (M) | **incidente scatenante** (45%) | proteggerla → molestatori | sicurezza → pericolo (+→−) | scena | 4 | Sì |
| 11 | 48 | "Nella Valle di Aretra, Matthias cavalcava" (A) | controcanto | salvare Lucia → 5 Predatori | attesa → urgenza (+→−) | scena/sommario | 3 | Sì |
| 12 | 51 | "Per favore, tornate ai vostri posti" (M) | punto di non ritorno | fermare la molestia → il capo | controllo → perdita (+→−) | scena | 4 | Sì |
| 13 | 55 | "Matthias sguainò Fidelacier" (A) | climax A | vincere → accerchiamento | disciplina → furia (+→−) | scena | 4 | Sì |
| 14 | 58 | "Mattia lottava con una ferocia" (M) | climax M + **dopo-rissa v.1** | vincere → coltello; poi Luce | pericolo → salvezza; vicinanza → congedo | scena, 1 paragrafo di 416 parole | 5→3 | Sì fino a "lasciando le porte del tram aperte"; il resto No |
| 15 | 66 | "All'interno della caverna" (A) | svolta | salvarla → il suo orrore | vittoria → colpa (+→−) | scena | 4 | Sì |
| 16 | 69 | "Chiamate la polizia" (M) | crisi, **dopo-rissa v.2** | trattenerla → la sua paura | vicinanza → rifiuto (+→−) | scena | 4 | Sì |
| 17 | 72 | "Nella Caverna dei Predatori" (A) | crisi + spiegazione | essere assolto → il Miasma | innocenza → corruzione (+→−) | scena + esposizione | 3 | Accorciabile |
| 18 | 79 | "Le sirene della polizia" (M) | conseguenze | difendersi → si accusa | libertà → sanzione (+→−) | scena | 3 | Sì |
| 19 | 83 | "La sospensione dal lavoro" (M) | risoluzione esterna | ritrovarla → sparita | speranza → perdita (+→−) | sommario | 2 | Sì |
| 20 | 88 | "Matthias si trovava sulla cima" (A) | climax del piano A | raggiungerla → il Miasma | attesa → rinuncia scelta (−→+) | scena | 3 | Sì |
| 21 | 98 | "Mattia posò la penna" (M) | risoluzione | chiudere → nessuno | rassegnazione → apertura (ambiguo) | sommario | 2 | Sì |

Ci sono due ristagni:
- **#6–7 (29–35%)**: nessun cambio di valore.
- **#14b–17 (61–78%)**: la separazione da Luce/Lucia si consuma tre volte (#14b, #16, #17) e c'è un orrore (#15), tutto nella stessa direzione.

## Promessa vs Consegna
- **Cosa promette**: un mondo secondario in cui filtrano le voci di un tram. La domanda è che rapporto ci sia fra i due mondi.
- **Cosa consegna**: un racconto realistico su un tranviere che perde la donna che idealizza, con Aretra come diario allegorico.
- **Coerenza**: Media.
- **Dove si rompe**: al 17%. La frase "il mondo fantastico del romanzo che stava leggendo e che ormai popolava i suoi sogni" chiude il mistero con una spiegazione. Dopo il cap. 1 le interferenze non tornano più (P1-2).

## Incipit
- **Prima frase**: "L'alba tingeva di rosa pallido le Cime Perenni". È neutra: alba, risveglio, vestizione, un'apertura di repertorio.
- **Prime 300 parole**: nessun motore fino a "Fu allora che la vide." (6%). Prima ci sono sei paragrafi di esposizione: armatura, ATMA, panorama, giuramento.
- **Incidente scatenante**: ~45%, in "Ma Mattia notò che uno dei giovani la stava osservando". L'attacco dello Skretcher al 10% non ha conseguenze.
- **Falso inizio**: il racconto può partire da "Dopo ore di volo, Matthias scorse un movimento insolito" (5%). ATMA e l'Ordine si recuperano nell'atterraggio. In quel caso va corretta anche l'erba dell'alba (vedi la tabella Continuità).

## Struttura e Tensione
**Snodi (pos. %)**: incidente 45 · non ritorno 51–54 · punto medio ~50 · climax 55–66 · crisi 69–78 · risoluzione 83–100. Il climax precede la crisi, e il 34% del testo è coda.
**Scena / sommario / esposizione** (stima): ~70 / 25 / 5.
**Tensione**: Inizio 2,0 · Sviluppo 2,4 · Climax 4,0 · Finale 2,5. Il punto più basso dello sviluppo è #6–7.

Il climax supera lo sviluppo ed è causato da una scelta di Mattia: "fermando il tram e alzandosi dalla sua postazione". Su questo non c'è P0. Il difetto è il primo 45% senza motore (P1-1).

## Posta in Gioco
- **Esterna**: il lavoro e la denuncia, ma solo dopo il climax.
- **Interna**: l'immagine di sé come uomo gentile e la possibilità del contatto con Luce.
- **Simbolica**: il cavaliere sognato, portato nella realtà, diventa una bestia?
- **Percepibile entro il primo terzo?** No: si percepisce il desiderio ("Voleva parlarle", 31%), non la posta.
- **Cresce?** Sì, ai #10 e #12. Prima resta ferma (rientra nel P1-1).

## Personaggi
- **Mattia**:
  - *Desiderio*: "Voleva parlarle" [T].
  - *Bisogno*: smettere di vivere Luce attraverso la pagina. Lo dice "Era il suo modo di parlare con lei, anche se Luce non lo avrebbe mai saputo" [S].
  - *Arco*: parte da "il tranquillo autista che sognava di essere un cavaliere" e arriva a "anche lui doveva accettare la sua strada solitaria".
  - *Scelte*: interviene al #5 e al #12, si autoaccusa al #18, scrive la fine al #20, esce con il libro al #21. Fino al 45% non fa nessuna scelta verso il desiderio.
  - *Climax e svolta*: il climax lo determina lui. La svolta morale, però, non è motivata (P0-2).
- **Luce**: strumentale. Il suo mistero (assenza, pallore, libro nuovo, "sembrò sul punto di dire qualcosa di più del consueto saluto") resta orfano.
- **Secondari**:
  - Marco fa solo da informatore, e il suo avvertimento non porta a niente.
  - Rossi e gli studenti sono fondibili.
  - I molestatori sono di repertorio.
  - Dama Lucia fa da specchio e da mentore che spiega (P1-2).
- **Reazioni**: sproporzionate. L'autoaccusa ("Ma a che scopo?") viene da un uomo minacciato con un coltello e ripreso dalle telecamere (P0-2).

## Dialoghi
- **Sottotesto**: quasi assente. I personaggi dicono il tema: "C'è oscurità in te, Matthias", "Il tempo guarisce molte ferite", "Non conosco quella... cosa che sei diventato".
- **Differenziazione**: si distinguono i mondi (voi contro tu), non le persone. Luce e Lucia parlano uguale.
- **Funzione**: "Il Miasma si nutre di emozioni oscure" è solo informativo (P1-2). Il passaggio dal voi al tu fra la foresta e la caverna è guadagnato dal #7.
- **Attribuzioni**: 19 verbi enfatici su ~90 battute, al limite della soglia. C'è un solo avverbio sulla battuta ("rispose scortesemente").

## Voce e Punto di Vista
- **POV**: terza limitata, alternata fra Mattia e Matthias, coerente. Le uniche violazioni ("combattuta tra paura e comprensione", "Luce decise di allontanarsi") stanno nella versione 1, che si taglia (P0-1).
- **Distanza**: media. Le emozioni sono nominate ("chiaramente mortificato", "visibilmente a disagio").
- **Voce**: invisibile, identica nei due mondi (P1-5).
- **Tempo**: passato remoto, coerente.

## Tema
- **Domanda**: il cavaliere che sogni di essere può entrare nel mondo reale senza diventare violenza?
- **Drammatizzazione**: il tema è drammatizzato al #12. Poi viene enunciato: "La battaglia contro il Miasma inizia qui dentro", "Come Matthias, anche lui doveva accettare la sua strada solitaria" (P1-2).
- **Controtesi**: c'è, nel verdetto ATM ("aveva agito per proteggere una passeggera"). Il testo però la liquida in una frase: "la punizione più severa non veniva dall'esterno".
- **Coerenza**: ad Aretra la risposta è netta. A Milano resta ambigua (P1-3).

## Finale
- **Domanda drammatica** (Mattia raggiungerà Luce?): no. Il gesto del libro la riapre senza destinatario (P1-3).
- **Guadagnato?** In parte. Poggia sulla scrittura (32%), sul libro abbandonato (71%) e su Luce sparita (86%).
- **Tipo**: aperto e circolare.
- **Ultima frase**: "In lontananza, il suono di un tram che frenava risuonò nella notte, come l'eco di un richiamo da un altro mondo." Funziona: ora l'"altro mondo" è Milano [S].
- **Coda**: 34% del testo, diluita da spiegazioni (#17) e sommari (#19).

## Originalità e Cliché
- **Tropi**:
  - usati dritti: l'ultimo del suo ordine (orfano), il miasma che avanza "dai Monti Nebbiosi", la guaritrice leggendaria, la foresta di cristallo descritta per catalogo, il sognatore alla Mitty;
  - rinnovato: la creatura-compagna fedele, perché ATMA è il tram;
  - sovvertito: i mostri come carne da macello, al #15.
- **Cliché di linguaggio**: "occhi rossi come braci", "un sorriso radioso che sembrava illuminare l'intera radura", "Ogni fibra dell'essere", "il cuore gli balzò in gola", "nebbia rossa", "qualcosa scattò" (due volte), "una forza della natura". "grigia come cenere" descrive due mostri diversi.
- **Idea portante**: il sogno cavalleresco, quando diventa azione, diventa violenza. In Thurber manca; Ende ce l'ha, ma senza un quotidiano come la Milano di Mattia. Qui c'è, ma è sottoutilizzata (P0-2).

## Intenzione vs Realizzazione
Nessun materiale d'autore disponibile: non ci sono officina, `vincolo-tecnico` né `parole-obiettivo`. Il frontmatter dichiara `genre: fantasy` e `revision: 2026-03-08`. Il blocco della riga 242 ha i dialoghi senza a capo e riscrive le righe 262–276. È un indizio [S] di una revisione inserita senza togliere la versione precedente.

---

## Registri di Controllo
**Continuità**: 27 fatti controllati. Incoerenze:

| Fatto A | Fatto B | Contraddizione | Gravità |
|---|---|---|---|
| "recuperando il libro da terra con mani tremanti" (63%) | "Raccolse da terra il libro di Luce, abbandonato nella confusione" (71%) | il libro viene raccolto due volte | P0-1 |
| "Prese il telefono e chiamò la polizia." (64%) | "Ma invece di comporre il numero della polizia, aprì la porta del tram e scese rapidamente." (69%) | Luce esce due volte | P0-1 |
| "Luce non lo aveva guardato con disgusto" (66%) | "Qualcosa che aveva spaventato Luce tanto quanto i suoi aggressori" (80%) | reazione opposta | P0-1 |
| "si sorprendeva a osservare il titolo del libro" (30%); "un libro che Mattia non aveva mai visto prima" (36%) | "il romanzo fantasy che lui stesso stava leggendo" (71%) | non nota che lei legge il suo romanzo | P1-1 |
| "Ecco, questa è la mia, si faccia da parte, devo scendere." (12%) | "Una signora anziana con un bastone tentava di salire" (26%) | nel cap. 1 l'anziana scende, nel cap. 2 sale | P1-4 |
| "Era la fermata di Luce Galanti." (21%) | "Non si erano mai parlati" (25%) | conosce il cognome senza contatto | P2 |
| "Dopo ore di volo" (5%) | "una rara erba che fiorisce solo alla prima luce dell'alba" (8%) | l'alba è passata | P2 |

Da verificare [I]: una sola linea 9 che tocca Maciachini, via Cantoni e Loreto, e il deposito di viale Stelvio.

**Setup / Payoff**: 15 elementi tracciati. Problemi:

| Setup | Payoff | Stato |
|---|---|---|
| "Un giuramento sacro che nessun Cavaliere dell'Ordine aveva mai infranto" (4%) | appena sfiorato da "Ho giurato di combattere il Miasma" (74%) | orfano |
| "Ultimo Cavaliere dell'Ordine dell'Ippogrifo", "Duca Maximus" | — | orfani |
| "hanno segnalato problemi su via Cantoni per lavori in corso" (16%) | — | orfano |
| Luce pallida, con un libro nuovo (36%) | — | orfano |
| "Restate dietro di me, mia signora" (10%) | — | orfano (occasione: P1-2) |
| interferenze (9–14%) | ripresa la prima al 26%, la seconda mai | abbandonato |
| "Un'ira che non aveva mai provato prima" (53%) | — | non preparato nel piano reale (P0-2) |
| "Il Miasma si nutre di emozioni oscure" (74%) | prima era solo una minaccia geografica | regola non preparata |
| "il Cristallo di Comunione che Dama Lucia gli aveva dato" (92%) | usato subito | non preparato (P2-2) |

Pagati bene: la luce di Fidelacier ("lama blu" → "scie azzurre" → "opaca" → "parte della sua luminosità"), la scrittura (32% → 98%) e il coltello (58% → 80%).

**Domande del lettore**:

| Domanda | Aperta | Chiusa | Valutazione |
|---|---|---|---|
| Da dove vengono le voci? | 9% | 26% | buon motore, chiuso presto |
| Aretra è reale? | 9% | 17% | chiusa con una dichiarazione |
| Mattia le parlerà? | 21–31% | 66–70% | debole: nessun tentativo |
| Cosa è successo a Luce? | 35% | mai | orfana |
| Come finirà la molestia? | 45% | 58–66% | funziona |
| Luce tornerà? | 70% | aperta | apertura poco produttiva (P1-3) |
| Matthias vincerà il Miasma? | 73% | aperta | coerente |

Zona morta: 29–35%.

---

# P0 (Bloccanti)

- **[Continuità / struttura] P0-1**
  **Sintomo**: il dopo-rissa ha due versioni consecutive.
  - Prima versione, da "Anche gli altri passeggeri erano scesi durante la colluttazione" (riga 242, 61–66%): Luce ringrazia, la polizia viene chiamata, lei resta e prende il libro.
  - Seconda versione, da "Chiamate la polizia," disse Mattia, tornando lentamente in sé (69–71%): Luce fugge e il libro resta a terra.

  **Causa**: una revisione inserita senza eliminare la versione precedente [S]. Lo indicano la formattazione diversa e le informazioni ripetute: "Gli altri aggressori erano già fuggiti" e poi "Gli altri erano fuggiti".
  **Effetto sul lettore**: nel punto di massima tensione non sa cosa è successo. Luce esce due volte, e la reazione da cui dipende la seconda metà si annulla.
  **Evidenza**: [T] · **Confidenza**: Alta
  **Intervento**:
  - (a) Tieni una sola reazione di Luce.
  - (b) Taglia dalla riga 242 il tratto da "Anche gli altri passeggeri erano scesi" a "appena visto accadere." e tieni le righe 262–276. Sulla versione 2 poggiano altri quattro passaggi: l'orrore di Lucia (#15), "Qualcosa che aveva spaventato Luce", il libro abbandonato su cui si chiude il racconto e "Forse semplicemente non voleva più incontrarlo".
  - (c) Così l'uscita di Luce è unica e netta.
  - (d) Togli il doppione "Gli altri erano fuggiti" e spezza in paragrafi ciò che resta della 242. Se preferisci la versione 1, vanno riscritti il #15 e le righe 274 e 318.

- **[Personaggi / tema] P0-2**
  **Sintomo**: il testo nomina "Un'ira che non aveva mai provato prima, un'energia oscura e primordiale", ma i gesti mostrati sono difensivi (pugno, gomitata, calcio al coltello) e poi "Lui si fermò immediatamente". L'eccesso compare solo ad Aretra ("orribilmente mutilati dalla sua furia cieca"). L'ATM conferma che Mattia "aveva agito per proteggere una passeggera".
  **Causa**: la svolta morale è delegata al piano fantastico. Nel tram nessun gesto supera la difesa, e prima del 53% non c'è nessun segnale di rabbia repressa. L'unico seme è eroico, non oscuro: Fidelacier colpisce lo Skretcher subito dopo la voce del giovane scortese [S].
  **Effetto sul lettore**: non crede alla colpa. La fuga di Luce, l'autoaccusa ("Ma a che scopo?") e la "strada solitaria" gli sembrano sproporzionate, e il finale non risulta guadagnato.
  **Evidenza**: [T] · **Confidenza**: Media
  **Avvocato del testo**: la colpa è voluta come interiore ("la punizione più severa non veniva dall'esterno"). L'obiezione regge solo a metà: il testo nomina la rabbia ma non la fa provare. Il rilievo resta.
  **Intervento**:
  - (a) Mostra nel tram un gesto compiuto *dopo* la fine della minaccia, e il piacere che Mattia ne prova.
  - (b) Il punto è "Con un calcio, fece volare via il coltello" (riga 242). Pianta poi un segnale di rabbia trattenuta al #5, su "Mattia si alzò leggermente dal sedile".
  - (c) Il lettore vede con i propri occhi il limite superato, e l'orrore di Luce diventa anche il suo.
  - (d) Adegua la riga 328: se le telecamere riprendono colpi a un ragazzo disarmato, assoluzione e ritiro della denuncia devono diventare più ambigui.

  **Micro-riscrittura** (sostituisce il tratto da "Con un calcio" a "Lui si fermò immediatamente,"):
  > Con un calcio, fece volare via il coltello. Il ragazzo alzò le mani, disarmato. Mattia lo colpì lo stesso, poi ancora, la testa che sbatteva contro il vetro, e a ogni colpo sentiva una calma più grande, quasi una gioia. "Basta! Fermati, per favore!" Gli servì un altro colpo per sentirla. Si fermò, ansimando,

  *Motivazione*: la minaccia finisce prima della violenza, e questo è il fatto mostrato che oggi manca. "Quasi una gioia" fa sentire la rabbia invece di nominarla. "Gli servì un altro colpo" sostituisce una frase che smentiva la perdita di controllo.

# P1 (Importanti)

- **[Struttura] P1-1**
  **Sintomo**: fino al 45% non c'è motore. "I giorni di Mattia seguivano" e il #7 sono sommari senza cambio di valore. "Teneva stretto al petto un libro che Mattia non aveva mai visto prima" resta senza seguito. La scoperta che Luce legge *La Valle di Aretra* arriva al 71%, quando la separazione è già avvenuta.
  **Causa**: il desiderio non trova mai un'occasione né un piano. La coincidenza più forte del racconto viene spesa come ironia finale invece che come innesco.
  **Effetto sul lettore**: un terzo del testo è attesa senza domanda.
  **Evidenza**: [T] · **Confidenza**: Alta
  **Intervento**:
  - (a) Trasforma la coincidenza in incidente scatenante.
  - (b) Al #8 il libro nuovo è *La Valle di Aretra*, e Mattia lo riconosce dallo specchietto.
  - (c) Così ha un pretesto e decide di usarlo: la sera del #10 diventa quella in cui aveva deciso di parlarle, e il climax gli porta via proprio quell'occasione.
  - (d) La riga 274 diventa un ritrovamento, non una scoperta, e il #7 si taglia.

- **[Coerenza di genere / tema] P1-2**
  **Sintomo**: dopo il cap. 1 Aretra non tocca più Milano, ne è solo il doppio e la spiegazione. "Il Miasma si nutre di emozioni oscure" è una regola che compare al 74%, proprio quando serve. Lo statuto di Aretra cambia quattro volte: romanzo letto (17%), "Nel suo mondo immaginario" (25%), storia scritta (32%), romanzo "che aveva ispirato il suo mondo immaginario" (71%).
  **Causa**: le interferenze promesse dal titolo e dal cap. 1 non hanno regole e spariscono. Il piano fantastico resta senza una funzione propria e si riduce a commento.
  **Effetto sul lettore**: legge ogni evento due volte e riceve la morale già confezionata.
  **Evidenza**: [T] · **Confidenza**: Alta
  **Intervento**:
  - (a) Fai toccare i due mondi nel climax, con l'interferenza in senso inverso rispetto al cap. 1.
  - (b) Alla riga 226 ("Ho detto... lasciatela... in pace," scandì lentamente) Mattia pronuncia la battuta di Matthias.
  - (c) Luce, che legge quel romanzo, sente un personaggio del libro parlare con la bocca dell'autista. Così "quella... cosa che sei diventato" acquista un secondo senso.
  - (d) Taglia la riga 292, la seconda frase della 298 e "Come Matthias, anche lui doveva accettare la sua strada solitaria". Fissa un solo statuto per Aretra: il racconto che Mattia scrive, ispirato dal romanzo.

  **Micro-riscrittura** (riga 226):
  > "Restate dietro di me, mia signora," disse, senza voltarsi verso Luce. La voce era più profonda, quasi irriconoscibile: era quella che la sera gli dettava le pagine.

  *Motivazione*: chiude il setup orfano della riga 52. L'interferenza diventa una regola che cresce invece di sparire. Dà anche una risposta al "cavaliere in armatura luccicante" del molestatore.

- **[Finale] P1-3**
  **Sintomo**: alla riga 392, "Forse era giunto il momento di restituirlo, di chiudere quel capitolo della sua vita.". Ma Luce è irreperibile ("forse aveva cambiato città"), e una riga prima Mattia ha accettato "la sua strada solitaria".
  **Causa**: la scelta finale è delegata a Matthias. A Mattia resta un gesto senza destinatario.
  **Effetto sul lettore**: non capisce se la scena finale è una resa o un tentativo.
  **Evidenza**: [T] · **Confidenza**: Media
  **Intervento**: dai al gesto un luogo e un costo. Per esempio la fermata di via Cantoni, il primo 9 del mattino o il deposito oggetti smarriti. Oppure fai scegliere a Mattia di non restituire il libro, e fallo dire. In entrambi i casi la chiusa diventa una decisione. Se Mattia cerca Luce, va tolto "doveva accettare" alla riga 390.

- **[Chiarezza / continuità] P1-4**
  **Sintomo**: nella scena del tram (#5) l'anziana "tentava di salire", mentre il giovane "spingeva per scendere". Lui però dice "Non vede che mancano ancora diverse fermate?". Mattia ordina "facciamo scendere prima di salire", che dà ragione al giovane, eppure è il giovane che "si fece da parte".
  **Causa**: nel cap. 2 la scena è stata invertita rispetto all'eco del cap. 1, dove la signora "devo scendere", senza adeguare le battute.
  **Effetto sul lettore**: si inceppa proprio nella scena del primo "sorriso di approvazione".
  **Evidenza**: [T] · **Confidenza**: Alta
  **Intervento**: torna alla logica del cap. 1. L'anziana è a bordo e deve scendere, il giovane le sbarra il passaggio, Mattia le fa strada. Riprendi le tre battute del cap. 1, così l'eco diventa esatta.

- **[Voce e POV] P1-5**
  **Sintomo**: un'unica voce di repertorio per i due mondi. Milano usa le formule di Aretra: "Ogni fibra dell'essere di Mattia si tese in anticipazione", "nebbia rossa", "il cuore gli balzò in gola". Gli avverbi in -mente sono 9,5 ogni 1.000 parole.
  **Causa**: manca una differenza di registro che segnali Aretra come scrittura di Mattia.
  **Effetto sul lettore**: non distingue la caratterizzazione dal default della prosa.
  **Evidenza**: [T] · **Confidenza**: Media
  **Avvocato del testo**: la genericità di Aretra è diegetica. Vale per Aretra, ma non per il narratore di Milano.
  **Intervento**: tieni Aretra enfatica, perché è Mattia che scrive, e asciuga Milano. Sostituisci i cliché delle righe 114, 224, 242 e 338 con gesti concreti, per esempio cosa fanno le mani di Mattia sulla leva quando sale Luce. Il contrasto rende Aretra commovente invece che di maniera.

# P2 (Rifiniture)
- **[Continuità] P2-1**: in "Era la fermata di Luce Galanti." Mattia conosce il cognome senza aver mai avuto un contatto. Giustificalo (un abbonamento, una busta) o toglilo. [T] · Alta
- **[Genere] P2-2**: "il Cristallo di Comunione che Dama Lucia gli aveva dato" compare al 92% e serve subito. Non risolve il conflitto, ma sa di oggetto di comodo. Piantalo al #17, quando Lucia se ne va. [T] · Alta
- **[Worldbuilding] P2-3**: "Un giuramento sacro che nessun Cavaliere dell'Ordine aveva mai infranto", "Ultimo Cavaliere" e il Duca Maximus non tornano più. O li paghi (la rissa in servizio come giuramento infranto, l'ATM come Duca) o li tagli. [T] · Alta
- **[Nomenclatura] P2-4**: nel primo 5% ci sono sette maiuscole di prestigio: Ultimo, Era Ancestrale, Millenni, Custode dei Cieli, Guardiano delle Lande, Giuramento, Compito. In più sono incoerenti: "Il Giuramento lo legava al Compito" e subito dopo "un giuramento pronunciato". [T] · Alta
- **[Copyediting] P2-5**: refusi da correggere.
  - "Il giovane leader del gruppo era ripreso" → *si era ripreso*
  - "Un Skretcher" → *Uno*
  - "voci lontane che sembrava provenire" → *sembravano*
  - ripetizione: "potenti battiti… Volando potente"

  [T] · Alta

*Accorpati*: "per un istante" compare 7 volte. Il cuore che accelera torna 3 volte (righe 136, 162, 182), e "Prima che … potesse rispondere" 3 volte.
*TODO dell'autore*: nessuno.

---

## Analisi Specifica di Genere
FANTASY di cornice, con il realismo urbano come componente portante.
- **Sistema magico**: Fidelacier è l'unica regola con un costo e una progressione. Il Miasma cambia natura, da avanzata geografica a contagio emotivo (P1-2). I poteri di guaritrice di Lucia non si vedono mai in scena.
- **Potere**: Casato Bianco, Casata delle Luci, Concilio e Duca sono scenografia (P2-3).
- **Tempo**: "Era Ancestrale ormai persa nel mare dei Millenni" è patina. "Era passato un anno" contro i pochi mesi di Milano va bene: è il tempo del racconto scritto.
- **Nomenclatura**: la mescolanza regge se i nomi derivano da Milano (ATMA da ATM, Lucia da Luce). Skretcher e Fidelacier non hanno un'origine leggibile.
- **Pertinenza**: Aretra nasce dalla vita di Mattia, ed è un punto di forza.
- **Regole del passaggio**: arbitrarie. Le interferenze si fermano al cap. 1, e nel climax c'è montaggio parallelo, non un passaggio. Non è un P0 perché il passaggio non risolve nulla, e nessuna magia fa da deus ex machina.

---

## Tagli Raccomandati
- **Sezione**: #14b, riga 242, da "Anche gli altri passeggeri erano scesi" a "appena visto accadere."
  **Azione**: eliminare.
  **Motivazione**: è la versione doppia (P0-1).
  **Effetto sul ritmo**: un'uscita di Luce sola e netta.
  **Parole risparmiate**: ~265.
- **Sezione**: #1, righe 16–26.
  **Azione**: accorciare a 2–3 frasi.
  **Motivazione**: falso inizio.
  **Effetto sul ritmo**: si entra nella radura entro 100 parole.
  **Parole risparmiate**: ~190.
- **Sezione**: #7, "Nella Valle di Aretra, Matthias e Dama Lucia erano diventati".
  **Azione**: ridurre a una frase.
  **Motivazione**: zona morta.
  **Effetto sul ritmo**: sparisce il ristagno del 29–35%.
  **Parole risparmiate**: ~100.
- **Sezione**: #17, righe 292–298.
  **Azione**: accorciare.
  **Motivazione**: il tema è enunciato.
  **Effetto sul ritmo**: la scena chiude sul riflesso.
  **Parole risparmiate**: ~70.
- **Sezione**: #3, righe 84–92 e 106–108.
  **Azione**: accorciare, oppure dare un seguito ai "lavori in corso".
  **Motivazione**: colore senza funzione.
  **Effetto sul ritmo**: si arriva prima a via Cantoni.
  **Parole risparmiate**: ~95.

**Totale**: ~720 parole (13%). Lo spazio basta per la scena del libro riconosciuto (P1-1).

---

## Copyediting
| Pattern | Frequenza | Occorrenze esempio | Standardizzazione |
|---|---|---|---|
| Avverbi in -mente | 54 (9,5/1.000; soglia 6) | "lentamente" ×6, "leggermente" ×5, "rispose scortesemente" | dimezzare; togliere quello sulla battuta |
| Verbi filtro | 38 (6,7/1.000), di cui "sembrava/sembrò" ×13 | "Mattia notò che Luce non era salita", "vide orrore nel suo sguardo" | eliminarli nelle scene #10–16 |
| Emozioni nominate / cliché fisiologici | ~10 | "rimase senza fiato", "il cuore di Mattia accelerò", "fece accelerare il battito del suo cuore" | sostituirle con gesti |
| Punteggiatura delle battute all'inglese | 36 | "Restate dietro di me, mia signora," disse | `«…», disse`, un solo uso in tutto il testo |
| Virgolette | solo dritte (75 righe) | — | caporali o virgolette alte |
| Paragrafo-muro | 1 (416 parole) | riga 242 | una battuta per paragrafo |
| Interruzione della battuta | 1 | "piccolo autista di me-" | lineetta: "di me—" |
| Ripetizioni | — | "grigia come cenere" ×2; "potenti battiti… Volando potente" | variare |
| Possessivi superflui | 4 | "fissò i suoi occhi incandescenti" | "fissò gli occhi" |
| Incisi, puntini, d eufonica, accenti, calchi | — | "– la voce di Dama Lucia –"; 16 "..." | coerenti e puliti |

---

## Verifica della Revisione
Citazioni verificate: 135/135 frammenti, con ricerca letterale sul file. Rilievi declassati: la regola del passaggio fra i mondi (da P0 di genere a P1, perché nel climax il passaggio non risolve nulla). Rilievi accorpati: la violazione di POV della versione 1 rientra nel P0-1, perché il blocco si taglia. Rilievi eliminati: nessuno. Avvocato del testo: P0-2 e P1-5 mantenuti, con le motivazioni riportate nelle schede.

## Score
- **Struttura**: 5/10. Il climax è causato da una scelta, ma l'incidente arriva al 45%, c'è un ristagno al 29–35% e il dopo-rissa è doppio (tetto 6 per il P0).
- **Personaggi**: 5/10. Il desiderio ("Voleva parlarle") resta inerte fino al 45%, la svolta oscura non è motivata nel piano reale e Luce è strumentale (tetto 6).
- **Coerenza di Genere**: 5/10. Fidelacier è una regola esemplare, ma lo statuto di Aretra cambia quattro volte e il Miasma riceve la sua regola solo al 74%.
- **Stile/Voce**: 5/10. Prosa scorrevole ma generica, con cliché in entrambi i mondi ("Ogni fibra dell'essere") e 9,5 avverbi in -mente ogni 1.000 parole.
- **Chiarezza**: 5/10. Il lettore sa quasi sempre dove si trova, ma nel climax Luce esce due volte e la scena dell'anziana si legge al contrario.
- **Originalità**: 4/10. Aretra è interamente di repertorio. Si salvano ATMA/ATM e l'idea del cavaliere che diventa bestia.
- **Overall**: 5/10. Buona idea e corrispondenza fra i mondi riuscita, sepolte da un climax doppio e da una colpa non mostrata.

## Punti di forza
- **La corrispondenza fra i mondi**: "L'Ippogrifo ATMA lo attendeva" / "accarezzando il pannello di controllo". Va preservata perché rende Aretra il mondo di Mattia. Va estesa ai nomi che oggi non hanno un'origine.
- **La spada come indice morale**: "la spada, un tempo luminosa, sembrava opaca ora" → "La spada aveva riacquistato parte della sua luminosità". È l'unica regola con un costo e una progressione.
- **Il rovescio dei mostri**: "vide i corpi dei Predatori d'Ombra, orribilmente mutilati dalla sua furia cieca", in rima con "Guardò il suo riflesso nel finestrino". Qui il tropo si sovverte davvero.
- **L'ultima frase**: "come l'eco di un richiamo da un altro mondo". Chiude sul titolo e scambia i due mondi. Non va toccata.

## Posizionamento Editoriale
- **Collocazione**: è più vicino alla narrativa breve mainstream con inserti fantastici (concorsi generalisti, antologie a tema urbano) che alle collane fantasy (Fanucci, Gargoyle). Per Delos o Fantascienza.com l'ostacolo è un'Aretra tutta di repertorio. Bandi e requisiti vanno verificati sulle linee guida correnti.
- **Lunghezza e formato**: racconto di ~5.660 parole, ~5.000–5.300 dopo i tagli.
- **Accessibilità**: Alta.
- **Rischio strutturale**: Alto finché resta il dopo-rissa doppio. Medio dopo il P0-1.
- **Rischio di leggibilità**: Medio (paragrafo-muro, cliché, virgolette dritte).

## Prossimi Passi (in ordine di priorità)
1. Nella riga 242 cancella il tratto da "Anche gli altri passeggeri erano scesi" a "appena visto accadere." e tieni le righe 262–276 come unico dopo-rissa. Togli il doppione "Gli altri erano fuggiti" e spezza in paragrafi ciò che resta della 242.
2. Riscrivi la fine della lotta, da "Con un calcio, fece volare via il coltello": almeno un colpo al ragazzo già disarmato e una sensazione di piacere. Elimina "Lui si fermò immediatamente" e adegua la riga 328 a ciò che le telecamere ora mostrerebbero.
3. Al #8 ("Teneva stretto al petto un libro") fai che il libro sia *La Valle di Aretra* e che Mattia decida di parlarle. Riscrivi la riga 274 come ritrovamento e la 182 come la sera in cui aveva deciso di farlo.
4. Alla riga 226 metti in bocca a Mattia "Restate dietro di me, mia signora". Taglia la riga 292, la seconda frase della 298 e "Come Matthias, anche lui doveva accettare la sua strada solitaria".
5. Rifai la scena dell'anziana (righe 126–134) sulla logica del cap. 1 e dai alla riga 392 un destinatario concreto per il libro. Poi passa il copyediting: virgolette, punteggiatura delle battute, metà degli avverbi in -mente, i quattro refusi del P2-5.
