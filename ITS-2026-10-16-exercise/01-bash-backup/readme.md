\# 01 — A safer backup script



\## La mia soluzione



Uno script di backup più sicuro dovrebbe:



1\. Verificare che sorgente e destinazione siano disponibili.

2\. Creare una nuova copia con data e ora.

3\. Interrompersi in caso di errore, senza cancellare i backup precedenti.

4\. Verificare che la copia sia completa.

5\. Eliminare solo i backup scaduti e mantenere più versioni.

6\. Registrare l'esito dell'operazione in un log.



\## Ragionamento



Questi passaggi riducono il rischio di perdita dei dati e permettono di recuperare versioni precedenti.



\## Verifica



Ripristinare il backup in un ambiente di test e verificare che i file e l'applicazione funzionino correttamente.



\*Verifiche non eseguite.\*



\## Incertezze / aspetti da approfondire



\- Numero di versioni da conservare.

\- Spazio disponibile e destinazione separata.

\- Consistenza dei dati durante la copia.













