# Metodologia

Questa metodologia descrive il workflow OSINT che ho usato per analizzare un sospetto clone di account business su Instagram. I dettagli sono redatti, ma il processo riflette la logica reale dell'indagine.

## 1. Rilevamento iniziale dell'account sospetto

La revisione e' iniziata dopo aver individuato un profilo Instagram molto simile a un account business legittimo. A prima vista sembrava credibile: branding familiare, immagine profilo simile e bio coerente con la stessa categoria di attivita'.

Il primo controllo e' stato semplice: confrontare il profilo sospetto con l'account legittimo conosciuto. In questa versione pubblica uso le etichette `suspected_account` e `legitimate_account`.

## 2. Analisi dello username e logica di typosquatting

Ho controllato lo username carattere per carattere. L'account sospetto usava una variazione molto piccola rispetto al nome dell'account legittimo. Non sembrava una scelta casuale o un'identita' separata, ma una differenza ortografica che un utente normale avrebbe potuto non notare.

Sui social il typosquatting puo' comparire con:

- una lettera aggiunta o mancante
- lettere invertite
- vocali o consonanti ripetute
- uso diverso degli underscore
- piccole variazioni in nomi business lunghi

La domanda pratica non era se lo username fosse identico, ma se un utente potesse confonderlo con il brand legittimo.

## 3. Confronto dei contenuti

Il passaggio successivo e' stato il confronto manuale dei contenuti visibili. Mi sono concentrato su:

- similarita' di immagine profilo e logo
- testo della bio e categorie di servizio
- anteprime dei post e possibile riuso di media
- segnali di anzianita' dell'account, quando visibili
- pattern generale di follower e following

Il profilo sospetto sembrava ricalcare la presentazione dell'account legittimo. Gli elementi copiati non erano limitati a un singolo campo: layout, branding e scelta dei contenuti risultavano intenzionalmente vicini, almeno sulla base delle evidenze visibili.

## 4. Username intelligence con Maigret

Ho usato Maigret per verificare se lo username sospetto comparisse su altre piattaforme pubbliche. Lo scopo non era dimostrare la proprieta' di ogni risultato, ma capire se lo username avesse un footprint digitale coerente e piu' ampio.

La scansione ha prodotto molti possibili match. Questo e' normale per strumenti di username intelligence, soprattutto quando controllano molte piattaforme e generano URL profilo sulla base dello username. Un URL restituito non significa automaticamente che esista un account reale e attivo.

Le osservazioni utili sono state:

- molti risultati sembravano auto-generati o a bassa confidenza
- non sono stati estratti dettagli profilo arricchiti
- diverse piattaforme erano fuori contesto rispetto all'attivita' analizzata
- non emergeva un pattern coerente di attivita' nel tempo

## 5. Interpretazione dei risultati

La username intelligence non supportava l'idea che `suspected_account` avesse un'identita' consolidata fuori da Instagram. A mio avviso, i risultati indicavano un footprint debole o creato per uno scopo specifico.

Questo non prova da solo un intento malevolo, ma aggiunge peso quando viene combinato con gli indicatori di clonazione visiva e con lo username quasi identico.

## 6. Falsi positivi

I falsi positivi sono stati una parte importante dell'analisi, non semplice rumore da ignorare. Gli strumenti di ricerca username possono produrre risultati che sembrano importanti ma che, da soli, non sono realmente utili.

Cause comuni di falsi positivi:

- piattaforme che creano pagine profilo dinamiche quando viene richiesto uno username
- pagine di ricerca che accettano qualsiasi query e restituiscono un URL
- placeholder inattivi senza contenuto
- community non pertinenti al contesto business
- pagine di redirect o bot protection interpretate come match parziali

Per questo motivo non ho considerato significativo un risultato se non mostrava attivita' reale, metadati del profilo, post, interazioni o dettagli coerenti di identita'.

## 7. Valutazione del rischio

Ho valutato il rischio dal punto di vista della fiducia nel brand e della possibile confusione degli utenti. Il profilo sospetto era abbastanza simile da creare confusione, soprattutto per chi cerca rapidamente da mobile.

Rischi potenziali:

- utenti che contattano l'account sbagliato
- danno reputazionale al brand
- reindirizzamento verso messaggi o link non affidabili
- possibile abuso futuro per phishing o richieste di pagamento
- perdita di fiducia nella presenza social legittima

La mia valutazione finale e' stata alta per probabilita' di impersonificazione e medio-alta per impatto sugli utenti, soprattutto se l'account avesse iniziato a interagire con clienti o follower.
