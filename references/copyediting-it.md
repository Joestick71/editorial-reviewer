# Riferimento – Copyediting italiano

**Uso**: lancia `Grep` sul file del testo con ciascun pattern (output `content` con numeri di riga, oppure `count` per la frequenza). I pattern usano la sintassi regex di ripgrep; aggiungi `-i` dove indicato. I risultati sono **candidati**: leggi il contesto e scarta i falsi positivi prima di riportarli.

**Apostrofi e virgolette**: i testi possono usare `'` oppure `’`, e `"` oppure `“ ”` oppure `« »`. I pattern usano classi come `['’]` per coprire entrambe le forme.

**Soglie**: sono indicative. Riporta sempre la frequenza (occorrenze e, quando utile, per 1.000 parole) e giudica nel contesto: un pattern concentrato nel climax pesa più dello stesso pattern distribuito.

---

## A. Pattern stilistici

**Avverbi in -mente** — soglia: oltre 6 per 1.000 parole. Falsi positivi: veemente, clemente, demente.
```
\b\w{3,}mente\b
```

**Verbi filtro, terza persona** (`-i`) — critici nelle scene ad alta tensione.
```
\b(vide|vedeva|sentì|sentiva|udì|notò|notava|percepì|pensò|pensava|osservò|si rese conto|si accorse|capì|sembrava|sembrò)\b
```

**Verbi filtro, prima persona** (`-i`)
```
\b(vidi|vedevo|sentii|sentivo|notai|notavo|percepii|pensai|pensavo|mi resi conto|mi accorsi|capii|mi sembrava|mi sembrò)\b
```

**Esistenziali deboli** (`-i`) — rilevanti in apertura di paragrafo o di scena.
```
\b(c['’]era|c['’]erano|vi era|vi erano|esisteva|esistevano)\b
```

**Emozioni nominate e cliché fisiologici** (`-i`) — ogni occorrenza nel climax è candidata.
```
brivid|cuore in gola|cuore (mi |gli |le )?(batteva|mancò|perse un colpo)|si gelò|senza fiato|fiato sospeso|nodo alla gola|gola secca|pelle d['’]oca
```

**Aggettivi d'effetto** (`-i`) — dicono al lettore cosa provare; nel weird oltre 3 per 1.000 parole è un segnale.
```
\b(inquietant|sinistr|misterios|spaventos|terrificant|agghiacciant|angosciant)\w*|\bstran[oaie]\b
```

**Verbi dichiarativi enfatici** (`-i`) — oltre uno ogni cinque battute; preferire "disse" o nessuna attribuzione.
```
\b(sibilò|ringhiò|tuonò|sentenziò|ribatté|esclamò|sbottò|sospirò|mormorò|sussurrò|gracchiò|ruggì)\b
```

**Avverbio sulla battuta** (`-i`) — ogni occorrenza è candidata.
```
\b(disse|rispose|chiese|domandò|aggiunse)\s+\w+mente\b
```

**Gerundio in apertura di paragrafo** — tre o più paragrafi ravvicinati.
```
^\s*[A-ZÀ-Ù]\w*(ando|endo)\b
```

**Paragrafi che aprono con articolo** — tre o più consecutivi (controlla i numeri di riga).
```
^\s*(Il|Lo|La|I|Gli|Le|L['’]|Un|Una|Uno)\s
```

**Pronomi soggetto superflui** — l'italiano ha il soggetto implicito: l'abuso è un calco dall'inglese.
```
(^|[.!?…]\s+)(Lui|Lei|Egli|Ella|Esso|Essa|Loro|Io)\s
```

**Possessivi superflui con parti del corpo** (`-i`) — "alzò la sua mano" → "alzò la mano".
```
\b(la sua|il suo|le sue|i suoi|la mia|il mio|le mie|i miei)\s+(mano|mani|testa|occhi|bocca|braccio|braccia|spalle|spalla|viso|volto|capelli|dita|labbra)\b
```

**Passivi** (`-i`) — sistematici con agente noto e rilevante.
```
\b(venne|vennero|veniva|venivano|fu|furono)\s+\w+(at|ut|it)[oaie]\b
```

**Maiuscole a metà frase** — produce l'elenco da filtrare a mano: separa i nomi propri dalle maiuscole di prestigio ("il Compito", "il Giuramento") e conta queste ultime.
```
[a-zà-ù,;:]\s+[A-ZÀ-Ù][a-zà-ù]{3,}
```

Ripetizioni lessicali ravvicinate, pronomi con referente ambiguo, aggettivi a catena e discorso indiretto libero indistinto non si trovano con un pattern: verificali in lettura, almeno nelle scene chiave.

---

## B. Norme ortotipografiche italiane

**Punteggiatura delle battute secondo l'uso inglese** — virgola o punto dentro le virgolette prima dell'attribuzione (`"Vieni," disse`). Nell'uso italiano la punteggiatura segue la virgoletta di chiusura: `«Vieni», disse` oppure `«Vieni» disse`. Scegli una forma e applicala ovunque.
```
[,.]["”»]\s+(disse|rispose|chiese|domandò|sussurrò|mormorò|aggiunse|gridò|esclamò|replicò|sibilò|ribatté)
```

**Sistema di virgolette dei dialoghi** — conta separatamente le battute che aprono con ciascun segno; un solo sistema per tutto il testo (virgolette alte “ ”, caporali « », oppure lineetta — come sistema alternativo coerente). Le virgolette dritte `"` sono accettabili in bozza, non in un testo da inviare.
```
^\s*"
^\s*“
^\s*«
^\s*[—–]
```

**D eufonica davanti a consonante** — errore.
```
\b(ad|ed|od)\s+[b-df-hj-np-tv-zB-DF-HJ-NP-TV-Z]
```

**D eufonica davanti a vocale diversa** — l'uso moderno la limita alla stessa vocale ("ad andare", "ed ecco"); restano accettate le espressioni cristallizzate "ad esempio" e "ad eccezione".
```
\bad\s+[eiouEIOUèéìòù]
\bed\s+[aiouAIOUàìòù]
```

**Accenti, apostrofi, È maiuscola** (`-i`) — perché, poiché, affinché, benché, finché, giacché, né, sé, trentatré: accento acuto; "un po'" con apostrofo; "qual è" senza apostrofo; "È" e non "E'".
```
\b(perchè|poichè|affinchè|benchè|finchè|giacchè|nè|sè|trentatrè|ventitrè)\b|\bun pò\b|\bqual['’]\s?è\b|\bE['’]\s
```

**Accenti non italiani** — salvo nomi stranieri, in italiano su a, i, u l'accento è grave: à, ì, ù.
```
[áíúÁÍÚ]
```

**Puntini di sospensione** — tre punti oppure il carattere …, sempre lo stesso; mai quattro o più.
```
\.\.\.
…
\.{4,}
```

**Trattini usati come incisi** — per gli incisi lineetta (—) o trattino medio (–); il trattino breve (-) solo nei composti. Un solo sistema.
```
\s-\s|--
```

**Mesi e giorni con la maiuscola a metà frase** — in italiano vanno minuscoli.
```
[a-zà-ù,;]\s+(Gennaio|Febbraio|Marzo|Aprile|Maggio|Giugno|Luglio|Agosto|Settembre|Ottobre|Novembre|Dicembre|Lunedì|Martedì|Mercoledì|Giovedì|Venerdì|Sabato|Domenica)\b
```

**Spazi doppi**
```
\S  +\S
```

---

## C. Calchi dall'inglese e falsi amici

Cerca con `-i`. Ogni voce è un candidato: in alcuni contesti l'uso italiano è corretto (es. "assumere" = prendere alle dipendenze).

| Forma sospetta | Pattern | Calco di | Forma italiana |
|---|---|---|---|
| eulogia | `\beulogi` | eulogy | elogio funebre, orazione funebre (*eulogia* in italiano è il pane benedetto) |
| intervista di lavoro | `\bintervist\w* di lavoro` | job interview | colloquio di lavoro |
| realizzare (= capire) | `\brealizz\w*` | to realize | rendersi conto, capire |
| eventualmente (= alla fine) | `\beventualmente\b` | eventually | alla fine, prima o poi |
| attualmente (= in realtà) | `\battualmente\b` | actually | in realtà, in effetti |
| supportare | `\bsupport(are\|o\|a\|ava\|ò\|ando)\b` | to support | sostenere, appoggiare |
| assumere (= presumere) | `\bassum\w*` | to assume | supporre, presumere |
| evidenza (= prova) | `\bevidenz\w*` | evidence | prove, indizi |
| consistente (= coerente) | `\bconsistent\w*` | consistent | coerente, costante |
| drammaticamente | `\bdrammaticamente\b` | dramatically | radicalmente, nettamente |
| fare senso | `\bfa(ceva\|re\|nno)? senso\b` | to make sense | avere senso |
| giocare un ruolo | `\bgioc\w* un ruolo\b` | to play a role | avere, svolgere un ruolo |
| processare (dati) | `\bprocess\w* (le \|i \|dei \|delle )?(informazion\|dati)` | to process | elaborare |
| silicone (= silicio) | `\bsilicon\w*` | silicon | silicio (il silicone è un polimero) |
| libreria (= biblioteca) | `\blibreri\w*` | library | biblioteca (nel software "libreria" è accettato) |
| educato (= istruito) | `\beducat\w*` | educated | istruito, colto |
| sensibile (= sensato) | `\bsensibil\w*` | sensible | sensato, ragionevole |
| salvare tempo | `\bsalv\w* (tempo\|soldi)\b` | to save time | risparmiare |
| in accordo a | `\bin accordo (a\|con)\b` | according to | secondo, in base a |
| scioccato | `\bscioccat\w*` | shocked | sconvolto, scosso |

Nella tabella `\|` serve solo a non rompere la tabella Markdown: nel pattern passato a `Grep` scrivi `|` senza barra.

---

## D. Cosa riportare

- Frequenza di ogni pattern della sezione A (occorrenze e per 1.000 parole) e le 2–3 occorrenze più rappresentative con numero di riga.
- Sistema di virgolette rilevato e incoerenze.
- Violazioni ortotipografiche della sezione B raggruppate per tipo, con la forma corretta.
- Calchi confermati dopo la verifica del contesto, con la forma italiana proposta.
