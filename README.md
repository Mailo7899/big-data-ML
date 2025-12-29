# 📊 Predictive Modeling, AI, Machine Learning, NLP & XAI Data Science Projects

Repository che raccoglie i principali progetti accademici e applicativi sviluppati nell’ambito di **Machine Learning, Deep Learning, NLP, LLM, Explainable AI (XAI) e Statistica Computazionale**.  
I progetti sono organizzati per area tematica e includono sia applicazioni su dati reali sia studi metodologici.

---

## 🧠 LLM, NLP, XAI & Recommendation Systems

### 📚 BookMates – Recommendation System per Compagni di Lettura
**Sistema di raccomandazione di libri basato su NLP e Deep Learning**

Il progetto utilizza due dataset:  
- informazioni sui libri (titolo, autore, prezzo, data di uscita, descrizione)  
- recensioni degli utenti associate ai libri  

L’obiettivo è la creazione di un **sistema di raccomandazione di libri personalizzato**, in grado di suggerire titoli simili a partire da un libro fornito dall’utente.

**Tecniche e strumenti principali:**
- Word Embeddings con **Sentence-BERT (SBERT)**
- **TF-IDF** e **Cosine Similarity**
- Ricerca fuzzy dei titoli tramite **RapidFuzz**
- Analisi del sentiment delle recensioni con **BERT + CNN**
- Interpretabilità del modello con **LIME**
- Riassunto automatico dei libri tramite **BART**
- Interfaccia grafica interattiva sviluppata con **Gradio**

Il sistema restituisce i **10 libri più simili**, includendo:
- motivazioni delle recensioni positive (XAI)
- riassunto del contenuto del libro consigliato

---

### 🏥 Predizione della Mortalità Ospedaliera da Big Data Sanitari (SDO)
**Machine Learning, Deep Learning, NLP e Explainable AI applicati alla sanità**

Studio basato su dati reali provenienti dalle **Schede di Dimissione Ospedaliera (SDO) italiane** (2012–2016), per un totale di circa **3,5 milioni di pazienti**.

Il dataset comprende:
- **dati strutturati** (variabili cliniche e amministrative)
- **dati non strutturati** (descrizioni testuali delle diagnosi ICD-9-CM)

**Obiettivi principali:**
- Sviluppare e confrontare modelli di **ML, DL e NLP** per la previsione della mortalità ospedaliera
- Valutare l’**interpretabilità** dei modelli tramite tecniche di **Explainable AI (XAI)**

**Risultati principali:**
- L’approccio **ibrido** (dati strutturati + testuali) mostra le migliori performance  
  - Accuracy ≈ 97%  
  - Macro F1 ≈ 78%  
  - ROC AUC ≈ 0.96  

Il progetto evidenzia il potenziale dell’AI nel supporto alle decisioni cliniche, migliorando **accuratezza, trasparenza e affidabilità** dei modelli predittivi in ambito medico.

---

## 📈 Modelli Predittivi & Machine Learning

### 🥗 Classificazione del Livello di Obesità
**Modelli di Machine Learning su dati comportamentali e antropometrici**

Il dataset, proveniente dalla **UCI Machine Learning Repository**, contiene **2111 osservazioni** su **17 variabili**, relative a individui di Messico, Perù e Colombia.

Il target è la variabile **NObesity**, con 7 livelli di classificazione (da sottopeso a obesità di tipo III).

**Caratteristiche del dataset:**
- Abitudini alimentari
- Condizioni fisiche
- Dati demografici e antropometrici
- Dati parzialmente sintetici (SMOTE)

**Obiettivo:**
Individuare il **miglior modello classificatore** per identificare correttamente i soggetti obesi e generalizzare su nuove osservazioni.

Il progetto evidenzia l’importanza della prevenzione e del supporto decisionale in ambito sanitario.

---

### 💼 Predizione del Default dei Prestiti – US Small Business Administration
**Classificazione del rischio creditizio delle PMI**

Dataset reale della **US SBA**, composto da circa **89.000 osservazioni** e **27 variabili** economiche, finanziarie e amministrative.

**Target:**
- `MIS_Status` (binaria):  
  - Prestito rimborsato (PIF)  
  - Prestito in default (CHGOFF)

**Obiettivo:**
Sviluppare modelli predittivi in grado di:
- identificare le aziende a rischio di insolvenza
- supportare le decisioni nel mercato del credito

Il progetto affronta una problematica reale con forti implicazioni economiche e sociali.

---

### 🚗 Statistica Computazionale – Predizione del Prezzo delle Auto
**Analisi statistica avanzata e modellazione robusta**

Studio basato su **205 osservazioni** e **26 variabili**, con l’obiettivo di individuare i fattori più rilevanti nella determinazione del prezzo di un’automobile.

**Approccio metodologico:**
- Analisi dei dati e gestione dei missing values
- Eliminazione della collinearità
- Trasformazioni di Box-Cox
- Model Selection
- Analisi di outlier e punti influenti
- Verifica dell’eteroschedasticità
- Inferenza robusta e Bootstrap
- Confronto tra modello iniziale e finale

Il progetto unisce **statistica classica e computazionale**, con particolare attenzione all’interpretabilità e alla robustezza del modello.

---

## 🛠️ Linguaggi e Strumenti
- **Python, R**
- **scikit-learn, TensorFlow, Keras, PyTorch**
- **NLP & Transformers (HuggingFace)**
- **Explainable AI (LIME)**
- **Statistica Computazionale**
- **Data Visualization & Data Analysis**

---

📌 *Questa repository rappresenta un percorso di studio e ricerca focalizzato sull’utilizzo dei dati e dell’intelligenza artificiale per supportare decisioni complesse in ambito sanitario, economico e sociale.*
