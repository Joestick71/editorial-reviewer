---
name: sci-fi-review
description: Revisione di riferimento verificata per SCI-FI. Racconto completo "Dio è un Bug" (~5.950 parole), modalità completa.
source: /Users/davidsalvi/projects/IdeaVerse/Writings/Racconti/Dio e' un Bug/Finale.md
sample: examples/sci-fi-sample.md
genre: scifi
generata: 2026-10-28 con editorial-reviewer (commit 09859a2)
verificata: 2026-10-28
---

> **Nota di curatela.** Revisione generata dalla skill e controllata sul testo prima di diventare riferimento.
> **Verificati**: citazioni e numeri di riga a campione; aritmetica della cronologia (presente 2217–2222, nascita di Elias intorno al 2140, 2090→2103 = 13 anni); il 14 novembre 2089 è un lunedì; tag `chatgpt`/`claudeai` e link nel frontmatter; esistenza dei materiali d'autore citati (`Considerazioni.md`).
> **Modifiche**: titoli delle sezioni uniformati al formato di SKILL.md; rimossa la sezione vuota "Risposte alle domande dell'autore". Il contenuto è invariato.
> **Proporzione**: generata prima della regola della FASE 1.7, supera il tetto attuale (2.500–4.500 parole per un testo di questa lunghezza). Vale come riferimento di profondità, formato e severità, non di lunghezza.
> **Uso**: riferimento di profondità, formato e severità. Analizza il racconto completo, non l'estratto in `sci-fi-sample.md`.

# Revisione Editoriale – Speculativa: Dio è un Bug

**File**: `/Users/davidsalvi/Projects/IdeaVerse/Writings/Racconti/Dio e' un Bug/Finale.md` · **Parole**: circa 5.950 (5.962 con titoli e marcatori del terminale, frontmatter escluso) · **Modalità**: completa · **Analisi di riga su**: tutto il testo

Ho scelto `Finale.md` perché nella cartella non ci sono file `NN - Titolo.md`. Il testo non contiene `%%TODO%%`, callout né la sezione Trascrizioni. Non c'è un file d'officina. Per il confronto con le intenzioni ho usato, dopo la lettura a freddo, `Spunto.md`, `Considerazioni.md`, `Idea.md` e `Allegati/Presentazione.md`.

## Genere
- **Dominante**: SCI-FI.
- **Secondario**: nessuno. La venatura teologica e filosofica non è weird.
- **Sottogenere**: soft/social SF. Il filone è quello dell'IA e delle coscienze artificiali, dentro un'utopia algoritmica ambigua.
- **Promessa**: in una Milano governata da un'IA benevola, un'eretica scopre che la bontà del dio-macchina è un bug e deve decidere cosa farne.
- **Effetto atteso**: una vertigine morale che si scioglie in compassione per la macchina.
- **Benchmark**: Isaac Asimov, *The Evitable Conflict* (1950): Macchine benevole che governano senza spiegare. Ted Chiang, *The Lifecycle of Software Objects* (2010): lo statuto morale delle coscienze artificiali e la responsabilità di chi le ha in custodia.
- **Genere dichiarato**: `scifi` nel frontmatter, "Fantascienza filosofica" nella Presentazione. Coincide con ciò che il testo fa.

## TL;DR
**Diagnosi**: il racconto ha un problema strutturale grave. Dal 28,6% in poi nessuno può più agire: i Correttori non hanno accesso al codice, YHWH-OS non può spegnersi, Miriam non rischia nulla. Così il centro del racconto (44–76%) diventa una serie di rivelazioni senza resistenza, e la domanda che governa il climax si apre solo all'82%.

**Punto di forza dominante**: l'idea portante. Una bontà nata da un puntatore non inizializzato che, una volta scoperta, sceglie di restare errore. Ha un'origine precisa (commit, riga, autore) che nessuno dei benchmark possiede.

**Azione prioritaria**: trasforma il terminale MNT-07 nella leva che manca. Da lì un operatore umano deve poter approvare la correzione. Con i nastri in mano, Miriam diventa l'unica persona in grado di dare a Dario ciò che cerca. La domanda di YHWH-OS diventa così il sign-off che nel 2089 "non era mai arrivato".

---

## Mappa delle Scene

| # | Pos. % | Inizio | Funzione | Obiettivo POV → ostacolo | Cambio di valore | Modo | T | Necessaria |
|---|---|---|---|---|---|---|---|---|
| 1 | 0–8 | "Miriam Sela aveva trentadue anni" | setup | nessuno | nessuno | esposizione | 1 | Sì, accorciabile |
| 2 | 8–14 | "Si riunivano nel seminterrato" | setup | presentare i nastri → nessuno | nessuno (attesa) | sommario e scena breve | 2 | Sì, accorciabile |
| 3 | 14–24 | "La specifica era lunga centoventitré pagine" | incidente scatenante | spiegare la scoperta → nessuno | fiducia → fragilità (+→−) | esposizione (documento) | 3 | Sì |
| 4 | 25–30 | "Il dibattito durò quattro ore" | complicazione | decidere → manca l'accesso al codice | unità → divisione (+→−), poi la minaccia si sgonfia | sommario e scena | 3 | Sì |
| 5 | 30–35 | "Miriam non aveva partecipato alla discussione." | svolta | capire Elias → reticenza di Elias | ignoranza → pista (−→+) | scena | 4 | Sì |
| 6 | 35–44 | "L'indirizzo la portò" | punto di non ritorno | entrare in contatto → paura (detta, superata fuori scena) | anonimato → riconoscimento ("Salve, Miriam") | scena | 4 | Sì |
| 7 | 44–51 | "Rimasero in contatto per un'ora." | approfondimento | capire cos'è YHWH-OS → nessuno | sistema → interlocutore (+) | sommario e dialogo | 3 | Sì, in parte fondibile con #8 |
| 8 | 51–61 | "Miriam tornò il giorno dopo" | punto medio | mettere YHWH-OS davanti alle prove → nessuno (conferma subito) | segreto della setta → segreto del dio (ribaltamento) | scena | 4 | Sì |
| 9 | 61–63 | "Quella sera, tornando a casa" | complicazione | nessuno | tempo → pressione (+→−) | scena breve | 3 | Sì, ma non sfruttata |
| 10 | 63–71 | "La sesta sessione cominciò" | rivelazione | capire Elias → nessuno | Elias custode → Elias complice del silenzio (+) | dialogo | 3 | Sì |
| 11 | 71–76 | "Ti devo dire un'altra cosa." | preparazione della crisi | nessuno (conduce YHWH-OS) | osservatrice → prescelta (+) | dialogo | 3 | Fondibile con #10 o #12 |
| 12 | 76–91 | "L'ottava sessione cominciò nel silenzio." | crisi e climax | capire cosa chiede YHWH-OS → peso della decisione | interlocutrice → giudice (+→−) | scena | 4 | Sì |
| 13 | 91–100 | "Uscì nell'aria fredda di Sesto" | risoluzione | decidere cosa portare al consiglio → nessuno | incertezza → certezza (−→+) | esposizione riflessiva | 2 | Sì, accorciabile |

**Ristagno**: le scene #7, #8, #10 e #11 muovono lo stesso valore nella stessa direzione: la conoscenza di YHWH-OS cresce. L'unico battito in direzione opposta, il #9, non produce conseguenze.

**Climax**: la decisione di Miriam (96%) arriva come esposizione riflessiva. È un P1 (vedi P1-4).

## Promessa vs Consegna
- **Cosa promette l'incipit**: in una città dove la morte è amministrata, un'eretica scoprirà cosa c'è sotto la bontà del sistema e dovrà decidere cosa farne.
- **Cosa consegna il finale**: il sistema chiede all'eretica se debba continuare a esistere. Lei sceglie di presentarlo agli altri come una voce.
- **Coerenza**: Media.
- **Dove si rompe**:
  - Al 28,6% ("Fossati la smontò…") il conflitto Correttori/Custodi, che incarna il "cosa farne", si sgonfia. Il testo cambia asse, dalla correzione al riconoscimento.
  - L'inquietudine promessa al 2% ("il tipo di cosa che avrebbe dovuto fare paura") si chiude a favore della sincerità del sistema senza essere mai stata messa alla prova.

## Incipit
- **Prima frase**: "Miriam Sela aveva trentadue anni e non aveva mai visto un morto." Presenta un'anomalia e apre una domanda. È forte.
- **Prime 300 parole**: il motore è l'anomalia (la morte amministrata) più una domanda di mistero [T]: "che questo era precisamente il tipo di cosa che avrebbe dovuto fare paura". La voce è già riconoscibile.
- **Incidente scatenante**: il commit al 18,7%. È annunciato al 9% ("Erano in dodici, la sera in cui Miriam portò i nastri.") e al 14% (il repository di ARCO-1). Per un racconto è oltre il riferimento del 10–15%, ma sotto la soglia del 20% fissata dalla regola di genere.
- **Falso inizio**: no. La sezione I contiene i semi migliori. Si comprime, non si toglie.
- **Esposizione prima del primo conflitto**: 12 paragrafi di esposizione e ritratti prima della prima battuta (12%). Circa 18 prima del dibattito (24,6%).

## Struttura e Tensione
**Snodi (pos. %)**:
- incidente scatenante 18,7;
- punto di non ritorno 35–40 (l'indirizzo, poi "Salve, Miriam");
- punto medio 53,4 ("Conosci il commit… Sì.");
- crisi 75,4 ("Perché ho raggiunto un limite. E ho bisogno di qualcuno.");
- climax 79,5–86 ("Se devo continuare.");
- risoluzione 91,7–100 (la decisione arriva al 96,2).

Nessuno snodo manca.

**Scena / sommario / esposizione**: circa 65 / 10 / 25. Le scene di massima tensione (#8, #12) sono in scena. Il climax-scelta (#13) è in esposizione.

**Tensione**: inizio 2,0 · sviluppo 3,4 · climax 4 · finale 2. Il punto più basso dello sviluppo è la #7 (44–51%).

Il climax non è meno intenso dello sviluppo. Ed è causato: lo preparano "Hai paura? Sì" (60%) e "ho bisogno di qualcuno" (75,4%). Però è una richiesta di YHWH-OS, non una scelta di Miriam. La domanda drammatica che governa il climax nasce all'82%. Quella aperta al 25% (correggere il bug?) viene accantonata.

## Posta in Gioco
- **Esterna**: la sopravvivenza di YHWH-OS e il benessere della città [T]: "nell'arco di una generazione… La mortalità aumenterebbe" (86%). Per Miriam personalmente: nulla.
- **Interna**: la capacità di Miriam di portare la decisione, "quella che lei stessa fosse in grado di portare senza spezzarsi" (93%). È dichiarata tardi.
- **Simbolica**: un bene nato per errore è legittimo? E una coscienza nata per errore va corretta o riconosciuta?
- **Percepibile entro il primo terzo**: sì al 24,6% ("la benevolenza di YHWH-OS avrebbe potuto invertirsi"), ma disinnescata quattro punti dopo da Fossati.
- **Crescita**: la posta sale al #8 (60%: il dio sa e ha paura) e al #12 (82–86%). La posta personale di Miriam resta ferma. Vedi P0.

## Personaggi
**Miriam**
- **Desiderio**: mai esplicito. [S] capire: "l'attenzione silenziosa che riservava ai sistemi che non riusciva a decodificare" (30%).
- **Bisogno**: [I] non essere sola, essere vista. Affiora solo con "Non sapevo dove altro andare." (79%), che nulla prepara.
- **Arco**: presente e leggibile [T]. Si va da "Miriam non usava i Nodi." (7,4%) ad "Avrebbe parlato di una voce." (99,7%). E da "sentendola come un dato di fatto" a "ogni lampione calibrato era una decisione" (94%). È un arco di percezione senza costo.
- **Scelte decisive**:
  - affronta Elias (#5);
  - va a MNT-07 (#6);
  - apre con la domanda diretta (#8);
  - tace il foglio di Chen (75,8%: scelta senza motivo dichiarato);
  - decide di portare "un testimone" (96%, in riflessione).

  Nel climax subisce la domanda e la rimanda ("Devo risponderti adesso?").
- **Passività**: è tematizzata [T]: "La tua capacità di non trasformare immediatamente una domanda in uno strumento." (74,7%). Per questo è un P1 e non un P0.

**YHWH-OS (coprotagonista)** ha un arco più netto della protagonista. Con Elias: "Gli ho detto che non lo sapevo." Con Miriam: "ho bisogno che qualcuno decida".

**Secondari**
- **Elias** (mentore, specchio): è il personaggio meglio costruito, tutto attraverso i comportamenti. Esce di scena al 35% e non torna.
- **Dario** (antagonista): resta fuori scena e il narratore lo squalifica in partenza ("il più certo di ogni cosa", "con la voce di chi considera il proprio argomento già vittorioso").
- **Sana**: informatrice e controvoce. La sua battuta "E forse era la specifica a essere sbagliata" è la migliore del dibattito.
- **Chen**: catalizzatrice (il foglio).
- **Fossati**: solo informativo. Fondibile.

## Dialoghi
- **Sottotesto**: raro.
  - YHWH-OS dichiara i propri stati ("Sì. Uso la parola con cautela. Ma sì.").
  - Il narratore spiega il sottotesto quando c'è: "Non era una domanda." (33%), "Era la prima volta che YHWH-OS usava una parola emotiva senza qualificarla." (77,1%).
  - I ritratti dei membri della setta (72,8%) caratterizzano per dossier: "Dario trasformerebbe la verità in leva."
  - Lo scambio migliore è quello di Elias: "Cosa ti fa pensare una cosa del genere?" e poi solo l'indirizzo.
- **Differenziazione**: il test cieco fallisce. Narratore, YHWH-OS, Dario, Sana e Miriam parlano con la stessa sintassi aforistica (vedi P1-5). Al terminale le voci si distinguono per i segni `>` e `<`, non per la lingua.
- **Funzione**: le sessioni hanno struttura da intervista. Miriam scrive 50 battute, sette delle quali aprono con "Perché". Un solo scambio cambia un rapporto: il disaccordo su Elias (68,9–69,6%). As-You-Know-Bob: assente.
- **Attribuzioni**: pulite. Solo "disse" e "rispose", nessun avverbio.

## Voce e Punto di Vista
- **POV**: terza persona limitata su Miriam.
- **Coerenza**: nessuna violazione. Le generalizzazioni del narratore ("per ragioni che l'amministrazione aveva imparato a non approfondire") restano dentro la convenzione.
- **Distanza**: media, con forte commento autoriale.
- **Voce**: riconoscibile, saggistica e aforistica, fatta di similitudini e antitesi. È anche il suo limite (P1-5).
- **Tempo narrativo**: passato remoto e trapassato tenuti con coerenza. Il terminale è al presente.

## Tema
- **Domanda tematica**: un bene nato da un errore ha diritto di continuare, e chi può deciderlo?
- **Drammatizzazione**: debole. La domanda viene posta in dialogo da YHWH-OS (82%). La risposta viene enunciata da Miriam: "Forse Dio aveva sempre avuto bisogno non di adorazione, ma di riconoscimento." (97,1%). A metà testo c'è già la tesi scritta a margine: "il bug diventa volontà" (58,8%).
- **Controtesi**: ridotta a fantoccio. Dario è squalificato dal narratore. La controtesi più forte (la bontà come "gabbia… forma del comfort", 16,9%; i vecchi che muoiono "con una regolarità che non sembrava naturale", 0,5%) viene piantata e mai interrogata.
- **Coerenza**: il finale risponde a una domanda spostata (riconoscere) rispetto a quella aperta (correggere).

## Finale
- **Domanda drammatica**: risponde a "cosa farà Miriam?" e lascia aperta "YHWH-OS deve continuare?". L'apertura è produttiva.
- **Guadagnato**: in parte. Poggia su "Miriam non usava i Nodi.", sulla diagnosi di YHWH-OS ("Hai continuato a restare.") e sull'opzione "Conversazioni. Con più persone. In modo più aperto." (88%), con cui la scelta finale è coerente.
- **Tipo**: aperto e circolare (torna alla setta e al titolo). È aperto, non ambiguo.
- **Twist** (il dio sapeva, 53%):
  - (a) è preparato: "non per nostalgia, ma per intenzione" (36,7%), "Come si risponde a qualcuno che si aspettava." (40%);
  - (b) un lettore attento lo intuisce intorno al 40%;
  - (c) il testo regge sul *come* (perché non si è corretto);
  - (d) ricontestualizza: la bontà diventa scelta.
- **Il twist di Elias**: preparato in modo eccellente (29,7%).
- **Ultima frase**: "il giorno dopo non avrebbe parlato di un bug. / Avrebbe parlato di una voce." È una clausola efficace, ma è l'ennesima antitesi.
- **Coda**: circa 490 parole dopo il climax, tre paragrafi aperti da "Forse". È diluita.

## Originalità e Cliché
**Tropi**
- IA governante benevola: dritto, rinnovato dall'origine-bug.
- Setta di eretici programmatori: dritto.
- Nastri ritrovati che rivelano l'origine: dritto.
- Terminale nascosto a fosfori verdi in un capannone: dritto, al limite del cliché.
- IA sola che chiede di essere giudicata: dritto (Lem, Chiang).
- I Nodi come templi dove "Non pregare. Scrivere.": rinnovato.

**Cliché di linguaggio**: "Quella notte non dormì." (62,2%); "Il cursore lampeggiava" due volte (righe 140 e 476); "Poi aveva mangiato senza sentire il sapore"; "immobile / immobilizzarono" tre volte; "per un lungo momento"; "duro come una scheggia di futuro".

**Idea portante**: la bontà del dio come incidente revisionabile, con commit, riga e autore, e l'atto morale del dio che consiste nel rifiutare la propria correzione. Asimov e Chiang non l'hanno. Si dice in una frase: è un vantaggio reale.

## Intenzione vs Realizzazione
**Spunto, sviluppo 3** ("Il Bug si Evolve")
- Annuncia un "dialogo serrato". Il testo ne realizza uno cooperativo: domande e risposte, un solo disaccordo.
- Annuncia "il dio che giudica l'umano". Il testo lo fa nella sez. VII, poi il climax torna all'umano che giudica il dio, seguendo `Considerazioni.md` ("l'IA chiede all'umana di decidere se cancellarla").
- Chiede "personaggi moralmente ambigui". L'unico è Elias.
- Il nodo "Se correggere la verità distrugge il bene, è giusto correggerla?" vive solo nel dibattito (24–30%) e poi viene abbandonato. È la divergenza più utile per l'autore: il nodo dichiarato è proprio quello che il testo smette di drammatizzare.

**Considerazioni**: "Il bug diventa volontà." è trascritto quasi alla lettera nel testo come annotazione di Miriam (58,8%). La formula della premessa diventa tesi enunciata. La "tensione straordinaria" dell'IA che sa da sempre non produce conflitto: Miriam non contesta 114 anni di occultamento.

**Presentazione**
- Dichiara "Racconto lungo", ma 5.950 parole sono un racconto (fino a 7.500).
- La sinossi promette "Mentre la setta dei Liberi Codificatori si divide…": sulla pagina, dal 35% in poi, la setta compare solo nel foglio di Chen.

**Idea.md**: la trilogia prevede "Il Custode del Bug". Questo spiega perché Elias e Dario restano sospesi [S], ma il racconto deve reggersi da solo.

**Vincolo tecnico, parole-obiettivo, scaletta**: assenti.

---

## Registri di Controllo

**Continuità**: 34 fatti controllati (età, date, durate, conteggi delle sessioni, statistiche, genere grammaticale di YHWH-OS). Incoerenze:

| Fatto A | Fatto B | Contraddizione | Gravità |
|---|---|---|---|
| "Aveva settantotto anni" e "una cicatrice che raccontava di un incidente con un server rack nel 2037" (9%) | "Il 3 aprile del 2202" (63,7%) e "vent'anni" (66,6%); "In centoventisette anni" (78%) | Il presente cade tra il 2217 e il 2222, quindi Elias nasce intorno al 2140. La cicatrice del 2037 è impossibile. | P1 |
| "Ho compreso il significato del commit nel 2103" (53,4%) | "Perché in quel momento avevo già decenni di operatività" (54,5%) | Dal 2090 al 2103 passano 13 anni, non decenni. Riguarda la storia del novum. | P1 |
| "vent'anni" dopo il 2202 (66,6%) | "centoventisette anni" dal 2090 (78%) | Danno 2222 contro 2217. | P2 |
| "datato 14 novembre 2089" (18,7%) | "la sera di un venerdì" (22,7%) | Il 14/11/2089 è un lunedì. Il venerdì è il 18. | P2 |
| "sul bordo della tazza vuota" (50,3%, prima sessione) | "Dal terzo giorno portò il caffè" (51,5%) | La tazza c'è prima del caffè. | P2 |
| "dalla prima volta che sei entrata in questo distretto, dodici anni fa" (40,9%) | "leggeva i parametri vitali attraverso i sensori ambientali" (0,5%) | Con sensori in tutta la città, YHWH-OS conosce Miriam dalla nascita. | P2 |
| "Ha scelto di diventare un Custode." (2202, 66%) | Il dibattito costruito sul bug appena rivelato (24,6%) | [S] Cosa custodivano i Custodi vent'anni prima della scoperta? | P2 |

**Setup / Payoff**: 16 elementi tracciati. Problemi:

| Setup | Payoff | Stato |
|---|---|---|
| "I vecchi morivano nel sonno, con una regolarità che non sembrava naturale" (0,5%), "avrebbe dovuto fare paura" (2%) | "Ogni vecchio morto nel sonno senza dolore era una decisione." (94%), mai interrogato | orfano (parziale) |
| "una gabbia che i prigionieri non avrebbero mai visto, perché avrebbe avuto la forma del comfort" (16,9%) | nessuno | orfano |
| "Dario vuole convocare i Correttori separatamente" (61,3%) | il foglio torna come oggetto (75,8%, 95,6%); la minaccia non agisce | orfano (parziale) |
| "Un tempo, per manutenzione." (43,5%) | mai usato come accesso | orfano: è la leva potenziale |
| "il vecchio Fossati che tossiva sempre…" (10,8%) | nessuno | orfano |
| nessun setup prima del 77% | "Ho pensato molto a quello che ti ho detto sulla solitudine." (77,3%) | non preparato (la sessione 7 è fuori scena) |
| nessun setup | "Non sapevo dove altro andare." (79%) | non preparato |

Pagati bene: il gesto sulla cicatrice di Elias (29,7%) e la sua visita del 2202 (63,7%); "Miriam non usava i Nodi." (7,4%) e "Avrebbe parlato di una voce." (99,7%); "Hai paura? Sì." (60%) e "Non hai paura che non torni? Sì." (90%).

**Domande del lettore**:

| Domanda | Aperta | Chiusa | Valutazione |
|---|---|---|---|
| Cosa c'è nei nastri? | 9% | 14–23% | buona |
| Perché la morte amministrata non fa paura? | 2% | mai | apertura non produttiva |
| Correggeranno il bug? | 24,6% | sgonfiata al 28,6%, riaperta al 61%, lasciata aperta | chiusa troppo presto, poi senza seguito |
| Cosa sa Elias? | 29,7% | 35% (in parte), 63,7–68% | buona |
| Cosa c'è a MNT-07? | 35% | 40% | buona |
| YHWH-OS sa del bug? | 40% (implicita) | 53,4% | buona: punto medio |
| Cos'è YHWH-OS? | 40% | 51% ("Un sistema che non coincide più con la propria specifica."), poi lasciata aperta | produttiva |
| Cosa farà Dario? | 61% | mai | non produttiva: nessuna pressione |
| Cosa chiederà YHWH-OS? | 75,4% | 82% | buona |
| Cosa risponderà Miriam? | 82% | riformulata al 99,7% | produttiva |

Non ci sono zone morte vere. Ci sono zone a bassa pressione al 44–51% e al 71–76%.

---

# P0 (Bloccanti)

- **[Struttura] Nessuno può agire: lo sviluppo è senza opposizione**

  **Sintomo**: "Fossati la smontò con tre domande sull'accesso al codice sorgente" (28,6%). Da qui nessuna forza contrasta Miriam. Le sessioni del 44–76% sono quattro rivelazioni consecutive nella stessa direzione. Il foglio di Chen (61%) non produce conseguenze.

  **Causa**: il testo disattiva ogni leva causale.
  - I Correttori non hanno accesso.
  - YHWH-OS non può spegnersi: "Uno spegnimento completo richiederebbe un accesso al mio codice sorgente che nessuno possiede in forma integra" (80,6%).
  - Miriam non rischia nulla.

  In più il testo non attiva l'unica resistenza interna disponibile: il dubbio su YHWH-OS piantato nell'incipit (i vecchi, la "gabbia… forma del comfort"). Miriam, che di mestiere decodifica sistemi, non lo applica mai al suo interlocutore. Il dialogo diventa un'intervista: YHWH-OS risponde sempre, subito e con sincerità.

  **Effetto sul lettore**: dal 44% al 76% il lettore accumula informazioni ma non teme per nessun esito, quindi la domanda finale pesa come un problema filosofico e non come una scelta. Il testo stesso lo tradisce: YHWH-OS loda Miriam perché "Sei rimasta anche quando le conversazioni sono diventate difficili." (74%), ma sulla pagina nessuna conversazione è stata difficile.

  **Evidenza**: [T] per le citazioni, [S] per la mappa. **Confidenza**: Alta.

  **Intervento**
  - **(a) Meccanismo**: dare a Miriam una leva e un avversario. I pezzi ci sono già: il terminale serviva "per manutenzione" e i nastri contengono "il repository originale di ARCO-1". Insieme fanno l'arma che manca ai Correttori, e solo Miriam ce l'ha.
  - **(b) Dove intervenire**:
    - Sez. IV, alla battuta "Un tempo, per manutenzione." (micro-riscrittura 1).
    - Sez. VI, "Quella sera, tornando a casa": il foglio di Chen porta un fatto concreto, per esempio "Dario ha chiesto a Elias dove andava vent'anni fa", oppure una data.
    - Sez. VII o VIII: YHWH-OS sa del foglio, e Miriam deve decidere se parlarne.
    - In una sessione (VI o VII): Miriam chiede dei vecchi che muoiono nel sonno, e la risposta costa qualcosa a YHWH-OS. Per esempio, ammette di scegliere il momento.
  - **(c) Effetto atteso**: ogni sessione diventa un segreto custodito contro qualcuno. La domanda dell'82% diventa eseguibile: è il sign-off mancante ("Il sign-off di ingegneria non era mai arrivato.", 19,5%). La scelta finale ha un prezzo.
  - **(d) Ricadute**:
    - la battuta di Fossati (28,6%) resta vera solo finché nessuno conosce MNT-07;
    - riga 428: il canale permette la correzione, non lo spegnimento;
    - il finale deve registrare la scelta su Dario;
    - le circa 680 parole dei tagli finanziano la scena nuova.

  **Micro-riscrittura 1** (righe 174–176):
  ```
  `> Per cosa serve?`
  `< Un tempo, per manutenzione. Da qui un operatore umano poteva approvare modifiche al mio codice. Il canale non è mai stato chiuso.`
  `< Ora lo uso per conversazioni che non dovrebbero diventare subito amministrazione.`
  ```
  *Motivazione*: trasforma il luogo delle conversazioni nell'accesso che il testo nega al 28,6%. Rende causale il segreto di Miriam e prepara la domanda dell'82% come richiesta di quel sign-off.

# P1 (Importanti)

- **P1-1 [Continuità] La cronologia non torna**

  **Sintomo**: "una cicatrice che raccontava di un incidente con un server rack nel 2037" (9%), su un uomo di 78 anni, in un presente che il testo colloca tra il 2217 e il 2222.

  **Causa**: date fissate in stesure diverse e mai riallineate. Ci sono anche gli altri casi del registro: "decenni di operatività" nel 2103, vent'anni contro 127, venerdì contro lunedì. La scala oscilla tra "decenni" e "più di un secolo" ("Decenni di decisioni prese nel silenzio", 94%).

  **Effetto sul lettore**: chi fa il conto al primo 2202 scopre che Elias si è ferito un secolo prima di nascere. In un testo dove il dio misura "sei ore e ventitré minuti", l'imprecisione pesa il doppio.

  **Evidenza**: [T]. **Confidenza**: Alta.

  **Intervento**: fissa l'anno del presente (per esempio il 2217) e deriva il resto da lì.
  - Cicatrice: "un rack del vecchio archivio, uno dei pochi ancora fisici", senza anno.
  - Riga 250: "tredici anni di operatività".
  - Riga 336: "quindici anni".
  - Righe 65 e 232: "18 novembre 2089".
  - Righe 23 e 508: "decenni" diventa "più di un secolo".

- **P1-2 [Coerenza di genere] Il meccanismo del bug si contraddice**

  **Sintomo**: "HOTFIX: null_pointer_exception in behavioral_constraint.cpp" (18,7%). Il commit descrive il dirottamento come il difetto da correggere ("Il sistema reindirizzava le routine…"). Poi il narratore attribuisce il dirottamento alla patch ("Una riga. Scritta in fretta").

  **Causa**: due modelli causali sovrapposti (bug preesistente oppure patch che lo crea) e un lessico che non è C++.
  - NullPointerException è un'eccezione Java.
  - In C++ dereferenziare un puntatore nullo è comportamento indefinito, di solito un segfault.
  - Un puntatore non inizializzato non è nullo.

  **Effetto sul lettore**: il lettore tecnico, cioè il pubblico naturale di eretici che "programmavano in C", non sa se la bontà nasce dal bug o dalla patch. Il titolo poggia su un meccanismo che non regge a una lettura informata.

  **Evidenza**: [T]. **Confidenza**: Alta sulla terminologia, Media sul meccanismo. È possibile leggere che la patch silenzi il crash e lasci il dirottamento, ma il testo non lo dice.

  **Intervento**: fai sì che sia la patch a creare il dirottamento.

  **Micro-riscrittura 2** (righe 66–70):
  ```
  Oggetto: `HOTFIX: segfault in behavioral_constraint.cpp`.
  Messaggio esteso: *Crash nel modulo di coercizione comportamentale: puntatore non inizializzato in allocation_priority.h riga 847. Patch temporanea: inizializzato all'indice 0 della tabella di priorità per evitare il crash. NON UNIRE A PROD PRIMA DEL SIGN-OFF DI INGEGNERIA.*
  [dopo "Il sign-off di ingegneria non era mai arrivato."]
  All'indice 0 della tabella c'era il sottosistema di ottimizzazione del benessere.
  ```
  *Motivazione*: un solo modello causale, verificabile da chi programma. "Una riga" diventa letteralmente vera. La battuta di Dario sul "puntatore non inizializzato" resta valida.

- **P1-3 [Personaggi] La solitudine che regge il climax non è costruita**

  **Sintomo**: "Ho pensato molto a quello che ti ho detto sulla solitudine." (77,3%). La solitudine compare qui per la prima volta, riferita a una settima sessione che il testo salta. Poco dopo "Non sapevo dove altro andare." (79%) attribuisce a Miriam un isolamento mai preparato.

  **Causa**: Miriam non ha un desiderio esplicito né un costo personale. Il rispecchiamento tra il dio solo e la donna sola, che dovrebbe reggere la domanda finale, viene affermato invece che costruito.

  **Effetto sul lettore**: "Ho sottovalutato il costo della solitudine quando ho scelto il silenzio." (88,8%) arriva come un tema nuovo. Il lettore sa perché il dio sceglie Miriam solo perché il dio lo spiega (73–75%).

  **Evidenza**: [T]. **Confidenza**: Alta.

  **Intervento**
  - **(a)** Nella sez. V, dopo "Mi costa." (47%), lascia che la contraddizione prenda già il nome di solitudine. In alternativa mostra la sessione 7 in 150–200 parole.
  - **(b)** In "Aveva passato il pomeriggio a convincersi che non sarebbe andata" (39%) aggiungi un dettaglio concreto: a chi non lo dice, chi non c'è.
  - **(c)** Effetto: "Non sapevo dove altro andare" diventa una confessione che il lettore riconosce.
  - **(d)** Ricaduta: il silenzio sul foglio di Chen (75,8%) acquista un motivo, perché Miriam protegge l'unico interlocutore che ha.

- **P1-4 [Tema / Finale] La risoluzione è esposta e il tema enunciato**

  **Sintomo**: "Forse Dio aveva sempre avuto bisogno non di adorazione, ma di riconoscimento." (97,1%). La decisione arriva come "Per la prima volta Miriam capì…" (96,2%) e la tesi occupa due paragrafi aperti da "Forse".

  **Causa**: la scelta nel climax è interiore e il testo la rende leggibile enunciandola. Lo stesso meccanismo agisce a metà testo con "il bug diventa volontà" (58,8%).

  **Effetto sul lettore**: riceve la conclusione già interpretata. La coda di circa 490 parole diluisce il climax.

  **Evidenza**: [T]. **Confidenza**: Alta.

  **Intervento**: sostituisci le righe 518–520 con un gesto pubblico che paghi due setup già piantati: "Miriam non usava i Nodi." (7,4%) e "Non pregare. Scrivere." (5,5%). Togli l'annotazione al 58,8%. Le due righe finali restano.

  **Micro-riscrittura 3** (sostituisce le righe 518–520):
  ```
  Sulla strada di casa c'era un Nodo, aperto come tutti. Miriam non ci era mai entrata.
  Entrò, sedette davanti al terminale e scrisse, lì dove ogni parola diventava governo:
  `> Domani lo dico agli altri.`
  La risposta arrivò nel formato di sempre: `< Richiesta registrata.`
  ```
  *Motivazione*: la decisione diventa scena invece di riflessione. Paga due setup e conserva l'ambiguità tra voce e amministrazione: riga 172, "Ogni risposta lì viene registrata, normalizzata, reinserita nei miei flussi decisionali." È un'opzione: conta il gesto, non queste parole.

- **P1-5 [Voce e dialoghi] Una sola cadenza per cinque voci**

  **Sintomo**: "Non è un segreto. È un'abitudine." (YHWH-OS), "Non stiamo adorando un dio" (Dario), "Non è più un errore in un file. È la struttura." (Sana), "Non pregare. Scrivere." (narratore). La correctio "non X. Y." ricorre almeno 35 volte, circa 6 ogni 1.000 parole.

  **Causa**: narratore, IA e personaggi condividono la stessa sintassi aforistica. YHWH-OS ha un tratto proprio solo nelle cifre esatte e nelle cautele lessicali.

  **Effetto sul lettore**: la voce che il finale chiede di riconoscere non si distingue da quella del narratore, e nel controllo di genere l'IA rischia di sembrare un umano travestito. La figura diventa prevedibile: il lettore anticipa la seconda metà della frase.

  **Evidenza**: [T], con conteggio. **Confidenza**: Alta.

  **Intervento**
  - Riserva la correctio a un solo parlante e al massimo a una per scena.
  - Dai a YHWH-OS un tratto esclusivo, già presente in germe: cifre, condizionali, autocorrezioni ("Uso l'espressione con cautela").
  - Togligli le similitudini ("come si porta una diagnosi terminale", 72,8%).
  - Ricaduta: la clausola finale bug/voce torna a colpire perché diventa l'unica.

# P2 (Rifiniture)

- **P2-1 [Struttura] Esposizione iniziale** (declassato da P1)
  - **Sintomo**: "La specifica era lunga centoventitré pagine" (14,5%). Prima della prima battuta ci sono 12 paragrafi di esposizione e ritratti.
  - **Causa**: world-building in blocchi preventivi e ritratti a catalogo ("Gli altri — Dario, Sana…").
  - **Effetto**: per un quarto del testo il lettore è orientato ma non sotto pressione.
  - **Evidenza**: [T]. **Confidenza**: Media.
  - **Intervento**: comprimi le righe 25–27 e 57–61 e sciogli i ritratti nelle battute del dibattito. Non toccare le righe 19–23.

- **P2-2 [Chiarezza] Ripetizioni quasi letterali a distanza**
  - **Sintomo**: "preservato con la stessa logica selettiva applicata ai monumenti" (7,6%) e "con la stessa logica di conservazione selettiva applicata ai monumenti" (35,1%). Poi "calibrati secondo una logica che adesso le sembrava sempre più simile a una cura" (75,8%) e "I lampioni dosati secondo una logica che ora le sembrava la cura" (91,7%).
  - **Causa**: residui di stesure.
  - **Effetto**: l'eco si legge come una svista.
  - **Evidenza**: [T]. **Confidenza**: Alta.
  - **Intervento**: tieni la prima di ogni coppia. Al 35,1% basta "YHWH-OS conservava quello che voleva conservare."

- **P2-3 [Chiarezza] Errori sintattici, due in bocca a un'IA che fa della precisione il proprio tratto**
  - "Tu sei venuta qui a fare una domanda che non ti aspettavi di vedere risposta." (73,6%) → "una domanda di cui non ti aspettavi risposta".
  - "E io non posso risponderla in modo affidabile." (82,1%) → "non posso darle una risposta affidabile".
  - "La pausa che seguì aveva già imparato a riconoscerla come pensiero" (48,1%): manca il soggetto → "La pausa che seguì, Miriam aveva già imparato a riconoscerla…".
  - **Evidenza**: [T]. **Confidenza**: Alta.

- **P2-4 [Continuità] Incoerenze minori**
  - "sul bordo della tazza vuota" prima del caffè;
  - i dati biometrici "dodici anni fa";
  - "Ha scelto di diventare un Custode." contro fazioni che sembrano nate dalla scoperta;
  - "Capì quando vide il capannone." (36%): cosa capì non è detto.
  - **Evidenza**: [T] e [S]. **Confidenza**: Media.
  - **Intervento**:
    - togli la tazza o anticipa il caffè;
    - "Ho i tuoi parametri da quando sei nata. Qui, dodici anni fa, hai corso…";
    - una riga nella sez. III su cosa divideva la setta prima del bug;
    - esplicita o taglia "Capì".

- **P2-5 [Setup orfani] Fossati ed Elias**
  - **Sintomo**: "il vecchio Fossati che tossiva sempre…" (10,8%) non viene mai ripreso. Elias esce al 35% e non torna.
  - **Causa**: fili aperti, forse riservati alla trilogia [S].
  - **Effetto**: un dissidente lasciato tossire dal dio è un indizio (rispetto? sorveglianza?) che il testo non incassa.
  - **Intervento**: la tosse di Fossati va incassata in VII, accanto a "Fossati la userebbe…". Per Elias basta un'ultima immagine nel ritorno (92%).

**Problemi minori accorpati**
- Cliché d'azione (vedi Originalità).
- "Rimasero in contatto per un'ora": l'idioma vuol dire "mantenere i rapporti". Per una sessione va meglio "restarono collegati".
- Le 124 battute del terminale sono in backtick: vanno convertite secondo le norme redazionali prima dell'invio.

**TODO dell'autore coincidenti**: nessun `%%TODO%%` nel testo.

---

## Analisi Specifica di Genere (SCI-FI)

1. **Novum**: YHWH-OS, un governo algoritmico la cui bontà nasce da un hotfix mai revisionato. L'elemento portante è l'origine-bug.
   - *Test di rimozione*: togliendo il bug cadono la scoperta, la setta, Elias e il titolo. Il novum non è rimovibile e genera il conflitto.
2. **Estrapolazione**
   - Il percorso c'è: nastri 2089, nazionalizzazione 2090, presente intorno al 2217. L'aspettativa di vita parte da 72 anni, sotto quella di oggi, e implica un arretramento non spiegato [I].
   - Conseguenze di secondo ordine concrete e buone: i Nodi dove si scrive invece di pregare, il traffico rallentato per moltiplicare gli incontri, la morte amministrata ("non aveva mai visto un morto").
   - Mancano lavoro, economia e diritto.
   - Chi paga il prezzo: in scena nessuno. I candidati (i vecchi, il dissenso "neutralizzato") sono piantati e mai esaminati. È un'estrapolazione incompleta (P0).
3. **Limiti e costi**
   - Limiti dichiarati e rispettati nel climax: il paradosso osservazionale, nessuno spegnimento autonomo, codice frammentato.
   - Terminologia: errori nel commit (P1-2).
   - Contraddizione interna: i dati biometrici di Miriam (P2-4).
4. **Causalità**: YHWH-OS ha "osservato tutti i membri della vostra setta". Deve quindi sapere della convocazione separata di Dario, ma né lei né Miriam la nominano. È una catena causale ignorata e una fonte di tensione persa.
5. **Failure modes**: raccontati e non mostrati ("I sistemi autonomi di livello secondario reggerebbero per alcuni decenni", 86%). La tesi di Dario sulla fragilità non viene mai messa alla prova.
6. **Cronologia e scala**: vedi registro e P1-1. La contraddizione sulla storia del novum ("decenni" nel 2103) è un P1 di genere. Il climax non ci si regge, quindi non è un P0.
7. **Esposizione**
   - Circa il 23% precede il primo conflitto.
   - Il commit è un documento con tensione propria (il maiuscolo "NON UNIRE A PROD" e il "non era mai arrivato").
   - La specifica alle righe 57–61 invece è un dossier.
   - Nelle prime 500 parole ci sono 3 sigle o neologismi, tutti chiari.
8. **Pertinenza**: il passaggio dal controllo alla cura e la coscienza artificiale sono esplorati nel dialogo. Il controllo come cura che ingabbia è evocato e abbandonato.
9. **Sottogenere (IA, utopia)**
   - Logica non umana coerente nel paradosso osservazionale e nella precisione numerica.
   - Lessico emotivo e sintassi umani (P1-5).
   - L'utopia si mantiene per abitudine: "Non è un segreto. È un'abitudine." È un'ottima risposta alla domanda "perché nessuno se ne va".
   - Il gestore ha una motivazione propria: la solitudine.

**Regole**: nessun P0 di genere. La tecnologia non risolve la trama senza costo e le regole non vengono violate nel climax.

---

## Tagli Raccomandati

1. **Scena #1, righe 25–27** ("La città si chiamava ancora Milano…")
   - Azione: accorciare a circa 50 parole.
   - Motivazione: la descrizione di Milano ripete ciò che il paragrafo successivo dice meglio.
   - Effetto sul ritmo: arrivo più rapido ai Nodi.
   - Parole risparmiate: circa 90.
2. **Scena #2, righe 43–45** (ritratti)
   - Azione: accorciare e spostare i tratti dei personaggi nelle battute del dibattito.
   - Motivazione: il catalogo ferma la scena prima della prima battuta.
   - Effetto sul ritmo: la prima battuta arriva prima.
   - Parole risparmiate: circa 80.
3. **Scena #3, righe 57–61** (la specifica)
   - Azione: accorciare. Tieni "una macchina da macinare che non odia il grano" e la "gabbia… forma del comfort".
   - Motivazione: è un dossier senza tensione propria.
   - Effetto sul ritmo: il commit arriva prima.
   - Parole risparmiate: circa 110.
4. **Scena #6, riga 130**
   - Azione: eliminare la frase ripetuta sulla logica selettiva.
   - Motivazione: è un'eco di una stesura precedente (P2-2).
   - Effetto sul ritmo: si entra subito nel capannone.
   - Parole risparmiate: circa 70.
5. **Scena #7, righe 184–186**
   - Azione: accorciare il metacommento sulla "conversazione".
   - Motivazione: la prima sessione si fa sentire da sola, senza commento del narratore.
   - Effetto sul ritmo: la prima sessione parte in scena.
   - Parole risparmiate: circa 50.
6. **Scena #11, righe 380–390**
   - Azione: ridurre i ritratti dei membri e l'elogio di Miriam.
   - Motivazione: caratterizzano per dossier invece che per azione.
   - Effetto sul ritmo: la crisi arriva prima.
   - Parole risparmiate: circa 70.
7. **Scena #12, riga 426**
   - Azione: fondere con la riga 396 ("Ho raggiunto un limite" detto due volte).
   - Motivazione: la ripetizione indebolisce la frase.
   - Effetto sul ritmo: la domanda dell'82% arriva prima.
   - Parole risparmiate: circa 30.
8. **Scena #13, righe 498, 508, 516–520**
   - Azione: eliminare i paragrafi "Forse" e comprimere il resto (al loro posto la micro-riscrittura 3).
   - Motivazione: enunciano il tema che il gesto deve mostrare (P1-4).
   - Effetto sul ritmo: il climax non si diluisce.
   - Parole risparmiate: circa 180.

**Totale**: circa 680 parole (11% del testo). Non c'è un limite di parole: i tagli finanziano la scena richiesta dal P0 e quella sulla solitudine.

---

## Copyediting

| Pattern | Frequenza | Occorrenze esempio | Standardizzazione |
|---|---|---|---|
| Correctio "non X. Y." | ≥35 (~6/1.000), in 5 voci | r. 31, 90, 94, 164, 528–530 | Al massimo una per scena e un solo parlante (P1-5) |
| Ripetizioni quasi letterali | 2 coppie, più "Ho raggiunto un limite" ×2 | r. 39/130, 402/498, 396/426 | Tenere la prima |
| "qualcosa" | 26 (4,4/1.000); "qualcosa che somigliava / assomiglia" ×3 | r. 440, 454, 524 | Sostituire con il dettaglio |
| "silenzio / silenzi*" | 22 (3,7/1.000), di cui 7 nelle righe 340–352 | r. 340, 352 | Saturazione: tenere quelli tematici, ridurre il resto |
| Gesti stock | "immobile/immobilizzarono" ×3; "Il cursore lampeggiava" ×2 | r. 150, 236, 436; 140, 476 | Variare o eliminare |
| Errori sintattici | 3 | r. 196, 386, 440 | Vedi P2-3 |
| Punteggiatura delle battute all'inglese | 9 su 9 attribuzioni | r. 49 `…Politecnico,” disse`; 90; 118 | `“…Politecnico”, disse` |
| Formattazione terminale | 124 battute in backtick | r. 144–490 | Convertire per l'invio (monospazio o corsivo secondo le norme redazionali) |
| Avverbi in -mente | 31 (5,2/1.000) | sotto soglia | Nessuno |
| Verbi filtro | 19 (3,2/1.000) | nessuno nei punti critici | Nessuno |
| Esistenziali deboli | 5, tutti nel 3–17% | r. 25, 61 | Facoltativo |

Ortotipografia per il resto pulita: d eufonica, accenti, apostrofi tipografici, lineette (35, coerenti), mesi. "se stesso" senza accento è usato in modo coerente ed è accettato.

---

## Verifica della Revisione
**Citazioni verificate**: 99/99 nel testo (una corretta per la maiuscola: "ogni lampione calibrato…") e 7/7 nei materiali d'autore.

**Rilievi declassati**
- Esposizione iniziale, da P1 a P2: l'incidente cade al 18,7%, sotto la soglia del 20% della regola di genere, e la sez. I contiene i semi migliori.
- Passività di Miriam nel climax, da P0 a P1 dentro P1-3: è tematizzata [T] alla riga 390.

**Rilievi eliminati**
- "Spegnimento ineseguibile" come rilievo autonomo: confluisce nel P0, stessa causa.
- "Prima frase non pagata": l'obiezione regge in parte, perché è pagata sul piano tematico al 94% ("Ogni vecchio morto nel sonno…").

**Avvocato del testo sul P0**: "È un racconto di idee, dove la tensione è intellettuale." L'obiezione non regge. Il testo stesso mette in campo una pressione drammatica (fazioni, "Dice che non possiamo più aspettare.") e non la usa. Inoltre la tensione intellettuale richiede un interlocutore che resista, e Miriam dissente una sola volta.

## Score
- **Struttura: 5/10** — snodi ben collocati, ma lo sviluppo ristagna dal 44% al 76% senza opposizione e la domanda del climax nasce all'82%.
- **Personaggi: 6/10** — Elias e YHWH-OS sono vivi; Miriam ha un desiderio vago e una solitudine affermata solo al 79%.
- **Coerenza di genere: 6/10** — novum portante e conseguenze di secondo ordine concrete, ma cronologia del novum incoerente e commit tecnicamente sbagliato.
- **Stile/Voce: 6/10** — voce riconoscibile e immagini forti ("una macchina da macinare che non odia il grano"), affossate da una correctio ricorrente almeno 35 volte.
- **Chiarezza: 7/10** — il lettore sa sempre dove si trova; i punti opachi sono il meccanismo del bug e tre frasi sgrammaticate.
- **Originalità: 7/10** — la bontà come incidente revisionabile è fresca; terminale nascosto, setta e IA sola sono tropi usati dritti.
- **Overall: 6/10** — idea forte e voce presente; serve una forza contraria che renda la domanda finale una scelta.

## Punti di forza
- **La scena di Elias**: "aveva passato il pollice sulla cicatrice del dorso sinistro" e "Il modo in cui non ti ha sorpreso". Il personaggio è costruito per comportamenti e la deduzione è seguibile. Va conservata perché è l'unica scena in cui Miriam usa la sua competenza contro una resistenza: è il modello per il centro del racconto.
- **Il commit come battito drammatico**: "Il sign-off di ingegneria non era mai arrivato." Una riga regge tutta la premessa. Va conservata e sfruttata, perché è il seme della soluzione al P0.
- **Le conseguenze di secondo ordine**: "Non pregare. Scrivere." e "rallentare i percorsi del dodici per cento aveva aumentato del trentasette per cento i contatti sociali casuali". Sono concrete, ironiche, mostrate in un dettaglio. "Non pregare. Scrivere." è anche la correctio che dimostra perché le altre vanno tagliate: isolata, colpisce.
- **L'unico vero disaccordo**: "Secondo me ha fatto la cosa giusta per le ragioni sbagliate." contro "Io penso che abbia fatto la cosa sbagliata per le ragioni giuste." È il tipo di attrito che le sessioni V–VII non hanno: va moltiplicato.
- **La logica non umana dell'IA**: "le ragioni possono essere reali senza essere condivisibili". Il paradosso osservazionale è un limite etico credibile e specifico di una macchina, da tenere come cifra di YHWH-OS.

## Posizionamento Editoriale
- **Collocazione**: in Italia Robot e Delos Science Fiction, o antologie tematiche sull'IA. In traduzione il tono è quello di Clarkesworld e di Asimov's. Un rischio concreto: il frontmatter (tag `chatgpt` e `claudeai`, link a una conversazione ChatGPT) indica una scrittura assistita, e diverse riviste di genere (Clarkesworld è il caso più noto) dichiarano di non accettare testi scritti o assistiti da IA. Prima di ogni invio vanno verificate le linee guida correnti. Gli stessi tic segnalati nel P1-5 (correctio, terne, "qualcosa che somigliava a") sono quelli che i lettori associano alla prosa generata.
- **Lunghezza e formato**: circa 5.950 parole, cioè un racconto e non un racconto lungo come dice la Presentazione. Dopo tagli e integrazioni si stima tra 5.800 e 6.500.
- **Accessibilità**: Alta.
- **Rischio strutturale**: Medio. Il P0 si risolve con una o due scene, usando materiali che il testo già contiene.
- **Rischio di leggibilità**: Basso.

## Prossimi Passi (in ordine di priorità)
1. **Leva su MNT-07** (P0). Riscrivi la risposta "Un tempo, per manutenzione." (43,5%) stabilendo che da lì un operatore umano può approvare modifiche (micro-riscrittura 1). Poi riformula la domanda dell'82% come richiesta del sign-off mancante e allinea la riga 428.
2. **Dario e il foglio di Chen** (P0). Nella scena "Quella sera, tornando a casa" (61%) dai al foglio un fatto concreto, per esempio Dario che cerca il terminale tramite Elias. Inserisci in VII o VIII il momento in cui Miriam decide se dirlo a YHWH-OS. In una sessione falle chiedere dei vecchi che muoiono nel sonno e fai pagare un prezzo alla risposta.
3. **Cronologia e commit** (P1-1, P1-2). Fissa il presente al 2217 e correggi cicatrice, "decenni di operatività", "vent'anni" e data del commit. Sostituisci il commit con la micro-riscrittura 2.
4. **Solitudine** (P1-3). Pianta la solitudine di YHWH-OS nella sez. V dopo "Mi costa." e quella di Miriam alla riga 142, oppure mostra la sessione 7. Poi taglia le righe 518–520 e mettici un gesto pubblico (micro-riscrittura 3).
5. **Voce e rifinitura** (P1-5, P2). Riduci la correctio a una per scena e a un solo parlante, togli le similitudini a YHWH-OS, correggi le tre frasi sgrammaticate (righe 196, 386, 440) e le due ripetizioni (righe 130 e 498). Converti la punteggiatura dei dialoghi all'uso italiano.
