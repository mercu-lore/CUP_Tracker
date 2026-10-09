<div align="center">

# 🗓️ CUP Tracker

### Meno tempo a cercare. Più tempo per te.

Un’app desktop gratuita per seguire le disponibilità di visite ed esami,
ricevere avvisi e gestire i tuoi appuntamenti sanitari.

**Gratuita** · **Dati sul dispositivo** · **Profili per te e i tuoi familiari**

**Liguria: in sviluppo e verifica** · **Toscana: integrazione in lavorazione**

</div>

---

> **Stato del progetto:** la versione **1.04 è in preparazione**. L’applicazione e il suo installer sono ancora in sviluppo: questo repository, per ora, presenta il progetto attraverso il solo README. Non contiene un’app pronta da scaricare.
>
> **Progetto indipendente:** CUP Tracker non è affiliato, autorizzato o patrocinato da Regione Liguria, Regione Toscana, Liguria Digitale, ASL o altri enti del servizio sanitario.

## 💙 Perché nasce

Cercare una visita o un esame può significare tornare sul portale più volte, controllare le stesse sedi e sperare che si liberi un posto. Per alcune prestazioni, come un’ecografia, le disponibilità possono essere poche e cambiare nel tempo.

CUP Tracker nasce da questa esperienza concreta: rendere più semplice accorgersi di una disponibilità utile e tenere insieme ricette, appuntamenti e documenti.

Oggi il progetto viene sviluppato e provato da un piccolo gruppo di persone. Vogliamo trasformare questo beneficio in uno strumento accessibile a tutti, anche a chi non ha competenze tecniche o aiuta un familiare a gestire le prenotazioni.

**L’app sarà gratuita. Non vogliamo lucrare sulla difficoltà di accedere alle cure:** non sono previsti abbonamenti né funzioni di prenotazione vendute a pagamento. Restano naturalmente gli eventuali ticket e costi delle prestazioni stabiliti dal servizio sanitario.

## ✨ Cosa potrai fare

Le funzioni seguenti sono implementate nel prototipo della v1.04 e in fase di verifica prima della distribuzione.

| Funzione | Come ti aiuta |
| :--- | :--- |
| **Cercare visite ed esami** | Consultare le sedi e gli orari restituiti dal CUP per la tua ricetta. |
| **Monitorare nuove disponibilità** | Ricevere un avviso quando compaiono posti compatibili con il periodo e gli orari scelti. |
| **Cercare un appuntamento prima** | Monitorare date precedenti a una prenotazione già esistente. |
| **Gestire più profili** | Seguire le tue ricette e quelle di familiari o altre persone che ti hanno autorizzato. |
| **Ricevere notifiche** | Vedere gli aggiornamenti nell’app e, se lo desideri, su Telegram. |
| **Prenotare con conferma esplicita** | Scegliere sede, giorno e ora e confermare personalmente l’operazione. |
| **Aggiungere una prenotazione esistente** | Collegare un appuntamento usando numero di prenotazione e codice di verifica. |
| **Cambiare o annullare un appuntamento** | Gestire le operazioni supportate dal portale, dopo la tua conferma. |
| **Salvare i documenti** | Conservare promemoria, ricevute e documenti disponibili nelle cartelle che scegli. |
| **Ricordare gli appuntamenti** | Ricevere una conferma dopo la prenotazione e un promemoria il giorno prima, con l’app in esecuzione. |

La copertura dipende dalla regione, dalla ricetta e dalle operazioni consentite dal portale. Le funzioni del prototipo non equivalgono ancora a una versione pubblica convalidata per ogni prestazione.

## 🔎 Come funziona il monitoraggio

1. **Scegli il profilo** e inserisci il numero della ricetta elettronica.
2. **Imposta le preferenze:** periodo, fascia oraria, eventuali giorni feriali e sede preferita facoltativa.
3. **Attiva il monitoraggio.** Se hai indicato una sede preferita, il primo controllo parte da quella sede; poi la ricerca prosegue nelle altre, con richieste distanziate.
4. **Ricevi un riepilogo:** una notifica nell’app e, se configurato, un messaggio Telegram con il totale degli orari e dei giorni e le sedi trovate.
5. **Apri le date trovate.** L’app aggiorna la disponibilità prima di accompagnarti alla scelta e alla conferma della prenotazione.

La sede preferita **non esclude le altre sedi**. Il monitoraggio può aiutarti sia prima della prima prenotazione sia quando cerchi una data anticipata. Dopo un risultato continua a cercare, fino alla pausa, alla fine del periodo impostato o alla disattivazione.

Le disponibilità possono cambiare tra il controllo e la conferma: un avviso non riserva un posto. L’app consulta le agende esposte dal CUP e non può creare disponibilità che il portale non ha pubblicato. In caso di errori o limiti del servizio, sospende temporaneamente i controlli e mostra il motivo.

**Il monitoraggio e i promemoria funzionano dal tuo computer:** l’app deve essere aperta, anche in background, e connessa a Internet. Non continuano da un nostro server quando il dispositivo è spento.

## 👨‍👩‍👧 Profili per te e per chi aiuti

Puoi creare profili separati per te, un genitore, il partner o un’altra persona che ti ha autorizzato. Ogni profilo conserva le proprie ricette, preferenze e prenotazioni.

Il profilo prevede **nome, cognome e alias facoltativo**. Su Telegram viene usato l’alias, se compilato, oppure soltanto il nome; il cognome non viene incluso automaticamente nei messaggi.

Gestire un profilo altrui richiede il consenso o l’autorizzazione della persona interessata e il rispetto delle regole del servizio sanitario. Avere i suoi dati non sostituisce questa autorizzazione.

## 🔐 I dati restano sotto il tuo controllo

CUP Tracker non usa un nostro server per raccogliere profili, ricette o prenotazioni. La conservazione dei dati avviene sul dispositivo: nel prototipo Windows, l’archivio locale è cifrato e la chiave è protetta tramite il sistema operativo.

Per consultare o gestire un appuntamento, l’app comunica direttamente con i servizi regionali e trasmette i dati necessari a quella richiesta. **Salvataggio locale non significa assenza di comunicazioni esterne.**

Telegram è facoltativo. Se lo attivi, i messaggi vengono inviati tramite il tuo bot ai servizi Telegram: nome o alias, date, orari e sedi possono quindi uscire dal dispositivo. Il nome della prestazione viene incluso soltanto con l’apposita scelta nelle impostazioni. Codice fiscale, numero della tessera sanitaria e NRE non sono destinati ai messaggi Telegram.

I PDF che esporti sono salvati nella cartella scelta da te. Una volta esportati, sono file normali: la cifratura dell’archivio dell’app non protegge automaticamente quelle copie. Se scegli una cartella sincronizzata con un servizio cloud, i documenti seguono le impostazioni di quel servizio.

Il flusso Liguria utilizza i dati richiesti dal portale per ricetta e assistito; non richiede di consegnare all’app le tue credenziali SPID.

## 🧭 Nella v1.04 la decisione resta tua

**Il monitoraggio non prenota, non cambia e non annulla appuntamenti automaticamente.** Cerca disponibilità e ti avvisa. Le operazioni sul CUP richiedono una tua scelta e conferma esplicita.

Una possibile automazione delle prenotazioni sarà valutata soltanto in futuro. Non è presente nella v1.04 e non è una promessa di rilascio.

Questa scelta serve anche a evitare cambi o cancellazioni indesiderati vicino all’appuntamento. La documentazione regionale richiama termini di disdetta, tra cui **almeno due giorni lavorativi (48 ore)**, e possibili addebiti per mancata o tardiva disdetta, con eccezioni e modalità specifiche. Non va interpretata come una regola universale di 48 ore di calendario: prima di annullare occorre verificare le indicazioni aggiornate del CUP e della struttura.

Riferimenti ufficiali: [CUP Liguria e gestione delle disdette](https://www.regione.liguria.it/homepage-salute/come-fare-per/cup-liguria.html), [documentazione regionale sulle liste di attesa e sulle disdette](https://www.regione.liguria.it/components/com_publiccompetitions/includes/download.php?id=78011%3Adocumenti-formato-open.pdf), [ASL 5: recupero del ticket per mancata disdetta](https://www.asl5.liguria.it/Home/RECUPERODELTICKETPERMANCATADISDETTA.aspx).

## 🗺️ Regioni e prossimi passi

| Area | Stato |
| :--- | :--- |
| **Liguria** | Prima integrazione del progetto, attualmente in sviluppo e verifica sul flusso PrenotoSalute. |
| **Toscana** | Integrazione in lavorazione. Il monitoraggio automatico non è disponibile nella v1.04 attuale. |
| **Altre regioni** | Possibili sviluppi futuri, senza una data o una copertura garantita. |
| **Installer Windows** | In preparazione per rendere l’app utilizzabile senza configurazioni tecniche manuali. |
| **Distribuzione dell’app** | Arriverà dopo le verifiche dei flussi, dei documenti, delle notifiche e dell’installazione. |

L’obiettivo è partire da un’app semplice da installare, affidabile nei passaggi più delicati e comprensibile anche quando il portale non restituisce posti o segnala un errore.

## 🤝 Un progetto per rendere la ricerca più accessibile

CUP Tracker è un aiuto nella consultazione e nella gestione degli appuntamenti, non un servizio sanitario ufficiale. Non assegna priorità cliniche, non garantisce tempi di attesa e non sostituisce il medico, il CUP o i percorsi di tutela previsti dal servizio sanitario.

Per capire cosa migliorare sono utili osservazioni su chiarezza, accessibilità e uso quotidiano. Quando segnali un problema, evita di pubblicare codici fiscali, tessere sanitarie, ricette, codici di prenotazione, token o documenti con dati personali. Usa esempi fittizi o schermate oscurate.

---

<div align="center">

**Nato da un’esigenza quotidiana. Costruito per diventare utile a tutti.**

Gratuito · Indipendente · Dati conservati sul dispositivo

</div>
