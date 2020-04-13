# Ponti Ripetitori Italiani - Database

In questo repository si trova il dump di un database (`SQLite3`) che contiene i parametri relativi ai ponti ripetitori italiani, come risulta dal foglio elettronico pubblicato da [IK2ANE](http://www.ik2ane.it/ham.htm).

Questo repository è aggiornato automaticamente, entro 24 ore, in corrispondenza degli aggiornamenti rilasciati da IK2ANE.

## Creare un database

Per creare un database `SQLite3` a partire dal file dump `repeaters.sql`, da riga di comando:

```bash
cat repeaters.sql | sqlite3 repeaters.db
```

Per navigare i dati nell'unica tabella `repeaters` del database si può utilizzare `sqlitebrowser`, che ha una comoda interfaccia grafica e consente, fra l'altro, di eseguire query `SQL`.

## Licenza d'uso

La licenza d'uso di questi dati è quella indicata da IK2ANE nella sua pagina web sopra riportata, indicata anche nel file scaricabile [`pontixls.xls`](http://www.ik2ane.it/pontixls.xls).