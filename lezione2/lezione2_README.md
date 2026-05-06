# Lezione 2 — Prompt Engineering

📅 Giovedì 21/05/2026 | ⏱ 5 ore | Monte ore: 10/30

---

## Obiettivi

Al termine di questa lezione saprai:

- Distinguere tra tecniche di **elicitazione** e tecniche di **steering**
- Scrivere prompt efficaci con **zero-shot**, **few-shot** e **Chain-of-Thought**
- Costruire un **system prompt** per definire la personalità del chatbot
- Difenderti dal **prompt injection**
- Creare una **Prompt Library** con template riutilizzabili

---

## File in questa cartella

| File | Descrizione |
|------|-------------|
| `Lezione2_Colab.ipynb` | Notebook con teoria, esempi e esercizi |
| `Lezione2_TUONOME.ipynb` | ← Il tuo notebook completato (da caricare) |

---

## Come seguire la lezione

1. Apri il notebook su Colab cliccando il badge:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcouras/AI-engineering-fundamentals/blob/main/lezione2/Lezione2_Colab.ipynb)

2. `File → Salva una copia in Drive`
3. Esegui le celle dall'alto verso il basso con `Shift+Invio`
4. Completa tutti e 4 gli esercizi

---

## Esercizi

| # | Difficoltà | Descrizione |
|---|-----------|-------------|
| 1 | ★☆☆ | Zero-shot vs Few-shot su un task di classificazione a tua scelta |
| 2 | ★★☆ | Chain-of-Thought su un problema logico |
| 3 | ★★☆ | System prompt per il chatbot di supporto WiData |
| 4 | ★★★ | **Deliverable** — Prompt Library con 10 template documentati |

---

## 📬 Compito a casa

Entro la sera della lezione:

```bash
# Scarica il notebook da Colab: File → Scarica → .ipynb
# Rinominalo: Lezione2_TUONOME.ipynb

cp ~/Downloads/Lezione2_TUONOME.ipynb lezione2/
git add lezione2/
git commit -m "Lezione 2 completata"
git push
```

---

## Deliverable

File `Lezione2_TUONOME.ipynb` con la **Prompt Library** completa:
- 10 template documentati
- Ogni template ha: nome, system prompt, template con `{variabili}`, esempio, parametri consigliati
- Almeno 1 template legato a WiData/IoT

---

## Riferimenti Huyen

- **Cap. 5** — Prompt Engineering (integrale): elicitazione, steering, zero-shot, few-shot, CoT, self-consistency, defensive prompting

---

## Prossima lezione

📅 **Martedì 26/05** — Conversazione & Memoria

**Leggi prima:** Huyen Cap. 2 (sezione context window e token)
