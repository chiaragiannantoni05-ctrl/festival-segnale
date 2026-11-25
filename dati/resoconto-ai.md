# Resoconto del lavoro con l'AI — Segnale

## Sessione 1

### 1.1
Ho chiesto di far caricare a `programma.html` gli eventi da `eventi.json` e `sedi.json` con `fetch`, con messaggi di caricamento, nessun evento ed errore e «Sede da definire»; di aggiungere a `info.html` il meteo di Torino da Open-Meteo; di spiegarmi gli errori che incontravo; di proporre un piano di prove.
### 1.2
Ho completato autonomamente e senza l'uso dell'AI i due file `eventi.json` e `sedi.json`.
### 1.3
Ho usato il codice proposto dall'AI:
  - schede: `caricaJSON`, `Promise.all`, `Map` per le sedi, `createElement` e `textContent`;
  - meteo: sezione con elenco di definizioni, script separato da quello di Swiper, CSS `.meteo` e `.stato-meteo`.
### 1.4
Ho modificato io i file:
  - `programma.html`: ho cancellato le sei schede scritte a mano, inserito la nuova sezione e lo script, poi corretto l'annidamento (avevo incollato la sezione dentro il vecchio `event-grid`, con titolo e `id` duplicati);
  - `info.html`: ho inserito la sezione «Meteo a Torino adesso» dopo «Come arrivare» e lo script del meteo dopo quello di Swiper;
  - `style.css`: ho aggiunto `.stato-eventi`, esteso la regola a 
  `.stato-meteo` e aggiunto le regole `.meteo`;
### 1.5
Ho verificato con Live Preview, non con il doppio clic, le prove su nome sede, `[]` in `eventi.json`, `sedi.json` rinominato, `sede_id` inesistente e dato meteo sbagliato e il sito a larghezza di telefono e di computer; tutte le verifiche sono risultate corrette. 
