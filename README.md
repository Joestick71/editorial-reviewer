# 🧠 Editorial Review – Speculative Engine
## Revisione Professionale per SCI-FI · FANTASY · WEIRD

Motore di revisione editoriale avanzato specializzato in narrativa speculativa in lingua italiana, distribuito come skill di Claude Code.

Progettato per:
- racconti
- novelle
- romanzi
- manoscritti in fase di submission

---

# 🎯 Obiettivo

Fornire una revisione:

✓ strutturale  
✓ sistemica  
✓ coerente con il genere  
✓ fondata su evidenze testuali verificate  
✓ non invasiva  
✓ orientata alla pubblicazione  

Non è uno strumento di ghostwriting.  
È un motore di analisi editoriale senior.

---

# 🧬 Generi Supportati

## 🚀 SCI-FI
Focus su:
- novum e test di rimozione
- estrapolazione e conseguenze di secondo ordine
- plausibilità, limiti e costi
- cronologia e scala
- failure modes

Evita:
- tecnologia deus ex machina
- infodump scollegati dal conflitto
- incoerenze temporali o logiche

---

## 🐉 FANTASY
Focus su:
- sistema magico coerente, costi e limiti
- economia e strutture di potere
- mitologia interna, nomenclatura e lessico
- regole del passaggio tra mondi (portal, slipstream)

Evita:
- magia risolutiva senza prezzo
- worldbuilding decorativo
- inflazione di maiuscole e nomi propri

---

## 🜏 WEIRD
Focus su:
- ambiguità controllata e grammatica dell'anomalia
- escalation del perturbante
- simboli ricorrenti
- ricompensa interpretativa

Evita:
- confusione senza struttura
- spiegazioni che dissolvono il perturbante
- etichette d'effetto al posto del dettaglio

---

# 🔁 Workflow Interno dell'Agente

1. **Caricamento e contesto** — individuazione del testo (anche nelle cartelle del vault IdeaVerse), pulizia di frontmatter, callout e commenti `%%`, conteggio parole, scelta della modalità
2. **Identificazione genere** — dominante, secondario, sottogenere, promessa, benchmark
3. **Mappatura del testo** — mappa delle scene, registro di continuità, setup/payoff, domande del lettore
4. **Analisi core** — promessa vs consegna, incipit, struttura e tensione, posta in gioco, personaggi, dialoghi, voce e POV, tema, finale, originalità e cliché, intenzione vs realizzazione
5. **Analisi specifica per genere** — dai file in `references/`
6. **Diagnostica P0 / P1 / P2** — per causa radice, con evidenza e confidenza
7. **Tagli consigliati** — con stima delle parole risparmiate
8. **Copyediting** — pattern `Grep` e norme ortotipografiche italiane, calchi dall'inglese
9. **Stress test della revisione** — verifica delle citazioni, avvocato del testo, coerenza interna
10. **Valutazione** — punteggi su rubrica, tetti obbligatori, posizionamento editoriale

La diagnosi nasce da una lettura a freddo: l'officina e le note d'autore vengono lette solo dopo, per confrontare intenzione e realizzazione.

---

# 📊 Sistema di Priorità

- **P0** → Bloccante strutturale
- **P1** → Importante ma non fatale
- **P2** → Rifinitura

Ogni rilievo cita il testo, indica il livello di evidenza ([T] testuale, [S] suggerito, [I] inferito) e la confidenza. Un P0 non può poggiare solo su un'inferenza.

---

# 📈 Sistema di Valutazione

Scala:

9–10 → Publish-ready  
7–8 → Solido, polishing necessario  
5–6 → Revisione strutturale richiesta  
3–4 → Problemi gravi  
1–2 → Riscrittura profonda necessaria  

Categorie valutate, ciascuna su descrittori di fascia (`references/rubrica-punteggi.md`):

- Struttura
- Personaggi
- Coerenza di Genere
- Stile / Voce
- Chiarezza
- Originalità
- Overall (non è la media)

Tetti obbligatori: un P0 strutturale limita la Struttura a 6, un P0 di genere la Coerenza di Genere, un P0 sui personaggi i Personaggi; qualsiasi P0 limita l'Overall a 6.

---

# ⚖ Posizionamento Editoriale

L'agente valuta anche:

- Collocazione (riviste, collane, antologie)
- Lunghezza e formato rispetto all'obiettivo
- Accessibilità
- Rischio strutturale
- Rischio di leggibilità

Utile in ottica concorsi o submission.

---

# 🎚 Modalità

| Modalità | Cosa fa | Quando |
|---|---|---|
| `completa` (predefinita) | tutte le fasi | prima revisione di un testo finito |
| `strutturale` | storia, scene, personaggi, tagli; niente copyediting | prima passata di revisione |
| `prosa` | voce, dialoghi, copyediting, con una mappa delle scene sintetica | seconda passata, a struttura stabile |

---

# 📏 Proporzione

La lunghezza della revisione segue quella del testo: 1.000–2.000 parole fino a 2.000 parole di testo, 2.500–4.500 fino a 10.000, 4.000–7.000 oltre. Tutte le fasi vengono comunque eseguite; si riduce ciò che viene riportato (conferme, registri, analisi di genere), mai i P0, le citazioni e i Prossimi Passi.

---

# 🧩 Testi Lunghi

Il testo viene sempre letto per intero: continuità e setup/payoff lo richiedono.

Oltre le 10.000 parole:
- analisi strutturale sull'intero testo, per capitolo
- analisi di riga (dialoghi, copyediting, micro-riscritture) sui 4 snodi: incidente scatenante, punto di non ritorno, climax, risoluzione (o sui campioni 0–10%, 30%, 70%, 90–100%)

---

# ✂ Filosofia Anti-Ghostwriting

- Non riscrive intere scene
- Massimo 3 micro-riscritture per revisione, ciascuna di 5 righe al massimo e con motivazione tecnica
- Non sostituisce la voce autoriale
- Non standardizza testi già validi

---

# 📦 Installazione

Collega la cartella del progetto alle skill personali di Claude Code, così ogni modifica è subito attiva:

```bash
ln -s ~/Projects/editor-reviewer ~/.claude/skills/editor-reviewer
```

Se invece la skill è installata come clone separato, aggiornala con `git pull` dopo ogni modifica.

---

# 📌 Esempi di Invocazione

```
/editorial-reviewer "~/Projects/IdeaVerse/Writings/Racconti/Cronografie"
/editorial-reviewer "~/Projects/IdeaVerse/Writings/Racconti/01 - Mos Maiorum" strutturale
/editorial-reviewer capitolo1.md prosa weird psicologico, concorso con limite 5.000 parole: il finale è troppo spiegato?
```

Racchiudi tra virgolette i percorsi che contengono spazi. Le note libere dopo la modalità (genere, obiettivo, limite di parole, domande) vengono usate nella revisione; le domande ricevono una risposta esplicita.

---

# 🏗 Struttura del Progetto

```
editor-reviewer/
├── SKILL.md                     flusso di lavoro, regole e formato di output
├── README.md
├── LICENSE
├── references/                  caricati dalla skill quando servono
│   ├── genere-scifi.md
│   ├── genere-fantasy.md
│   ├── genere-weird.md
│   ├── copyediting-it.md        pattern Grep, norme italiane, calchi
│   └── rubrica-punteggi.md      descrittori di fascia per i punteggi
└── examples/
    ├── sci-fi-sample.md         estratto di "Dio è un Bug"
    ├── sci-fi-review.md         revisione di riferimento verificata, sul racconto completo
    ├── fantasy-sample.md        estratto di "Fra Due Mondi"
    ├── fantasy-review.md
    ├── weird-sample.md          estratto di "Cronografie"
    └── weird-review.md
```

---

# 🛠 Possibili Evoluzioni

- Salvataggio della revisione nel vault, accanto al racconto
- Confronto tra due versioni dello stesso testo (cosa è migliorato, cosa è regredito)
- Tracciamento dei difetti ricorrenti tra racconti, collegato alle Retrospettive
- Integrazione con la pipeline redazionale multi-agente

---

# 🧭 Principio Fondante

Un testo speculativo non deve solo essere corretto.

Deve:
- sostenere il proprio sistema interno
- mantenere la promessa narrativa
- generare conseguenze credibili
- lasciare una trasformazione

Se non genera frizione, non è pronto.
