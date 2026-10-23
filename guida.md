# guida.md - Progetto Nomentum Immobiliare (agenzia immobiliare luxury)

Sito: https://cialdecompatibili-netizen.github.io/immobiliarenomentum/
Repo: https://github.com/cialdecompatibili-netizen/immobiliarenomentum
Cartella: Desktop\repository\immobiliarenomentum
Base: clonata da villanomentum (Jekyll + minimal-mistakes, home a blocchi in `_data/blocks_home.json`, admin in `admin/`).

## Obiettivo
Sito credibile da agenzia immobiliare, stile luxury (riferimento RE/MAX e agenzie premium), sfondo bianco, tipografia sobria, molta aria, foto grandi. Compravendita, affitti, mutui e tutti i servizi tipici di un'agenzia.

## Regole di design
- Sfondo bianco, un solo colore d'accento (blu notte o verde bosco, da scegliere), testi scuri con contrasto almeno 4.5:1.
- Titoli con font serif elegante, testi con sans-serif pulito. Pulsanti rettangolari, poco arrotondati.
- MAI bordi laterali colorati su box, citazioni, avvisi (regola di Mirco).
- Card immobili: foto grande, prezzo, zona, metri quadri, locali, bagni, classe energetica, riferimento.
- Menu su una riga, senza sovrapposizioni (vedi menu.css/menu.js di pannellisolari2 se serve).

## Struttura del sito (pagine)
1. Home: hero con ricerca (Compra / Affitta / Vendi), immobili in evidenza, numeri (anni, immobili venduti, tempo medio di vendita), servizi, come lavoriamo, recensioni, zone, contatti.
2. Immobili in vendita / in affitto: elenco con filtri (zona, tipologia, prezzo, locali). Scheda immobile in stile portale (vedi sotto).
3. Vendi con noi: valutazione gratuita, strategia di vendita, tempi, commissioni, modulo "Quanto vale la mia casa".
4. Compra casa: percorso passo per passo, ricerca personalizzata, assistenza fino al rogito.
5. Affitti: locazioni abitative e transitorie, gestione contratti.
6. Mutui e finanziamenti: consulenza con mediatore creditizio, prequalifica, simulatore rata, parole chiave (LTV, TAN, TAEG, tasso fisso/variabile).
7. Servizi (una pagina ciascuno): valutazione e stime, home staging, foto e video professionali, virtual tour, consulenza legale e notarile, pratiche catastali e APE, ristrutturazioni e progettazione, consulenza fiscale, gestione affitti, immobili di pregio, investimenti, vendita a stranieri.
8. Zone: Mentana, Monterotondo, Roma nord, Nomentano, Sabina (pagine locali per la SEO).
9. Chi siamo e Team.
10. Blog / Guide: guide su mutuo prima casa, agevolazioni, costi di acquisto, imposte, come preparare la casa alla vendita.
11. Contatti: modulo, WhatsApp, telefono, mappa, orari.

## Servizi che offrono le agenzie (da RE/MAX e concorrenti)
- Intermediazione immobiliare (vendita e acquisto)
- Locazioni
- Stime e valutazione gratuita
- Consulenza
- Mutui e finanziamenti (RE/MAX ha anche corner di mediazione creditizia in agenzia)
- Home staging
- Consulenza legale

Da aggiungere per distinguersi: foto professionali, virtual tour, certificazione energetica, pratiche catastali, gestione dell'assistenza post vendita (utenze, volture).

## Scheda immobile (ispirata a Immobiliare.it)
Prezzo e prezzo al m2, tipologia, contratto, piano, ascensore, superficie con dettaglio (abitazione, giardino, terrazzo, posto auto), locali, camere, bagni, cucina, arredato, riscaldamento, climatizzazione, classe energetica e consumo, altre caratteristiche (allarme, porta blindata, fibra, ecc.), descrizione, galleria foto, planimetria, mappa, pulsanti Contatta / WhatsApp / Richiedi visita.
Un immobile = un file in una collection `immobili` (campi nel front matter), cosi si aggiunge senza toccare le pagine.

## Fiducia (credibilita)
Numeri veri soltanto (non inventare): anni di attivita, immobili venduti, tempo medio di vendita, recensioni reali con nome. Se mancano, mettere segnaposto da completare.
Dati obbligatori: ragione sociale, P. IVA, REA, iscrizione agente immobiliare (FIMAA o simile), polizza, privacy e cookie.

## Dati che servono da Mirco
Nome definitivo agenzia, zona operativa, telefono/WhatsApp/email, indirizzo e orari, colore e logo, foto, primi 3-5 immobili reali, commissioni (se pubbliche), team, recensioni vere, dati legali.

## Stato lavori
- [x] Repo creata, Pages attivo, contenuto ancora quello della villa
- [x] Guida.md creata
- [ ] Palette, font e menu
- [ ] Home a blocchi
- [ ] Collection immobili e scheda
- [ ] Pagine servizi, mutui, vendi, compra, affitti
- [ ] Zone, team, blog, contatti
- [ ] Contatti reali (WhatsApp, modulo) e dati legali
