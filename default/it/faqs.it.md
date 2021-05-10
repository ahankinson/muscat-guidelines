### Utilizzare Muscat&nbsp;  

1. **Dove posso trovare dei&nbsp;tutorial per Muscat?**  
Tutti i tutorial si trovano collegati sulla pagina Muscat&nbsp;della Redazione centrale RISM:&nbsp;[http://www.rism.info/en/community/muscat.html](http://www.rism.info/en/community/muscat.html)
2. **Come posso prendere contatto con altri utenti&nbsp;Muscat?**  
Per prendere contatto con gli sviluppatori Muscat, riferisci qualsiasi errore, domanda, commento o suggerimento in qualsiasi momento a&nbsp;muscat@rism.info.&nbsp;  
  
**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**,&nbsp;un gruppo&nbsp;Google, è la lista di discussione ufficiale Muscat cui ogni utente Muscat deve partecipare. Ogni annuncio ufficiali da parte della Redazione centrale e degli sviluppatori Muscat sarà diffuso unicamente attraverso questo gruppo. Inoltre, ogni utente Muscat è incoraggiato a porre domande o sollevare questioni da discutere.&nbsp;  
  
Non è necessario possedere un conto Google. Un invito a partecipare al gruppo ti verrà mandato al momento di ricevere le informazioni sul tuo conto Muscat.  
  
Vi è anche un canale di discussione su Slack:&nbsp;  
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)  
  
3. **Tutta la bibliografia citata in Muscat si trova presso la Redazione centrale?**  
No, soltanto la bibliografia segnata con "HB" o "Handbibliothek" o "RISM-ZR" si trova effettivamente nel nostro ufficio. I materiali sono a disposizione di tutti coloro che contribuiscono a RISM, dunque se abbiamo una pubblicazione che vuoi consultare, puoi farcelo sapere e cercheremo di farti avere ciò che ti serve. Anche se ti interessi di una pubblicazione che non è nel nostro ufficio, è possibile che conosciamo qualcuno che la possiede.  
  
4. **Cosa faccio se dimentico la mia password o desidero cambiarla?**  
Le password sono gestite dalla Redazione centrale. Mettiti in contatto con noi se hai perduto la tua password. Non puoi cambiare da solo la tua password.  
  
5. **Posso mostrare&nbsp;Muscat ai miei colleghi?&nbsp;Posso realizzare una dimostrazione di&nbsp;Muscat a un congresso o un seminario?**  
Certamente! Esiste una&nbsp;versione di prova di&nbsp;Muscat esattamente per questi scopi all'indirizzo&nbsp;[http://muscat-training.rism.info](http://muscat-training.rism.info/).&nbsp;  
  
Ogni utente&nbsp;Muscat può effettuare il&nbsp;login con le proprie credenziali personali. Esistono anche 50 conti di prova&nbsp;(da "training01@rism.info" a "training50@rism.info"), tutti con la&nbsp;password "password". Si può usare uno qualsiasi di questi conti di prova.  
  
Ogni cosa nella versione di prova può essere aggiunta, modificata o cancellata. Viene sincronizzata una volta alla settimana (di domenica) con i dati attuali di Muscat. Questo significa che anche le schede più recenti sono disponibili, ma anche che quelle create nella versione di prova saranno cancellate.&nbsp;  
  
6. **Nello storico delle modifiche, cosa significa se l'autore è indicato come&nbsp;"[system]"?**  
Puoi osservare una modifica di sistema se viene modificato&nbsp;uno dei campi indicizzati collegato alla tua scheda. Il cambiamento nella voce d'autorità sarà segnalato come un cambiamento anche nella tua scheda.  
  
7. **Posso creare una scheda basandomi su una descrizione in un catalogo stampato?**  
Sì! A volte, per vari motivi, non è possibile avere accesso a una fonte ed è disponibile soltanto la sua descrizione in un catalogo stampato o in un catalogo tematico.&nbsp;Puoi usare una simile descrizione come base per la tua notizia. Se decidi di farlo, aggiungi una **Osservazione (500)** come "Scheda basata sulla descrizione in YouV" e istituisci il relativo collegamento&nbsp;nel campo&nbsp;**Riferimenti bibliografici (691)**.

&nbsp;

### Aspetti tecnici di Muscat
**1. Che requisiti tecnici esistono per Muscat?**  

- Muscat è indipendente dalla piattaforma e funziona su Macintosh e PC.
- Si accede attraverso un URL e si richiede una connessione Internet.
- Muscat funziona al meglio su schermi di almeno 1366 x 768 pixel.
- Muscat è ottimizzato per Firefox e Chrome. Si prega di non usare Internet Explorer!   

**2. Quali sono gli aspetti tecnici salienti di Muscat?**

- Muscat è open source. Il codice sorgente è disponibile presso il deposito [GitHub](https://github.com/rism-ch/muscat).
- Muscat è un’applicazione Ruby on Rails.
- [Verovio](http://www.verovio.org/pae-examples.xhtml) è utilizzato per visualizzare gli incipit musicali attraverso MEI.&nbsp;
- Solr è utilizzato come motore di ricerca.
- Muscat ha un servizio&nbsp;[SRU](https://github.com/rism-ch/muscat/wiki/SRU)&nbsp;e uno strumento di [download SRU](https://github.com/rism-international/sru-downloader)&nbsp;per esportare schede&nbsp;MARCXML.
Puoi trovare ulteriori informazioni sullo sviluppo di Musicat sul sito di [RISM Svizzera](http://rism-ch.org/infrastructure/muscat.html?locale=en).   

**3. Quali sono gli aspetti tecnici della ricerca per incipit?**

- È basata sul motore di ricerca&nbsp;[Themefinder](http://www.themefinder.org/)&nbsp;sviluppato all'Università di&nbsp;Stanford.&nbsp;
- Sfrutta il sistema di indicizzazione sottostante&nbsp;(Solr), utilizzato per tutte le ricerche in&nbsp;Muscat, che è stato adattato per permettere l'analisi della notazione PAE utilizzata nel compilare le schede. Il processo di indicizzazione è del tutto trasparente per utenti e catalogatori, ed è necessaria soltanto il normale inserimento della notazione codificata nel campo 031.

**4. Cosa caratterizza Muscat, ad esempio?**

- **Versionamento** : Chi cataloga può vedere i cambiamenti fatti alle schede
- **VIAF** : I nomi di persona possono essere importati attraverso il [Virtual International Authority File (VIAF)](https://viaf.org/).&nbsp;

**5. Cosa è in programma per lo sviluppo futuro di Muscat?**

- Integrare immagini utilizzando [IIIF](http://iiif.io/)   
- Accogliere i commenti degli utenti
- Aggiungere ulteriori traduzioni dell’interfaccia e delle regole di catalogazione
- L’importazione/esportazione aggregata e differita (batch) da e per Muscat