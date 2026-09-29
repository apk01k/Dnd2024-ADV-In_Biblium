<!-- =========================================================
IN BIBLIUM — Homebrewery V3
Avventura per D&D 2024
6 personaggi di 3° livello · circa 4 ore

Style Editor: In_Biblium_Style.css
Repository immagini: https://github.com/apk01k/in-biblium

SIMBOLO CONSEGNABILE AI GIOCATORI: {{far,fa-file}}

LOGO DI COLLANA / AVVENTURE
Percorso canonico previsto:
https://raw.githubusercontent.com/apk01k/in-biblium/main/images/Master_Ludorum_Logo.png
Se nel repository il file ha un nome diverso, modificare soltanto l'URL del logo qui sotto.
========================================================= -->

<!-- =========================================================
LAYOUT RAPIDO

TABELLA A LARGHEZZA PAGINA:
{{wideTable
| ... |
}}

IMMAGINE A LARGHEZZA PAGINA:
{{wideImage
![Descrizione](URL_RAW)
}}

IMMAGINE LIBERA A DESTRA CON TESTO ATTORNO:
{{floatRight,floatSoft
![PNG trasparente](URL_RAW)
}}
Testo che deve scorrere attorno all'immagine...
{{clearFloat}}

Usa floatRound per medaglioni/simboli.
Usa floatRect per immagini rettangolari.
========================================================= -->


{{titlepage

![Torre di Aldebrando](https://raw.githubusercontent.com/apk01k/in-biblium/main/images/locations/In_Biblium_1_Torre_Aldebrando.png){position:absolute,top:0px,left:0px,width:816px,height:1056px,object-fit:cover,z-index:-2}

{{coverShade}}

{{coverLogo
![Magister Ludorum](https://raw.githubusercontent.com/apk01k/in-biblium/main/images/Master_Ludorum_Logo.png)
}}

{{coverTitle
# IN BIBLIUM

### *Scientia non perit*

**Un'avventura per D&D 2024**  
**6 personaggi di 3° livello · Durata: circa 4 ore**
}}

{{artist,bottom:12px,right:20px
##### MagisterLudorum
}}

}}

\page


# IN BIBLIUM

{{motto
SCIENTIA NON PERIT
}}

{{bibliumRule
##### La conoscenza non perisce
**In Biblium** è un archivio extradimensionale di ciò che è stato scritto, dimenticato, perduto o lasciato indietro dalla memoria.
}}

## Come usare questa avventura

*In Biblium* è una one-shot investigativa ed esplorativa per **sei personaggi di 3° livello**, progettata per una sessione di circa **quattro ore**.

Il documento contiene tutto ciò che serve al DM per condurre l'avventura: struttura delle scene, testi da leggere o parafrasare, indizi, prove, conseguenze, incontri e statistiche delle creature.

{{dmnote
##### Convenzioni editoriali
**Testo in box dorato:** leggere o parafrasare ai giocatori.  
**Nota blu:** informazione operativa riservata al DM.  
**Indizio:** informazione che i personaggi possono scoprire.  
**{{far,fa-file}} Hxx:** esiste un handout consegnabile ai giocatori, raccolto nell'Appendice D.  
**Violazione:** comportamento che può modificare la risposta di In Biblium.
}}

## Premessa

Il grande mago **Aldebrando Astrofulgo** ha affrontato demoni, interrogato spiriti e consultato oracoli per risolvere un problema apparentemente insolubile.

Sua figlia **Elandra** compie gli anni.

Aldebrando vuole prepararle la stessa torta che sua nonna **Ermelinda** preparava per lui quando era bambino.

Ricorda perfettamente il sapore. Ricorda la cucina. Ricorda Ermelinda che impastava mentre lui cercava di rubare qualcosa dal tavolo.

Ricorda persino alcuni ingredienti:

- **Latte di Luna**
- **Polvere di Stella**
- **Farina dei Giganti**
- **Essenza di Drago**

E soprattutto ricorda che Ermelinda parlava di un misterioso **Ingrediente Segreto**.

Ma non ricorda quale fosse.

Nessun essere interrogato da Aldebrando ha saputo dargli una risposta.

Rimane un'unica possibilità: **In Biblium**.

---

## La verità

Ermelinda non utilizzava ingredienti magici. I ricordi di Aldebrando sono quelli di un bambino che interpretava letteralmente nomi, cognomi e battute familiari.

{{wideTable
| Ricordo | Realtà |
|:--|:--|
| **Latte di Luna** | Latte della **mucca Luna** |
| **Polvere di Stella** | Zucchero fine prestato da **Estrella**, la vicina |
| **Farina dei Giganti** | Farina del **Mulino Giganti** |
| **Essenza di Drago** | Cannella con un pizzico di paprika |
| **Ingrediente Segreto** | **Non esiste** |
}}

La torta era speciale perché la preparava **Ermelinda per lui**.

{{dmnote
##### Non rivelare la soluzione
Questa verità non deve essere semplicemente raccontata ai personaggi. L'intera avventura serve a permettere loro di ricostruirla attraverso documenti, memorie e collegamenti bibliografici.
}}

\page

# Struttura dell'avventura

{{wideTable
| Scena | Tempo | Funzione |
|:--|--:|:--|
| 1. Torre di Aldebrando | 25 min | Hook, briefing, portale |
| 2. Ingresso di In Biblium | 25 min | Reveal, Refusi |
| 3. Pozzo dei Libri | 25 min | Esplorazione, Libri Volanti |
| 4. Catalogo Generale | 40 min | Indagine sugli ingredienti |
| 5. Sala dei Leggii | 15 min | Mimic, intermezzo |
| 6. Archivio delle Storie e dei Ricordi | 55 min | Libro dei PG, memoria di Ermelinda |
| 7. Uscita / eventuale escalation | 20 min | Bibliotecari o Custode |
| 8. Ritorno ed epilogo | 15 min | Rivelazione e conclusione |
}}

**Totale previsto:** circa **220 minuti**, con circa 20 minuti di margine per improvvisazione, pause e combattimenti più lunghi.

## Principio di conduzione

Questa non è un'avventura nella quale i personaggi devono indovinare la soluzione prevista dal DM.

Ogni ostacolo dovrebbe accettare almeno tre approcci:

**ragionamento · interazione · forza**

Se i personaggi escogitano una soluzione plausibile, lasciala funzionare.

Un fallimento non dovrebbe mai bloccare l'avventura. Deve invece produrre una conseguenza:

- perdita di tempo;
- complicazione;
- aumento della Violazione;
- posizione sfavorevole;
- informazione incompleta.

## L'accesso a In Biblium

In Biblium non è una biblioteca proibita. È una biblioteca **aperta a chi necessita di una nuova e specifica conoscenza**.

Tre condizioni regolano l'accesso:

1. il visitatore deve cercare una conoscenza specifica;
2. deve realmente ignorarla;
3. deve desiderare autenticamente conoscerla.

Questo spiega perché i personaggi possono entrare e perché Aldebrando no.

{{bibliumRule
##### Regola d'accesso
**Aldebrando conosceva la ricetta. L'ha dimenticata.**  
Per In Biblium, dimenticare qualcosa non equivale ad acquisire una nuova conoscenza.
}}

## Violazione di In Biblium

In Biblium permette grande libertà ai propri visitatori, ma non permette che il proprio patrimonio venga devastato.

Il DM tiene segretamente un **Indice di Violazione**.

{{wideTable
| Indice | Stato | Reazione |
|--:|:--|:--|
| 0 | Visitatore | Nessuna |
| 1 | Irregolare | Osservazione |
| 2 | Trasgressore | Ammonimento |
| 3 | Vandalo | Intervento dei Bibliotecari |
| 4 | Minaccia | Intervento del Custode |
}}

### Aumentare la Violazione

Non assegnare punti per ogni piccola infrazione. Aumenta l'indice quando il comportamento del gruppo diventa significativamente distruttivo.

**+1** distruggere deliberatamente libri o documenti.  
**+1** rubare un'opera dopo aver ricevuto ordine di restituirla.  
**+1** aggredire deliberatamente un Bibliotecario non ostile.  
**+1** danneggiare sistematicamente la Biblioteca.

Un atto catastrofico, per esempio incendiare deliberatamente un'intera sezione, può portare direttamente l'indice a **4**.

### Ridurre la Violazione

Restituire materiale sottratto, riparare un danno, accettare una sanzione o collaborare con i Bibliotecari può ridurre l'indice di 1.

{{dmnote
##### Scopo della Violazione
La Violazione non serve a punire i giocatori. Serve a far sì che **In Biblium reagisca coerentemente alle loro azioni** e a fornire una via alternativa di escalation.
}}

\page

{{location
## 1. La Torre di Aldebrando
}}

{{readaloud
Oltre l'ultima collina, fra alberi carichi di fiori bianchi, si innalza una torre di pietra chiara.

Cinque piani.

Li potete contare senza difficoltà.

Intorno alla torre si estende un frutteto in piena fioritura. Api ronzano tra i rami e petali bianchi attraversano lentamente il sentiero.

Sulla porta vi attende un elfo dalla veste decisamente troppo elegante per qualcuno che sembra aver trascorso la mattina litigando con l'universo.
}}

## Aldebrando Astrofulgo

Aldebrando è un **elfo**, un mago di enorme potere, perfettamente consapevole della propria intelligenza e poco incline a fingere modestia.

È **scontroso, spocchioso e saccente**, ma non crudele. La sua irritazione nasce soprattutto dal fatto che un problema apparentemente banale ha resistito a mezzi arcani che egli riteneva infallibili.

Parla come se stesse correggendo una tesi mediocre. Anche quando chiede aiuto, riesce a farlo con l'aria di chi sta concedendo agli interlocutori un'importante opportunità formativa.

{{dmnote
##### Interpretare Aldebrando
Non renderlo gratuitamente antipatico. La sua arroganza deve essere divertente e leggibile, ma il legame con Elandra e il ricordo di Ermelinda devono mostrare che dietro l'ego esiste un affetto autentico.
}}

## {{far,fa-file}} H01 — Lettera di convocazione

Prima dell'inizio dell'avventura, consegna ai giocatori **H01 — Lettera di Aldebrando**, riportata nell'Appendice D.

La Compagnia della Catena ha ricevuto una richiesta insolita e urgente.

## Nove piani

Entrando nella torre, i personaggi scoprono che possiede **nove piani**.

Se qualcuno osserva che dall'esterno ne aveva cinque:

{{readaloud
«Naturalmente. Se ne avesse nove anche all'esterno sarebbe molto più alta.»
}}

Aldebrando non comprende quale sia il problema.

Non soffermarti troppo sull'esplorazione della torre: è un'introduzione.

## Il problema di Aldebrando

Aldebrando racconta della torta di Ermelinda e degli ingredienti che ricorda.

Può inoltre fornire:

- il nome completo di **Ermelinda Astrofulgo**;
- il periodo approssimativo della propria infanzia;
- il paese in cui vivevano;
- la certezza quasi ossessiva dell'esistenza dell'Ingrediente Segreto.

Se i personaggi suggeriscono immediatamente che forse l'Ingrediente Segreto non esiste:

{{readaloud
«Vi assicuro che mia nonna non avrebbe avuto alcuna ragione di mentire a un bambino di sette anni.»
}}

Lascia che la frase maturi.

## Il nono piano

Il nono piano contiene una stanza quasi vuota. Al centro si apre un portale verticale completamente nero.

Sull'arco è inciso:

{{motto
SCIENTIA NON PERIT
}}

Aldebrando non può attraversarlo. La superficie diventa solida al suo contatto. Può dimostrarlo con crescente irritazione.

Se i personaggi chiedono perché:

{{readaloud
«Se lo sapessi, suppongo che non avrei bisogno di voi.»
}}

## Fischietto di Richiamo Astrofulgico

Prima che entrino, Aldebrando consegna al gruppo un piccolo fischietto d'argento.

{{clue
##### Fischietto di Richiamo Astrofulgico
Una creatura all'interno di In Biblium può soffiarvi come **azione**.

Dopo **1 round** si apre nelle vicinanze un portale verso il nono piano della Torre Astrofulgo. Il portale rimane aperto per **1 minuto**.

Il fischietto funziona **una sola volta**.
}}

{{readaloud
«Non perdetelo.»

Pausa.

«Sul serio.»
}}

\page

{{location
## 2. Ingresso di In Biblium
}}

<!-- IMMAGINE A LARGHEZZA PAGINA:
{{wideImage
![Ingresso di In Biblium](URL_RAW_DELL_IMMAGINE)
}}
Ingresso della biblioteca.
Caricare nel repository e inserire qui l'URL raw.githubusercontent.com. -->

{{readaloud
Attraversate il nero.

Per un istante non esiste nulla.

Poi compare una luce.

E un'altra.

E un'altra ancora.

Solo dopo qualche secondo comprendete che quelle che sembravano stelle sono lampade sospese a decine di metri sopra di voi.

Scaffali smisurati salgono nell'oscurità fino a scomparire alla vista. Scale e passerelle attraversano il vuoto. File di libri proseguono tanto lontano da dissolversi in una foschia azzurra.

Da qualche parte, molto in alto, qualcosa sbatte le copertine come ali.

Nel pavimento di pietra chiara e inserti dorati è incisa una frase:

**SCIENTIA NON PERIT.**
}}

Il primo obiettivo è trovare il **Catalogo Generale**.

Un cartello indica la direzione.

Il problema sono i Refusi.

## I Refusi

Un gruppo di piccole creature di carta sta divorando un cartello bibliografico.

Non mangiano la carta. Mangiano **ciò che vi è scritto**.

Quando inghiottono una parola, questa scompare materialmente dalla pagina.

{{clue
##### Il cartello
**ERMELINDA ASTROFULGO**  
MEMORIE DOMESTICHE  
ARCHIVIO DELLE STORIE E DEI RICORDI  
CONSULTARE PRIMA IL CATALOGO GENERALE
}}

I Refusi stanno cancellando proprio queste parole.

### Risolvere la scena

I personaggi possono:

- scacciare i Refusi;
- combatterli;
- offrire loro altro materiale scritto;
- catturarne uno;
- recuperare il testo prima che venga divorato.

**INT (Indagare) CD 12:** ricostruire una parte cancellata dal contesto.  
**SAG (Percezione) CD 12:** individuare frammenti integri.  
**CAR (Addestrare Animali) CD 13:** sorprendentemente, funziona.

Un giocatore che offre ai Refusi qualcosa di particolarmente "gustoso" — un contratto, un grimorio, una lettera molto lunga — ottiene automaticamente la loro attenzione.

## Incontro 1 — Refusi

Per sei PG di 3° livello usa **3 Sciami di Refusi**.

Lo scontro deve essere rapido. I Refusi non combattono fino alla morte. Quando rimane un solo sciame con metà PF o meno, fugge negli scaffali.

### Catturare un Refuso

Un Refuso isolato può essere intrappolato con una prova appropriata **CD 13**.

Un Refuso catturato può cancellare una breve parola o alcune lettere da un testo.

Esempio:

`ACCESSO VIETATO` → `ACCESSO`

Il DM determina gli effetti secondo il contesto. Questa capacità non altera automaticamente la realtà universale, ma **In Biblium attribuisce enorme importanza a ciò che è scritto**.

Premia gli utilizzi creativi.

\page

{{location
## 3. Il Pozzo dei Libri
}}

<!-- IMMAGINE A LARGHEZZA PAGINA:
{{wideImage
![Pozzo dei Libri](URL_RAW_DELL_IMMAGINE)
}}
Pozzo dei Libri cilindrico, labirintico, senza creature volanti.
Caricare nel repository e inserire qui l'URL raw.githubusercontent.com. -->

{{readaloud
Il corridoio termina.

Non davanti a una porta.

Davanti al vuoto.

Oltre la balaustra si apre una voragine perfettamente cilindrica, tanto vasta che la parete opposta è velata dalla foschia.

Ogni centimetro delle pareti è coperto da scaffali.

Scale, passerelle e ponti attraversano il pozzo a differenti altezze, scendendo in un intreccio così fitto da sembrare il progetto di un labirinto costruito in verticale.

Guardate verso il basso.

Non vedete il fondo.

Un libro precipita da uno scaffale.

Cade per alcuni metri.

Poi rallenta.

Si ferma.

E comincia a cadere verso l'alto.
}}

Il Catalogo Generale si trova dall'altro lato del Pozzo.

## Gravità bibliografica

La gravità del Pozzo non è uniforme.

Le passerelle seguono associazioni concettuali anziché una geometria normale. Un percorso può riportare apparentemente nello stesso punto ma su un livello diverso.

### Attraversamento

Richiedi **3 successi prima di 2 fallimenti**.

Ogni personaggio può contribuire descrivendo il proprio approccio.

**FOR (Atletica) CD 12:** attraversare una sezione danneggiata.  
**DES (Acrobazia) CD 12:** passare su una scala mobile o passerella inclinata.  
**INT (Indagare) CD 12:** comprendere la logica delle classificazioni.  
**SAG (Percezione) CD 13:** individuare il percorso più sicuro.

Magia o idee particolarmente appropriate possono concedere un successo automatico.

### Fallimento

Nessuno precipita automaticamente nel nulla.

Con 2 fallimenti il gruppo raggiunge comunque l'altra parte, ma provoca uno stormo di **Libri Volanti**.

## Libri Volanti

Decine di volumi riposano negli scaffali superiori con il dorso rivolto verso il basso.

Quando disturbati aprono le copertine e prendono il volo.

{{readaloud
Un libro apre lentamente la copertina.

Poi un altro.

Poi cinquanta.

Lo scaffale esplode.

Uno stormo di volumi attraversa il Pozzo con il frastuono di centinaia di pagine sfogliate contemporaneamente.
}}

I Libri Volanti **non sono normalmente ostili**.

Chi si trova sulla passerella effettua un **TS DES CD 12**.

**Fallimento:** viene sbilanciato e afferra il parapetto; perde un piccolo oggetto non assicurato oppure subisce **1d6 danni contundenti**, a scelta del giocatore.

Attaccare lo stormo lo disperde.

Non tirare iniziativa salvo che i giocatori insistano nel combatterlo.

\page

{{location
## 4. Catalogo Generale
}}

<!-- IMMAGINE A LARGHEZZA PAGINA:
{{wideImage
![Catalogo Generale](URL_RAW_DELL_IMMAGINE)
}}
Catalogo Generale con schedari anche sul soffitto e Bibliotecari.
Caricare nel repository e inserire qui l'URL raw.githubusercontent.com. -->

{{readaloud
Il Catalogo Generale sembra ancora più impossibile della Biblioteca.

Migliaia di schedari occupano pavimento, pareti, balconate e passerelle.

Poi alzate gli occhi.

Altri schedari ricoprono completamente il soffitto.

Figure incappucciate camminano lassù come se fosse perfettamente normale, le vesti rivolte verso l'alto rispetto a voi.

Non hanno piedi.

Una di loro apre un cassetto sopra le vostre teste.

Alcune schede cadono.

Verso il soffitto.
}}

Sono i **Bibliotecari**.

Non sono ostili.

## I Bibliotecari

I Bibliotecari assomigliano a frati amanuensi sospesi pochi centimetri dal suolo.

Non hanno piedi. Le loro maschere possiedono un lungo naso adunco. Ogni mano ha **quattro dita complessive: tre dita e un pollice**.

Parlano con tono educato, preciso e completamente privo di ironia.

### Primo contatto

Un Bibliotecario si avvicina.

{{readaloud
«Conoscenza richiesta?»
}}

Se i personaggi rispondono genericamente «una ricetta»:

{{readaloud
«Richiesta insufficiente.»
}}

Se nominano Ermelinda:

{{readaloud
«Ermelinda Astrofulgo. Memoria domestica. Preparazione alimentare. Periodo compatibile. Ricerca ammessa.»
}}

## Cercare gli ingredienti

Il Catalogo interpreta inizialmente le parole di Aldebrando **alla lettera**.

### Latte di Luna

La ricerca conduce a:

**Zootecnia extraplanare → Fauna lunare → Secrezioni commestibili**

Decine di risultati. Nessuno pertinente.

Una ricerca per **Ermelinda**, invece, produce una ricevuta.

{{handout
##### {{far,fa-file}} H02 — RISULTATO DEL CATALOGO
**LUNA — bovino domestico**  
Produzione giornaliera: **latte fresco — 2 brocche**.
}}

Consegna ai giocatori **H02**.

### Polvere di Stella

La ricerca letterale conduce a trattati astronomici e campioni minerali.

Cercando nelle spese domestiche:

{{handout
##### {{far,fa-file}} H03 — RISULTATO DEL CATALOGO
**ESTRELLA — vicina della casa accanto**  
Annotazione domestica: **zucchero fine — da restituire**.
}}

Consegna ai giocatori **H03**.

### Farina dei Giganti

Il Catalogo propone inizialmente:

**Giganti → Alimentazione → Cereali → Farina**

Nessuna corrispondenza.

Un vecchio registro commerciale riporta:

{{handout
##### {{far,fa-file}} H04 — RISULTATO DEL CATALOGO
**MULINO GIGANTI**  
Farine e cereali.
}}

Consegna ai giocatori **H04**.

### Essenza di Drago

La ricerca letterale conduce a:

**Draghi → Anatomia → Secrezioni → Distillazione**

Un Bibliotecario può osservare:

{{readaloud
«Consultazione sconsigliata durante i pasti.»
}}

La ricerca nelle annotazioni di Ermelinda produce invece:

{{handout
##### {{far,fa-file}} H05 — RISULTATO DEL CATALOGO
*Cannella. Un pizzico di paprika.*

*Aldebrando dice che brucia come un drago.*
}}

Consegna ai giocatori **H05**.

## Capire il meccanismo

Dopo due rivelazioni, un personaggio può effettuare **INT (Indagare) CD 11**.

**Successo:** Aldebrando non ricordava nomi fantastici; ricordava **come quei nomi suonavano a un bambino**.

Dopo tre rivelazioni non è necessaria alcuna prova.

## L'Ingrediente Segreto

Nessuna ricerca produce un ingrediente.

Compare invece:

{{clue
##### Collegamento bibliografico
**ASTROFULGO, ERMELINDA**  
Memorie domestiche  
Preparazioni alimentari  
Ricordi familiari

**ARCHIVIO DELLE STORIE E DEI RICORDI**
}}

Un Bibliotecario indica la strada.

\page

{{location
## 5. Sala dei Leggii
}}

<!-- IMMAGINE A LARGHEZZA PAGINA:
{{wideImage
![Sala dei Leggii](URL_RAW_DELL_IMMAGINE)
}}
Sala dei Leggii con pochi leggii vuoti e un unico leggio centrale.
Caricare nel repository e inserire qui l'URL raw.githubusercontent.com. -->

Per raggiungere l'Archivio occorre attraversare un salone altissimo.

{{readaloud
La sala è quasi vuota.

Pareti di libri salgono per decine di metri.

Sul pavimento sono disposti pochi leggii, tutti vuoti.

Tutti tranne uno.

Al centro della sala, perfettamente illuminato, riposa un enorme tomo rilegato in cuoio scuro, chiuso da eleganti borchie metalliche.

È probabilmente il libro più invitante che abbiate mai visto.
}}

Lascia che i giocatori reagiscano.

Il libro non è un mimic.

**Il leggio sì.**

## Il Mimic del Leggio

Quando qualcuno tocca il tomo, il leggio cerca di afferrarlo.

Questo incontro deve essere rapido e leggermente assurdo.

Usa il blocco statistiche **Mimic del Leggio** nell'Appendice A.

### Il libro

Dopo lo scontro i personaggi possono finalmente aprirlo.

È:

{{clue
##### Indice Generale delle Norme per la Corretta Manutenzione dei Leggii — Volume VII
Non contiene nulla di utile.
}}

Sul pavimento, sotto il mimic, una targhetta recita:

{{readaloud
**È severamente vietato nutrire gli arredi.**
}}

## Tagliare questa scena

Se sono trascorse **più di 2 ore e 15 minuti** dall'inizio della sessione, il mimic non attacca.

Il leggio emette semplicemente un piccolo ringhio quando qualcuno si avvicina. La scena dura trenta secondi e si prosegue.

\page

{{location
## 6. Archivio delle Storie e dei Ricordi
}}

<!-- IMMAGINE A LARGHEZZA PAGINA O FIGURA LIBERA:
{{wideImage
![Archivio delle Storie e dei Ricordi](URL_RAW_DELL_IMMAGINE)
}}
Archivio delle Storie e dei Ricordi, verticale o a mezza pagina.
Caricare nel repository e inserire qui l'URL raw.githubusercontent.com. -->

{{readaloud
Qui gli scaffali sono più bassi.

I libri sono più distanti fra loro.

E sopra di voi fluttuano centinaia di sfere trasparenti.

Dentro ognuna si muove una scena.

Un matrimonio.

Una battaglia.

Una bambina che corre sotto la pioggia.

Un vecchio che osserva il mare.

Un uomo che chiude una porta per l'ultima volta.

Le immagini non producono alcun suono.

Bolle di memoria salgono lentamente dai libri e si perdono fra gli scaffali.
}}

# Il libro che racconta i personaggi

Durante la ricerca, un personaggio nota un volume.

Sulla copertina:

{{motto
IN BIBLIUM
}}

All'interno:

{{readaloud
*Il potente mago Aldebrando Astrofulgo desiderava preparare una torta per sua figlia Elandra...*
}}

Continuando a leggere, il testo descrive **la sessione appena giocata**.

Il DM deve inserire dettagli realmente accaduti. Cita almeno:

- una battuta di un personaggio;
- una scelta insolita;
- l'esito del Pozzo;
- ciò che è successo con il mimic.

Poi:

{{readaloud
*E fu allora che trovarono un libro intitolato In Biblium.*
}}

Voltano pagina.

{{readaloud
*Naturalmente, qualcuno pensò immediatamente di leggere la fine.*
}}

Fermati.

## Leggere il futuro

**Permettilo.**

Il libro non è un trucco. Può realmente fornire informazioni.

La pagina finale recita:

{{readaloud
*E quando finalmente compresero quale fosse l'Ingrediente Segreto di Ermelinda, capirono perché nessun demone, spirito o sapiente aveva mai potuto rivelarlo.*
}}

Non specifica quale sia.

Il libro contiene la **storia dei personaggi**, non conoscenze che essi non hanno ancora acquisito.

## Domande al libro

### «Dove troviamo Ermelinda?»

{{readaloud
*Fu seguendo la memoria di Aldebrando che trovarono ciò che cercavano.*
}}

Concede vantaggio alla prossima prova di ricerca.

### «Come supereremo il Custode?»

Se non hanno ancora provocato il Custode:

{{readaloud
*Fortunatamente, non ebbero bisogno di scoprirlo.*
}}

### «Cosa c'è dietro quella porta?»

Il libro può dirlo.

### «Moriremo?»

{{readaloud
*In quel momento decisero che forse alcune pagine non dovevano essere lette in anticipo.*
}}

Se insistono, il DM può descrivere **una possibilità**, mai un destino inevitabile.

## Il futuro cambia

Il libro descrive il futuro più coerente con la situazione corrente.

Se qualcuno legge:

*Arven aprì la porta.*

e Arven decide di non farlo, le parole lentamente svaniscono.

Compare:

*Dopo aver letto ciò che avrebbe fatto, Arven decise di non aprire la porta.*

Il libero arbitrio non viene mai negato.

\page

# Prelievo non autorizzato

Consultare il libro è consentito.

**Portarlo via dal suo posto non lo è.**

Se i personaggi decidono di utilizzarlo come guida permanente, dopo poco compare un Bibliotecario.

{{readaloud
«Il volume deve essere ricollocato.»
}}

Se rifiutano:

{{readaloud
«Prelievo non autorizzato.»
}}

Se continuano:

{{readaloud
«Secondo avviso. Ricollocare il volume.»
}}

Al terzo rifiuto l'Indice di Violazione aumenta di 1.

Se il gruppo insiste, altri Bibliotecari intervengono. Questo può condurre allo **Scontro 2**.

{{dmnote
##### Il vero problema
Il problema dei Bibliotecari non è che il libro predica il futuro. È che **non è stato registrato il prestito**.
}}

# Cercare Ermelinda

La scheda del Catalogo permette di individuare il volume:

{{clue
##### ASTROFULGO, ALDEBRANDO — RICORDI D'INFANZIA
Collegamento: **ERMELINDA**
}}

Quando viene aperto, una delle bolle sopra il libro comincia a crescere.

Fino a inglobare i personaggi.

# La cucina di Ermelinda

{{readaloud
La Biblioteca scompare.

Sentite pioggia.

Siete in una piccola cucina.

Il fuoco crepita sotto una pentola. Una finestra appannata guarda su un cortile bagnato.

Una donna anziana sta lavorando un impasto.

Accanto al tavolo siede un bambino.

Avrà sette anni.

Lo riconoscete soltanto dopo qualche istante.

È Aldebrando.
}}

I personaggi non possono cambiare significativamente il ricordo. Possono muoversi e osservare.

Ermelinda prepara la torta.

Osservando la cucina possono riconoscere:

- un sacco marchiato **Mulino Giganti**;
- una brocca di latte appena munto e, oltre la finestra, la mucca **Luna**;
- un piccolo involto di zucchero con una nota: **«Estrella — da restituire»**;
- burro;
- uova;
- cannella;
- paprika.

## La conversazione

Il piccolo Aldebrando cerca di rubare qualcosa dall'impasto.

Ermelinda gli dà un colpetto sulla mano.

{{readaloud
**ALDEBRANDO:** «Perché la tua torta è più buona di tutte?»

**ERMELINDA:** «Perché la mia ha un ingrediente segreto.»

**ALDEBRANDO:** «Quale?»

Ermelinda sorride.

Si china verso di lui.
}}

Proprio allora la scena si lacera.

Le parole diventano incomprensibili.

La cucina scompare.

## Il ricordo mancante

I personaggi tornano nell'Archivio.

La memoria non contiene ciò che Ermelinda disse. Quella parte è stata realmente dimenticata.

Ma sul libro compare un collegamento bibliografico:

{{clue
##### ERMELINDA ASTROFULGO — QUADERNO DOMESTICO
Ricette, contabilità, annotazioni.  
**Scaffale R-17.**
}}

Non richiedere altre prove. Sono arrivati alla soluzione.

# Il quaderno di Ermelinda

Non è protetto. Non è incatenato. Non emette luce.

È un piccolo quaderno con la copertina consumata e alcune macchie di farina.

Consegna ai giocatori **{{far,fa-file}} H06 — Ricetta di Ermelinda**.

{{handout
##### {{far,fa-file}} H06 — RICETTA DI ERMELINDA
### TORTA PER TUTTE LE OCCASIONI
Farina  
Latte  
Zucchero fine  
Uova  
Burro  
Cannella  
Un pizzico di paprika

**Ingrediente segreto:** nessuno.

*Aldebrando continua a chiedermi quale sia. Gli dico che è segreto perché così mangia la torta convinto che dentro ci sia qualcosa di magico.*

Più sotto, aggiunto successivamente:

*Forse un segreto c'è davvero.*

*Che gliela preparo io.*
}}

Lascia qualche secondo di silenzio.

Non spiegare il significato.

## Uscire da In Biblium

I personaggi possiedono ora la conoscenza richiesta.

Non è necessario rubare il quaderno. Possono copiarne la ricetta.

Se vogliono portare l'originale:

{{readaloud
«Opera non disponibile al prestito.»
}}

I Bibliotecari permettono senza problemi di trascriverla.

Quando sono pronti, possono usare il **Fischietto di Richiamo Astrofulgico**.

\page

# Scontro 2 — I Bibliotecari

Questo incontro avviene solo se il comportamento dei personaggi lo provoca.

Per sei PG di 3° livello usa **3 Bibliotecari**.

I Bibliotecari non cercano di uccidere.

Il loro obiettivo è:

1. recuperare materiale sottratto;
2. immobilizzare i responsabili;
3. espellerli.

Un Bibliotecario che raggiunge **10 PF o meno** si ritira.

Se metà dei Bibliotecari viene sconfitta, quello rimasto offre nuovamente una soluzione amministrativa:

{{readaloud
«Possiamo ancora risolvere la questione senza ulteriori irregolarità.»
}}

Restituire il materiale termina immediatamente lo scontro.

# Scontro 3 — Il Custode

Il Custode appare soltanto a **Violazione 4**.

{{readaloud
Tutti i rumori cessano.

Le pagine smettono di voltarsi.

Le bolle dei ricordi si immobilizzano.

Persino le lampade sembrano abbassare la propria luce.

Da qualche parte, molto lontano, risuona:

**TUM.**

Poi ancora.

**TUM.**

Un bastone contro la pietra.

I Bibliotecari si fanno da parte.

Dal corridoio emerge una figura più alta delle altre.

Non cammina.

Fluttua.

Nella mano stringe un lungo bastone nodoso.

«Restituire.»

Pausa.

«Riparare.»

«Uscire.»
}}

Il Custode è severo.

Non è malvagio.

E soprattutto **non è necessario sconfiggerlo**.

## Risolvere l'incontro senza combattere

Il Custode accetta:

- restituzione del materiale;
- riparazione ragionevole;
- compensazione del danno;
- un'argomentazione fondata sulle regole di In Biblium;
- una soluzione creativa basata sui Refusi;
- resa e successiva espulsione.

Il libro *In Biblium*, se ancora disponibile, contiene:

{{readaloud
*Non potevano sconfiggere il Custode.*

*Fortunatamente non era necessario.*
}}

Non aggiungere altro.

Lascia ai giocatori la soluzione.

\page

{{location
## 7. Ritorno alla Torre
}}

Il fischietto produce un suono sorprendentemente debole.

Un secondo dopo il portale nero si apre.

Dall'altra parte c'è Aldebrando.

Li sta aspettando.

{{readaloud
«Ebbene?»
}}

Lascia ai giocatori raccontare ciò che hanno scoperto.

Non anticipare le battute.

Se spiegano gli ingredienti uno alla volta:

**Latte di Luna?**

{{readaloud
«...una mucca?»
}}

**Polvere di Stella?**

{{readaloud
«Zucchero.»
}}

**Farina dei Giganti?**

{{readaloud
«Giganti era il cognome del mugnaio.»
}}

**Essenza di Drago?**

{{readaloud
«Io... chiamavo così la cannella?»
}}

Poi inevitabilmente:

{{readaloud
«E l'Ingrediente Segreto?»
}}

Lascia che siano i giocatori a rispondere.

Aldebrando rimane in silenzio.

Se gli mostrano l'annotazione di Ermelinda, la legge due volte.

Poi:

{{readaloud
«Capisco.»
}}

Questa è una delle rare occasioni in cui Aldebrando non aggiunge altro.

## Ricompensa

Aldebrando mantiene la promessa.

Una ricompensa appropriata per una one-shot può essere **75–100 mo per personaggio**, oppure equivalente concordato dalla Compagnia della Catena.

Inoltre, ciascun personaggio riceve un piccolo **Segnalibro di In Biblium**, prova del diritto a presentare in futuro una nuova richiesta di consultazione.

Non consente automaticamente l'accesso. La Biblioteca decide sempre se la richiesta soddisfa le proprie regole.

# Epilogo

I personaggi **non assistono a questa scena**.

Dopo aver ricevuto il compenso vengono congedati.

Il DM può leggerla come breve epilogo cinematografico.

{{readaloud
Quella sera la Torre Astrofulgo è insolitamente silenziosa.

Sul tavolo della cucina c'è una torta.

Non è perfetta.

Una parte è leggermente più alta dell'altra e sulla superficie c'è decisamente troppa cannella.

Aldebrando ha preparato tutto personalmente.

Nessuna magia.

Elandra entra.

Guarda suo padre.

Guarda la torta.

Ne taglia una fetta.

Aldebrando, che ha contrattato con demoni e discusso con esseri immortali, sembra improvvisamente incapace di respirare.

Elandra assaggia.

«Com'è?»

Lei mastica.

Guarda la fetta.

Ne prende un altro boccone.

Poi sorride.

«Buona.»

Aldebrando sorride a sua volta.

Sul tavolo, accanto alla torta, riposa la ricetta di Ermelinda.

**SCIENTIA NON PERIT.**
}}

\page

# APPENDICE A — CREATURE

## Sciame di Refusi

{{monster,frame
## Sciame di Refusi {{bonus **GS 1**}}
*Uno sciame di minuscole aberrazioni di carta e inchiostro che divora parole, lettere e significati.*

{{stats
{{vitals
**CA**         :: 13
**PF**         :: 27 (6d8)
**Velocità**   :: 9 m, scalare 9 m
\column
**Iniziativa** :: +3 (13)
**Taglia**     :: Media (sciame di creature Minuscole)
**Tipo**       :: Aberrazione
}}

{{tables
|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|For| 6 | -2 | -2 |
|Int| 7 | -2 | -2 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Des|16 | +3 | +3 |
|Sag|12 | +1 | +1 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Cos|10 | +0 | +0 |
|Car| 8 | -1 | -1 |
}}

**Abilità** :: Furtività +5
**Resistenze** :: contundente, perforante, tagliente
**Immunità** :: Condizioni: Afferrato, Prono, Trattenuto
**Sensi** :: Scurovisione 18 m, Percezione Passiva 11
**Linguaggi** :: comprende il Comune scritto ma non parla
**PE** :: 200 {{bonus **Bonus di Competenza** +2}}
}}

### Tratti

***Sciame.*** Lo sciame può occupare lo spazio di un'altra creatura e viceversa e può attraversare aperture sufficienti a una creatura Minuscola. Non può recuperare PF né ottenere PF Temporanei.

***Fame di Parole.*** Lo sciame infligge danni doppi agli oggetti di carta, pergamena o materiali analoghi che contengano scrittura.

### Azioni

***Morsi di Carta.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m, un bersaglio. *Colpito:* 10 (3d4 + 3) danni taglienti, oppure 6 (1d6 + 3) se lo sciame possiede metà dei propri PF o meno.

***Mangiare le Parole.*** Lo sciame prende come bersaglio un testo non indossato entro 1,5 m. Una frase breve, etichetta o iscrizione scompare. Per documenti più grandi il DM determina una porzione appropriata.
}}

## Mimic del Leggio

{{monster,frame
## Mimic del Leggio {{bonus **GS 2**}}
*Un leggio di legno scuro che aspetta immobile che qualcuno si interessi al libro appoggiato sopra di lui.*

{{stats
{{vitals
**CA**         :: 13
**PF**         :: 45 (6d8 + 18)
**Velocità**   :: 4,5 m
\column
**Iniziativa** :: +1 (11)
**Taglia**     :: Media
**Tipo**       :: Mostruosità
}}

{{tables
|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|For|17 | +3 | +3 |
|Int| 5 | -3 | -3 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Des|12 | +1 | +1 |
|Sag|13 | +1 | +1 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Cos|16 | +3 | +3 |
|Car| 8 | -1 | -1 |
}}

**Abilità** :: Furtività +5
**Immunità** :: Danni: acido; Condizioni: Prono
**Sensi** :: Scurovisione 18 m, Percezione Passiva 11
**Linguaggi** :: —
**PE** :: 450 {{bonus **Bonus di Competenza** +2}}
}}

### Tratti

***Falso Aspetto.*** Finché rimane immobile, il mimic è indistinguibile da un normale leggio.

***Adesivo.*** Una creatura colpita dallo Pseudopodo è Afferrata (CD 13 per sfuggire). Finché l'afferramento dura, il mimic ha vantaggio agli attacchi contro quella creatura.

### Azioni

***Pseudopodo.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 8 (1d10 + 3) danni contundenti e il bersaglio è Afferrato.

***Morso.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 10 (2d6 + 3) danni perforanti.

### Tattiche

Il mimic vuole mangiare, non morire. A **15 PF o meno** cerca di fuggire trascinandosi goffamente verso gli scaffali.
}}

\page

## Bibliotecario

{{monster,frame
## Bibliotecario {{bonus **GS 2**}}
*Un archivista fluttuante, privo di piedi, con veste da amanuense e maschera dal lungo naso adunco.*

{{stats
{{vitals
**CA**         :: 15
**PF**         :: 39 (6d8 + 12)
**Velocità**   :: 0 m, volare 9 m (fluttuare)
\column
**Iniziativa** :: +2 (12)
**Taglia**     :: Media
**Tipo**       :: Aberrazione
}}

{{tables
|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|For|10 | +0 | +0 |
|Int|16 | +3 | +5 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Des|14 | +2 | +2 |
|Sag|15 | +2 | +4 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Cos|14 | +2 | +2 |
|Car|12 | +1 | +1 |
}}

**Abilità** :: Arcano +5, Indagare +5, Percezione +4
**Resistenze** :: psichico
**Immunità** :: Condizioni: Prono
**Sensi** :: Scurovisione 18 m, Percezione Passiva 14
**Linguaggi** :: Comune più tre linguaggi; comprende qualsiasi linguaggio scritto
**PE** :: 450 {{bonus **Bonus di Competenza** +2}}
}}

### Tratti

***Senza Piedi.*** Il Bibliotecario fluttua e non può essere buttato Prono.

***Autorità del Catalogo.*** Il Bibliotecario ha vantaggio alle prove effettuate per individuare una creatura che trasporta un'opera sottratta a In Biblium.

### Azioni

***Penna d'Archivio.*** *Tiro per Colpire Magico in Mischia:* +5, portata 1,5 m. *Colpito:* 9 (1d8 + 3 più 1d4) danni da forza.

***Vincolo di Consultazione (Ricarica 5–6).*** Una creatura entro 12 m deve superare un **TS FOR CD 13** o essere Trattenuta da nastri di pergamena animata. La creatura può ripetere il tiro salvezza alla fine di ciascun proprio turno, terminando l'effetto con un successo.

***Silenzio, prego.*** Una creatura entro 18 m che il Bibliotecario può vedere effettua un **TS SAG CD 13**. *Fallimento:* fino all'inizio del turno successivo del Bibliotecario non può effettuare Reazioni e parla soltanto sottovoce. Questo effetto non impedisce le componenti verbali degli incantesimi.

### Reazioni

***Ricollocazione.*** {{font-variant:small-caps **Trigger:**}} una creatura entro 1,5 m tenta di allontanarsi portando un oggetto appartenente alla Biblioteca. {{font-variant:small-caps **Risposta:**}} il Bibliotecario si muove fino a 3 m senza provocare Attacchi di Opportunità.

### Tattiche

I Bibliotecari usano **Vincolo di Consultazione**, recuperano gli oggetti e cercano di espellere gli intrusi. Non attaccano creature Incoscienti.
}}

## Custode di In Biblium

{{monster,frame
## Custode di In Biblium {{bonus **GS 5**}}
*La massima autorità operativa della Biblioteca: un archivista spettrale, austero, fluttuante, armato di un lungo bastone nodoso.*

{{stats
{{vitals
**CA**         :: 17
**PF**         :: 105 (14d10 + 28)
**Velocità**   :: 0 m, volare 9 m (fluttuare)
\column
**Iniziativa** :: +1 (11)
**Taglia**     :: Grande
**Tipo**       :: Aberrazione
}}

{{tables
|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|For|18 | +4 | +7 |
|Int|18 | +4 | +7 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Des|12 | +1 | +1 |
|Sag|17 | +3 | +6 |

|   |   | MOD | TS |
|:--|:-:|:---:|:--:|
|Cos|15 | +2 | +2 |
|Car|15 | +2 | +2 |
}}

**Abilità** :: Arcano +7, Indagare +7, Intuizione +6, Percezione +6
**Resistenze** :: forza, psichico
**Immunità** :: Condizioni: Affascinato, Spaventato, Prono
**Sensi** :: Scurovisione 36 m, Percezione Passiva 16
**Linguaggi** :: comprende e parla qualsiasi linguaggio usato da una creatura all'interno di In Biblium
**PE** :: 1.800 {{bonus **Bonus di Competenza** +3}}
}}

### Tratti

***Custode del Patrimonio.*** Il Custode conosce la posizione di ogni opera sottratta entro 90 m.

***Autorità Assoluta.*** Il Custode ha vantaggio ai tiri salvezza contro effetti che lo sposterebbero contro la sua volontà.

### Azioni

***Multiattacco.*** Il Custode effettua due attacchi con **Bastone Nodoso**.

***Bastone Nodoso.*** *Tiro per Colpire in Mischia:* +7, portata 3 m. *Colpito:* 11 (1d10 + 4 più 1d4) danni contundenti e da forza.

***Restituire.*** Una creatura entro 18 m che trasporta un oggetto appartenente a In Biblium deve superare un **TS FOR CD 15**. *Fallimento:* l'oggetto vola immediatamente nella mano libera del Custode o sullo scaffale più vicino.

***Espulsione (Ricarica 5–6).*** Il Custode colpisce il pavimento con il bastone. Ogni creatura ostile entro 4,5 m effettua un **TS FOR CD 15**. *Fallimento:* 13 (3d8) danni da forza, spinta di 6 m e Prono. *Successo:* metà danni e nessuno spostamento.

### Azioni Bonus

***Ricollocare.*** Il Custode teletrasporta un oggetto incustodito appartenente alla Biblioteca che può vedere entro 18 m su uno scaffale libero entro la stessa distanza.

### Reazioni

***Silenzio.*** {{font-variant:small-caps **Trigger:**}} una creatura entro 18 m lancia un incantesimo. {{font-variant:small-caps **Risposta:**}} il Custode impone svantaggio a un eventuale tiro per colpire dell'incantesimo oppure ottiene vantaggio al primo tiro salvezza effettuato contro quell'incantesimo.

### Tattiche

Il Custode non combatte per uccidere. Attacca chi continua a distruggere il patrimonio e usa **Espulsione** per separare il gruppo.

Se recupera tutti gli oggetti sottratti e i personaggi cessano le ostilità, interrompe immediatamente il combattimento.
}}

{{dmnote
##### Nota per il DM
Per sei personaggi di 3° livello il Custode è un avversario serio, ma l'economia delle azioni favorisce fortemente il gruppo.

Il suo vero vantaggio è che **non deve vincere riducendo tutti a 0 PF**. Deve recuperare il patrimonio e costringerli ad andarsene.
}}

\page

# APPENDICE B — SCALARE GLI INCONTRI

L'avventura è calibrata per **6 PG di 3° livello**.

Non aumentare automaticamente PF e CA per gruppi più grandi. Aggiungere creature è generalmente più interessante perché modifica l'economia delle azioni senza creare "sacchi di PF".

## Incontro 1 — Refusi

**Base: 6 PG livello 3 → 3 Sciami di Refusi.**

| Gruppo | Modifica |
|:--|:--|
| 4 PG livello 3 | 2 sciami |
| 5 PG livello 3 | 2 sciami; un terzo arriva solo se lo scontro è troppo facile |
| 6 PG livello 3 | 3 sciami |
| 7–8 PG livello 3 | 4 sciami |
| 6 PG livello 4 | 4 sciami |
| 6 PG livello 5 | 4 sciami, 35 PF ciascuno |

Per PG di livello superiore non aumentare la CA.

## Mimic del Leggio

**Base: 1 Mimic del Leggio.**

Non è progettato come scontro impegnativo. Deve durare circa **2–3 round**.

Per 7–8 PG o personaggi di 4°–5° livello, porta i PF a **60** e concedigli una volta per round una reazione:

***Scatto Adesivo.*** Quando viene mancato da un attacco in mischia, il mimic si muove di 1,5 m senza provocare Attacchi di Opportunità.

Non aggiungere altri mimic: rovinerebbe la gag.

## Incontro 2 — Bibliotecari

**Base: 6 PG livello 3 → 3 Bibliotecari.**

| Gruppo | Modifica |
|:--|:--|
| 4 PG livello 3 | 2 Bibliotecari |
| 5 PG livello 3 | 2 Bibliotecari |
| 6 PG livello 3 | 3 Bibliotecari |
| 7–8 PG livello 3 | 4 Bibliotecari |
| 6 PG livello 4 | 4 Bibliotecari |
| 6 PG livello 5 | 4 Bibliotecari, 48 PF ciascuno |

Ricorda che lo scontro può terminare diplomaticamente in qualunque momento.

## Incontro 3 — Custode

**Base: 6 PG livello 3 → 1 Custode.**

Per gruppi più forti **non aggiungere un secondo Custode**.

| Gruppo | Modifica |
|:--|:--|
| 4 PG livello 3 | 85 PF; Espulsione 2d8 |
| 5 PG livello 3 | 95 PF |
| 6 PG livello 3 | statistiche normali |
| 7–8 PG livello 3 | 125 PF |
| 6 PG livello 4 | 125 PF; +1 Bibliotecario |
| 6 PG livello 5 | 145 PF; +2 Bibliotecari |

Per PG di 5° livello, il Custode può effettuare **3 attacchi** con Multiattacco anziché 2.

Questi rinforzi compaiono solo se necessari e possono arrivare al secondo round.

\page

# APPENDICE C — GESTIONE DELLE 4 ORE

## Se il gruppo è in orario

Gioca tutte le scene.

## Ritardo di 15 minuti

Riduci il Pozzo a **2 successi prima di 2 fallimenti**.

## Ritardo di 30 minuti

Il Mimic ringhia ma non combatte.

## Ritardo di 45 minuti

Nel Catalogo, dopo la scoperta di due ingredienti, un Bibliotecario consegna spontaneamente i riferimenti necessari per gli altri due.

## Ritardo di 60 minuti

Non utilizzare alcun combattimento con Bibliotecari o Custode salvo che i giocatori lo provochino deliberatamente.

{{dmnote
##### Non tagliare
- il libro *In Biblium*;
- il ricordo di Ermelinda;
- la rivelazione dell'Ingrediente Segreto;
- il confronto finale con Aldebrando.

Sono il cuore dell'avventura.
}}

# REFERENCE RAPIDA DEL DM

| Elemento | Reference |
|:--|:--|
| **Obiettivo** | Recuperare la ricetta di Ermelinda |
| **Verità** | Non esiste un ingrediente magico |
| **Latte di Luna** | mucca Luna |
| **Polvere di Stella** | zucchero fine prestato da Estrella |
| **Farina dei Giganti** | Mulino Giganti |
| **Essenza di Drago** | cannella + paprika |
| **Ingrediente Segreto** | nessuno / Ermelinda |
| **Accesso** | conoscenza nuova + specifica + realmente ignorata |
| **Uscita** | Fischietto di Richiamo Astrofulgico |
| **Escalation** | 0 Visitatore → 1 Irregolare → 2 Trasgressore → 3 Vandalo → 4 Minaccia |

**Refusi** → mangiano parole.  
**Libri Volanti** → fauna ambientale.  
**Mimic** → il leggio, non il libro.  
**Bibliotecari** → amministrazione.  
**Custode** → ultima escalation.

{{motto
SCIENTIA NON PERIT
}}

**Tema:** La conoscenza non è necessariamente ciò che è stato scritto. La memoria non è necessariamente ciò che è accaduto. E alcune cose diventano straordinarie non per ciò che contengono, ma per **chi ce le ha donate**.

\page

# APPENDICE D — HANDOUT PER I GIOCATORI

{{dmnote
##### Uso degli handout
Nel corpo dell'avventura il simbolo **{{far,fa-file}}** identifica un materiale consegnabile. Le pagine seguenti possono essere stampate o ritagliate separatamente.
}}

## {{far,fa-file}} H01 — Lettera di Aldebrando

{{letter
**ALLA STIMATISSIMA COMPAGNIA DELLA CATENA,**  
**E A CHI, FRA I SUOI VALOROSI ASSOCIATI, POSSEGGA ANIMO SALDO, INGEGNO PRONTO E UNA RAGIONEVOLE DISPOSIZIONE VERSO L'IGNOTO**

Io, **Aldebrando Astrofulgo**, Maestro delle Arti Astrali, Scrutatore delle Nove Sfere, Custode della Fiamma di Asterione, Vincitore della Disputa dei Sette Sigilli, già Consigliere Straordinario presso tre Corti, due Conclavi e un'entità extraplanare il cui nome non è prudente affidare alla corrispondenza ordinaria,

mi trovo costretto da estreme circostanze a richiedere imminentemente i servigi della vostra stimata Compagnia.

La questione che mi induce a scrivervi è della massima urgenza, di considerevole delicatezza e — non temo di affermarlo — di importanza pressoché incalcolabile.

Ho pertanto necessità di cinque o sei individui di comprovato coraggio, non troppo colti, preferibilmente dotati di curiosità, discernimento, capacità di adattamento e sufficiente istinto di conservazione da non toccare qualunque cosa su cui si posi il loro sguardo.

Il disturbo non dovrebbe richiedere più di alcune ore e sarà adeguatamente compensato.

Per ragioni di riservatezza, la natura esatta dell'impresa sarà comunicata esclusivamente agli incaricati che si presenteranno presso la mia dimora.

Considerata la gravità della situazione, richiedo che essi giungano senza indugio.

È essenziale che la questione sia risolta entro questa sera.

Confido che la Compagnia della Catena comprenderà l'onore implicito nell'essere stata prescelta per un incarico che ha già sconfitto alcune fra le più notevoli intelligenze di questo e di altri piani d'esistenza.

Attendo dunque i vostri uomini e donne migliori.

O, qualora costoro fossero già impegnati,

quelli immediatamente disponibili.

Con la considerazione che la circostanza richiede,

**ALDEBRANDO ASTROFULGO**  
Maestro delle Arti Astrali  
Scrutatore delle Nove Sfere  
Custode della Fiamma di Asterione  
Vincitore della Disputa dei Sette Sigilli  
*eccetera, eccetera*

**P.S.** La puntualità è essenziale.  
**P.P.S.** Non è necessario saper cucinare.
}}

\page

## {{far,fa-file}} H02 — Latte di Luna

{{handout
##### CATALOGO GENERALE — RISULTATO DI CONSULTAZIONE
### LUNA
**Classificazione:** bovino domestico  
**Nucleo domestico:** Ermelinda Astrofulgo  
**Produzione giornaliera:** latte fresco — **2 brocche**
}}

::::

## {{far,fa-file}} H03 — Polvere di Stella

{{handout
##### CATALOGO GENERALE — NOTA DOMESTICA
### ESTRELLA
**Relazione:** vicina della casa accanto  
**Prestito:** zucchero fine  
**Annotazione:** *da restituire*
}}

::::

## {{far,fa-file}} H04 — Farina dei Giganti

{{handout
##### CATALOGO GENERALE — REGISTRO COMMERCIALE
### MULINO GIGANTI
**Attività:** farine e cereali  
**Fornitura ricorrente:** famiglia Astrofulgo
}}

::::

## {{far,fa-file}} H05 — Essenza di Drago

{{handout
##### CATALOGO GENERALE — ANNOTAZIONE DI ERMELINDA
*Cannella. Un pizzico di paprika.*

*Aldebrando dice che brucia come un drago.*
}}

\page

## {{far,fa-file}} H06 — Ricetta di Ermelinda

{{letter
### TORTA PER TUTTE LE OCCASIONI

Farina  
Latte  
Zucchero fine  
Uova  
Burro  
Cannella  
Un pizzico di paprika

---

**Ingrediente segreto:** nessuno.

*Aldebrando continua a chiedermi quale sia. Gli dico che è segreto perché così mangia la torta convinto che dentro ci sia qualcosa di magico.*

Più sotto, aggiunto successivamente:

*Forse un segreto c'è davvero.*

*Che gliela preparo io.*
}}

\page

# APPENDICE E — CHECKLIST PRE-SESSIONE

Prima di iniziare:

- [ ] stampa o prepara **H01–H06**;
- [ ] annota CA, PP e altre statistiche passive utili dei PG;
- [ ] prepara 3 Sciami di Refusi;
- [ ] prepara Mimic, Bibliotecari e Custode, ma ricorda che gli ultimi due incontri sono condizionali;
- [ ] tieni nascosto l'Indice di Violazione;
- [ ] annota l'orario reale di inizio sessione;
- [ ] lascia spazio per appuntare una battuta e una scelta insolita dei PG da inserire nel libro *In Biblium*;
- [ ] non anticipare la soluzione dell'Ingrediente Segreto;
- [ ] ricorda che il fallimento deve complicare, non bloccare.

{{bibliumRule
##### Ultima regola per il DM
Quando i giocatori propongono qualcosa che **ha senso nella logica di In Biblium**, preferisci una conseguenza interessante a un semplice «no».
}}

{{motto
SCIENTIA NON PERIT
}}
