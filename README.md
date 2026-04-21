# 📊 L'Espansione Silenziosa: Analisi della Ricettività Digitale a Riposto
### Rapporto Tecnico di Triangolazione Dati: ISTAT, Airbnb, OpenStreetMap (2024-2026)

---

## 📋 Descrizione del Progetto
Questo studio analizza l'evoluzione del mercato turistico nel Comune di **Riposto (CT)** nel periodo 2024-2026. Attraverso una metodologia di integrazione multi-fonte, l'analisi evidenzia il "Sorpasso Digitale" del territorio rispetto ai benchmark di **Giardini-Naxos** e **Zafferana Etnea**.

L'obiettivo è fornire all'Amministrazione Locale una base scientifica per trasformare la crescita spontanea in una programmazione consapevole basata sull'evidenza dei dati.

### 💡 Risultati Chiave (Insights dal Report)
* **Eccedenza Digitale**: A Riposto, il mercato extralberghiero su Airbnb è oltre il triplo rispetto all'offerta ufficiale censita, con un'incidenza del **333,33%**.
* **Capacità "Ombra"**: Sono stati rilevati **+187 posti letto** aggiuntivi rispetto alle statistiche ISTAT, rendendo la sharing economy la vera infrastruttura portante del territorio.
* **Performance Premium**: Riposto genera un **Revenue Annuo Medio di 3.244,72€** per unità, superando l'efficienza economica del benchmark di massa di Giardini-Naxos.
* **Eccellenza Qualitativa**: Il territorio domina la reputazione digitale con un **rating medio di 4.81/5**.
* **Dominanza Tipologica**: L'offerta è trainata per l'**83,8%** dalla categoria "Entire home/apt", evidenziando una trazione fortemente residenziale.

---

## 🛠️ Metodologia e Validazione
Il dataset è stato processato seguendo rigorosi standard di Data Science per garantire l'affidabilità delle evidenze:
* **Data Sourcing**: Integrazione di Inside Airbnb (LTM 2025-2026), ISTAT (2024) e Geospatial Data Scraping via OpenStreetMap.
* **Trattamento Outlier**: Applicazione del **Tukey's Extreme Method** per la rimozione delle anomalie statistiche di prezzo.
* **KPI Modeling**: Implementazione del **San Francisco Model** per la stima dei tassi di occupazione e del fatturato reale basato sul Review-to-Stay ratio.

---

## 💻 Tech Stack
Il workflow è stato sviluppato interamente in **Python**, utilizzando le seguenti librerie:
* `pandas`: Manipolazione e pulizia dei dati istituzionali e di mercato.
* `seaborn` & `matplotlib`: Visualizzazione statistica avanzata (Distribuzione prezzi, Boxplot, Incidenza digitale).
* `osmnx`: Geospatial Data Scraping tramite protocollo Overpass API di OpenStreetMap.
* `requests`: Gestione delle chiamate per il recupero dati dal web.

---

## 🔒 Riservatezza e Integrità dei Dati
Si precisa che l'analisi presentata nel **Rapporto Tecnico ufficiale** è stata condotta sull'intero dataset reale. In questa repository pubblica:
1. **I dati originali NON sono inclusi** per ragioni di licenza e riservatezza dei dati istituzionali e di mercato.
2. **Viene utilizzato un dataset sintetico/dummy** che ricalca la struttura degli originali per permettere di testare la logica del codice e la riproducibilità dei grafici senza violare i vincoli di riservatezza.

---

## 👤 Autore
**Francesco Scavo** *Analista Dati / Studente di Data Science* www.linkedin.com/in/francescoscavo
