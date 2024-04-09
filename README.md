### script per la preparazione all'esame per le prove di carteggio oltre le 12 miglia
- **requisiti**: un account google e un notebook con python, ad esempio su [colab](https://colab.research.google.com/)
- creare il proprio foglio di lavoro scaricando il [file](https://github.com/gmazzitelli/patente/blob/master/files/domenteOlre12.gsheet) e salvandolo sul proptio google drive
- crearsi gli accessi di scrittura lettura (ad esempio come descritto [qui](https://medium.com/@alestamm/automating-reports-with-google-sheets-jupyter-notebook-connection-8f9cfa5e8588))
- condividere il foglio in scrittura con il servizio creato e in lettura a tutti (piu' rapido per usare i dataframe) salvando le credenziali nel file ".google_credentials.json" (o come volete voi modificando la chimata nello script) e copiarlo nella directory di lavoro.
- sostiure la key con il vistro google sheet. 
- per gli esercizi e' bene usare le carte ufficiali, ma stampati su A3 sono sufficienti i settori della 5D e 42D [qui riportati](https://drive.google.com/drive/folders/1_m-Zc5H9npr0q1Zl4BXpAJV00jlWM8Wc?usp=drive_link): stampare il PDF della 5D su 4 A3 mentre per la 42D e' necessario avere [gimp](https://www.gimp.org/)


nel folder ci sono 2 script, [quesiti](https://github.com/gmazzitelli/patente/blob/master/quesiti.ipynb), che sceglie le domande casulamente e fa ripetere 
gli esercizzi sbagliati (se si vuole fare piu' di 2 volte tutti gli esercizzi bisogna modificare il codice), e uno che far le [statistiche](https://github.com/gmazzitelli/patente/blob/master/statistiche.ipynb)

![stat](/files/stat.png)
