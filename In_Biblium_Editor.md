<!-- =========================================================
IN BIBLIUM — Homebrewery V3
Avventura per D&D 5.5e 2024
6 personaggi di 3° livello · circa 4 ore

Style Editor: Magister Ludorum
Repository immagini: https://github.com/apk01k/in-biblium

SIMBOLO CONSEGNABILE AI GIOCATORI: {{far,fa-file}}

LOGO DI COLLANA / AVVENTURE
Percorso canonico previsto:
https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/Master_Ludorum_Logo.png
Se nel repository il file ha un nome diverso, modificare soltanto l'URL del logo qui sotto.
========================================================= -->

<!-- =========================================================
LAYOUT RAPIDO — MAGISTER LUDORUM

TITOLO LIVELLO 1
Usare un titolo Markdown di livello 1.
→ Kings · 34 pt · doppia colonna · riga oro

TABELLA NORMALE
| Voce | Descrizione |
|:--|:--|
| ... | ... |

TABELLA SENZA INTESTAZIONE VISIBILE
{{noHeader
...tabella...
}}

TABELLA A DOPPIA COLONNA
{{wideTable
...tabella...
}}

IMMAGINE IN UNA COLONNA CON TESTO ATTORNO
{{floatRight,floatSoft
![Descrizione](URL_RAW)
}}
Testo...
{{clearFloat}}

Varianti: floatLeft · floatRound · floatRect

IMMAGINE CENTRALE A DOPPIA COLONNA
{{centerSpread
{{centerSpreadLeft
Testo sinistro.
}}
{{centerSpreadArt
![Descrizione](URL_RAW)
}}
{{centerSpreadRight
Testo destro.
}}
}}

Varianti: centerSpread,compact · centerSpread,large

IMMAGINE WIDE
{{wideImage
![Descrizione](URL_RAW)
}}

FIGURA WIDE CON DIDASCALIA
{{wideFigure
![Descrizione](URL_RAW)
{{caption
Didascalia.
}}
}}

IMMAGINE WIDE IN BASSO
{{bottomArtMedium}}
{{wideImageBottom
![Descrizione](URL_RAW)
}}

PNG IN COLONNA
{{pngArt,pngLeft,pngMid,pngMedium
![Descrizione](URL_RAW)
}}

Varianti:
pngLeft · pngRight
pngTop · pngMid · pngBottom
pngSmall · pngMedium · pngLarge

STAT BLOCK
{{monster,frame
...
}}
Varianti: monsterKeep · monsterCompact · monsterWide

NUMERI PAGINA
Copertina: skipCounting.
Pagine successive: pageNumber,auto.
Dispari a sinistra; pari a destra.

NOTA
Non inserire in questo commento direttive di cambio pagina
o cambio colonna come righe isolate.
========================================================= -->


{{skipCounting}}

{{titlepage

![Biblium](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_2_Ingresso.png){position:absolute,top:0px,left:0px,width:100%,height:100%,margin:0,padding:0,object-position: center center,object-fit:cover,z-index:-2}

{{coverShade}}

{{coverLogo
![Magister Ludorum](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/Master_Ludorum_Logo.png)
}}

{{coverTitle
# IN BIBLIUM

### *Una biblioteca impossibile*
### *e un segreto mai svelato*

**Avventura per D&D 5.5e 2024**
}}

{{artist,bottom:12px,right:20px
##### MagisterLudorum
}}

}}

\page

{{pageNumber,auto}}

# IN BIBLIUM

Questa è un'avventura investigativa ed esplorativa per **sei personaggi di 3° livello**, progettata per essere conclusa in una singola sessione (one-shot) di circa **quattro ore**.

## Come usare questa avventura

Il documento contiene quanto serve al DM per condurre la sessione: testi da leggere o parafrasare, indizi, procedure, conseguenze, incontri, statistiche delle creature, scaling e handout (non obbligatori).

{{dmnote
##### Convenzioni editoriali
**Box dorato:** leggere o parafrasare ai giocatori.
:
**Nota blu:** informazione operativa per il DM.
:
**Indizio:** informazione che i personaggi possono scoprire.
:
**{{far,fa-file}} Hxx:** handout consegnabile ai giocatori, raccolto nell'Appendice D.
:
**Violazione:** comportamento che può modificare la risposta di In Biblium.
}}

## Punti chiave

- **Aldebrando Astrofulgo** vuole preparare per il compleanno di sua figlia **Elandra** la torta che sua nonna **Ermelinda** preparava per lui. Ha bisogno di trovare la ricetta.
- Aldebrando ha aperto un portale verso la biblioteca extradimensionale **Biblium**, ma non può entrare: la Biblioteca ammette chi cerca una conoscenza specifica che **ignora realmente e non ha mai posseduto**. I personaggi possono entrare perché la ricetta di Ermelinda costituisce per loro una conoscenza nuova.
- La Biblioteca non è ostile: reagisce soltanto se i visitatori danneggiano, sottraggono o aggrediscono.
- Il misterioso **Ingrediente Segreto non esiste**. La torta era speciale perché era Ermelinda a prepararla per Aldebrando.

## Preparazione

Prima della sessione:
1. Consegna o prepara **H01 — Lettera di Aldebrando**;
2. Tieni pronti gli handout **H02–H06**;
3. Rivedi i blocchi di **Refusi, Mimic del Leggio, Bibliotecari e Custode** nell'Appendice A;
4. Tieni a portata l'**Indice di Violazione**, lo scaling dell'Appendice B e il pacing dell'Appendice C.

## Antefatto

Il potentissimo **Aldebrando Astrofulgo** ha un problema che nessuna delle sue prodigiose arti magiche è riuscita a risolvere.
Il grande mago ha evocato demoni, interrogato spiriti e consultato oracoli per svelare il segreto più importante della sua vita.

Sua figlia **Elandra** compie gli anni e lui vuole prepararle la stessa torta che sua nonna **Ermelinda** preparava quando era bambino.

Ricorda il sapore, la cucina e gli ingredienti. Da bambino aveva visto Ermelinda prepararla così tante volte da conoscerne la ricetta. Ricorda soprattutto che Ermelinda parlava di un misterioso **Ingrediente Segreto**, ma non ricorda quale fosse.

Nessun essere interrogato da Aldebrando ha saputo svelare il segreto. Rimane un'unica possibilità: la biblioteca extradimensionale chiamata **Biblium**, che conserva libri, documenti, storie e conoscenze perdute. Aldebrando ha trovato il modo di aprirvi un portale ma non può attraversarlo. Per questo ha bisogno degli avventurieri.

## La verità

I ricordi di Aldebrando sono quelli di un bambino che interpretava letteralmente nomi, cognomi e battute familiari.

| Ricordo | Realtà |
|:--|:--|
| **Latte di Luna** | Latte della **mucca Luna** |
| **Polvere di Stella** | Zucchero fine prestato da **Estrella**, la vicina |
| **Farina dei Giganti** | Farina del **Mulino Giganti** |
| **Essenza di Drago** | Cannella con un pizzico di paprika |
| **Ingrediente Segreto** | **Non esiste** |

La torta era speciale perché la preparava **Ermelinda per lui**.

{{dmnote
##### Non rivelare la soluzione
Non raccontare questa verità ai personaggi.
:
L'avventura deve permettere loro di ricostruirla attraverso documenti, memorie e collegamenti bibliografici.
}}

\page

{{pageNumber,auto}}

# PANORAMICA AVVENTURA

{{wideTable
| Scena | Tempo | Funzione |
|:--|--:|:--|
| 1. Torre di Aldebrando | 25 min | Aggancio, briefing, portale |
| 2. Ingresso di In Biblium | 25 min | Rivelazione, Refusi |
| 3. Sala dei Leggii | 20 min | Mimic, intermezzo |
| 4. Pozzo dei Libri | 20 min | Esplorazione, Libri Volanti |
| 5. Catalogo Generale | 40 min | Indagine sugli ingredienti |
| 6. Archivio delle Storie e dei Ricordi | 40 min | Libro dei PG, memoria di Ermelinda |
| 7. Uscire da Biblium | 30 min | Uscita o escalation|
| 8. Ritorno alla Torre | 20 min | Rivelazione, ricompensa, epilogo|
}}

**Totale previsto:** circa **220 minuti**, con circa **20 minuti di margine** per improvvisazione, pause e combattimenti più lunghi.

## Principio di conduzione

Questa non è un'avventura nella quale i personaggi devono indovinare la soluzione prevista dal DM.

Ogni ostacolo dovrebbe accettare almeno tre approcci: **ragionamento · interazione · forza**.

Se i personaggi escogitano una soluzione plausibile, lasciala funzionare. Un fallimento non deve bloccare l'avventura: deve produrre **tempo perso, complicazioni, Violazione, posizione sfavorevole o informazione incompleta**.
### Accesso alla biblioteca

**Biblium** è aperta a chi cerca una **conoscenza nuova e specifica**.

{{ruleBox
##### Regola d'accesso a BIBLIUM
Per accedere, il visitatore deve:
1. Cercare una conoscenza specifica;
2. Ignorarla realmente e non averla mai posseduta;
3. Desiderare autenticamente conoscerla.
}}

Per Biblium, **acquisire** e **recuperare** conoscenza sono cose diverse.

Il desiderio non deve essere disinteressato: è sufficiente voler realmente acquisire la conoscenza per uno scopo concreto, anche per conto di qualcun altro.

Aldebrando non può entrare perché la ricetta di Ermelinda appartiene a conoscenze che ha già posseduto e in parte dimenticato. Il presunto **Ingrediente Segreto**, inoltre, non costituisce una conoscenza da acquisire perché non esiste.

I personaggi, invece, non hanno mai posseduto quella conoscenza e soddisfano la regola d'accesso.
\column
### Indice di Violazione

Il DM tiene segretamente un **Indice di Violazione**.

| Indice | Stato | Reazione |
|--:|:--|:--|
| 0 | Visitatore | Nessuna |
| 1 | Irregolare | Osservazione |
| 2 | Trasgressore | Ammonimento |
| 3 | Vandalo | Intervento dei Bibliotecari |
| 4 | Minaccia | Intervento del Custode |

**Aumenta di 1** per distruzione deliberata di libri o documenti, furto dopo un ordine di restituzione, aggressione a un Bibliotecario non ostile, **schiamazzi persistenti dopo un ammonimento** o danni sistematici.

Un atto catastrofico può portare direttamente a **4**.

**Riduci di 1** quando il gruppo restituisce materiale, ripara un danno, accetta una sanzione o collabora con i Bibliotecari.

{{dmnote
##### Scopo della Violazione
La Violazione non punisce i giocatori: permette a **In Biblium di reagire coerentemente** e fornisce una via alternativa di escalation.
}}

\page


{{wideImage
![Torre di Aldebrando](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_1_Torre_Aldebrando.png)
}}

# 1. TORRE DI ALDEBRANDO
{{readaloud
La compagnia ha ricevuto una richiesta insolita.

Vi viene consegnata una lettera piegata, chiusa con un sigillo rappresentante una stella cadente.

La carta è pesante e di qualità, emana una appena percepibile energia.
}}
Consegna **{{far,fa-file}} H01 — Lettera di Aldebrando** (Appendice D) e attendi che la leggano ad alta voce.

{{readaloud
Appena terminate la lettura della missiva, un cerchio di luce comincia a tracciarsi sul pavimento attorno a voi e continua a tracciarsi a spirale nell'aria andando verso l'alto.

Un improvviso bagliore vi acceca e, quando gli occhi si riabituano alla luce, vi trovate in una verde valle tra le colline.

Fra alberi carichi di fiori bianchi illuminati dalla luce dell'imbrunire, si innalza una torre di pietra chiara. Cinque piani. Li potete contare senza difficoltà.

Intorno alla torre si estende un frutteto in piena fioritura. Api ronzano tra i rami e petali bianchi attraversano lentamente il sentiero.
}}
:
{{readaloud
Sulla porta vi attende un elfo dalla veste decisamente troppo elegante che ha l'aspetto di qualcuno che sembra aver trascorso la mattina a litigare con l'universo.
}}

## Aldebrando Astrofulgo

Aldebrando è un **elfo**, un mago di enorme potere, perfettamente consapevole della propria intelligenza e poco incline a fingere modestia.
:
È **scontroso, spocchioso e saccente**, ma non crudele. La sua irritazione nasce soprattutto dal fatto che un problema apparentemente banale ha resistito a mezzi arcani che egli riteneva infallibili.
:
Parla come se stesse correggendo una tesi mediocre. Anche quando chiede aiuto, riesce a farlo con l'aria di chi sta concedendo agli interlocutori un'importante opportunità formativa.

{{pageNumber,auto}}
\page

{{dmnote
##### Interpretare Aldebrando
Non renderlo gratuitamente antipatico. La sua arroganza deve essere divertente e leggibile, ma il legame con **Elandra** e il ricordo di **Ermelinda** devono mostrare che dietro l'ego esiste un affetto autentico.
}}

{{readaloud
«Eccovi finalmente! Pensavo che "situazione della massima urgenza" fosse comprensibile per voi… devo aver usato un linguaggio troppo forbito.
Bando agli indugi, l'impresa vi attende.»
}}

## Nove piani

Entrando nella torre, i personaggi scoprono che possiede **nove piani**.

Se qualcuno osserva che dall'esterno ne aveva cinque:

{{readaloud
«Naturalmente. Se ne avesse nove anche all'esterno sarebbe molto più alta.»
}}

Aldebrando non comprende quale sia il problema.

Non soffermarti troppo sull'esplorazione della torre: è un'introduzione.
{{pngArt,pngLeft,pngTop,pngLarge
![Aldebrando Astrofulgo](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/creatures/In_Biblium_Aldebrando.png)
}}
\column
## Il problema di Aldebrando
Sua figlia **Elandra** compie gli anni domani e lui vuole prepararle la stessa torta che sua nonna **Ermelinda** preparava quando era bambino.

Ricorda il sapore, la cucina e gli ingredienti. Ricorda soprattutto che Ermelinda parlava di un misterioso **Ingrediente Segreto**, ma non ricorda quale fosse.

Aldebrando racconta della torta di **Ermelinda** e degli ingredienti che ricorda.
| | |
|:-:|:-:|
| **Latte di Luna** | **Uova** |
| **Polvere di Stella** |**Farina dei Giganti** |
| **Essenza di Drago** |**Burro** |
| **Ingrediente Segreto** | |

Può inoltre fornire:
- il nome completo di **Ermelinda Soffiovento**;
- il periodo della propria infanzia, **430 anni fa**;
- il paese in cui vivevano;
- la certezza quasi ossessiva dell'esistenza dell'**Ingrediente Segreto**.

### Compenso

Se i personaggi chiedono del pagamento, Aldebrando offre **100 mo a testa** per il recupero della ricetta.

Non considera la cifra negoziabile, ma potrebbe cambiare idea davanti a un'argomentazione particolarmente convincente.

Se i personaggi suggeriscono immediatamente che forse l'Ingrediente Segreto non esiste:

{{readaloud
«Vi assicuro che mia nonna non avrebbe avuto alcuna ragione di mentire a un bambino di sette anni.»
}}

Lascia che la frase maturi.

Se i personaggi suggeriscono di usare la magia per svelare l'Ingrediente Segreto:

{{readaloud
«Ho fatto già ricorso alle mie arti magiche.

Ho consultato sapienti, evocato spiriti e interrogato demoni.

Nessuno è riuscito a svelarmelo.

Ho interrogato persino creature extraplanari.

Un demone del sesto girone mi ha assicurato di conoscere diciassettemila modi di corrompere un'anima immortale, ma non l'ingrediente segreto della ricetta per la torta di mia nonna. Incompetente.»
}}
{{pageNumber,auto}}
\page
## Il nono piano e il portale
{{readaloud
Al nono piano si trova una stanza quasi spoglia.
Lungo le pareti ci sono soltanto uno scaffale e alcune scrivanie ingombre di ingredienti e pergamene.

Al centro un ampio spazio vuoto è occupato da un portale verticale che sembra un vortice in un cielo stellato.
}}
{{readaloud
«Credo di aver trovato il modo di risolvere questo segreto arcano.

La biblioteca extradimensionale Biblium conserva libri, documenti, storie e conoscenze perdute.

Ho trovato il modo di aprirvi un portale ed è qui che entrate in scena voi avventurieri.

Dovete entrare e recuperare per me la ricetta prima di mezzanotte».
}}

Aldebrando non può attraversarlo. La superficie diventa solida al suo contatto. Può dimostrarlo con crescente irritazione.
{{readaloud
Ho provato teletrasporto, forma eterea, evocazione, trasmutazione e altre magie.

Niente.
}}
Se i personaggi chiedono perché:
{{readaloud
«Se lo sapessi, suppongo che non avrei bisogno di voi.»
}}

## Fischietto di Richiamo Astrofulgico

Prima che entrino, Aldebrando consegna al gruppo un piccolo fischietto d'argento.

{{clue
##### Fischietto di Richiamo Astrofulgico
Una creatura all'interno di In Biblium può soffiarvi come **azione**.

Dopo **1 round** si apre nelle vicinanze un portale verso il nono piano della Torre di Astrofulgo. Il portale rimane aperto per **1 minuto**.

Il fischietto funziona **una sola volta**.
}}

{{readaloud
«Non perdetelo.»

Pausa.
\
«Sul serio.»
}}


# 2. IN BIBLIUM


{{readaloud
Attraversate il portale.

Per un istante non esiste nulla e vi sembra di cadere in un vortice sempre più nero.

Poi compare una luce.

E un'altra.

E un'altra ancora.

Solo dopo qualche secondo comprendete che quelle che sembravano stelle sono lampade sospese a decine di metri sopra di voi.

Scaffali smisurati salgono nell'oscurità fino a scomparire alla vista.

Scale e passerelle attraversano il vuoto.

File di libri proseguono tanto lontano da dissolversi in una foschia azzurra.

Nel pavimento di pietra chiara e inserti dorati è incisa una frase: **SCIENTIA NON PERIT.**
}}

Il primo obiettivo è trovare il **Catalogo Generale**.

Un cartello indica la direzione.

Il problema sono i Refusi.
\column
## I Refusi

Un gruppo di piccole creature di carta sta divorando un cartello.

Non mangiano la carta. Mangiano **ciò che vi è scritto**.

{{pngArt,pngLeft,pngTop,pngLarge
![ReFUsi](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/creatures/In_Biblium_Refusi.png)
}}
{{pageNumber,auto}}
\page

{{fullPageArt
![Biblium](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_2_Ingresso.png)
}}
\page

Quando inghiottono una parola, questa scompare materialmente dalla pagina.

{{clue
##### ERMELINDA SOFFIOVENTO

MEMORIE DOMESTICHE CONSULTARE CATALOGO GENERALE
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

**SAG (Addestrare Animali) CD 13:** sorprendentemente, funziona.

Un giocatore che offre ai Refusi qualcosa di particolarmente "gustoso" — un contratto, un grimorio, una lettera molto lunga — ottiene automaticamente la loro attenzione.

## Incontro 1: Refusi

Per sei PG di 3° livello usa **3 Sciami di Refusi**.

Lo scontro deve essere rapido.

I Refusi non combattono fino alla morte.

Quando rimane un solo sciame con metà PF o meno, fugge negli scaffali.

Se lo scontro raggiunge il termine del **terzo round**, gli eventuali Refusi rimasti fuggono negli scaffali non appena ne hanno occasione.

### Sviluppo: catturare un Refuso

Un Refuso isolato può essere intrappolato con una prova appropriata **CD 18**.

Un Refuso catturato può essere indirizzato **una sola volta** a divorare una breve parola o alcune lettere da un testo. Subito dopo approfitta della confusione per fuggire negli scaffali.

La cancellazione **non altera la realtà in generale**.

Quando un Refuso cancella una negazione da una **norma o istruzione operativa di Biblium**, il testo modificato viene interpretato letteralmente.

**L'effetto è locale:** la modifica riguarda soltanto quella specifica iscrizione o istruzione. Non riscrive le leggi generali di Biblium e non modifica altri esemplari dello stesso testo.

Esempio:

`NON AUTORIZZATO` → `AUTORIZZATO`

Per mantenere semplice la gestione al tavolo, usa questa capacità soprattutto per cancellare **NON** o un'altra breve negazione. Non permette di aggiungere parole, riscrivere frasi o creare nuove istruzioni.

Premia gli utilizzi creativi coerenti con questa regola.

{{monster,frame
## Sciame di Refusi {{bonus **GS 1**}}
*Uno sciame di minuscole aberrazioni di carta e inchiostro che divora parole, lettere e significati.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 13
**PF**         :: 27 (6d8)
**Velocità**   :: 9 m, scalare 9 m
}}

{{vitalsCol
**Iniziativa** :: +3 (13)
**Taglia**     :: Media (sciame di creature Minuscole)
**Tipo**       :: Aberrazione
}}
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
{{pageNumber,auto}}
\page

# 3. SALA DEI LEGGII
{{wideImage
![Sala dei Leggii](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_2_Sala_lettura.png)
}}
Per raggiungere il Catalogo Generale occorre attraversare un salone altissimo.

{{readaloud
La sala è quasi vuota.

Pareti di libri salgono per decine di metri.

Sul pavimento sono disposti pochi leggii, tutti vuoti.

Tutti tranne uno.

Al centro della sala, perfettamente illuminato, riposa un enorme tomo rilegato in cuoio scuro, chiuso da eleganti borchie metalliche e con una decorazione familiare.

È probabilmente il libro più invitante che abbiate mai visto.
}}

Lascia che i giocatori reagiscano.
:
Il libro non è un mimic.
:
**Il leggio sì.**
\column
## Gestione del tempo: tagliare questa scena

Se sono trascorse **più di 1 ora e 20 minuti** dall'inizio della sessione, il mimic non attacca.

Il leggio emette semplicemente un piccolo ringhio quando qualcuno si avvicina. La scena dura trenta secondi e si prosegue.
{{pageNumber,auto}}
\page
## Il Mimic del Leggio
{{pngArt,pngLeft,pngTop,pngLarge
![Mimic](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/creatures/In_Biblium_Mimic.png)
}}
Quando qualcuno tocca il tomo, il leggio cerca di afferrarlo.

Questo incontro deve essere rapido e leggermente assurdo.

Usa il blocco statistiche **Mimic del Leggio**

{{monster,frame
## Mimic del Leggio {{bonus **GS 2**}}
*Un leggio di legno scuro che aspetta immobile che qualcuno si interessi al libro appoggiato sopra di lui.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 13
**PF**         :: 45 (6d8 + 18)
**Velocità**   :: 4,5 m
}}

{{vitalsCol
**Iniziativa** :: +1 (11)
**Taglia**     :: Media
**Tipo**       :: Mostruosità
}}
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

***Adesivo.*** Una creatura colpita dallo Pseudopodo è **Afferrata**. Come Azione può effettuare una prova di **FOR (Atletica) o DES (Acrobazia) CD 13**, terminando la condizione con un successo. Finché l'afferramento dura, il mimic ha Vantaggio agli attacchi contro quella creatura.
### Azioni

***Pseudopodo.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 8 (1d10 + 3) danni contundenti e il bersaglio è Afferrato.

***Morso.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 10 (2d6 + 3) danni perforanti.

### Tattiche

Il mimic vuole mangiare, non morire. A **15 PF o meno** cerca di fuggire trascinandosi goffamente verso gli scaffali.
}}


Sul pavimento, sotto il mimic, una targhetta recita:

{{readaloud
**È severamente vietato nutrire gli arredi.**
}}
{{pageNumber,auto}}
\page

## Il libro

Una volta superato, neutralizzato o aggirato il leggio, i personaggi possono finalmente aprire il tomo.

{{clue
##### Indice Generale delle Norme per la Consultazione della Biblioteca BIBLIUM

**Accesso**

Per accedere, il visitatore deve:

1. Cercare una conoscenza specifica;
2. Ignorarla realmente e non averla mai posseduta;
3. Desiderare autenticamente conoscerla.

:

**Ricerca di un'opera**

Qualora titolo, autore o collocazione siano ignoti, il visitatore è invitato a rivolgersi al **Catalogo Generale**.

La ricerca può essere effettuata indicando almeno uno dei seguenti elementi:

- argomento;
- persona cui la conoscenza è collegata;
- luogo;
- evento;
- periodo;
- ricordo associato.

:
**Ricordi e conoscenze non formalizzate**

Le conoscenze legate a esperienze personali, ricordi o fatti mai formalmente trascritti possono essere ricercate nell'**Archivio delle Storie e dei Ricordi**.

:

**Consultazione**

I volumi possono essere consultati liberamente.

Non possono essere sottratti dalla Biblioteca senza autorizzazione.

I materiali prelevati devono essere restituiti al luogo di provenienza o affidati a un Bibliotecario.

:

**Condotta**

Non saranno tollerati:

- schiamazzi persistenti;
- danneggiamenti intenzionali;
- sottrazioni illecite;
- aggressioni al personale della Biblioteca.

Le violazioni possono comportare l'intervento dei **Bibliotecari** e, nei casi più gravi, del **Custode**.
}}
{{pageNumber,auto}}
\page
# 4. IL POZZO DEI LIBRI

{{readaloud
Il corridoio termina.

Non davanti a una porta.

Davanti al vuoto.

Oltre la balaustra si apre una voragine perfettamente cilindrica, tanto vasta che la parete opposta è velata dalla foschia.

Ogni centimetro delle pareti è coperto da scaffali.

Scale, passerelle e ponti attraversano il pozzo a differenti altezze, scendendo in un intreccio così fitto da sembrare il progetto di un labirinto costruito in verticale.

Guardate verso il basso.

Non vedete il fondo.

}}

Il Catalogo Generale si trova dall'altro lato del Pozzo.

## Gravità bibliografica

La gravità del Pozzo non è uniforme.

Le passerelle seguono associazioni concettuali anziché una geometria normale.

Un percorso può riportare apparentemente nello stesso punto ma su un livello diverso.

## Attraversare il Pozzo

Richiedi **3 successi prima di 2 fallimenti**.

Ogni personaggio può contribuire descrivendo il proprio approccio.

Ogni personaggio può contribuire **una volta** prima che qualcuno agisca nuovamente. La stessa abilità può essere riutilizzata solo descrivendo un approccio sostanzialmente diverso.

**FOR (Atletica) CD 12:** attraversare una sezione pericolante.

**DES (Acrobazia) CD 12:** passare su una scala mobile o passerella inclinata.

**INT (Indagare) CD 12:** comprendere la logica delle classificazioni.

**SAG (Percezione) CD 13:** individuare il percorso più sicuro.

Magia o idee particolarmente appropriate possono concedere un successo automatico.

### Conseguenza del fallimento

Nessuno precipita automaticamente nel nulla.

Con 2 fallimenti il gruppo raggiunge comunque l'altra parte, ma provoca uno stormo di **Libri Volanti**.
\column
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
:
Chi si trova sulla passerella effettua un **TS DES CD 12**.
:
**Fallimento:** (a scelta del DM)
- viene sbilanciato e afferra il parapetto;
- perde un piccolo oggetto non assicurato;
- subisce **1d6 danni contundenti**.

:
Un attacco riuscito contro lo stormo lo disperde.
:
Non tirare iniziativa salvo che i giocatori insistano nel combatterlo.
{{pngArt,pngRight,pngBottom,pngLarge
![Libri Volanti](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/creatures/In_Biblium_Libri_volanti.png)
}}
{{pageNumber,auto}}
\page
{{fullPageArt
![Pozzo dei Libri](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_3_Pozzo.png)
}}
\page
# 5. CATALOGO GENERALE

{{readaloud
Il Catalogo Generale sembra ancora più impossibile della Biblioteca.

Migliaia di schedari occupano pavimento, pareti, balconate e passerelle.

Poi alzate gli occhi.

Altri schedari ricoprono completamente il soffitto.

Figure incappucciate camminano lassù come se fosse perfettamente normale.

Non hanno piedi.

Una di loro apre un cassetto sopra le vostre teste.

Alcune schede cadono. Ma verso il soffitto.
}}

Sono i **Bibliotecari**.

Non sono ostili (forse).

## I Bibliotecari

I Bibliotecari assomigliano a frati amanuensi sospesi pochi centimetri dal suolo.

Non hanno piedi. Le loro maschere possiedono un lungo naso adunco. Ogni mano ha **quattro dita complessive: tre dita e un pollice**.

Parlano con tono educato, preciso e completamente privo di ironia.
{{pngArt,pngLeft,pngMid,pngMedium
![Bibliotecario](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/creatures/In_Biblium_Biblotecario1.png)
}}
\column
### Primo contatto

Un Bibliotecario si avvicina.

{{readaloud
«Conoscenza richiesta?»
}}

Se i personaggi rispondono genericamente «una ricetta»:

{{readaloud
«Richiesta insufficiente.»
}}

Se nominano Ermelinda Soffiovento oppure Aldebrando Astrofulgo:

{{readaloud
«Memoria domestica. Preparazione alimentare. Ricerca ammessa.»
}}

## Ricerca nel Catalogo

Il Catalogo interpreta inizialmente le parole di Aldebrando **alla lettera**.

### Latte di Luna

La ricerca conduce a:

**Zootecnia extraplanare → Fauna lunare → Secrezioni commestibili**

Decine di risultati. Nessuno pertinente.
:
Una ricerca per **Ermelinda**, nonna o torta, invece, produce una scheda.

{{handout
##### {{far,fa-file}} H02 — RISULTATO DEL CATALOGO
**LUNA — Nome proprio di bovino domestico**

Proprietario: **Ermelinda Soffiovento**
Produzione giornaliera: **latte fresco — 2 brocche**.
}}

Consegna ai giocatori **H02**.

### Polvere di Stella

La ricerca letterale conduce a trattati astronomici e campioni minerali.

Cercando nelle liste della spesa:

{{handout
##### {{far,fa-file}} H03 — RISULTATO DEL CATALOGO
**ESTRELLA — vicina della casa accanto**

Annotazione domestica: **zucchero fine — prestito**

*Me ne serve per la torta da fare ad Aldebrando.*
}}

Consegna ai giocatori **H03**.
{{pageNumber,auto}}
\page
{{fullPageArt
![Catalogo](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_4_Catalogo.png)
}}
\page
### Farina dei Giganti

Il Catalogo propone inizialmente:

**Giganti → Alimentazione → Cereali → Farina**

Nessuna corrispondenza.

Cercando nelle spese domestiche, un vecchio registro commerciale riporta:

{{handout
##### {{far,fa-file}} H04 — RISULTATO DEL CATALOGO
**MULINO GIGANTI — Registro Commerciale**

Produzione farine e cereali.
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

*Aldebrando dice che ha il sapore di fuoco di drago.*
}}

Consegna ai giocatori **H05**.
\column
## Sviluppo: capire il meccanismo

Dopo due rivelazioni, un personaggio può effettuare **INT (Indagare) CD 15**.

**Successo:** Aldebrando non ricordava nomi fantastici; ricordava **come quei nomi suonavano a un bambino**.

Dopo tre rivelazioni non è necessaria alcuna prova.

## L'Ingrediente Segreto

Nessuna ricerca produce un ingrediente.

Compare invece:

{{clue
##### Collegamento bibliografico
**SOFFIOVENTO, ERMELINDA**
Memorie domestiche
Preparazioni alimentari
Ricordi familiari

**ARCHIVIO DELLE STORIE E DEI RICORDI**
}}

Un Bibliotecario indica la strada.
::::::::::::::::

# 6. ARCHIVIO DELLE STORIE E DEI RICORDI

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

## Il libro che racconta i personaggi

Durante la ricerca, un personaggio nota un volume.

Sulla copertina:

{{clue
IN BIBLIUM
}}

All'interno:

{{readaloud
*Il potente mago Aldebrando Astrofulgo desiderava preparare una torta per sua figlia Elandra...*
}}

Continuando a leggere, il testo descrive **la sessione appena giocata**.

Il DM deve inserire dettagli realmente accaduti.
{{pageNumber,auto}}
\page
{{fullPageArt
![Ricordi](https://raw.githubusercontent.com/apk01k/Dnd2024-ADV-In_Biblium/main/images/locations/In_Biblium_5_Sala_dei_Ricordi.png)
}}
\page
Cita almeno **una battuta di un personaggio, una scelta insolita, l'esito del Pozzo e ciò che è successo con il mimic.**

Poi:

{{readaloud
*E fu allora che trovarono un libro intitolato **In Biblium**.*
}}

Voltano pagina.

{{readaloud
*Naturalmente, qualcuno pensò immediatamente di leggere la fine.*
}}

Fermati.

## Leggere il futuro

**Permettilo.**

Il libro non è un trucco: può realmente fornire informazioni.

La pagina finale recita:

{{readaloud
*E quando finalmente compresero quale fosse l'Ingrediente Segreto di Ermelinda, capirono perché nessun demone, spirito o sapiente aveva mai potuto rivelarlo.*
}}

Non specifica quale sia. Il libro contiene la **storia dei personaggi**, non conoscenze che essi non hanno ancora acquisito.

{{dmnote
##### Gestire le domande al libro
Lascia che i personaggi sperimentino liberamente con il volume, ma evita che la scena assorba l'intera sessione. Dopo **3–4 domande significative**, rendi le risposte progressivamente più ellittiche e orienta l'attenzione verso i **Ricordi d'Infanzia di Aldebrando**.
}}
La frase conduce a **ASTROFULGO, ALDEBRANDO — RICORDI D'INFANZIA**.
\
**«Come supereremo il Custode?»** Se non lo hanno ancora provocato:

{{readaloud
*Fortunatamente, non ebbero bisogno di scoprirlo.*
}}

**«Cosa c'è dietro quella porta?»**

{{readaloud
*Non lo seppero finché non la aprirono.*
}}

**«Moriremo?»**

{{readaloud
*In quel momento decisero che forse alcune pagine non dovevano essere lette in anticipo.*
}}

Se insistono, descrivi **una possibilità**, mai un destino inevitabile.

## Il futuro cambia

Il libro descrive il futuro più coerente con la situazione corrente.

{{clue
*Arven aprì la porta.*  
→  
*Dopo aver letto ciò che avrebbe fatto, Arven decise di non aprire la porta.*
}}

Le parole cambiano insieme alle decisioni. **Il libero arbitrio non viene mai negato.**

## Prelievo non autorizzato

Consultare il libro è consentito. **Portarlo via dal suo posto non lo è.**

Se i personaggi decidono di utilizzarlo come guida permanente, compare un Bibliotecario.

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
:
Indipendentemente dall'Indice, i Bibliotecari possono intervenire per recuperare fisicamente un'opera non restituita. Lo scontro inizia soltanto se i personaggi oppongono resistenza, tentano di fuggire con il volume o aggrediscono il personale.
:
Se il gruppo insiste, altri Bibliotecari intervengono. Questo può condurre allo **Scontro** (vedi i blocchi di Bibliotecario e Custode in Appendice A).

{{dmnote
##### Il vero problema
Ai Bibliotecari non interessa che il libro predice il futuro; interessa che **il prestito non sia stato registrato**.
}}
{{pageNumber,auto}}
\page
## Cercare Ermelinda

La scheda del Catalogo permette di individuare il volume:

{{clue
##### ASTROFULGO, ALDEBRANDO — RICORDI D'INFANZIA
Collegamento: **ERMELINDA**
}}

Quando viene aperto, una delle bolle sopra il libro comincia a crescere.

Fino a inglobare i personaggi.

## La cucina di Ermelinda

{{readaloud
La Biblioteca scompare.

Sentite pioggia.

Siete in una piccola cucina.

Il fuoco crepita sotto una pentola. Una finestra appannata guarda su un cortile bagnato.

Un'elfa anziana sta lavorando un impasto.

Accanto al tavolo siede un bambino.

Avrà sette anni.
}}

I personaggi non possono cambiare significativamente il ricordo. Possono muoversi e osservare.

Ermelinda prepara la torta.

Osservando la cucina possono riconoscere:

- un sacco marchiato **Mulino Giganti**;
- una brocca di latte appena munto e, dalla finestra, il muggito della mucca **Luna**;
- un piccolo involto di zucchero con una nota: **«Ricordati che ne voglio una fetta — Estrella»**;
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
**ERMELINDA:** «Visto che è un segreto non posso dirtelo. Dovrai scoprirlo da solo.»
}}

Proprio allora la scena si lacera.

Le parole diventano incomprensibili.

La cucina scompare.

## Il ricordo incompleto

I personaggi tornano nell'Archivio.

Il ricordo termina esattamente dove termina anche la memoria di Aldebrando: **Ermelinda non gli rivelò mai altro**.

La risposta non è quindi nascosta in una parte dimenticata del ricordo.

Sul volume compare però un collegamento bibliografico:

{{clue
##### SOFFIOVENTO, ERMELINDA — QUADERNO DOMESTICO
Ricette, contabilità, annotazioni.
**Scaffale R-17.**
}}

Non richiedere altre prove. Sono arrivati alla soluzione.

## Il quaderno di Ermelinda

Non è protetto. Non è incatenato. Non emette luce.

È un piccolo quaderno con la copertina consumata e alcune macchie di farina.

Accanto al quaderno, una targhetta recita:

{{clue
**OPERA NON DISPONIBILE AL PRESTITO**
}}

Se i personaggi hanno conservato un **Refuso catturato**, possono usarlo per cancellare **NON**:

`OPERA NON DISPONIBILE AL PRESTITO` → `OPERA DISPONIBILE AL PRESTITO`

Per la regola locale dei Refusi, la modifica vale soltanto per **questo specifico quaderno**. In tal caso i Bibliotecari permettono di portarlo fuori senza aumentare l'Indice di Violazione.

Consegna ai giocatori **{{far,fa-file}} H06 — Ricetta di Ermelinda**.

:

Lascia qualche secondo di silenzio.

Non spiegare il significato.
{{pageNumber,auto}}
\page



# 7. USCIRE DA IN BIBLIUM

## Uscita ordinaria

I personaggi possiedono ora la conoscenza richiesta.

Non è necessario portare via il quaderno. Possono copiarne la ricetta. 
Se vogliono portare l'originale e **non** hanno modificato la targhetta con un Refuso:

{{readaloud
«Opera non disponibile al prestito.»
}}

I Bibliotecari permettono senza problemi di trascriverla. Se invece la targhetta è stata modificata in **OPERA DISPONIBILE AL PRESTITO**, il quaderno può essere portato fuori senza Violazione.

Quando sono pronti, possono usare il **Fischietto di Richiamo Astrofulgico**.

### Se il fischietto non è disponibile

Non bloccare l'avventura se il Fischietto di Richiamo Astrofulgico viene perso o utilizzato troppo presto.

Se i personaggi hanno già acquisito la conoscenza richiesta, un **Bibliotecario** può aprire su richiesta un **varco amministrativo** verso il luogo dal quale sono entrati.

Il varco non consente di portare fuori opere o materiali **privi di autorizzazione al prestito**. Un'opera regolarmente autorizzata può attraversarlo.

Se invece il gruppo viene espulso dal **Custode**, l'espulsione lo riporta automaticamente al **nono piano della Torre di Aldebrando**.

Se il fischietto è stato utilizzato prematuramente, Aldebrando può riaprire il portale d'ingresso e i personaggi possono attraversarlo nuovamente finché soddisfano ancora la Regola d'accesso.

## Escalation condizionale

Gli incontri seguenti avvengono soltanto se l'Indice di Violazione e le azioni del gruppo li rendono necessari.

## Scontro 2: I Bibliotecari

Questo incontro avviene solo se il comportamento dei personaggi lo provoca. Per sei PG di 3° livello usa **3 Bibliotecari**. I Bibliotecari non cercano di uccidere.
\
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

## Scontro 3: Il Custode

Il Custode appare soltanto a **Violazione 4**.

{{dmnote
##### Quando interviene il Custode
Se il Custode interviene durante o subito dopo uno scontro con i Bibliotecari, i Bibliotecari cessano immediatamente le ostilità e si fanno da parte.
:
Non trattare **Bibliotecari e Custode come due incontri completi consecutivi**.
}}

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
- resa e successiva espulsione.


\
Il libro *In Biblium*, se ancora disponibile, contiene:
{{readaloud
*Non potevano sconfiggere il Custode.*
\
*Fortunatamente non era necessario.*
}}

Non aggiungere altro. 
Lascia ai giocatori la soluzione.
{{pageNumber,auto}}
\page

{{pageNumber,auto}}

# 8. RITORNO ALLA TORRE

Se i personaggi usano il **Fischietto di Richiamo Astrofulgico**:

{{readaloud
Il fischietto non produce suono. Per un istante, tutto intorno a voi diventa completamente silenzioso.

Un secondo dopo, una luce si irradia dal pavimento e vi circonda a spirale.
}}

Se utilizzano un **varco amministrativo** o vengono **espulsi**, descrivi invece il passaggio secondo la procedura utilizzata.

In ogni caso, si ritrovano davanti ad Aldebrando al nono piano della torre.

{{readaloud
«Ebbene?»
}}

Lascia ai giocatori raccontare ciò che hanno scoperto.

Non anticipare le battute.

Se spiegano gli ingredienti uno alla volta:

**Latte di Luna?**

{{readaloud
«…una mucca?»
}}

**Polvere di Stella?**

{{readaloud
«Estrella, me la ricordo!»
}}

**Farina dei Giganti?**

{{readaloud
«Giganti era il cognome del mugnaio.»
}}

**Essenza di Drago?**

{{readaloud
«Io... chiamavo così la cannella e la paprika?»
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

Aldebrando salda il compenso promesso e consegna a ciascun personaggio le **100 mo**.

{{dmnote
### Eventuale
Inoltre, ciascun personaggio riceve un piccolo **Segnalibro di In Biblium**, prova del diritto a presentare in futuro una nuova richiesta di consultazione.

Non consente automaticamente l'accesso. La Biblioteca decide sempre se la richiesta soddisfa le proprie regole.
}}
## Epilogo

I personaggi **non assistono a questa scena**.

Dopo aver ricevuto il compenso vengono congedati.

Il DM può leggerla come breve epilogo cinematografico.

{{readaloud
L'indomani mattina la Torre è insolitamente silenziosa.
\
Sul tavolo della cucina c'è una torta.
:
Non è perfetta.
:
Una parte è leggermente più alta dell'altra e sulla superficie c'è decisamente qualche imperfezione.
\
Aldebrando ha preparato tutto personalmente.
:
Nessuna magia.
:
Aldebrando, che ha contrattato con demoni e discusso con esseri immortali, sembra improvvisamente incapace di respirare.
:
Elandra, seduta a tavola, assaggia una fetta di torta.
:
Poi sorride. «Buona.» E Aldebrando sorride a sua volta.
}}
{{pageNumber,auto}}
\page

{{pageNumber,auto}}

# APPENDICE A — CREATURE

{{monster,frame
## Sciame di Refusi {{bonus **GS 1**}}
*Uno sciame di minuscole aberrazioni di carta e inchiostro che divora parole, lettere e significati.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 13
**PF**         :: 27 (6d8)
**Velocità**   :: 9 m, scalare 9 m
}}

{{vitalsCol
**Iniziativa** :: +3 (13)
**Taglia**     :: Media (sciame di creature Minuscole)
**Tipo**       :: Aberrazione
}}
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

{{monster,frame
## Mimic del Leggio {{bonus **GS 2**}}
*Un leggio di legno scuro che aspetta immobile che qualcuno si interessi al libro appoggiato sopra di lui.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 13
**PF**         :: 45 (6d8 + 18)
**Velocità**   :: 4,5 m
}}

{{vitalsCol
**Iniziativa** :: +1 (11)
**Taglia**     :: Media
**Tipo**       :: Mostruosità
}}
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

***Adesivo.*** Una creatura colpita dallo Pseudopodo è **Afferrata**. Come Azione può effettuare una prova di **FOR (Atletica) o DES (Acrobazia) CD 13**, terminando la condizione con un successo. Finché l'afferramento dura, il mimic ha Vantaggio agli attacchi contro quella creatura.

### Azioni

***Pseudopodo.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 8 (1d10 + 3) danni contundenti e il bersaglio è Afferrato.

***Morso.*** *Tiro per Colpire in Mischia:* +5, portata 1,5 m. *Colpito:* 10 (2d6 + 3) danni perforanti.

### Tattiche

Il mimic vuole mangiare, non morire. A **15 PF o meno** cerca di fuggire trascinandosi goffamente verso gli scaffali.
}}

\page

{{pageNumber,auto}}

{{monster,frame
## Bibliotecario {{bonus **GS 2**}}
*Un archivista fluttuante, privo di piedi, con veste da amanuense e maschera dal lungo naso adunco.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 15
**PF**         :: 39 (6d8 + 12)
**Velocità**   :: 0 m, volare 9 m (fluttuare)
}}

{{vitalsCol
**Iniziativa** :: +2 (12)
**Taglia**     :: Media
**Tipo**       :: Aberrazione
}}
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

***Penna d'Archivio.*** *Tiro per Colpire Magico in Mischia:* +5, portata 1,5 m. *Colpito:* 10 (1d8 + 3 più 1d4) danni da forza.

***Vincolo di Consultazione (Ricarica 5–6).*** Una creatura entro 12 m deve superare un **TS FOR CD 13** o essere Trattenuta da nastri di pergamena animata. La creatura può ripetere il tiro salvezza alla fine di ciascun proprio turno, terminando l'effetto con un successo.

***Silenzio, prego.*** Una creatura entro 18 m che il Bibliotecario può vedere effettua un **TS SAG CD 13**. *Fallimento:* fino all'inizio del turno successivo del Bibliotecario non può effettuare Reazioni e parla soltanto sottovoce. Questo effetto non impedisce le componenti verbali degli incantesimi.

### Reazioni

***Ricollocazione.*** {{font-variant:small-caps **Trigger:**}} una creatura entro 1,5 m tenta di allontanarsi portando un oggetto appartenente alla Biblioteca. {{font-variant:small-caps **Risposta:**}} il Bibliotecario si muove fino a 3 m senza provocare Attacchi di Opportunità.

### Tattiche

I Bibliotecari usano **Vincolo di Consultazione**, recuperano gli oggetti e cercano di espellere gli intrusi. Non attaccano creature Incoscienti.
}}

{{monster,frame
## Custode {{bonus **GS 5**}}
*La massima autorità operativa della Biblioteca: un archivista spettrale, austero, fluttuante, armato di un lungo bastone nodoso.*

{{stats
{{vitals
{{vitalsCol
**CA**         :: 17
**PF**         :: 105 (14d10 + 28)
**Velocità**   :: 0 m, volare 9 m (fluttuare)
}}

{{vitalsCol
**Iniziativa** :: +1 (11)
**Taglia**     :: Grande
**Tipo**       :: Aberrazione
}}
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

***Bastone Nodoso.*** *Tiro per Colpire in Mischia:* +7, portata 3 m. *Colpito:* 12 (1d10 + 4 più 1d4) danni contundenti e da forza.

***Restituire.*** Una creatura entro 18 m che trasporta un oggetto appartenente a In Biblium deve superare un **TS FOR CD 15**. *Fallimento:* l'oggetto vola immediatamente nella mano libera del Custode o sullo scaffale più vicino.

***Ondata d'Espulsione (Ricarica 5–6).*** Il Custode colpisce il pavimento con il bastone. Ogni creatura ostile entro 4,5 m effettua un **TS FOR CD 15**. *Fallimento:* 13 (3d8) danni da forza, spinta di 6 m e Prono. *Successo:* metà danni e nessuno spostamento.

### Azioni Bonus

***Ricollocare.*** Il Custode teletrasporta un oggetto incustodito appartenente alla Biblioteca che può vedere entro 18 m su uno scaffale libero entro la stessa distanza.

### Reazioni

***Silenzio.*** {{font-variant:small-caps **Trigger:**}} una creatura entro 18 m lancia un incantesimo. {{font-variant:small-caps **Risposta:**}} il Custode impone svantaggio a un eventuale tiro per colpire dell'incantesimo oppure ottiene vantaggio al primo tiro salvezza effettuato contro quell'incantesimo.
}}
{{pageNumber,auto}}
\page

{{monster,frame
### Tattiche

Il Custode non combatte per uccidere. Attacca chi continua a distruggere il patrimonio e usa **Ondata d'Espulsione** per separare il gruppo.

Se recupera tutti gli oggetti sottratti e i personaggi cessano le ostilità, interrompe immediatamente il combattimento.
}}

{{dmnote
##### Nota per il DM
Per sei personaggi di 3° livello il Custode è un avversario serio, ma l'economia delle azioni favorisce fortemente il gruppo.

Il suo vero vantaggio è che **non deve vincere riducendo tutti a 0 PF**. Deve recuperare il patrimonio e costringerli ad andarsene.
}}
{{pageNumber,auto}}
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

Non è progettato come scontro impegnativo. Deve durare circa **1–2 round**.

Per 7–8 PG o personaggi di 4°–5° livello, porta i PF a **60** e concedigli una volta per round una reazione:

***Scatto Adesivo.*** Quando viene mancato da un attacco in mischia, il mimic si muove di 1,5 m senza provocare Attacchi di Opportunità.

Non aggiungere altri mimic: rovinerebbe la gag.
\column
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
| 4 PG livello 3 | 85 PF; Ondata d'Espulsione 2d8 |
| 5 PG livello 3 | 95 PF |
| 6 PG livello 3 | statistiche normali |
| 7–8 PG livello 3 | 125 PF |
| 6 PG livello 4 | 125 PF; +1 Bibliotecario |
| 6 PG livello 5 | 145 PF; +2 Bibliotecari |

Per PG di 5° livello, il Custode può effettuare **3 attacchi** con Multiattacco anziché 2.

Questi rinforzi compaiono solo se necessari e possono arrivare al secondo round.
{{pageNumber,auto}}
\page
# APPENDICE C — GESTIONE DELLA SESSIONE
## Reference rapida del DM

| Elemento | Reference |
|:--|:--|
| **Obiettivo** | Recuperare la ricetta di Ermelinda |
| **Verità** | Non esiste un ingrediente magico |
| **Accesso** | conoscenza specifica + realmente ignorata + mai posseduta |
| **Uscita** | Fischietto; in emergenza varco amministrativo o espulsione |
| **Escalation** | 0 Visitatore → 1 Irregolare → 2 Trasgressore → 3 Vandalo → 4 Minaccia |

{{ruleBox
##### Ricorda
Quando i giocatori propongono qualcosa che **ha senso nella logica di In Biblium**, preferisci una conseguenza interessante a un semplice «no».
}}

| Scontro | Descrizione |
|:--|:--|
|**Refusi** | mangiano parole|
|**Libri Volanti** | fauna ambientale|
|**Mimic** | il leggio, non il libro|
|**Bibliotecari** | amministrazione|
|**Custode** | ultima escalation|


**Tema:** La conoscenza non è necessariamente ciò che è stato scritto. La memoria non è necessariamente ciò che è accaduto. E alcune cose diventano straordinarie non per ciò che contengono, ma per **chi ce le ha donate**.

## Pacing delle 4 ore
{{dmnote
##### Non tagliare
- il libro *In Biblium*;
- il ricordo di Ermelinda;
- la rivelazione dell'Ingrediente Segreto;
- il confronto finale con Aldebrando.

Sono il cuore dell'avventura.
}}
\column
### Ritardo — taglia le scene
| | |
|:-|:-|
|15 min |Riduci il Pozzo a **2 successi prima di 2 fallimenti**.|
|30 min|Il Mimic ringhia ma non combatte.|
|45 min |Nel Catalogo, dopo la scoperta di due ingredienti, un Bibliotecario consegna spontaneamente i riferimenti necessari per gli altri due.|
|60 min |Non utilizzare alcun combattimento con Bibliotecari o Custode salvo che i giocatori lo provochino deliberatamente.|

{{dmnote
##### Micro-reference di combattimento

**Afferrato:** Velocità 0. Svantaggio agli attacchi contro bersagli diversi dall'afferrante. Per liberarsi: Azione e prova di **FOR (Atletica) o DES (Acrobazia)** contro la CD di fuga. Termina anche se l'afferrante è Incapacitato o perde la portata.
:
**Trattenuto:** Velocità 0; attacchi contro la creatura con Vantaggio; suoi attacchi e TS DES con Svantaggio.
:
**Prono:** per rialzarsi spende metà Velocità. Ha Svantaggio ai propri attacchi. Gli attacchi contro di lei hanno Vantaggio entro 1,5 m, altrimenti Svantaggio.
:
**Reazione:** dopo averne usata una, non può usarne un'altra fino all'inizio del proprio turno successivo.
:
**Attacco di Opportunità:** Reazione contro una creatura visibile che lascia la portata usando **una delle proprie Velocità**, un'Azione, un'Azione Bonus o una Reazione. L'attacco avviene prima che esca dalla portata.
:
**Ricarica 5–6:** all'inizio del turno tira 1d6; con **5–6** l'azione torna disponibile.
}}


{{pageNumber,auto}}
\page


# APPENDICE D — HANDOUT
{{wide
{{dmnote
##### Uso degli handout
Nel corpo dell'avventura il simbolo **{{far,fa-file}}** identifica un materiale consegnabile. Le pagine seguenti possono essere stampate o ritagliate separatamente.
}}
:

## {{far,fa-file}} H01 — Lettera di Aldebrando

{{letter,fontMedievalSharp
**A codesta stimatissima compagnia,**
:
**e a chi, fra i suoi valorosi associati, possegga animo saldo, ingegno pronto e una ragionevole disposizione verso l'ignoto**
:
Io, **Aldebrando Astrofulgo**, Maestro delle Arti Astrali, Scrutatore delle Nove Sfere, Custode della Fiamma di Asterione, Vincitore della Disputa dei Sette Sigilli, già Consigliere Straordinario presso tre Corti, due Conclavi e un'entità extraplanare il cui nome non è prudente affidare alla corrispondenza ordinaria, mi trovo costretto da estreme circostanze a richiedere con urgenza i servigi di codesta stimata Compagnia.

La questione che mi induce a scrivervi è della massima urgenza, di considerevole delicatezza e — non temo di affermarlo — di importanza pressoché incalcolabile.

Ho pertanto necessità di cinque o sei individui di comprovato coraggio, non troppo colti, preferibilmente dotati di curiosità, discernimento, capacità di adattamento e sufficiente istinto di conservazione da non toccare qualunque cosa su cui si posi il loro sguardo.

Il disturbo non dovrebbe richiedere più di alcune ore e sarà adeguatamente compensato.

Per ragioni di riservatezza, la natura esatta dell'impresa sarà comunicata esclusivamente agli incaricati che accetteranno l'impresa e si presenteranno presso la mia dimora.

Considerata la gravità della situazione, richiedo che essi giungano senza indugio.

**È essenziale che la questione sia risolta entro questa sera.**

Confido che codesta Compagnia comprenderà l'onore implicito nell'essere stata prescelta per un incarico che ha già sconfitto alcune fra le più notevoli intelligenze di questo e di altri piani d'esistenza.

Attendo dunque i vostri uomini e donne migliori.

O, qualora costoro fossero già impegnati, quelli immediatamente disponibili.

Con la considerazione che la circostanza richiede,

{{letterSignature

{{signatureName
Aldebrando Astrofulgo
}}

{{signatureTitles
Maestro delle Arti Astrali  
Scrutatore delle Nove Sfere  
Custode della Fiamma di Asterione  
Vincitore della Disputa dei Sette Sigilli  
*eccetera, eccetera*
}}

}}
}}
}}
{{pageNumber,auto}}
\page



## {{far,fa-file}} H02 — Latte di Luna

{{handout
##### {{far,fa-file}} H02 — RISULTATO DEL CATALOGO
**LUNA — Nome proprio di bovino domestico**

Proprietario: **Ermelinda Soffiovento**
Produzione giornaliera: **latte fresco — 2 brocche**.
}}

::::

## {{far,fa-file}} H03 — Polvere di Stella

{{handout
##### {{far,fa-file}} H03 — RISULTATO DEL CATALOGO
**ESTRELLA — vicina della casa accanto**

Annotazione domestica: **zucchero fine — prestito**

*Me ne serve per la torta da fare ad Aldebrando.*
}}

::::

## {{far,fa-file}} H04 — Farina dei Giganti

{{handout
##### {{far,fa-file}} H04 — RISULTATO DEL CATALOGO
**MULINO GIGANTI — Registro Commerciale**

Produzione farine e cereali.
}}

::::

## {{far,fa-file}} H05 — Essenza di Drago

{{handout
##### {{far,fa-file}} H05 — RISULTATO DEL CATALOGO
*Cannella. Un pizzico di paprika.*

*Aldebrando dice che ha il sapore di fuoco di drago.*
}}



## {{far,fa-file}} H06 — Ricetta di Ermelinda

{{handout
##### {{far,fa-file}} H06 — RICETTA DI ERMELINDA
### TORTA PER TUTTE LE OCCASIONI

**Ingredienti**

- Farina — **250 g**
- Latte — **100 ml**
- Zucchero fine — **160 g**
- Uova — **3**
- Burro — **120 g**
- Cannella — **1 cucchiaino**
- Paprika — **un pizzico**

**Preparazione**

1. Lascia ammorbidire il burro e lavoralo a lungo con lo zucchero, finché il composto diventa chiaro e soffice.
2. Separa le uova. Incorpora i tuorli uno alla volta, quindi aggiungi poco alla volta la farina alternandola con il latte.
3. Monta gli albumi a neve e incorporali delicatamente all'impasto. Unisci infine la cannella e **un solo pizzico di paprika**.
4. Versa l'impasto in una tortiera imburrata e cuoci in **forno moderato** finché la superficie è dorata e uno stecchino inserito al centro ne esce asciutto — circa **35–40 minuti**.

{{letter
*Ad Aldebrando dico sempre che nella torta c’è un Ingrediente Segreto.*

*Lui ogni volta cerca di indovinare quale sia, e io gli rispondo che un segreto smette di esserlo appena lo si racconta.*

*Così mangia la torta convinto che ci sia dentro chissà quale magia. È proprio carino!*
}}
}}

{{pageNumber,auto}}
