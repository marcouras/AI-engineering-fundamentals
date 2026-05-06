# Lezione 1 — Setup & Fondamenta

📅 Martedì 19/05/2026 | ⏱ 5 ore | Monte ore: 5/30

---

## Obiettivi

- Configurare un ambiente Python con virtual environment
- Effettuare la prima chiamata all'API di Claude
- Capire i parametri fondamentali: `model`, `temperature`, `system`
- Strutturare il progetto su GitHub

---

## File in questa cartella

| File | Descrizione |
|------|-------------|
| `hello_claude.py` | Script base — prima chiamata all'API |
| `esercizi.ipynb` | Notebook con gli esercizi della lezione |
| `soluzione_es4.py` | Soluzione esercizio 4 (deliverable) |

---

## Esercizi

| # | Difficoltà | Descrizione |
|---|-----------|-------------|
| 1 | ★☆☆ | Esegui `hello_claude.py` e modifica la domanda |
| 2 | ★★☆ | Confronta risposte con `temperature=0` e `temperature=1` |
| 3 | ★★☆ | Sperimenta con diversi system prompt |
| 4 | ★★★ | **Deliverable** — chatbot personalizzato con `input()` |

---

## Deliverable

Script `soluzione_es4.py` che:
- Chiede il nome utente con `input()`
- Usa il nome nel messaggio a Claude
- Stampa la risposta in modo formattato
- È pushato in questa cartella su GitHub

---

## Riferimenti Huyen

- Cap. 1 — AI Engineering stack, framework Crawl-Walk-Run
- Cap. 2 (parziale) — temperature, hallucination, context window
