  ------------------------------------------------------------
  OPIS PROJEKTA
  ------------------------------------------------------------
  Ovaj projekt implementira virtualnog asistenta za Fakultet
  primijenjene matematike i informatike (MATHOS). Sustav
  odgovara na studentska pitanja korištenjem kombinacije:

  1) BiLSTM modela za klasifikaciju namjere (intent
  classification) 2) TF-IDF + kosinusne sličnosti za
  dohvaćanje najprikladnijeg odgovora

STRUKTURA PROJEKTA

. ├── baza_faq.csv ├── models/ │ └── intent_bilstm.pt ├──
training_notebook.ipynb ├── chatbot_notebook.ipynb ├──
confusion_matrix_test.png ├── seminar.tex ├── requirements.txt └──
README.txt

  ---------------------
  POKRETANJE PROJEKTA
  ---------------------

1)  Instalacija paketa:

pip install -r requirements.txt

2)  Pokretanje treninga: Otvoriti bilstm.ipynb i pokrenuti
    sve ćelije. Model se sprema u: models/intent_bilstm.pt

3)  Pokretanje chatbot-a: Otvoriti chat.ipynb i pokrenuti
    chat_loop() funkciju.


  -------------
  TEHNOLOGIJE
  -------------

-   Python 3.x
-   PyTorch
-   Scikit-learn
-   Pandas
-   NumPy
-   Matplotlotlib
  -------
  AUTOR
  -------

Matko Gašparić
