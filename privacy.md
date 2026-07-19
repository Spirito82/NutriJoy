# Privacy Policy – NutriJoy

**Ultimo aggiornamento: 19 luglio 2026**

Titolare del trattamento: Emanuele Sinagra (sviluppatore indipendente), contattabile all'indirizzo email indicato al punto 8.

## 1. Introduzione

NutriJoy è un'app per il monitoraggio dell'alimentazione e dell'attività fisica ad uso personale. Questa informativa descrive quali dati vengono raccolti, come vengono utilizzati e quali diritti ha l'utente, in conformità al Regolamento (UE) 2016/679 ("GDPR").

NutriJoy **non fornisce consulenza medica, nutrizionale o di personal training** e non è un dispositivo medico. Per i dettagli su questo aspetto vedi i [Termini e Condizioni](terms.md).

## 2. Dati raccolti

### 2.1 Dati inseriti direttamente dall'utente
- Dati del profilo (es. età, sesso, peso, altezza, livello di attività) usati per calcolare in modo automatico stime di fabbisogno calorico e macronutrienti.
- Dati alimentari e di allenamento inseriti manualmente (alimenti, quantità, schede di allenamento, sessioni svolte).
- Indirizzo email e credenziali di accesso, se l'utente crea un account.

### 2.2 Dati raccolti tramite servizi di terze parti integrati nell'app
NutriJoy si appoggia ai seguenti servizi di terze parti, ciascuno regolato dalla propria informativa privacy:

| Servizio | Finalità | Dati trattati | Informativa |
|---|---|---|---|
| **Firebase Authentication (Google)** | Login e gestione account (email/password, Google Sign-In) | Email, identificativo account, token di autenticazione | https://policies.google.com/privacy |
| **Sentry** | Diagnostica e segnalazione crash/errori tecnici | Log tecnici, stack trace, informazioni su dispositivo/versione app. Non vengono inviate informazioni personali identificative (`SendDefaultPii = false`); se offline, gli eventi vengono messi in coda localmente e inviati alla riconnessione | https://sentry.io/privacy/ |
| **Open Food Facts** | Ricerca prodotti alimentari tramite codice a barre | Codice a barre interrogato (nessun dato personale associato) | https://world.openfoodfacts.org/privacy |
| **Google Play Billing** | Gestione di eventuali abbonamenti in-app | Stato dell'acquisto/abbonamento, gestito interamente da Google; NutriJoy non riceve né memorizza dati di pagamento (numero carta, ecc.) | https://policies.google.com/privacy |

Questi servizi possono comportare un trasferimento di dati verso server situati anche fuori dallo Spazio Economico Europeo (es. USA), sulla base delle clausole contrattuali standard e delle garanzie adottate dai rispettivi fornitori.

### 2.3 Dati tecnici anonimi
Dati diagnostici anonimi/aggregati necessari al funzionamento e alla stabilità dell'app (es. versione del sistema operativo, crash log come sopra descritto).

### Cosa NutriJoy non fa
- Non raccoglie dati di geolocalizzazione.
- Non accede a contatti, foto o altri dati del dispositivo non necessari al funzionamento dell'app.
- Non vende dati a terzi e non li utilizza per pubblicità profilata.

## 3. Base giuridica e finalità del trattamento

I dati sono trattati sulla base di:
- **Esecuzione di un contratto** (art. 6.1.b GDPR): per fornire le funzionalità dell'app (diario alimentare, schede di allenamento, account).
- **Consenso** (art. 6.1.a GDPR): per funzionalità opzionali (es. crash reporting, se l'utente non lo disabilita dove disponibile).
- **Legittimo interesse** (art. 6.1.f GDPR): per la sicurezza tecnica e la prevenzione di malfunzionamenti (log di errore).

I dati relativi ad alimentazione, peso e attività fisica possono rientrare tra le categorie di dati che rivelano informazioni sulla salute (art. 9 GDPR) qualora combinati tra loro. Tali dati vengono trattati solo con il consenso esplicito dell'utente all'atto dell'inserimento e restano, salvo funzionalità cloud esplicitamente abilitate, memorizzati localmente sul dispositivo.

## 4. Conservazione dei dati

- I dati alimentari, di allenamento e di profilo sono conservati **localmente sul dispositivo dell'utente** (database SQLite locale).
- I dati di account (email, autenticazione) sono conservati su Firebase per il tempo in cui l'account resta attivo.
- I dati diagnostici (Sentry) sono conservati secondo le policy di retention del fornitore (tipicamente 90 giorni).
- Alla disinstallazione dell'app, i dati locali sul dispositivo vengono eliminati; i dati di account su Firebase restano fino a richiesta di cancellazione (vedi punto 7).

## 5. Condivisione dei dati

I dati **non vengono venduti** e non vengono ceduti a terzi per finalità di marketing. Sono condivisi esclusivamente con i fornitori di servizi elencati al punto 2.2, nella misura strettamente necessaria a fornire le relative funzionalità (autenticazione, diagnostica, ricerca prodotti, gestione abbonamento).

## 6. Pubblico di destinazione

NutriJoy **non è destinata a bambini di età inferiore ai 13 anni**. Se hai tra 13 e 18 anni, puoi usare l'app solo con il consenso di un genitore o tutore. Se veniamo a conoscenza di aver raccolto dati di un minore senza il consenso richiesto, provvederemo alla cancellazione.

## 7. Diritti dell'utente

In quanto interessato ai sensi degli artt. 15-22 GDPR, hai diritto a:
- accedere ai tuoi dati e ottenerne copia;
- richiederne la rettifica o l'integrazione;
- richiederne la cancellazione ("diritto all'oblio");
- limitare od opporti al trattamento;
- ottenere la portabilità dei dati;
- revocare il consenso in qualsiasi momento, senza pregiudicare la liceità del trattamento già effettuato.

Puoi esercitare questi diritti in qualsiasi momento:
- cancellando i dati direttamente dall'app;
- disinstallando l'app (rimuove i dati locali);
- scrivendo all'indirizzo email al punto 8 per richiedere la cancellazione dell'account e dei dati associati conservati su Firebase.

Hai inoltre diritto a proporre reclamo all'Autorità Garante per la Protezione dei Dati Personali (www.garanteprivacy.it) se ritieni che il trattamento violi il GDPR.

## 8. Contatti

Per domande sulla privacy o per esercitare i tuoi diritti:
📧 email: emanuelesinagra@gmail.com

## 9. Modifiche a questa informativa

Questa informativa può essere aggiornata periodicamente, ad esempio in caso di nuove funzionalità o nuovi servizi di terze parti. La data di "ultimo aggiornamento" in cima al documento riflette l'ultima revisione. In caso di modifiche sostanziali, l'app potrà richiedere una nuova accettazione.
