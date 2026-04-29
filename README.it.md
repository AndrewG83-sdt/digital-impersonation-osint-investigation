# Digital Impersonation OSINT Investigation

Questa repository documenta un'investigazione OSINT basata su un caso reale che ho analizzato, relativo a una sospetta impersonificazione digitale su social media. Il caso originale riguardava il clone di un account business Instagram, ma il focus del progetto e' piu' ampio: coerenza dell'identita' digitale, indicatori di impersonificazione e validazione OSINT pratica.

Il caso e' stato completamente anonimizzato. Nomi, username, elementi visivi, URL, localita' e altri dettagli identificativi sono stati rimossi o generalizzati.

L'obiettivo e' mostrare il metodo di lavoro e il ragionamento seguito, non esporre una persona o un'organizzazione specifica. Ho trattato il materiale originale come appunti privati di indagine e l'ho ricostruito in una versione pulita da portfolio.

English version available here: [README.md](README.md)

## Obiettivi

- Rilevare un possibile account di impersonificazione.
- Analizzare la similarita' dello username e possibili logiche di typosquatting.
- Verificare la coerenza dell'identita' digitale su piattaforme pubbliche.
- Valutare il rischio pratico per il brand legittimo e per gli utenti.

## Strumenti utilizzati

- Maigret
- Sherlock, usato come controllo secondario sugli username
- Tecniche OSINT manuali: confronto dei profili, revisione dei contenuti e validazione base del footprint digitale

## Risultati principali

- L'account sospetto usava uno username con una variazione minima rispetto a quello legittimo. Era una differenza facile da non notare.
- I contenuti pubblici del profilo sembravano copiati o replicati molto da vicino, inclusi presentazione dell'account, struttura della bio e stile dei media.
- La ricerca username ha restituito molti possibili match, ma la maggior parte non mostrava attivita' utile o continuita' di identita'.
- Non ho trovato un footprint pubblico coerente che supportasse l'account sospetto come identita' autonoma e consolidata.
- Considerando gli indicatori nel loro insieme, l'account mostrava un'alta probabilita' di essere un profilo clone o di impersonificazione.

## Perche' e' rilevante in cybersecurity e threat intelligence

L'impersonificazione sui social viene spesso trattata solo come un problema reputazionale, ma puo' supportare frodi, phishing, reindirizzamento degli utenti e abuso della fiducia. Un account clone convincente non richiede capacita' tecniche avanzate. Deve solo sembrare abbastanza familiare da spingere gli utenti a fidarsi.

Per un lavoro di threat intelligence, questo tipo di caso e' utile perche' la conclusione nasce dall'unione di dettagli piccoli: variazione dello username, branding copiato, footprint esterno debole e comportamento della piattaforma. Nessun punto, da solo, basta a chiudere l'analisi; insieme pero' possono supportare un'escalation chiara.

## Competenze dimostrate

- Raccolta e validazione OSINT
- Analisi della minaccia
- Riconoscimento di pattern
- Individuazione di impersonificazione
- Analisi username
- Gestione dei falsi positivi
- Reportistica professionale
