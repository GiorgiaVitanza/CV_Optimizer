# CV_Optimizer
Kaggle.drop(l) - Final project - Edgemony Coding AI Bootcamp


- Prerequisiti:
1. Prima di lanciare il progetto bisogna installare tutti i pacchetti specificati nel file "requirements.txt" anche con un unico comando: pip install -r requirements.txt
2. La versione di python utilizzata è python 3.11
3. Utilizzare due chiavi API per Gemini create tramite AI Studio e salvate una in un file chiamato "api.env" in cui sia scritto API_KEY="nome_chiave_API" e un'altra in un file chiamato "api2.env" in cui sia scritto API_KEY="nome_chiave_API".

Il progetto è così strutturato:
- Il file da lanciare per vedere la web app è "app.py"
In dettaglio aprire il terminale e digitare: streamlit run app.py
- Nella cartella "assets" ci sono le immagini che ci servono per la parte grafica della web app
- Nella cartella "data" ci sono i templates di output per il CV ottimizzato
- Nella cartella "input_data" ci sono degli esempi di CV e annunci di lavoro con cui si può testare la web app
- Nella cartella "models" c'è il file "optimizer.py" che serve ad ottimizzare il CV
- Nella cartella "utils" ci sono:
    1. "cv_parser.py" per l'analisi del CV in input,
    2. "job_parser.py" per l'analisi dell'annuncio di lavoro in input,
    3. "gemini_matcher.py" per confrontare il CV con l'annuncio di lavoro e calcolare il matching score,
    4. "templates.py" che serve a riempire i vari campi dei CV di output con i valori provenienti dall'ottimizzazione.



