Dataset utilizzati:
italy_region #dataset contenente le informazioni sulla situazione italiana regionale

Le previsioni sono state effettuate su 3 regioni (Lombardia, Campania e Valle d'Aosta) in quanto regioni con i valori di PIL, Densità demografica più alti e bassi, rispettivamente Lombardia, Campania e Valle d'Aosta.

Al dataset delle regioni è stata aggiunta una colonna denominata "new_cases" che contiene il valore giornaliero di nuovi casi di infezione.

Le previsioni sono state effettuate utilizzando auto arima, sarima e infine prophet.