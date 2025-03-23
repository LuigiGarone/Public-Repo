# 🔮 Meta Prophet - Bitcoin Forecast Model

## 📋 Panoramica

Questo modello utilizza [Prophet](https://facebook.github.io/prophet/), un potente framework di previsione sviluppato da Meta (Facebook), per analizzare e prevedere i movimenti di prezzo di Bitcoin (BTC).

## 🛠️ Caratteristiche

- **Analisi dei Componenti**: Scomposizione della serie temporale in trend, stagionalità e componenti residue
- **Gestione Automatica delle Anomalie**: Identificazione e gestione di picchi e cali improvvisi
- **Previsione Multi-Periodo**: Capacità di generare previsioni a breve, medio e lungo termine
- **Intervalli di Confidenza**: Visualizzazione dell'incertezza nelle previsioni

## 🔧 Requisiti Tecnici

Il notebook richiede l'installazione di diverse librerie Python. È possibile installarle utilizzando il file `requirements.txt` incluso:

```bash
pip install -r requirements.txt
```

## 📊 Contenuti del Notebook

- **Preparazione dei Dati**: Caricamento e pre-elaborazione dei dati storici di Bitcoin
- **Addestramento del Modello**: Configurazione e training del modello Prophet
- **Valutazione delle Performance**: Metriche di errore e validazione del modello
- **Visualizzazioni**: Grafici interattivi per l'analisi dei risultati
- **Proiezioni Future**: Previsioni con intervalli di confidenza

## 🚀 Come Iniziare

1. Clona questa repository
2. Installa le dipendenze necessarie con `pip install -r requirements.txt`
3. Apri il notebook `Forecast_btc_Prophet_model.ipynb` in Jupyter
4. Esegui le celle in sequenza per replicare l'analisi

## 📝 Note Aggiuntive

Il modello è stato addestrato su dati storici fino alla data di pubblicazione. Per risultati ottimali con dati più recenti, potrebbe essere necessario riaddestramento.

## ⚠️ Disclaimer

Questo modello è fornito esclusivamente a scopo di ricerca e studio. Non costituisce una consulenza finanziaria o un'indicazione di investimento.