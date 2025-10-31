# Problem Reframing per Developer
> Guida pratica per ridefinire i problemi nello sviluppo Laravel e Web

## Indice Rapido

- [Introduzione](#introduzione)
- [Cos'è il Problem Reframing](#cosè-il-problem-reframing)
- [Come funziona](#come-funziona)
- [Tecniche e tool](#tecniche-e-tool)
    - [SCAMPER](#scamper)
    - [6 Cappelli di De Bono](#6-cappelli-di-de-bono)
    - [Mind Mapping](#mind-mapping)
    - [Role-play](#role-play)
    - [5 Whys](#5-whys)
- [Esempi applicati (Laravel & Web Dev)](#esempi-applicati-laravel-e-web-dev)
- [Esercizi Applicati](#esercizi-applicati)
- [Fonti e Riferimenti](#fonti-e-riferimenti)

---

## Introduzione

Il **Problem Reframing** è una tecnica di pensiero strategico che consente di analizzare i problemi da angolazioni diverse, stimolando nuove soluzioni e migliorando i processi creativi. Nel contesto dello sviluppo web e con Laravel in particolare, il reframing può trasformare ostacoli tecnici in opportunità di miglioramento.

---

## Cos'è il Problem Reframing

Il Problem Reframing consiste nel ridefinire il modo in cui si formula e si percepisce un problema. Spesso, una soluzione creativa o efficace emerge solo dopo aver riformulato la domanda iniziale, uscendo dal "frame" mentale che limita le possibilità.

---

## Come funziona

1. **Definisci chiaramente il problema attuale.**
2. **Cambia prospettiva:** Osserva il problema da altri punti di vista (utente, business, team, tecnologia).
3. **Scomponi il problema:** Analizza se esistono sottoproblemi o sintomi.
4. **Riformula la domanda:** Cambia le parole chiave o il focus della questione.
5. **Cerca analogie in altri settori.**
6. **Applica tecniche strutturate di reframing.**

---

## Tecniche e Tool

### SCAMPER

SCAMPER è un acronimo per tecniche operative:
- **Sostituisci:** Cambia un elemento del problema.
- **Combina:** Unisci parti diverse.
- **Adatta:** Modifica per nuovi scopi.
- **Modifica:** Alterare forma, funzione o processo.
- **Metti ad altri usi:** Riuso creativo.
- **Elimina:** Rimuovi ciò che non è essenziale.
- **Riordina:** Cambia sequenza/relation.

**Esempio:**  
Automatizzare il deploy Laravel: potresti *eliminare* la fase manuale, *combinare* con uno script CI/CD, *adattare* tool già usati.

---

### 6 Cappelli di De Bono

Ogni “cappello” rappresenta una modalità di pensiero:
- **Bianco:** Dati oggettivi
- **Rosso:** Emozioni e percezioni
- **Nero:** Critica e rischi
- **Giallo:** Positività e vantaggi
- **Verde:** Creatività e alternative
- **Blu:** Organizzazione e sintesi

**Applicazione:**  
Nel debugging Laravel, usa il cappello nero per analizzare i rischi di una patch, il giallo per vedere i vantaggi, il verde per ipotizzare una soluzione alternativa.

---

### Mind Mapping

Visualizza problemi e possibili soluzioni sotto forma di mappa.  
**Tool utili:** XMind, MindMeister, oppure semplici diagrammi su carta.

**Per developer:**  
Crea un mindmap dei pain point frequenti nel tuo workflow Laravel (deploy, testing, devOps).

---

### Role-play

Affronta il problema come se fossi un altro stakeholder (utente finale, tester, CTO…).

**Esempio:**  
Riformula il refactoring da sviluppatore a “responsabile della sicurezza” o “utente inesperto”.

---

### 5 Whys

Chiedi “Perché?” cinque volte di seguito (o più) per arrivare alla causa radice del problema.

**Esempio:**  
- Perché il deploy Laravel fallisce? Perché ci sono conflitti di versione.
- Perché ci sono conflitti? Perché vengono rilasciate dipendenze non testate in staging.
...

---

## Esempi applicati (Laravel & Web Dev)

**Esempio 1:**  
> Problema: “Il sistema di autenticazione genera molti ticket di supporto.”

- **Reframing:** “Come posso semplificare l’onboarding utente?”  
- **Soluzione potenziale:** Implementare social login o UX guidata.

**Esempio 2:**  
> Problema: “Il deploy manuale genera errori.”

- **Reframing:** “Come posso ridurre la dipendenza dalle azioni manuali?”  
- **Soluzione:** Implementare CICD con GitHub Actions per Laravel.

**Esempio 3:**  
> Problema: “Il codice frontend non è mantenibile.”

- **Reframing:** “Quali pattern posso introdurre per rendere il codice più scalabile?”  
- **Soluzione:** Adottare componenti riutilizzabili con Laravel Livewire.

---

## Esercizi Applicati

**Esercizio 1:**  
Scegli un bug Laravel recente e riformulalo con 3 domande alternative.

**Esercizio 2:**  
Applica lo schema SCAMPER al refactoring di una funzione ripetitiva su Laravel.

**Esercizio 3:**  
Usa i 6 cappelli di De Bono per analizzare una scelta architetturale nel tuo prossimo progetto.

**Esercizio 4:**  
Fai un role-play: immagina di essere un utente finale e scrivi un feedback sulla UX di una dashboard Laravel Nova/BackPack.

**Esercizio 5:**  
Mind mapping: rappresenta graficamente tutte le cause possibili del timeout di una query MySQL su Laravel.

---

## Fonti e Riferimenti

- **Edward de Bono – "Six Thinking Hats"**  
  La metodologia dei cappelli per ampliare la prospettiva nel problem solving:  
  [https://www.debonogroup.com/services/core-programs/six-thinking-hats/](https://www.debonogroup.com/services/core-programs/six-thinking-hats/) | [https://en.wikipedia.org/wiki/Six_Thinking_Hats](https://en.wikipedia.org/wiki/Six_Thinking_Hats)

- **SCAMPER technique**  
  Guida pratica alla tecnica SCAMPER:  
  [https://en.wikipedia.org/wiki/SCAMPER](https://en.wikipedia.org/wiki/SCAMPER) | [https://www.6sigma.us/lean-tools/scamper-technique/](https://www.6sigma.us/lean-tools/scamper-technique/) | [https://careerfoundry.com/en/blog/ux-design/scamper-technique/](https://careerfoundry.com/en/blog/ux-design/scamper-technique/)

- **HBR – Reframing the Problem**  
  Harvard Business Review, articolo sul reframing nella pratica manageriale:  
  [https://stvp.stanford.edu/articles/shift-your-lens-the-power-of-re-framing-problems](https://stvp.stanford.edu/articles/shift-your-lens-the-power-of-re-framing-problems) | [https://medium.com/nyc-design/reframing-the-problem-200f6c966dfc](https://medium.com/nyc-design/reframing-the-problem-200f6c966dfc)

- **IDEO – How to Reframe Your Problems to Unlock Innovation**  
  Metodo design thinking per il reframing:  
  [https://www.ideou.com/blogs/inspiration/how-to-reframe-your-problems-to-unlock-innovation](https://www.ideou.com/blogs/inspiration/how-to-reframe-your-problems-to-unlock-innovation)

- **“Reframing Problems in Software Development” – IEEE Software Magazine**  
  [https://ieeexplore.ieee.org/document/7859317](https://ieeexplore.ieee.org/document/7859317)

- **"The Five Whys Technique" – Lean Enterprise Institute**  
  [https://www.lean.org/lexicon/five-why-analysis](https://www.lean.org/lexicon/five-why-analysis) | [https://en.wikipedia.org/wiki/Five_whys](https://en.wikipedia.org/wiki/Five_whys)

- **Libro: “Agile Retrospectives: Making Good Teams Great” – Esther Derby, Diana Larsen**  
  Ottimo per reframing continuo in team agile.

- **Mind Mapping for Developers**  
  [https://www.smashingmagazine.com/2011/08/mind-mapping-for-web-developers/](https://www.smashingmagazine.com/2011/08/mind-mapping-for-web-developers/)

- **Laravel CI/CD tutorials**  
  [https://laravel-news.com/tag/ci-cd](https://laravel-news.com/tag/ci-cd)

- **Blog: “Reframing Problems in Web Development”**  
  [https://css-tricks.com/problem-reframing/](https://css-tricks.com/problem-reframing/)

---

> **Contribuisci:**  
> Se hai esempi, esercizi o modelli di reframing, apri una PR e condividi la tua esperienza!
