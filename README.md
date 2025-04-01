# MiniAI - Gestione Magazzino Intelligente

MiniAI è una soluzione innovativa per la gestione del magazzino che utilizza l'intelligenza artificiale per ottimizzare le operazioni di magazzino, prevedere la domanda e migliorare l'efficienza operativa.

## Caratteristiche Principali

- **Previsioni Intelligenti**: Utilizzo di AI per prevedere la domanda e ottimizzare le scorte
- **Gestione Automatica**: Automatizzazione delle operazioni di magazzino
- **Analisi Avanzate**: Report e dashboard personalizzabili
- **Integrazione API**: API RESTful per integrazione con altri sistemi
- **Gestione Multi-utente**: Supporto per diversi ruoli e permessi
- **Notifiche in Tempo Reale**: Sistema di notifiche per eventi importanti

## Requisiti di Sistema

- Python 3.8+
- SQLite 3
- pip (gestore pacchetti Python)

## Installazione

1. Clona il repository:
```bash
git clone https://github.com/tuousername/miniai.git
cd miniai
```

2. Crea un ambiente virtuale:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Installa le dipendenze:
```bash
pip install -r requirements.txt
```

4. Configura le variabili d'ambiente:
```bash
cp .env.example .env
# Modifica il file .env con le tue configurazioni
```

5. Inizializza il database:
```bash
flask db upgrade
```

6. Crea l'utente amministratore:
```bash
flask create-admin
```

## Avvio dell'Applicazione

```bash
python run.py
```

L'applicazione sarà disponibile all'indirizzo: http://localhost:5000

## Struttura del Progetto

```
miniai/
├── app/
│   ├── static/          # File statici (CSS, JS, immagini)
│   ├── templates/       # Template HTML
│   ├── models/         # Modelli del database
│   ├── routes/         # Route dell'applicazione
│   ├── services/       # Servizi e logica di business
│   └── utils/          # Utility e helper
├── instance/           # File di istanza (database, etc.)
├── migrations/         # Migrazioni del database
├── tests/             # Test unitari e di integrazione
├── .env               # Variabili d'ambiente
├── config.py          # Configurazioni
├── requirements.txt   # Dipendenze
└── run.py            # Script di avvio
```

## Contribuire

1. Fai un fork del repository
2. Crea un branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Committa le tue modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Pusha al branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## Licenza

Questo progetto è sotto licenza MIT. Vedi il file `LICENSE` per i dettagli.

## Supporto

Per supporto, email info@miniai.com o apri un issue nel repository GitHub.

## Crediti

- Design by [Your Name]
- Icons by [Icon Provider]
- Fonts by Google Fonts 