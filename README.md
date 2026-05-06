# AI Engineering Fundamentals 🤖

**ITS Novitas 4.0 — Corso Sviluppatore Intelligenza Artificiale**  
Docente: Marco Uras | Maggio–Giugno 2026 | 30 ore (6 lezioni)

---

## 🎯 Obiettivo del corso

Costruire un chatbot con intelligenza artificiale **da zero**, partendo dalla prima chiamata API fino al deploy pubblico su internet.

Ogni lezione aggiunge un nuovo livello di capacità al chatbot. Alla fine del corso avrai un prodotto reale, accessibile online, documentato e pronto da mostrare.

---

## 🗓 Programma

| # | Data | Argomento | Monte ore |
|---|------|-----------|-----------|
| 1 | Martedì 19/05 | [Setup & Fondamenta](./lezione1/) | 5/30 |
| 2 | Giovedì 21/05 | [Prompt Engineering](./lezione2/) | 10/30 |
| 3 | Martedì 26/05 | [Conversazione & Memoria](./lezione3/) | 15/30 |
| 4 | Giovedì 28/05 | [RAG — Conoscenza Personalizzata](./lezione4/) | 20/30 |
| 5 | Giovedì 04/06 | [Tools, Function Calling & MCP](./lezione5/) | 25/30 |
| 6 | Martedì 09/06 | [UI Web, Valutazione & Deploy](./lezione6/) | 30/30 |

---

## 🛠 Stack tecnologico

Tutto **gratuito**:

| Strumento | Uso |
|-----------|-----|
| Python 3.11+ | Linguaggio base |
| [Anthropic Claude API](https://docs.anthropic.com) | Modello LLM (tier free) |
| [ChromaDB](https://docs.trychroma.com) | Vector store per RAG |
| [Streamlit](https://docs.streamlit.io) | Interfaccia web |
| [Streamlit Cloud](https://streamlit.io/cloud) | Deploy pubblico gratuito |
| GitHub | Versionamento e portfolio |

---

## 🚀 Come iniziare

### 1. Clona la repository
```bash
git clone https://github.com/TUO-USERNAME/AI-engineering-fundamentals.git
cd AI-engineering-fundamentals
```

### 2. Crea il virtual environment
```bash
python -m venv venv

# Mac/Linux
source venv/bin/activate

# Windows
venv\Scripts\activate
```

### 3. Installa le dipendenze
```bash
pip install -r requirements.txt
```

### 4. Configura la API key
```bash
# Copia il file di esempio
cp .env.example .env

# Apri .env e inserisci la tua chiave Anthropic
# ANTHROPIC_API_KEY=sk-ant-...
```

> ⚠️ **Non committare mai il file `.env`** — è già incluso nel `.gitignore`

### 5. Ottieni la API key gratuita
Registrati su [console.anthropic.com](https://console.anthropic.com) e crea una API key.

---

## 📁 Struttura del progetto

```
AI-engineering-fundamentals/
├── lezione1/          # Setup & Fondamenta
├── lezione2/          # Prompt Engineering
├── lezione3/          # Conversazione & Memoria
├── lezione4/          # RAG
├── lezione5/          # Tools & MCP
├── lezione6/          # UI Web & Deploy
├── progetto_finale/   # Il tuo chatbot completo
├── .env.example       # Template variabili ambiente
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 📖 Libro di riferimento

**Chip Huyen — AI Engineering: Building Applications with Foundation Models**  
O'Reilly Media, 2025

Capitoli usati nel corso: 1, 2 (parziale), 3, 4, 5, 6, 10

---

## 🤝 Come contribuire (studenti)

1. Ogni studente lavora nella propria fork della repository
2. I deliverable vanno nella cartella della lezione corrispondente
3. Usa commit chiari: `git commit -m "Lezione1: hello_claude funzionante"`
4. Il progetto finale va in `progetto_finale/`

---

*Fondazione ITS Academy Novitas 4.0 — [www.itsnovitas.it](https://www.itsnovitas.it)*
# AI-engineering-fundamentals
